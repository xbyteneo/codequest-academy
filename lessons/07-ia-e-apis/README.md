# Lição 07: IA e APIs — Conectando seu Site à Nuvem 🌐🤖

> **Status:** 📋 Planejamento pedagógico. O projeto desta lição será implementado após a conclusão da Lição 06.

Nenhum aplicativo moderno vive isolado. Eles se comunicam com servidores pelo mundo inteiro para buscar dados de clima, placares de jogos, fotos e respostas de inteligência artificial. Nesta lição, o aluno aprende a usar o comando `fetch` e `async/await` para buscar dados vivos de APIs gratuitas e integrá-los à sua interface.

---

## 🎯 Objetivos de Aprendizado

- Compreender o que é uma **API** (a ponte de comunicação entre sistemas).
- Entender o formato de dados **JSON** (o idioma universal da internet).
- Fazer requisições HTTP assíncronas usando `fetch()` e `async/await`.
- Lidar com estados de carregamento (*Loading...*) e erros de conexão.
- Integrar respostas de serviços de IA ou APIs públicas gratuitas (Pokémon API, Rick and Morty API ou geradores de texto).

---

## 📋 Pré-requisitos

- Conclusão das lições 04, 05 e fundamentos de JavaScript assíncrono.

---

## 💻 Projeto Prático (Planejado)

**Assistente Inteligente / Buscador de Curiosidades com IA:**
Uma página onde o usuário digita uma pergunta ou clica em um botão para sortear um tema e a página busca dados ao vivo de uma API na internet, exibindo o resultado em um card estilizado.

---

## 🧗 Desafios Progressivos Planejados

1. **Nível 1 (O Primeiro Fetch):** Fazer uma requisição simples para uma API pública (ex.: PokéAPI ou Conselhos do Dia) e ver o JSON no console.
2. **Nível 2 (Exibindo na Tela):** Pegar a informação do JSON retornado e inseri-la dinamicamente dentro de um card no HTML.
3. **Nível 3 (Feedback Visual):** Mostrar um aviso de *"Carregando dados..."* enquanto a internet busca a resposta.
4. **Boss Fight:** Criar um formulário onde o usuário digita o que quer buscar e o site traz a informação correspondente da API.

---

## ✅ Critérios de Conclusão

- [ ] Requisição bem-sucedida usando `fetch` e `async/await`.
- [ ] Tratamento básico de carregamento ou erro com `try/catch`.
- [ ] Apresentação harmoniosa dos dados retornados na interface.
- [ ] Atualização do `progresso.json`.

---

## 💡 Dicas para o Aluno

- Pense na API como um garçom em um restaurante: você faz o pedido (`fetch`), ele vai até a cozinha (o servidor) e volta com o prato pronto (o JSON)!

---

## 👨‍🏫 Orientações para o Professor

- Utilize apenas APIs abertas que não exijam cartão de crédito, tokens pagos ou configurações complexas de CORS. Mantenha o foco no fluxo de dados.
