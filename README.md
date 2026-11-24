# 🎮 Gamificação — SI UNINTA

Repositório de jogos e dinâmicas de gamificação usados nas disciplinas do **Bacharelado em Sistemas de Informação da UNINTA Tianguá**. A ideia é simples: revisar conteúdo de forma ativa, em equipe, com competição saudável, e compartilhar os materiais para que outros professores possam reutilizar e adaptar.

## 📂 Jogos disponíveis

| Jogo | Disciplina | Módulo | Arquivo |
|---|---|---|---|
| 🥷 Batalha Ninja | Gestão de Sistemas de Informação | Módulo I | [`batalha-ninja/Batalha_Ninja_GSI_Modulo1.pptx`](batalha-ninja/Batalha_Ninja_GSI_Modulo1.pptx) |

---

## 🥷 Batalha Ninja — Gestão de SI (Módulo I)

**Autor:** Prof. Henrique Raulino

A Batalha Ninja é um jogo de tabuleiro em PowerPoint no estilo "batalha naval de cartas": a turma é dividida em **clãs ninja** que se revezam escolhendo coordenadas em um tabuleiro 4×4. Cada casa esconde um desafio sobre o conteúdo, um bônus ou uma armadilha. Vence o clã que acumular mais pontos ao final.

### Conteúdos abordados

- Conceito de Sistema de Informação e seus componentes
- Hierarquia Dado → Informação → Conhecimento (DIKW)
- Teoria Geral dos Sistemas (Bertalanffy)
- Os cinco componentes de um SI (hardware, software, dados, pessoas, procedimentos)
- Ciclo de processamento da informação
- Cadeia de Valor de Porter e o papel da TI
- Modelo de Alinhamento Estratégico (Henderson & Venkatraman)
- Governança de TI
- Papel do gestor de SI
- Classificação dos SI por nível organizacional (SPT, SIG, SAD) e pirâmide dos SI

### Estrutura do arquivo

| Slide | Função |
|---|---|
| 1 | Capa |
| 2 | **Tabuleiro** — grade 4×4 (colunas A–D, linhas 1–4). Cada carta é um hiperlink para o seu desafio |
| 3–19 | Cartas: desafios valendo 5 a 20 pontos, **3 armadilhas** (−10 pontos) e **2 bônus** (+5 pontos) |
| 20 | Tela final — "Clã vencedor!" |

O tabuleiro tem 16 casas: 11 desafios de conteúdo, 3 armadilhas e 2 bônus.

### Materiais necessários

- Projetor e o arquivo `.pptx` aberto no **modo de apresentação** (os hiperlinks só funcionam assim)
- Quadro ou folha para o placar dos clãs
- Cronômetro (o do celular serve)

### Regras

1. **Formação dos clãs.** Divida a turma em 3 a 5 clãs. Cada clã escolhe um nome ninja e um líder, que será o porta-voz.
2. **Ordem de jogada.** Sorteie o clã que começa. As jogadas seguem em rodízio.
3. **Escolha da casa.** Na sua vez, o clã escolhe uma coordenada do tabuleiro (ex.: *B3*). O professor clica na carta correspondente.
4. **Desafio de conteúdo.** A carta mostra um conceito e quanto ele vale. O clã tem **1 minuto** para discutir e o líder responde ao desafio proposto pelo professor, por exemplo:
   - explicar o conceito com as próprias palavras;
   - dar um exemplo real (uma empresa, um sistema que usam no dia a dia);
   - dizer se a afirmação está correta e justificar (veja a seção de adaptação para criar afirmações falsas).
5. **Pontuação.** Resposta correta e bem justificada: o clã ganha os pontos da carta. Resposta parcial: o professor pode dar metade dos pontos.
6. **Repasse (opcional).** Se o clã errar, o próximo clã na ordem pode tentar responder valendo metade dos pontos.
7. **Armadilha 💥.** A carta *"PERDE: −10 PONTOS"* desconta 10 pontos do clã que a escolheu, sem direito a resposta.
8. **Bônus 🎉.** A carta *"Parabéns! +5 PONTOS"* dá 5 pontos ao clã imediatamente.
9. **Casa usada.** Depois de revelada, a casa sai do jogo. Marque-a no quadro para ninguém escolher de novo.
10. **Fim de jogo.** O jogo termina quando todas as casas forem reveladas. O clã com mais pontos é o vencedor e ganha a tela final. Em caso de empate, faça uma pergunta extra de desempate.

> 💡 **Dica:** peça que o clã que acertou explique a resposta para a turma toda. Isso transforma cada rodada numa minirrevisão coletiva.

