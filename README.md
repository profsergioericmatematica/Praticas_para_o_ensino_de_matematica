# 🧮 Práticas para o Ensino de Matemática I - Univesp

Uma aplicação web interativa e gamificada desenvolvida para auxiliar estudantes na revisão e fixação dos conceitos teóricos da disciplina **Práticas para o Ensino de Matemática I** do curso de licenciatura da **UNIVESP**.

## 🎯 Objetivo do Projeto
Transformar o estudo teórico de metodologias, história da educação matemática e taxonomias do conhecimento docente (como MTSK, MKT e TPACK) em uma experiência dinâmica. O projeto substitui a leitura passiva por atividades ativas, utilizando metodologias de gamificação e navegação interativa.

## 📚 Estrutura do Curso
O conteúdo da aplicação está organizado ao longo de 7 semanas de estudo, cobrindo os seguintes temas:
* **Semana 1:** Práticas para o ensino de matemática I: entre concepções matemáticas e práticas pedagógicas
* **Semana 2:** O professor que ensina matemática hoje e a importância de seus conhecimentos profissionais
* **Semana 3:** O sentido dos números e das operações no currículo e nas práticas pedagógicas dos professores
* **Semana 4:** Pensamento algébrico e álgebra no decorrer do currículo e suas implicações nas práticas pedagógicas dos professores
* **Semana 5:** Conceitos e propriedades da geometria na educação básica e suas implicações nas práticas pedagógicas
* **Semana 6:** Estudos e práticas pedagógicas de grandezas e medidas
* **Semana 7:** Problematizações em contextos de probabilidade e estatística que refletem nas práticas pedagógicas

> **Nota:** As semanas 6 e 7 estão em desenvolvimento (páginas em construção no menu principal).

## ✨ Funcionalidades
O aplicativo é dividido por semanas de estudo, onde cada semana (1, 2, 3 e 4) oferece um conjunto completo de ferramentas de aprendizagem:

### 📇 Flashcards 3D
Cartões interativos de frente e verso para memorização ativa de siglas, conceitos, tendências pedagógicas, gerações da profissão docente, propriedades do SND, sentidos das operações e conceitos algébricos. Basta clicar no cartão para virar e conferir a resposta.

### 🎯 Quiz Interativo
Questões de múltipla escolha focadas na aplicação prática da teoria, com sistema de dicas, feedback imediato e explicações detalhadas. A pontuação e o número de questões restantes são exibidos em tempo real.

### 🔗 Jogo de Associação
Atividade rápida para relacionar definições a seus respectivos conceitos ou autores. O usuário deve escolher a opção correta entre as alternativas apresentadas.

### 📊 Painel Comparativo
Exercícios de classificação específicos para cada semana:
- **Semana 1:** Discursos Economicista vs. Crítico sobre avaliações em larga escala.
- **Semana 2:** Conceitos de Matemática Acadêmica vs. Escolar, Transposição Didática, Construção Autônoma, entre outros.
- **Semana 3:** Afirmações sobre algoritmos tradicionais vs. estratégias de decomposição (classificar como Verdadeiro ou Falso, com justificativa).
- **Semana 4:** Tendências do ensino de álgebra (Linguístico-pragmática, Fundamentalista-estrutural, Fundamentalista-analógica) – classifique as afirmações.
- **Semana 5:** Afirmações sobre fundamentos da geometria (poliedros convexos, relação de Euler, direção vs. sentido, planificação, etc.) – classifique como Verdadeiro ou Falso.

