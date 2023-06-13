# Verificação Etapa 4

## Introdução

Este documento possui como objetivo documentar os resultados da verificação dos artefatos da etapa 4 do grupo 7. O responsável por esta avaliação é o avaliador Natan Tavares Santana e a data de execução foi no dia 12 de junho de 2023. Na tabela 1, pode-se observar os artefatos avaliados e a versão dos mesmos no dia da avaliação.

| Artefato      | Versão                          |
| ----------- | ------------------------------------ |
| Histórias de Usuário       | `1.1`  |
| Backlog       | `1.1` |
| NFR Framework    | `1.1` |
<div style="text-align: center">
<p>Tabela 1: Artefatos avaliados da etapa 4 (Fonte: Natan, 2023)</p>
</div>

## Checklist

Nas tabela 2, 3 e 4 a seguir está disponível o checklist desenvolvido durante o [planejamento](./planejamento.md) respondido de acordo com os artefatos avaliados.

### Histórias de Usuário

| Número     | Pergunta | Resposta |
| ----------- | ----------- | ----------- | 
| 1 | As histórias de usuário seguem um modelo? | Sim |
| 2 | As histórias de usuário estão escritas em primeira pessoa de acordo com o modelo de voz do usuário?  | Sim |
| 3 | As histórias de usuário possui o papel (quem) de acordo com o modelo de voz de usuário? | Sim |
| 4 | As histórias de usuário possui a ação (o que) de acordo com o modelo de voz de usuário?  | Sim |
| 5 | As histórias de usuário possui o resultado da ação ou o valor de negócio (porque) de acordo com o modelo de voz de usuário? | Sim |
| 6 | Nas história de usuário, o papel representa quem se beneficiará da funcionalidade, e não quem está solicitando a funcionalidade? | Sim |
| 7 | Nas histórias de usuário, é usado um termo representando o perfil em vez do termo genérico "usuário"?  | ==Não== |
| 8 | É explicado o papel dos stakeholders quanto a criação e/ou validação das histórias de usuário?  | Sim |
| 9 | Todas as histórias de usuário são independentes?  | Sim |
| 10 | As histórias de usuária foram validadas como negociáveis e valiosas pelo PO? | ==Não== |
| 11 | As histórias de usuário aparentam ser estimáveis e pequenas de modo que poderiam ser alocados à uma sprint? | Sim |
| 12 | As histórias de usuário possuem critérios de aceitação os quais permitem que elas sejam testáveis? | Sim |
<div style="text-align: center">
<p>Tabela 2: Checklist de verificação do artefato "Histórias de Usuário" (Fonte: Natan, 2023)</p>
</div>

### Backlog

| Número     | Pergunta | Resposta |
| ----------- | ----------- | ----------- | 
| 13 | Foi usado uma metodologia para a construção do backlog? | Sim |
| 14 | É explicado como a metodologia DEEP foi utilizada no backlog? | ==Não== |
| 15 | O backlog possui épicos e temas bem definidos e descritos? | ==Não== |
| 16 | O PO participou da construção e/ou da validação do backlog? | ==Não== |
| 17 | Foi documentado se o PO pediu alguma mudança no backlog? | ==Não== |
<div style="text-align: center">
<p>Tabela 3: Checklist de verificação do artefato "Backlog" (Fonte: Natan, 2023)</p>
</div>

### NFR Framework

| Número     | Pergunta | Resposta |
| ----------- | ----------- | ----------- | 
| 18 | Os softgoals NFR representam requisitos não-funcionais? | Sim |
| 19 | Os softgoals de operacionalização representam soluções de implementação para satisfazer softgoals NFR ou outros softgoals de operacionalização? | Sim |
| 20 | Os softgoal de afirmação fornecem as razões para as decisões de desenvolvimento? | Sim |
| 21 | Os softgoals NFR possuem um tipo e pode possuir um ou mais tópicos? | Sim |
| 22 | Os tipos de contribuição seguem as definições apresentada na dissertação "NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados"? | Sim |
| 23 | Os impactos foram corretamente propagados? | Sim |
| 24 | Foi construído cartões de especificação de acordo com o modelo apresentado na dissertação "NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados" ou de alguma outra referência? | ==Não== |
| 25 | Os diagramas documentados estão legíveis? | ==Não== |
<div style="text-align: center">
<p>Tabela 4: Checklist de verificação do artefato "NFR Framework" (Fonte: Natan, 2023)</p>
</div>

## Resultados

É possível observar pela Figura 1 que das 25 perguntas do checklist, 8 foram respondidas como "Não" (32%) enquanto 17 foram respondidas como "Sim" (68%). A seguir será documentado as observações feitas sobre cada um dos artefatos com os pontos de atenção que foram notados pela execução do checklist.

Quanto às histórias de usuário:

- É usado o termo genérico "usuário" em vez de um termo que represente o perfil
- Não foi explicado como as história poderiam ser validadas como negociáveis e valiosas

Quanto ao Backlog:

- Foi explicado o que é a metodologia DEEP, mas não como ela será utilizada com o artefato de backlog do grupo
- Não foi definido temas do backlog, além disso não foi explicado o que seria uma "feature" que é apresentada na tabela
- Não foi documentado se teve a participação do PO na construção e/ou validação do backlog

Quanto ao NFR Framework:

- Não teve a criação de cartões de especificação
- Alguns diagramas estão com as letras e símbolos muito pequenos para serem vistos sem zoom, e alguns diagramas possuem a imagem do mouse em cima de elementos importantes

<figure markdown>
  ![Figura 1](../assets/graficoe4g7.png)
  <figcaption>Figura 1: gráfico das respostas do checklist da etapa 4</figcaption>
  <p style="margin-top: -10px; font-size: 10px">Fonte: Autoria própria</p>
</figure>

## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 12/06/2023 | `1.0`  | Documentação da execução da verificação | [Natan Santana](https://github.com/Neitan2001) | [Clara Ribeiro](https://github.com/clara-ribeiro) |
