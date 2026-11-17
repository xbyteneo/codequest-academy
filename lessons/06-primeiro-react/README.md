# Lição 06: Primeiro React — Pensando em Componentes ⚛️🧩

> **Status:** 📋 Planejamento pedagógico. O projeto desta lição será implementado após a conclusão da Lição 05.

Como os desenvolvedores de empresas como Instagram, Airbnb e Netflix criam interfaces gigantescas sem se perderem no código? Eles usam **Componentes**! Nesta lição, o aluno tem seu primeiro contato com o ecossistema moderno do React, aprendendo a quebrar páginas em blocos de Lego reutilizáveis.

---

## 🎯 Objetivos de Aprendizado

- Compreender a mentalidade de componentes: dividir para conquistar.
- Entender a sintaxe JSX (mistura elegante de HTML com poder do JavaScript).
- Aprender o conceito de **Props** (passando informações de pais para filhos).
- Conhecer o estado reativo com o hook `useState`.
- Renderizar listas dinâmicas com `.map()`.

---

## 📋 Pré-requisitos

- Conclusão das lições 01 a 05 (Domínio de HTML, CSS, Arrays e lógica básica com JavaScript).

---

## 💻 Projeto Prático (Planejado)

**Catálogo de Personagens / Galeria de Cards com Busca ao Vivo:**
Uma aplicação em React onde cada card é um componente independente. Conforme o usuário digita no campo de busca, os cards são filtrados na hora com renderização instantânea.

---

## 🧗 Desafios Progressivos Planejados

1. **Nível 1 (Meu Primeiro Componente):** Criar uma função que retorna um componente `<Card />` com JSX e usá-la 3 vezes na página.
2. **Nível 2 (Usando Props):** Passar título, imagem e descrição personalizados para cada `<Card />` através de props.
3. **Nível 3 (Estado Reativo):** Usar `useState` para criar um botão de curtida em cada card que atualiza o número de likes individualmente.
4. **Boss Fight:** Implementar uma barra de pesquisa que filtra a lista de personagens em tempo real usando `.filter()`.

---

## ✅ Critérios de Conclusão

- [ ] Criação e reutilização de ao menos um componente React.
- [ ] Passagem bem-sucedida de propriedades via `props`.
- [ ] Uso funcional do `useState` para atualizar a tela sem mexer diretamente no DOM.
- [ ] Registro de conclusão em `progresso.json`.

---

## 💡 Dicas para o Aluno

- No React, você não precisa ficar procurando elementos com `document.querySelector()`. Quando você muda o "estado" (`state`), o React redesenha a tela sozinho!

---

## 👨‍🏫 Orientações para o Professor

- Utilize ambientes sem atrito no início (como Vite pré-configurado ou CodeSandbox/StackBlitz) para que o aluno não gaste tempo com configurações de bundling e Babel.
