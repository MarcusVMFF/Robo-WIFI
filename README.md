﻿# 🤖 Robô Carro Controlado via Web Server

Projeto da área de robótica que utiliza comunicação via web server para controle de um robô carro com exibição de informações em display SSD1306 e sinalização com LEDs, desenvolvido com a placa BitDogLab.

---

## 🔎 Objetivo Geral

Implementar a comunicação entre um web server e a placa BitDogLab para controlar remotamente um robô carro, com comandos de movimento exibidos no display OLED SSD1306 e sinalizados por LEDs RGB correspondentes às ações realizadas.

---

## 🛠️ Tecnologias Utilizadas

- **Linguagem de Programação:** C / CMake  
- **Placas Microcontroladoras:**  
  - BitDogLab  
  - RP2040 (Pico W)  
- **Periféricos Utilizados:**  
  - Display OLED SSD1306 (via I2C)  
  - LEDs RGB (conectados aos GPIOs)  
  - Driver Ponte H dupla L298N  
  - 2 motores DC com Chassi Acrílico 2WD  
  - Suporte de pilhas AA  
  - Protoboard e jumpers diversos  

---

## 📖 Como Utilizar

1. Acesse o **web server** criado pela placa BitDogLab via Wi-Fi.  
2. O web server possui **3 botões principais**:
   - **FORWARD:** Move o robô para frente.  
   - **STOP:** Para o movimento do robô.  
   - **BACKWARD:** Move o robô para trás.  

3. Ao pressionar qualquer botão:
   - A ação será exibida no **display SSD1306** com as mensagens:
     - `"FRONTWARD"`  
     - `"STOP"`  
     - `"BACKWARD"`  
   - A ação será registrada no **Serial Monitor**.  
   - Um **LED RGB** será aceso com a cor correspondente:
     - 🟢 Verde → Frente  
     - 🔵 Azul → Parar  
     - 🔴 Vermelho → Ré  

---

## 📊 Funcionalidades Demonstradas

- Criação de um Web Server embarcado  
- Controle de motores DC com ponte H (L298N)  
- Manipulação do display OLED SSD1306 via I2C  
- Comunicação serial com o Serial Monitor  
- Controle de LEDs RGB via GPIO  
- Integração entre interface web e hardware embarcado  
- Utilização da placa BitDogLab para automação robótica

---

## 🎥 Demonstração

*https://drive.google.com/file/d/1nkPCs5fJnDnpDvzyqrgEh7cNKJIlXwEu/view?usp=drive_link*

