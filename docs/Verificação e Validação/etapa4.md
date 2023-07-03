# Verificação Etapa 4

## Introdução

Este documento possui como objetivo documentar os resultados da verificação dos artefatos da etapa 4 do aplicativo Letterboxd. O responsável por esta avaliação é o avaliador Natan Tavares Santana e a data de execução foi no dia 16 de junho de 2023. Na tabela 1, pode-se observar os artefatos avaliados e a versão dos mesmos no dia da avaliação.

| Artefato      | Versão                          |
| ----------- | ------------------------------------ |
| Histórias de Usuário       | `2.0`  |
| Backlog       | `1.1` |
| NFR Framework    | `1.0` |
<div style="text-align: center">
<p>Tabela 1: Artefatos avaliados da etapa 4 (Fonte: Natan, 2023)</p>
</div>

## Checklist

Nas tabela 2, 3 e 4 a seguir está disponível o checklist desenvolvido durante o [planejamento](./planejamento.md) respondido de acordo com os artefatos avaliados.

### Histórias de Usuário

| Número     | Pergunta | Resposta |
| ----------- | ----------- | ----------- | 
| 1 | As histórias de usuário seguem o padrão de voz de usuário?² | ==Não== |
| 2 | As histórias de usuário estão escritas em primeira pessoa de acordo com o modelo de voz do usuário?²  | Sim |
| 3 | As histórias de usuário possui o papel (quem) de acordo com o modelo de voz de usuário?² | Sim |
| 4 | As histórias de usuário possui a ação (o que) de acordo com o modelo de voz de usuário?²  | Sim |
| 5 | As histórias de usuário possui o resultado da ação ou o valor de negócio (porque) de acordo com o modelo de voz de usuário?² | Sim |
| 6 | Nas história de usuário, o papel representa quem se beneficiará da funcionalidade, e não quem está solicitando a funcionalidade?² | Sim |
| 7 | Nas histórias de usuário, é usado um termo representando o perfil em vez do termo genérico "usuário"?²  | ==Não== |
| 8 | É explicado o papel dos stakeholders quanto a criação e/ou validação das histórias de usuário? (Autoria Própria)  | ==Não== |
| 9 | As histórias de usuário possuem critérios de aceitação os quais permitem que elas sejam testáveis?² | Sim |
<div style="text-align: center">
<p>Tabela 2: Checklist de verificação do artefato "Histórias de Usuário" (Fonte: Natan, 2023)</p>
</div>

### Backlog

| Número     | Pergunta | Resposta |
| ----------- | ----------- | ----------- | 
| 10 | Foi usado uma metodologia para a construção do backlog?³ | Sim |
| 11 | O backlog possui épicos e temas bem definidos e descritos?³ | Sim |
| 12 | O PO participou da construção e/ou da validação do backlog?² | Sim |
| 13 | Foi documentado se o PO pediu alguma mudança no backlog? (Autoria Própria) | Sim |
<div style="text-align: center">
<p>Tabela 3: Checklist de verificação do artefato "Backlog" (Fonte: Natan, 2023)</p>
</div>

### NFR Framework

| Número     | Pergunta | Resposta |
| ----------- | ----------- | ----------- | 
| 14 | Os softgoals NFR representam requisitos não-funcionais?¹ | Sim |
| 15 | Os softgoals de operacionalização representam soluções de implementação para satisfazer softgoals NFR ou outros softgoals de operacionalização?¹ | Sim |
| 16 | Os softgoal de afirmação fornecem as razões para as decisões de desenvolvimento?¹ | Sim |
| 17 | Os softgoals NFR possuem um tipo e pode possuir um ou mais tópicos?¹ | Sim |
| 18 | Os tipos de contribuição seguem as definições apresentada na dissertação "NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados"?¹ | Sim |
| 19 | Os impactos foram corretamente propagados?³ | ==Não== |
| 20 | Foi construído cartões de especificação de acordo com o modelo apresentado na dissertação "NFR4ES: Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados" ou de alguma outra referência?³ | ==Não== |
| 21 | Os diagramas documentados estão legíveis? (Autoria Própria) | ==Não== |
<div style="text-align: center">
<p>Tabela 4: Checklist de verificação do artefato "NFR Framework" (Fonte: Natan, 2023)</p>
</div>

## Resultados

É possível observar pela Figura 1 que das 21 perguntas do checklist, 6 foram respondidas como "Não" (28,6%) enquanto 17 foram respondidas como "Sim" (71,4%). A seguir será documentado as observações feitas sobre cada um dos artefatos com os pontos de atenção que foram notados pela execução do checklist.

Quanto às histórias de usuário:

- US26 está fora do padrão de voz de usuário
- É usado o termo genérico "usuário" em vez de um termo que represente o perfil
- Não foi documentado como o PO participou da construção e/ou validação das histórias de usuário

Quanto ao NFR Framework:

- A propagação da usabilidade não foi feita
- Não foram feitos os cartões de especificação dos NFR's
- As letras dos diagramas de usabilidade e de confiabilidade estão muito pequenas e difíceis de ler

<figure markdown>
  ![Figura 1](../assets/graficoe4.png)
  <figcaption>Figura 1: gráfico das respostas do checklist da etapa 4</figcaption>
  <p style="margin-top: -10px; font-size: 10px">Fonte: Autoria própria</p>
</figure>

## Referência bibliográfica

> - [1] SILVA, Reinaldo Antônio da. NFR4ES:Um Catálogo de Requisitos Não-Funcionais para Sistemas Embarcados. Recife, 2019. Disponível em: <https://repositorio.ufpe.br/handle/123456789/34150#:~:text=Neste%20trabalho%20foi%20desenvolvido%20um,n%C3%A3o%2Dfuncionais%20em%20sistemas%20embarcados./> Lido em: 12 jun. 2023.
> - [2] REINEHR, Sheila. Engenharia de Requisitos. Porto Alegre: Sagah, 2020. Lido em: 12 jun. 2023.
> - [3] SALES, André Barros. Plano de ensino da disciplina. Disponível em: <a href="https://aprender3.unb.br">https://aprender3.unb.br</a>. Acesso em: 16 de junho de 2023.

## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 16/06/2023 | `1.0`  | Documentação da execução da verificação | [Natan Santana](https://github.com/Neitan2001) | [Clara Ribeiro](https://github.com/clara-ribeiro) |
| 03/07/2023 | `2.0`  | Adição das referências | [Natan Santana](https://github.com/Neitan2001) | [Clara Ribeiro](https://github.com/clara-ribeiro) |
