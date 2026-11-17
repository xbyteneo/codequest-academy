# Lição 03: Site Responsivo — Do Computador para o Celular 📱💻

> **Status:** 📋 Planejamento pedagógico. O projeto desta lição será implementado após a conclusão da Lição 02.

Mais de 70% dos acessos à internet acontecem na tela de um smartphone. Nesta aula, o aluno aprende a mágica das **Media Queries** e do design adaptativo para que seu site fique impecável tanto em um monitor widescreen quanto em um celular.

---

## 🎯 Objetivos de Aprendizado

- Compreender o conceito de **design responsivo** e a meta tag `viewport`.
- Aprender a utilizar a ferramenta de inspeção do navegador para simular telas de smartphones.
- Dominar a sintaxe de `@media (max-width: ...)` no CSS.
- Transformar menus horizontais em menus verticais adaptados para telas pequenas.
- Ajustar tamanhos de fontes e imagens proporcionalmente com unidades relativas (`rem`, `%`, `vw`).

---

## 📋 Pré-requisitos

- Conclusão das lições 01 e 02 (HTML Semântico, CSS e Flexbox).

---

## 💻 Projeto Prático (Planejado)

**Landing Page de um Evento ou Canal:**
Uma página promocional completa que se reorganiza elegantemente quando a largura da janela diminui: os elementos lado a lado viram uma coluna vertical fluida e legível.

---

## 🧗 Desafios Progressivos Planejados

1. **Nível 1 (O Inspetor):** Abrir as ferramentas de desenvolvedor do navegador (`F12` ou botão direito ➔ "Inspecionar") e alternar para a visualização de celular (iPhone/Android).
2. **Nível 2 (Primeira Media Query):** Criar uma regra que muda a cor de fundo da página ou o tamanho do título apenas em telas com menos de 600px.
3. **Nível 3 (Grid Adaptativo):** Fazer com que uma linha de 3 cards se transforme automaticamente em uma coluna de 1 card por linha em telas móveis.
4. **Boss Fight:** Construir uma barra de navegação que esconde links secundários no celular e foca no botão principal de chamada para ação.

---

## ✅ Critérios de Conclusão

- [ ] A página é legível e navegável em celulares sem necessidade de rolagem horizontal indesejada.
- [ ] Uso correto de ao menos um breakpoint com `@media`.
- [ ] O aluno sabe abrir e usar a emulação de dispositivos nas ferramentas de desenvolvedor.
- [ ] Atualização do `progresso.json`.

---

## 💡 Dicas para o Aluno

- Se aparecer uma barra de rolagem horizontal na parte de baixo do navegador, algo no seu CSS tem largura fixa (`width: 800px`, por exemplo). Use porcentagens ou `max-width` para evitar isso!

---

## 👨‍🏫 Orientações para o Professor

- Mostre aos alunos como inspecionar o site usando o atalho `Cmd+Opt+I` (Mac) ou `Ctrl+Shift+I` (Windows). Os adolescentes adoram descobrir os recursos ocultos do navegador.
