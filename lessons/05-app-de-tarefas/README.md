# Lição 05: App de Tarefas — Criando uma Aplicação com Memória 📝💾

> **Status:** 📋 Planejamento pedagógico. O projeto desta lição será implementado após a conclusão da Lição 04.

Um site que esquece tudo quando você aperta `F5` ainda não é um aplicativo completo. Nesta lição, o aluno dá um salto gigantesco: cria uma aplicação de lista de tarefas (To-Do List) capaz de adicionar itens, marcar como feito, deletar e **salvar tudo na memória do navegador** usando o `localStorage`.

---

## 🎯 Objetivos de Aprendizado

- Compreender a estrutura de dados básica: Listas/Arrays (`[]`) e Objetos (`{}`).
- Criar elementos HTML dinamicamente com JavaScript (`document.createElement`).
- Capturar dados digitados pelo usuário em campos de texto (`<input>`).
- Persistir e recuperar informações no navegador com `localStorage.setItem` e `localStorage.getItem`.
- Compreender conversão de dados com `JSON.stringify` e `JSON.parse`.

---

## 📋 Pré-requisitos

- Conclusão da Lição 04 (Fundamentos de eventos e manipulação de DOM com JavaScript).

---

## 💻 Projeto Prático (Planejado)

**TaskQuest: Gerenciador de Missões e Tarefas:**
Um aplicativo To-Do temático onde cada tarefa adicionada se parece com uma missão de RPG. O usuário pode adicionar tarefas, riscá-las ao concluir, filtrá-las e, mesmo fechando o navegador, as missões continuam salvas lá.

---

## 🧗 Desafios Progressivos Planejados

1. **Nível 1 (Adicionando na Lista):** Pegar o texto de um `<input>` e criar um novo item `<li>` na tela ao pressionar a tecla Enter ou clicar em "Adicionar".
2. **Nível 2 (Concluindo e Deletando):** Adicionar um botão de lixeira para remover a tarefa e um clique para riscar a tarefa concluída.
3. **Nível 3 (Memória com LocalStorage):** Salvar o array de tarefas no `localStorage` para que nada se perca ao recarregar a página.
4. **Boss Fight:** Adicionar um contador que mostra quantas tarefas estão pendentes e quantas já foram concluídas.

---

## ✅ Critérios de Conclusão

- [ ] Capacidade de adicionar e remover tarefas dinamicamente.
- [ ] Persistência funcional via `localStorage` comprovada após recarregar a página.
- [ ] Validação para não permitir adicionar tarefas vazias.
- [ ] Atualização do `progresso.json`.

---

## 💡 Dicas para o Aluno

- O `localStorage` é como o cartão de memória do videogame antigo: ele guarda suas informações até que você decida apagá-las!

---

## 👨‍🏫 Orientações para o Professor

- Ensine a olhar a aba "Application" ➔ "Local Storage" nas ferramentas do navegador. Ver o dado em texto puro gravado lá consolida o aprendizado de persistência de dados.
