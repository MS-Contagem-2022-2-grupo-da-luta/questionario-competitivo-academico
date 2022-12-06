<h1>Questionário Competitivo Academico</h1>

<h2> Documento de Software </h2>
<hr>
 <h2>Clube da Luta</h2>
<hr>
Integrantes:

<div>Adriano Henrique Xavier Rodrigues (RA UNA: 422210209)</div>
<div>Gustavo Lopes de Oliveira (RA UNA: 42114026)</div>
<div>Hugo Ferreira Menezes (RA UNA: 422210267)</div>
<div>João Pedro Santos Regis Teixeira (RA UNA: 422112192)</div>
<div>Márcio Christian Martins Almeida (RA UNA: 422137176)</div>
<div>Thiago Francisco Lima (RA UNA: 422221554)</div>

<hr>

<h1>1. Histórico de versões</h1>

| Data       | Versão | Descrição                                    | Autor                                           |   |
|------------|--------|----------------------------------------------|-------------------------------------------------|---|
| 06/09/2022 | 1.0    | Levantamento de Requisitos                   | Thiago Francisco Lima e Adriano Henrique        |   |
| 10/10/2022 | 1.1    | Protótipo                                    | Adriano Henrique, Hugo Ferreira, João Pedro     |   |
| 20/11/2022 | 1.2    | Diagrama de Caso de Uso                      | João Pedro, Hugo Menezes, Thiago Francisco      |   |
| 20/11/2022 | 1.3    | Diagrama de Classe                           | Hugo Ferreira, Gustavo Lopes e Márcio Christian |   |
| 22/11/2022 | 1.4    | Diagrama de Atividade, Diagrama de Sequencia | Thiago Francisco Lima                           |   |
| 22/11/2022 | 1.5    | Diagrama entidade Relacionamento             | Thiago Francisco Lima                           |   |

<hr>

<h2>Objetivos desde documento </h2>

O objetivo deste documento é registrar todos os artefatos que compõem a modelagem do software a ser desenvolvido pela equipe.
<hr>
<h2> Formulário de Entrevista </h2>

| Entrevistado:                                                             |                                João Pedro Teixeira                               |
|---------------------------------------------------------------------------|:--------------------------------------------------------------------------------:|
| Perguntas                                                                 | Respostas                                                                        |
| 01) COMO GOSTARIA DE UM SOFTWARE DE ENTRETENIMENTO PARA SUA UNIVERSIDADE? | UMA APLICAÇÃO DE PERGUNTAS E RESPOSTAS SOBRE CULTURA POP E DE CONTEÚDO ACADÊMICO |
| 02) QUAL SERIA O ESCOPO DA APLICAÇÃO?                                     | ENTRETENIMENTO E INTERAÇÃO DE INTERFACE E USUÁRIO.                               |
| 03) QUAIS PLATAFORMAS DE ACESSO?                                          | WEB E MOBILE (ANDROID/IOS)                                                       |
| 04) QUAIS TECNOLOGIAS DE PREFERÊNCIA?                                     | FRONT-END: JAVASCRIPT; REACT; BACK-END: NODE JS/PHP                              |
| 05) COMO GOSTARIA DA AVALIAÇÃO DE DESEMPENHO DOS USUÁRIOS E RANK?         | GRÁFICOS/RANK’S/NIVEIS E OUTROS                                                  |
<hr>
<h2>4. Requisitos</h2>
<h3>4.1 Requisitos Funcionais </h3>

|       ID     |                                 Descrição                                |     Prioridade    |
|:------------:|:------------------------------------------------------------------------:|:-----------------:|
|     RF-01    |                O usuário   interage com outro usuário através de chat    |           Alta    |
|     RF-02    |                                  O usuário   cadastra com id e senha     |           Alta    |
|     RF-03    |                            O usuário   pode fazer upload de questões     |           Alta    |
|     RF-04    |                O usuário   pode fazer alteração no seu perfil pessoal    |           Alta    |
|     RF-05    |                                       O usuário   pode criar torneio     |           Alto    |
|     RF-06    |               O usuário   pode convidar outros usuários para torneio     |           Alto    |
|     RF-07    |                  O usuário   pode pesquisar questões de seu interesse    |           Alto    |
|     RF-08    |     O usuário   pode filtrar questões por critério de sua preferência    |           Alto    |
|     RF-09    |                       O usuário   pode marcar questões como favoritas    |          Médio    |
|     RF-10    |                            O usuário   realiza questões de interesse     |           Alto    |

