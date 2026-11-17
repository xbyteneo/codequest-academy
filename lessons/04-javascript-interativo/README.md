# Lição 04: JavaScript Interativo — Dando Vida à Página ⚡🖱️

> **Status:** 📋 Planejamento pedagógico. O projeto desta lição será implementado após a conclusão da Lição 03.

Até aqui construímos páginas estáticas e bonitas. Agora é a hora de dar **cérebro e reflexos** ao site! Com o JavaScript puro, o aluno aprende a reagir a cliques do mouse, calcular valores, alterar textos dinamicamente e criar a funcionalidade mais amada da web: o alternador de Modo Escuro / Claro.

---

## 🎯 Objetivos de Aprendizado

- Entender o que é o JavaScript e seu papel como a "mente ativa" de uma página web.
- Aprender a selecionar elementos na tela usando `document.querySelector()`.
- Escutar eventos do usuário com `addEventListener('click', ...)`.
- Modificar o conteúdo da página em tempo real com `.textContent` e `.classList.toggle()`.
- Usar variáveis simples (`const` e `let`) e comandos condicionais (`if/else`).

---

## 📋 Pré-requisitos

- Conclusão das lições 01, 02 e 03 (HTML e CSS consolidados).

---

## 💻 Projeto Prático (Planejado)

**Painel Gamer com Contador de Cliques e Dark/Light Mode:**
Uma interface moderna com um contador de pontuação/likes interativo, efeitos visuais sonoros/animados e um botão de alternância entre tema claro e tema escuro.

---

## 🧗 Desafios Progressivos Planejados

1. **Nível 1 (O Primeiro Alerta):** Conectar um arquivo `script.js` e exibir uma mensagem amigável no console do navegador com `console.log()`.
2. **Nível 2 (O Botão Contador):** Fazer um botão que, a cada clique, soma +1 num número exibido na tela.
3. **Nível 3 (Alternador de Tema):** Criar um botão que alterna a classe `dark-theme` no `body`, mudando as cores do site instantaneamente.
4. **Boss Fight:** Criar um minigame de cliques rápidos (ex.: clique 10 vezes o mais rápido possível para desbloquear uma conquista).

---

## ✅ Critérios de Conclusão

- [ ] Arquivo `.js` importado corretamente na tag `<script src="...">`.
- [ ] Funcionamento sem erros no Console do navegador.
- [ ] Manipulação de pelo menos um evento de clique alterando a tela sem recarregar a página.
- [ ] Registro de conclusão em `progresso.json`.

---

## 💡 Dicas para o Aluno

- O `console.log()` é o melhor amigo do programador JavaScript. Se algo não funcionar, imprima o valor no console para ver o que está acontecendo por trás dos panos!

---

## 👨‍🏫 Orientações para o Professor

- Mantenha a sintaxe enxuta e moderna (`const`, `let`, arrow functions simples). Não complique com `var`, `hoisting` ou escopos complexos neste primeiro momento.
