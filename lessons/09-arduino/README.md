# Lição 09: Arduino e Robótica — Programando o Mundo Real 🤖💡

> **Status:** 📋 Planejamento pedagógico. O projeto desta lição será implementado após a conclusão da Lição 08.

O código não precisa ficar preso dentro da tela do computador! Nesta lição que coroa a jornada do **code-lessons**, o aluno entra no universo da computação física e da robótica: aprende a controlar LEDs, ler botões e sensores e entender como funcionam os semáforos, portões automáticos e dispositivos inteligentes do mundo real.

---

## 🎯 Objetivos de Aprendizado

- Compreender a diferença entre hardware e software.
- Conhecer o ciclo de vida do microcontrolador: `setup()` (iniciação) e `loop()` (execução contínua).
- Entender portas digitais de entrada (*INPUT*) e saída (*OUTPUT*).
- Controlar componentes elétricos simples: LEDs, resistores e botões tipo push-button.
- Utilizar simuladores online gratuitos (como Wokwi ou Tinkercad) dispensando a obrigatoriedade de peças físicas caras.

---

## 📋 Pré-requisitos

- Lógica de programação básica adquirida nas lições de JavaScript ou Python.

---

## 💻 Projeto Prático (Planejado)

**Semáforo Inteligente com Sensor de Pedestres:**
Um circuito de semáforo (LEDs verde, amarelo e vermelho) com botão de travessia para pedestres. Quando pressionado, o semáforo respeita o tempo de segurança dos carros, fecha e acende o sinal para o pedestre passar.

---

## 🧗 Desafios Progressivos Planejados

1. **Nível 1 (Blink / O Olá Mundo do Hardware):** Fazer um LED piscar a cada 1 segundo usando `digitalWrite()` e `delay()`.
2. **Nível 2 (O Semáforo Clássico):** Coordenar o acendimento sequencial de 3 LEDs simulando os tempos de trânsito real.
3. **Nível 3 (O Botão de Pedestre):** Ler o clique de um botão físico com `digitalRead()` para interromper o ciclo do semáforo com segurança.
4. **Boss Fight:** Adicionar um buzzer sonoro que apita ritmicamente avisando pessoas com deficiência visual quando o sinal de travessia está aberto.

---

## ✅ Critérios de Conclusão

- [ ] Montagem correta do circuito no simulador Wokwi/Tinkercad ou na placa física real.
- [ ] Código sem erros de compilação na estrutura `setup()` e `loop()`.
- [ ] Lógica temporal precisa sem travar a leitura dos botões.
- [ ] Conclusão de todo o currículo no arquivo `progresso.json`!

---

## 💡 Dicas para o Aluno

- Na robótica, cada pino é como um interruptor de luz: você pode mandar energia para acender algo (`HIGH`) ou desligar a energia (`LOW`).
- Você pode simular circuitos inteiros de Arduino de graça direto no navegador usando o [Wokwi](https://wokwi.com/)!

---

## 👨‍🏫 Orientações para o Professor

- Se a escola não possuir kits físicos de Arduino, use 100% de simuladores no navegador (Wokwi é excelente, rápido e não requer cadastro). A experiência de aprendizado da lógica é idêntica!