</hr>
<h3>4.2 Requisitos Não Funcionais</h3>
A tabela a seguir apresenta os requisitos não funcionais que o projeto deverá atender.

|       ID      |                                                         Descrição                                                        |     Prioridade    |
|:-------------:|:------------------------------------------------------------------------------------------------------------------------:|-------------------|
|     RNF-01    |     O site deve   ser publicado em um ambiente acessível publicamente na Internet (Repl.it,   GitHub Pages, Heroku);     |     Alta          |
|     RNF-02    |                  O site deverá ser responsivo   permitindo a visualização em um celular de forma adequada                |     Alta          |
|      RNF-0    |                                              O site deverá respeitar a LGPD                                              |     Alta          |
|     RNF-04    |       O site deve ser compatível com   os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge)     |     Alta          |
|     RNF-05    |                                O site deve ficar online 24   horas por dia, 365 dias no ano                              |     Alta          |

<h2>5. Protótipo</h3>

O protótipo completo com simulação de navegação, encontra-se disponível no Figma, clicando [aqui](https://www.figma.com/file/OOab6uN1F6ltpFiIgBvNKa/Untitled?node-id=0%3A1)

<hr>

<h2>6. História de usuários</h2>


|     ID            |     Eu como…                            |     Quero..                                                                                                   |     Para..                                                                            |
|-------------------|-----------------------------------------|---------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
|     01 (RF1)      |     Estudante do Ensino médio           |     Comunicar-me com outros estudantes                                                                        |     Conversar com pessoas que partilham o mesmo   interesse de estudo                 |
|     02 (RF3)      |     Professor de escola pública         |     Criar e publicar questões para estudantes responderem                                                     |     Mensurar a qualidade e dificuldades das minhas   questões                         |
|     03 (RF4)      |     Entusiasta de sites de Questões     |     Poder ter um perfil pessoal personalizado                                                                 |     Para mostrar o meu nível academico, meus   interesses, etc                        |
|     04 (RF5)      |     Estudante competitivo               |     Desafiar outros alunos para um teste de   conhecimento                                                    |     Disputar com outras pessoas afim de comparer   meu nivel de conhecimento          |
|     05 (RF7)      |     Graduando em Medicina               |     Ter acesso a quetões especificas da área da   biomedicina                                                 |     Estudar de maneira eficiente afim de ter um   melhor aproveitamento nas provas    |
|     06 (RF8)      |     Estudante de concurso público       |     Poder pesquisar por questões que atendam meus   interesses                                                |     Estudar e encontrar assuntos que gosto de   aprender                              |
|     07 (RF9)      |     Formando do Ensino Médio            |     Salvar questões favoritas para revisá-las posteriormente                                                  |     Manter o conhecimento sobre determinada   questão sempre “fresco” na mente        |
|     08 (S/ RF)    |     Pai de estudante do Ensino médio    |     Que meu filho possa interagir com outros   alunos no contexto do estudo  e   aprendizado                  |     Que meu filho tenha mais interesse em estudar                                     |
|     09 (S/ RF)    |     Amante de Biologia                  |     Ter acesso a um banco de questões gigante e   atualizado sobre Biologia                                   |     Para me manter informado sobre as melhores   questões da Biologia                 |
|     10            |     Entusiasta em Cálculo               |     Poder responder e disputar com outros usuários   sobre o conhecimento que tange a Matemática e Cálculo    |     Colocar a prova meus conhecimentos sobre   Matemática                             |
<hr>

<h2>6.1 Teste de Aceitação</h2>

|     ID do User Story    |                 Nome                |     Importância    |     PH    |                                                                         Como Demonstrar                                                                        |     Notas    |
|:-----------------------:|:-----------------------------------:|:------------------:|:---------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------------:|:------------:|
|          01 e 08        |        Comunicar com usuários       |          10        |      5    |            O usuário após logar-se, vai até a página do   perfil do pessoal, abre a aba do chat e seleciona o usuário no qual quer   enviar mensagem           |              |
|            02           |             Criar Questão           |         8,5        |      7    |                              Em seu perfil, o usuário clica em “Área de   Criação” e após a página aberta, clica em “Criar Questão”                            |              |
|            03           |          Personalizar Perfil        |          10        |      3    |     O usuário após ou durante a criação do perfil,   pode selecionar todas as informações pessoais relevante, desde onde nasceu   até a área no qual estuda    |              |
|          04 e 10        |         Disputar com usuários       |          10        |      7    |               O usuário    na página do perfil, clica em “Banco de Questões”, depois em “Desafiar   Usuário(s) e seleciona com quem quer competir              |              |
|        05, 06, 09       |     Pesquisar e filtrar questões    |          10        |      5    |                  O usuário ao clicar em “banco de questões” tem   disponível um filtro, no qual ele seleciona de acordo com a área de interesse                |              |
|            07           |          Favoritar questões         |          7         |      2    |                          O usuário após resolver a questão, tem a opção   de favoritar e ter ela destacada na área “Questões Favoritas”                        |              |
<hr>
<h2> 7. Cenário de Casos de Uso </h2>

|     Nome                    |     USUARIO   01                                                                                                                                                                                                                                                                                                                                                                                               |
|-----------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
|     Identificador           |     UC2015                                                                                                                                                                                                                                                                                                                                                                                                     |
|     Sumário                 |     USUARIO   RESPONDE QUESTIONARIO DE PERGUNTAS                                                                                                                                                                                                                                                                                                                                                               |
|     Ator primário           |     USUÁRIO                                                                                                                                                                                                                                                                                                                                                                                                    |
|     Ator secundário         |                                                                                                                                                                                                                                                                                                                                                                                                                |
|     Pré-condição            |     USUÁRIO   IDENTIFICADO E AUTENTICADO                                                                                                                                                                                                                                                                                                                                                                       |
|     Fluxo Principal         |     1- Usuário faz cadastro e acessa com login e senha           2- Pesquisa questões de seu interesse           3- Responde as questões selecionadas            4-   Encerra o questionário                                                                                                                                                                                                                   |
|     Fluxos Alternativos     |     (2-4) O usuário pode filtrar as questões do banco de questões   com matéria de seu interesse           2.1   Voltar ao passo 3           (1-4)   A qualquer momento, o usuário pode criar grupos           1.1   Usuário pode convidar amigos ao grupo criado           1.2   Usuário pode criar torneio a partir do grupo criado para resolução de   questões           1.3   Voltar ao passo 3           |
|     Fluxos de Exceções      |                                                                                                                                                                                                                                                                                                                                                                                                                |
|     Pós- condição           |     As   respostas corretas são computadas no sistema e pontuadas.                                                                                                                                                                                                                                                                                                                                             |
<h2>8. Diagrama de Caso de Uso</h2>

O Diagrama de Caso de Uso pode ser encontrado [Aqui](https://drive.google.com/file/d/1FxLsJckStTy4xTYgin1tW2klfSw_Bxz6/view)

<h2>9. Diagrama de Classes </h2>

O Diagrama de Classes pode ser encontrado [Aqui](https://drive.google.com/file/d/1yBTFrKrsbvkV_RuqkQHmc_s1Os5IsMt7/view)

<h2>10. Diagrama de Atividades </h2>

O Diagrama de Atividades pode ser encontrado [Aqui](https://drive.google.com/file/d/1uM-DwsGkklFVUfUz7XXepiTDnj0jpnaV/view)

<h2>11. Diagrama de Sequencia </h2>

O Diagrama de Sequencia pode ser encontrado [Aqui](https://drive.google.com/file/d/1gBmS2cyhyrtqgp-qEAsG4Q7OHRqrG8DN/view)

<h2>12. Diagrama Entidade Relacionamento</h2>

O Diagrama Entidade Relacionamento pode ser encontrado [Aqui](https://drive.google.com/file/d/1ThbmLW-3Wr4lnHLNfjFbs1fJGosiBv-U/view?usp=share_link)

<h2>13. Diagrama Modelo Lógico</h2>

O Diagrama Modelo Lógico pode ser encontrado [Aqui]( https://drive.google.com/file/d/1QphNWkUoek42CdgFpx2qQ29_fv1fIg1I/view)
<hr>

Clique [Aqui](https://drive.google.com/drive/folders/1Ae8g2kchKQdt1sVpcIPEMmW9w7ZeiJqV?usp=share_link) para ter acesso a todos os Diagramas em uma pasta centralizada.
