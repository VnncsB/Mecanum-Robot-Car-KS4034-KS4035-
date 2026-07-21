# Mecanum Robot Car - KS4034 / KS4035

<a href="https://github.com/VnncsB/Mecanum-Robot-Car-KS4034-KS4035-">
<img src="https://github.com/VnncsB/Mecanum-Robot-Car-KS4034-KS4035-/blob/main/IMG-20260721-WA0016.jpg">
</a>

Projeto de robótica educacional desenvolvido com o kit **Keyestudio micro:bit 4WD Mecanum Robot Car Kit V2.0 (KS4034/KS4035)**, um carrinho robô de 4 rodas Mecanum controlado pela placa **BBC micro:bit**.

## Sobre o Projeto

Este projeto foi proposto pelo **professor Robson Marinho** como forma de aprendizado prático em robótica e programação embarcada, desenvolvido no **Laboratório InovaMech**.

O robô foi montado e programado por:
- **Vinícius Brito de Oliveira**
- **João Bruno Matos do Reis**

A montagem e a programação seguiram os tutoriais e os códigos oficiais disponibilizados pela Keyestudio em [fs.keyestudio.com/KS4034-4035](https://fs.keyestudio.com/KS4034-4035), adaptados e organizados neste repositório para fins de estudo e documentação do processo.

## Sobre o Kit KS4034/KS4035

O KS4034/KS4035 é um carrinho robô DIY dedicado à placa micro:bit, equipado com:

- **4 motores DC** com redução de velocidade, acoplados a **rodas Mecanum**, que permitem movimentação em qualquer direção (frente, ré, lateral e diagonais) e rotação 360° sem a necessidade de mudar a orientação da carroceria;
- Placa base (PCB) com driver de motor integrado e sensores;
- **4 LEDs RGB WS2812** para efeitos de iluminação;
- **2 receptores infravermelho (IR)** para controle remoto;
- **Sensor de seguimento de linha (line tracking)**;
- **Sensor ultrassônico** para desvio/seguimento de obstáculos;
- **Buzzer passivo** para reprodução de sons/músicas;
- Controle via aplicativo (Bluetooth do micro:bit) e via controle remoto por infravermelho;
- Estrutura em acrílico com furos compatíveis com peças de encaixe (building blocks).

**Alimentação:** 2 baterias 18650 (não inclusas) | **Tensão de operação:** 5V | **Tensão de entrada:** DC 6V–9V

## Estrutura do Repositório

```
Mecanum-Robot-Car-KS4034-KS4035-
├── APP/         # Aplicativo de controle do robô (Android/iOS - keyes mecanum_robot)
├── Codes/       # Códigos-fonte utilizados na programação do robô (MakeCode / MicroPython)
├── Tutorial/    # Tutoriais e materiais de apoio (PDFs, guias de montagem e programação)
└── README.md    # Este arquivo
```

## Programação

O robô pode ser programado de duas formas, conforme os tutoriais oficiais da Keyestudio:

- **MakeCode (Blocos/JavaScript):** programação gráfica por blocos, ideal para o primeiro contato com a lógica de controle do robô;
- **MicroPython:** programação textual em Python, utilizando o software Mu para escrever e enviar o código à placa micro:bit.

Entre as funcionalidades programadas/exploradas no projeto estão:
- Controle de movimento omnidirecional (rodas Mecanum);
- Controle remoto via aplicativo e via infravermelho;
- Leitura de sensores (linha, ultrassônico, acelerômetro);
- Efeitos de iluminação com LEDs RGB;
- Reprodução de sons com o buzzer.

## Objetivo Educacional

O projeto teve como principal objetivo aplicar, na prática, conceitos de:
- Robótica móvel e cinemática de rodas Mecanum;
- Programação embarcada com micro:bit;
- Eletrônica e integração de sensores/atuadores;
- Trabalho em equipe e documentação técnica de projetos.

## Referências

- Tutorial e recursos oficiais do fabricante: [fs.keyestudio.com/KS4034-4035](https://fs.keyestudio.com/KS4034-4035)
- Documentação Keyestudio Wiki: [wiki.keyestudio.com](https://wiki.keyestudio.com/KS4034(KS4034F)KS4035(KS4035F)_Keyestudio_Microbit_4WD_Mecanum_Robot_Car_V2.0)

## Autores

| Nome | Função |
|------|--------|
| Vinícius Brito de Oliveira | Montagem e Programação |
| João Bruno Matos do Reis | Montagem e Programação |

**Orientação:** Prof. Robson Marinho
**Local:** Laboratório InovaMech

---
*Projeto acadêmico desenvolvido para fins de aprendizado em robótica.*
