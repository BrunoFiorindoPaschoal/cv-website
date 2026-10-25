---
title: Robótica
weight: 3
image: images/Robotics.svg
---
A robótica é onde tudo na mecatrônica precisa funcionar ao mesmo tempo: mecânica, eletrônica, controle e software.

## Sistema de posicionamento aéreo por cabos (PI7)

<img class="feature-image" src="/images/Robotics.svg" alt="Ilustração do sistema de posicionamento por cabos: dois carretéis motorizados em torres sustentam cabos que suspendem uma carga">

No Projeto Integrado 7 da USP (2025), nossa equipe de oito construiu um **robô de cabos no estilo "câmera aranha"**. Dois motores CC no alto da estrutura enrolam e desenrolam carretéis de cabo; variando os dois comprimentos de cabo, o sistema leva uma carga suspensa a qualquer ponto de um plano vertical.

O projeto cobriu os quatro pilares da mecatrônica em um único sistema construído pelos alunos:

- **Mecânica:** estrutura e mecanismo de carretéis, projetados e fabricados pela equipe.
- **Eletrônica:** placas próprias de driver de motor (projetadas no DipTrace) com a ponte H dupla L298N, com as duas pontes em paralelo para maior corrente, regulador 7805 para a alimentação lógica e cabo flat de 26 vias até as placas de controle.
- **Controle:** o motor foi identificado por ensaios de resposta ao degrau como uma planta de primeira ordem, e um **controlador PID de posição** foi sintonizado primeiro no MATLAB e depois experimentalmente na estrutura final. Ele roda em um microcontrolador PIC16F886 por motor, lendo um encoder incremental (1920 pulsos por volta) e acionando o motor por PWM.
- **Computação:** um Raspberry Pi Pico W recebe comandos do PC (USB ou Wi-Fi) e envia setpoints aos dois controladores de motor via serial.

O resultado foi um sistema estável e responsivo, que recebia comandos, acionava os motores e media a posição em tempo real. A principal limitação, a diferença de redução entre os dois motorredutores, mostrou como detalhes de hardware definem os limites do controle puramente por realimentação.

### Disciplinas relacionadas
Advanced Control, Robot Motion Planning, Optimal Control and Decision Making, Methods in Neuromechanics, Modeling and Reduction of Complex Systems (TUM) · Controle I, Sistemas Dinâmicos I e II, Mecanismos para Automação, Microprocessadores em Automação e Robótica, Sistemas Embarcados, Atuadores e Acionamentos (USP).