### 🧠 Mapa Interativo
Um sistema de **botões clicáveis** que exibe, sob demanda, conteúdos detalhados sobre cada tópico da semana.  
- **Semana 1:** botões para Tataravô, Bisavô, Avô, Pai, todas as tendências pedagógicas (Formalista Clássica, Empírico-Ativista, etc.), SAEB, TIMSS 2023, discursos sobre avaliação, Escuta Nacional de Professores (2025) e Políticas Públicas (PNE).  
- **Semana 2:** botões para Matemática Acadêmica vs. Escolar, Transposição Didática, Construção Autônoma, Professor vs. Pesquisador, Modelos Shulman, MKT, MTSK, TPACK, Saberes da Ação Pedagógica e Não Saberes.  
- **Semana 3:** botões para Sistema de Numeração Decimal (propriedades posicional, multiplicativa, aditiva), sentidos do número (cardinal, ordinal, medida, nominal, estimativa), sentidos da adição (juntar, acrescentar), subtração (retirar, completar, comparar), multiplicação (parcelas iguais, configuração retangular, combinatória), divisão (partilha equitativa, medida), algoritmo tradicional vs. decomposição, tampinhas coloridas, material dourado e ábaco.
- **Semana 4:** botões para evolução histórica da álgebra (fases retórica, sincopada, simbólica), pensamento algébrico vs. álgebra como artefato, três tendências do ensino de álgebra, pilares do pensamento algébrico (generalizar, formalizar, argumentar), BNCC (anos iniciais, anos finais, ensino médio), tarefas práticas (Jogo do Tum-pá, colar de contas, dividindo a cidade, cabo de guerra), desafios (transformismo algébrico, sinal de igual relacional, ensino exploratório).
- **Semana 5:** botões para fundamentos da geometria (origem, abandono curricular, desenvolvimento do pensamento geométrico), localização e movimentação (direção vs. sentido, referencial, mapas), geometria espacial (poliedros convexos/não convexos, corpos redondos, relação de Euler, planificação, prismas e pirâmides), recursos didáticos (materiais manipuláveis, tecnologias digitais, desconstrução dimensional), BNCC (anos iniciais, anos finais, ensino médio), pesquisa de Pavanello & Franco (diálogo artificial, efeito Topázio, imprecisões conceituais, negociação de significados).

**Diferencial:** Cada clique **substitui** o conteúdo exibido anteriormente (não acumula), mantendo a área de visualização sempre limpa e focada no último tópico selecionado. Não há botão de "limpar" – a própria substituição já organiza o estudo por tópico.

### 📖 Síntese Teórica
Um painel lateral de consulta rápida com os resumos essenciais dos textos base e videoaulas, disponível em todas as semanas.

### 📄 Download de Resumos (PDF)
Acesso rápido aos resumos gerados em LaTeX padronizados para impressão (arquivos `SEP401_apostila_semana1.pdf`, `SEP401_apostila_semana2.pdf`, `SEP401_apostila_semana3.pdf` e `SEP401_apostila_semana4.pdf`).

## 🛠️ Tecnologias Utilizadas
Este projeto foi construído puramente com tecnologias web padrão (Vanilla), garantindo leveza e fácil hospedagem:
* **HTML5:** Estruturação semântica e suporte a áudio (para feedback sonoro opcional).
* **CSS3:** Estilização responsiva (Mobile First), layouts com Flexbox/Grid, animações 3D nativas e efeitos visuais de transição.
* **JavaScript:** Lógica de manipulação do DOM, controle de pontuações, embaralhamento de questões, navegação por abas e substituição dinâmica de conteúdo no Mapa Interativo.

## 🚀 Como executar o projeto
1. Faça o clone ou download deste repositório.
2. Não é necessária nenhuma instalação ou configuração de servidor complexo.
3. Basta abrir o ficheiro `index.html` em qualquer navegador moderno (Chrome, Firefox, Edge, Safari).
4. *(Recomendado)* Para que a função de abrir/baixar os PDFs locais funcione sem bloqueios de segurança dos navegadores, utilize uma extensão de servidor local, como o **Live Server** no VS Code.
5. Navegue entre as semanas clicando nos botões do menu principal e, dentro de cada semana, explore as abas (Flashcards, Quiz, Associação, Comparativo, Mapa Interativo).

## 📁 Estrutura de arquivos

projeto/

|-- index.html

|-- semana1.html

|-- semana2.html

|-- semana3.html

|-- semana4.html

|-- semana5.html

|-- SEP401_apostila_semana1.pdf

|-- SEP401_apostila_semana2.pdf

|-- SEP401_apostila_semana3.pdf

|-- SEP401_apostila_semana4.pdf

|-- SEP401_apostila_semana5.pdf

|-- README.md

|-- LICENSE


## 👨‍🏫 Autor
Desenvolvido com 💡 por **Prof. Sergio Eric Reis de Oliveira** | Acompanhe no Instagram: [@prof.sergio.eric.matematica](https://instagram.com/prof.sergio.eric.matematica)

## 📄 Licença
Este projeto está sob a licença MIT. Veja o ficheiro [LICENSE](LICENSE) para mais detalhes.
