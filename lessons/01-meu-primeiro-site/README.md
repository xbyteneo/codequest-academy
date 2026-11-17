# Lição 01: Você Acabou de Virar um Criador de Sites! 🚀

Bem-vindo à sua primeira lição no **code-lessons**! Hoje você vai sair do zero absoluto e construir uma página web de verdade, com design profissional, cores modernas e efeitos visuais, tudo direto no seu navegador.

---

## ⏱️ Informações Gerais

- **Duração Estimada:** 60 a 90 minutos.
- **Nível:** Iniciante absoluto (Zero experiência prévia necessária).
- **Linguagens:** HTML5 e CSS3 puros.
- **Ferramentas:** Editor de código (VS Code) e qualquer navegador web moderno.

---

## 🎯 Objetivos de Aprendizado

Ao final desta lição, o estudante será capaz de:
1. Compreender o papel fundamental do **HTML** (estrutura e conteúdo) e do **CSS** (estilo visual).
2. Reconhecer a anatomia básica de uma tag HTML (`<tag>conteúdo</tag>`) e o que são elementos e atributos.
3. Entender a separação entre a tag `<head>` (configurações) e a tag `<body>` (conteúdo visível).
4. Abrir, inspecionar e atualizar um arquivo `.html` local no navegador sem intermediários.
5. Modificar textos, títulos, botões e atributos dentro do código HTML com autonomia.
6. Localizar e editar propriedades de cores, fundos e tamanhos no arquivo CSS.
7. Sentir confiança para experimentar, alterar e criar soluções sem medo de cometer erros de sintaxe.

---

## 📋 Pré-requisitos

- Nenhum conhecimento prévio de lógica ou computação.
- Um computador com editor de código instalado e navegador web funcional.

---

## 💻 Projeto Prático

O aluno criará ou customizará um **Hub Pessoal / Showcase Temático** sobre sua grande paixão (Games, Futebol, Música, Carros, Tecnologia, Cinema, etc.).

O projeto final possui:
- Barra de navegação moderna com logotipo e links.
- Seção Hero de impacto com badge brilhante, título em gradiente e botão interativo.
- Grid com 3 cards de destaque com efeitos suaves ao passar o mouse (*hover*).
- Barra de conquistas e pontos de XP.
- Rodapé estilizado.

O código-fonte base está disponível na pasta [`projeto/`](projeto/).

---

## 🧗 Roteiro da Aula e Desafios Progressivos

A aula é estruturada em 7 etapas progressivas:

### Etapa 1: O Primeiro Contato (A Conexão de Interesses)
O tutor de IA pergunta sobre as paixões do estudante (games, futebol, música, etc.) e conecta o projeto a um tema pelo qual o aluno realmente se interessa.

### Etapa 2: A Mágica (O Site Funcional)
Apresentação do site funcionando na pasta `projeto/index.html`. O aluno abre o arquivo no navegador e experimenta o impacto visual imediato de um site responsivo e profissional.

### Etapa 3: Descobrindo o HTML (A Anatomia do Código)
Desmontagem guiada pelo tutor:
- O que é o HTML e a metáfora do "esqueleto" da casa.
- Diferença entre `<head>` e `<body>`.
- Como funcionam as tags `<h1>`, `<p>`, `<button>`, `<article>`.
- Pequenas perguntas socráticas da IA para checar entendimento.

### Etapa 4: Primeiro Desafio Prático (Mão no Código)
O aluno deve editar com as próprias mãos no `index.html`:
1. **O Título Principal (`<h1>`):** Mudar para o nome do seu projeto ou tema.
2. **O Subtítulo (`<p class="hero-subtitulo">`):** Escrever um parágrafo que descreva o projeto.
3. **O Botão Principal (`<button>`):** Mudar o texto do botão para uma ação personalizada.

### Etapa 5: Descobrindo o CSS (O Estilista)
Apresentação do arquivo `style.css`:
- Como o CSS veste o esqueleto do HTML.
- Modificação prática de variáveis de cores (`:root`): `--fundo-principal`, `--cor-destaque`, `--cor-acento`.
- Explicação de propriedades básicas: `background-color`, `color`, `font-size`, `border-radius`.

### Etapa 6: Desafio Final (Personalização Completa)
O aluno deve transformar o site para que tenha sua identidade única:
- Alterar os 3 cards da seção de destaques com ícones, títulos e textos autorais.
- Modificar pelo menos duas cores no CSS para criar uma paleta personalizada.
- Responder a 3 perguntas de validação da IA:
  1. *Onde fica o texto do site?*
  2. *Onde ficam as cores e estilos?*
  3. *Como você faz para visualizar suas alterações no navegador?*

### Etapa 7: Conquista e Celebração
- Celebração do resultado alcançado.
- Registro da conclusão no arquivo local `progresso.json`.
- Apresentação de um resumo do que foi aprendido e prévia da **Lição 02 (CSS e Design: Flexbox e Grid)**.

---

## ✅ Critérios de Conclusão

A lição é considerada concluída quando o aluno demonstrar:
- [ ] O arquivo `index.html` foi aberto e visualizado com sucesso no navegador.
- [ ] O título `<h1>`, o subtítulo e o botão foram alterados manualmente pelo estudante.
- [ ] Pelo menos os 3 cards foram customizados com dados do tema escolhido.
- [ ] Pelo menos uma alteração de cor ou estilo foi aplicada no `style.css`.
- [ ] O aluno consegue explicar a diferença entre HTML (conteúdo) e CSS (aparência).
- [ ] O status no arquivo `progresso.json` foi atualizado.

---

## 💡 Dicas para o Aluno

- **Salvou o arquivo?** Se você alterou o código e nada mudou na tela, aperte `Ctrl+S` (Windows/Linux) ou `Cmd+S` (Mac) no editor e depois aperte `F5` no navegador!
- **Não apague os sinais `<` e `>`:** Eles são como parênteses do código. Se apagar sem querer, use `Ctrl+Z` para desfazer.
- **As aspas importam:** Em atributos como `class="card"`, certifique-se de que as aspas abrem e fecham direitinho.
- **Use emojis no HTML:** Você pode colar emojis normais (🎮, ⚽, 🎵, 🏎️) direto dentro das tags!

---

## 👨‍🏫 Orientações para o Professor

- **Nos primeiros 10 minutos:** Garanta que todos os alunos consigam abrir o `index.html` no navegador. O encantamento visual é o motor de engajamento da aula toda.
- **Supervisão da IA:** Observe se os alunos estão usando a IA para pedir dicas ou se estão tentando pedir código pronto. Reforce a regra de que no Desafio 4 e no Desafio 6 as alterações devem ser feitas pelo teclado do aluno.
- **Momento "Uau":** Quando um aluno mudar a cor de fundo pela primeira vez no CSS e der F5, comemore com ele. Essa é a primeira experiência real de controle sobre a máquina.
- **Fechamento coletivo:** Nos últimos 10 minutos, peça para 2 ou 3 alunos projetarem ou mostrarem suas páginas customizadas para a turma.