<details>
<summary>🔒 Gabarito do tabuleiro (para o professor, contém spoiler)</summary>

|   | A | B | C | D |
|---|---|---|---|---|
| **1** | SI: conceito (10) | DIKW (15) | TGS (5) | 5 componentes (10) |
| **2** | Ciclo de processamento (10) | 💥 −10 | Cadeia de Valor (15) | Alinhamento Estratégico (20) |
| **3** | Governança de TI (15) | Gestor de SI (5) | 💥 −10 | 🎉 +5 |
| **4** | Classificação SPT/SIG/SAD (15) | Pirâmide dos SI (10) | 🎉 +5 | 💥 −10 |

O slide 8 (evolução dos SI: PED → SIG → ERP/CRM → IA) está no arquivo, mas não tem link no tabuleiro. Pode ser usado como pergunta de desempate ou ligado a uma casa no lugar de uma armadilha.

</details>

---

## 🔧 Como adaptar o jogo para outras disciplinas

A mecânica não depende do conteúdo, então o mesmo arquivo serve de modelo para qualquer disciplina.

### 1. Duplique o arquivo

Copie o `.pptx` e renomeie seguindo o padrão `Batalha_Ninja_<SIGLA-DISCIPLINA>_Modulo<N>.pptx` (ex.: `Batalha_Ninja_BD_Modulo2.pptx`).

### 2. Troque o conteúdo das cartas

Em cada slide de desafio (3 a 19), edite:

- **o texto do conceito**: uma afirmação, pergunta, trecho de código, diagrama ou estudo de caso curto;
- **o valor em pontos**: use valores maiores (15–20) para conceitos mais difíceis e menores (5–10) para os básicos.

Exemplos rápidos:

| Disciplina | Exemplo de carta |
|---|---|
| Banco de Dados | "Qual a diferença entre chave primária e chave estrangeira?" (10 pts) |
| Lógica Matemática | "Monte a tabela-verdade de p → (q ∨ ¬p)." (15 pts) |
| Engenharia de Software | "Cite duas diferenças entre Scrum e Kanban." (10 pts) |
| Redes | "Em que camada do modelo OSI atua um roteador? Justifique." (15 pts) |
| Programação | Um trecho de código: "Qual a saída deste programa?" (20 pts) |

### 3. Inclua afirmações falsas (opcional)

No arquivo original todas as afirmações estão corretas. Para um formato **verdadeiro ou falso**, reescreva algumas cartas com um erro proposital (ex.: trocar *tático* por *estratégico*). O clã precisa dizer se está certo **e corrigir** o que estiver errado.

### 4. Ajuste armadilhas e bônus

Mantenha a proporção de 2 a 3 armadilhas e 2 bônus a cada 16 casas: isso deixa o jogo imprevisível sem punir demais. Você pode criar cartas especiais, como:

- **Roubo ninja:** rouba 5 pontos de outro clã;
- **Jutsu de proteção:** anula a próxima armadilha;
- **Desafio relâmpago:** 20 segundos para responder, valendo o dobro.

### 5. Mude o tamanho do tabuleiro (opcional)

1. No slide 2, duplique ou apague as cartas da grade.
2. Crie os novos slides de desafio.
3. Clique com o botão direito na carta → **Link** → **Colocar neste documento** → escolha o slide do desafio.
4. Em cada slide de desafio, garanta que exista um botão ou link de volta para o **slide 2** (o tabuleiro).

### 6. Troque o tema visual

O tema ninja é só ambientação. Troque o fundo da capa e as imagens das cartas para combinar com a disciplina ou a turma (espacial, medieval, futebol...). Use imagens próprias, livres de direitos (Unsplash, Pixabay, ícones do PowerPoint) ou geradas por IA para evitar problemas de direitos autorais ao publicar o material.

### 7. Teste antes da aula

Abra no modo de apresentação (F5) e clique em todas as casas para conferir os links de ida e volta.

---

## 🤝 Como contribuir

Criou uma versão para a sua disciplina? Compartilhe!

1. Crie uma pasta com o nome do jogo ou da disciplina (ex.: `batalha-ninja-banco-de-dados/`).
2. Coloque o arquivo `.pptx` (ou outro formato) dentro dela.
3. Adicione uma linha na tabela **Jogos disponíveis** deste README com disciplina, módulo e link.
4. Abra um *pull request* ou envie o arquivo para a coordenação do curso.

---

**Bacharelado em Sistemas de Informação — UNINTA Tianguá**
