# Guia do Professor — Metodologia e Condução Pedagógica

Este guia orienta o educador na facilitação das aulas do repositório **code-lessons**. O projeto foi desenhado especificamente para adolescentes do ensino médio sem conhecimento prévio de desenvolvimento de software, combinando acompanhamento docente humano com mentoria individualizada via IA no terminal.

---

## 1. Filosofia Pedagógica do Curso

O ensino tradicional de computação frequentemente comete o erro de ensinar semanas de sintaxe, lógica abstrata e teoria antes de permitir que o aluno crie algo que possa mostrar aos amigos ou à família.

Nossa abordagem inverte essa lógica:
1. **Resultado visual imediato:** No primeiro encontro, o aluno precisa sentir o poder de colocar uma interface moderna no navegador.
2. **Desconstrução curiosa:** Uma vez que ele viu algo funcionando e bonito, ele desenvolve o desejo genuíno de entender como aquilo foi feito.
3. **IA como tutora socrática:** A IA não é uma fábrica de respostas prontas; ela atua como um parceiro de pair programming experiente e paciente, fazendo perguntas reflexivas e oferecendo dicas graduais.

---

## 2. Preparação do Ambiente de Aula

Antes da chegada dos alunos ou do início da sessão:

1. **Hardware / SO:** Computador com Windows, macOS ou Linux.
2. **Software Necessário:**
   - **Editor de código:** Visual Studio Code (ou similar).
   - **Extensões recomendadas no VS Code:**
     - *Live Server* (facilita recarregar a página automaticamente ao salvar).
     - *Prettier - Code formatter* (opcional, para manter o código limpo).
   - **Navegador web moderno:** Google Chrome, Firefox, Microsoft Edge ou Safari.
   - **Assistente de IA:** Antigravity CLI, Claude Code, GitHub Copilot Chat, Gemini CLI ou qualquer agente com acesso aos arquivos do repositório e ao `AGENTS.md`.
3. **Verificação inicial:**
   - Clone o repositório na máquina do estudante.
   - Certifique-se de que o arquivo `progresso.json` esteja na raiz com os valores iniciais.
   - Confirme que o assistente de IA lê o arquivo `AGENTS.md` como diretriz principal de comportamento.

---

## 3. Dinâmica de Início de Aula (O "Gancho")

Não comece a aula explicando a história do HTML ou quem inventou a internet. Comece com uma provocação conectada ao cotidiano deles:

> *"Quantos sites ou apps vocês usaram hoje desde a hora que acordaram? TikTok, YouTube, Instagram, site de jogos... Quem aqui já imaginou como isso é construído por trás da tela? Hoje, em menos de 1 hora, você vai ter o seu próprio site rodando no seu computador."*

Instrua os alunos a abrirem o terminal ou assistente de IA e enviarem a frase disparadora:
```text
Quero começar minha primeira aula
```

---

## 4. O Papel do Professor: Mediação e Observação

Com cada aluno tendo um tutor de IA individual no terminal, o papel do professor muda de **transmissor de conteúdo** para **facilitador de experiências**:

- **Circule pela sala:** Observe as reações. Identifique sorrisos de surpresa e expressões de dúvida ou frustração.
- **Não tome o teclado:** Ao ajudar um aluno, coloque as mãos para trás. Pergunte o que ele acha que está acontecendo e aponte na tela, incentivando-o a digitar.
- **Estimule o compartilhamento:** Quando um aluno conseguir um visual legal ou mudar uma cor inusitada, incentive-o a mostrar para o colega ao lado.

---

## 5. Quando Permitir que a IA Escreva Código vs. Quando Exigir Autonomia

Essa é a fronteira pedagógica mais importante do curso.

| Momento / Situação | Papel da IA | Ação do Aluno |
| :--- | :--- | :--- |
| **Geração Inicial (A Mágica)** | Gera o boilerplate do site moderno baseado no tema escolhido (games, música, etc.). | Observa, escolhe o tema, abre no navegador e celebra o resultado. |
| **Desafio de Textos (`h1`, `p`, botões)** | **NÃO gera código.** Dá dicas de onde encontrar a tag no arquivo. | Localiza o texto no editor, edita manualmente, salva e recarrega. |
| **Desafio de Cores e Estilos (CSS)** | Mostra exemplos de propriedades (`background-color`, `color`), mas não aplica direto. | Testa valores hexadecimais ou nomes de cores no arquivo `style.css`. |
| **Erros e Bugs de Sintaxe** | Ajuda a debugar fazendo perguntas (*"Consegue achar a tag que ficou sem fechar?"*). | Revisa a linha indicada e corrige o erro. |

> **Alerta para o Professor:** Se perceber que um aluno está apenas pedindo *"faz isso pra mim"* para a IA, intervenha gentilmente:
> *"A IA é seu estagiário hoje, você é o arquiteto. Deixa ela te dar uma dica, mas coloca a mão no código pra sentir como funciona!"*

---

## 6. Como Avaliar o Aprendizado Sem Provas Tradicionais

Nossa avaliação é formativa e baseada em demonstração prática:

1. **Defesa do Código (1 a 2 minutos por aluno):**
   - Peça ao aluno para apontar onde está o arquivo que define os textos (HTML) e onde está o que define a aparência (CSS).
   - Peça para ele fazer uma pequena alteração ao vivo (ex.: *"Muda esse botão de azul para verde agora pra eu ver"*).
2. **Capacidade de Resolução:**
   - O aluno conseguiu identificar um erro simples de digitação com o auxílio das dicas do tutor?
3. **Autenticidade e Criatividade:**
   - O site final reflete a personalidade do aluno ou é apenas a cópia exata do modelo inicial?
4. **Registro no `progresso.json`:**
   - Verifique se os desafios da lição foram marcados como concluídos.

---

## 7. Como Adaptar o Ritmo da Turma

Em qualquer sala de aula haverá ritmos heterogêneos.

### Para Alunos Mais Rápidos (Aceleradores):
- Desafie-os a adicionar um novo card com imagem.
- Ensine a procurar uma paleta de cores moderna no site Coolors ou FlatUIColors.
- Proponha um efeito de transição ou sombra extra (`box-shadow`, `transform: translateY(-5px)`).
- Convide-os a atuar como "monitores voluntários" ajudando colegas que estão com dúvidas pontuais.

### Para Alunos que Precisam de Mais Tempo (Construção Segura):
- Foque em uma vitória por vez: primeiro garantir a troca do título principal (`<h1>`).
- Reduza o escopo: não se preocupe se ele não mexer em todas as cores; alterar a cor do fundo e do botão já consolida o conceito de CSS.
- Tranquilize o aluno quanto ao tempo: o ritmo da aprendizagem é individual.

---

## 8. Resolução de Problemas Técnicos Mais Comuns

- **"Mudei o arquivo mas o site não mudou no navegador":**
  - Quase sempre o aluno esqueceu de salvar o arquivo (`Ctrl+S` / `Cmd+S`) ou não recarregou a página (`F5`).
- **"O CSS sumiu e o site ficou todo branco e feio":**
  - Verifique se o caminho `<link rel="stylesheet" href="style.css">` foi alterado ou se o arquivo `style.css` foi renomeado/movido.
- **"O texto ficou gigante ou sumiu":**
  - Verifique se uma tag de fechamento (ex.: `</h1>` ou `</div>`) foi apagada por engano.
