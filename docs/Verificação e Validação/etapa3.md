# Verificação Etapa 3

## Introdução

Este documento possui como objetivo documentar os resultados da verificação dos artefatos da etapa 3 do aplicativo Letterboxd. O responsável por esta avaliação é a avaliadora Clara Marcelino Ribeiro de Sousa e a data de execução foi no dia 18 de junho de 2023. Na tabela 1, pode-se observar os artefatos avaliados e a versão dos mesmos no dia da avaliação.

| Artefato      | Versão                          |
| ----------- | ------------------------------------ |
| Cenários | `1.0`  |
| Especificação Suplementar | `1.0`  |
| Léxicos | `1.0`  |
| Casos de Uso | `1.1`  |
<div style="text-align: center">
  <p>Tabela 1: Artefatos avaliados da etapa 3</p> 
</div>

## Checklist

Nas tabelas 2, 3 e 4 a seguir está disponível o checklist desenvolvido durante o [planejamento](./planejamento.md) respondido de acordo com o artefato avaliado.

### Cenários
A tabela 2 a seguir possui as perguntas do checklist que será utilizado para fazer a verificação do artefato de Cenários.

| Número     | Pergunta | Resposta
| ----------- | ----------- |  ----------- |
| 1 | Os cenários possuem título?¹ | Sim |
| 2 | Os cenários possuem metas/objetivos?¹ | Sim |
| 3 | Os cenários possuem contexto?¹ | Sim |
| 4 | Os cenários possuem atores?¹ | Sim |
| 5 | Os cenários possuem recursos?¹ | Sim |
| 6 | Os cenários possuem exceção?¹ | Sim |
| 7 | Os cenários possuem episódios?¹ | Sim |
| 8 | O título do cenário é de fácil compreensão?² | Sim |
| 9 | As situações descritas são relevantes para o uso do sistema?² | Sim |
| 10 | Os léxicos estão presentes nos cenários?² | ==Incompleto== |

<div style="text-align: center">
<p>Tabela 2: Checklist de verificação do artefato "Cenários"</p>
</div>

### Especificação Suplementar

| Número     | Pergunta | Resposta
| ----------- | ----------- |  ----------- |
| 1 | O modelo adotado na especificação é o FURPS?³ | Sim |
| 2 | É possível testar os requisitos analisados?³ | ==Incompleto== |
| 3 | A especificação explicita a funcionalidade do requisito?³ | Sim |
| 4 | A especificação explicita a usabilidade do requisito?³ | Sim |
| 5 | A especificação explicita a confiabilidade do requisito?³ | Sim |
| 6 | A especificação explicita a performance do requisito?³ | Sim |
| 7 | A especificação explicita a suportabilidade do requisito?³ | Sim |

<div style="text-align: center">
<p>Tabela 3: Checklist de verificação do artefato "Especificação Suplementar"</p>
</div>

### Léxicos
| Número     | Pergunta | Resposta
| ----------- | ----------- | ----------- | 
| 1 | Os símbolos possuem noção (o significado so símbolo)?¹ | Sim |
| 2 | Os símbolos possuem impacto (o efeito do símbolo na aplicação)?¹ | Sim |
| 3 | Os símbolos possuem sinônimos?¹ | Sim |
| 4 | Os símbolos possuem tipo (verbo/objeto/estado)?¹ | Sim |
<div style="text-align: center">
<p>Tabela 4: Checklist de verificação do artefato "Léxicos"</p>
</div>

### Casos de Uso

| Número     | Pergunta | Resposta
| ----------- | ----------- | ----------- | 
| 1 | Utiliza verbos no infinitivo?⁴ | ==Incompleto== |
| 2 | Possui um fluxo principal?³ | ==Incompleto== |
| 3 | O fluxo principal representa o modo “default”/padrão que o ator irá usar a funcionalidade?³ | Sim |
| 4 | Possui fluxo alternativo, quando aplicável?³ | Sim |
| 5 | Possui fluxo de excessão, quando aplicável? | ==Não== |
| 6 | Há relacionamentos extend e include?³ | Sim |
| 7 | Possui atores?⁴ | Sim |
| 8 | Possui sistemas?⁴ | Sim |
| 9 | Possui metas?⁴ | Sim |
| 10 | Possui as atividades e variantes usadas para atingir as metas?⁴ | Sim |
| 11 | O ator principal está ao lado esquerdo do sistema?⁴ | Sim |
| 12 | O usuário está fora das fronteiras da aplicação?⁴ | Sim |
| 13 | Os casos especificados são de requisitos funcionais?⁴ | Sim |
| 14 | Os casos de uso são representados com um formato oval na horizontal e representa os diferentes usos que um usuários pode ter?⁴ | Sim |
<div style="text-align: center">
<p>Tabela 5: Checklist de verificação do artefato "Casos de Uso"</p>
</div>

## Resultados

É possível observar pela Figura 1 que das 35 perguntas do checklist, 5 foram respondidas como "Não" ou "Incompleto" (14,3%) enquanto 30 foram respondidas como "Sim" (85,7%). A seguir será documentado as observações feitas sobre cada um dos artefatos com os pontos de atenção que foram notados pela execução do checklist.

Cenários

- Os léxicos estão presentes nos cenários?
> Não há uma referência clara dos léxicos nos cenários

Especificação Suplementar

- É possível testar os requisitos analisados?
> U07	- Registro no diário mais intuitivo e com menos cliques. Esse requisito é muito amplo e subjetivo.<br/>
> D03 - O tempo de resposta do servidor deve ser rápido o suficiente para oferecer uma experiência de usuário satisfatória. Esse requisito precisa ser melhor especificado para conseguir ser testado eficientemente.

Casos de Uso

- Utiliza verbos no infinitivo?
> Alguns casos de uso não estão no infinitivo, como "UC04 - Botão de adicionar lista nova" e "UC07 - Fornece os dados de filmes assistidos". Ao não deixar os verbos no infinitivo não fica claro que o caso de uso é uma ação.

- Possui um fluxo principal?
> Alguns casos de uso não possuem, como "UC02 - Vizualizar todas as listas do usuário, incluindo listas curtidas", "UC07 - Fornece os dados de filmes assistidos" e "UC14 - Notificar usuários sobre artigos de filmes em suas listas".

- Possui fluxo de excessão, quando aplicável?
> Nenhum caso de uso possui um fluxo de excessão

<figure markdown>
  ![Figura 1](../assets/grafico1Etapa3.png)
  <figcaption>Figura 1: gráfico das respostas do checklist da etapa 3</figcaption>
  <p style="margin-top: -10px; font-size: 10px">Fonte: Autoria própria</p>
</figure>

## Referência Bibliográfica
> - [1] “Requisitos – Aula 10”, Milene Serrano e Maurício Serrano. Disponível em: <https://aprender3.unb.br/> Acesso em: 16 de junho de 2023.
> - [2] Leite, J.C.S.d.P., Rossi, G., Balaguer, F. et al. Enhancing a requirements baseline with scenarios. Requirements Eng 2, 44–53 (1997)
> - [3] “Requisitos – Aula 11”, Milene Serrano e Maurício Serrano. Disponível em: <https://aprender3.unb.br/> Acesso em: 16 de junho de 2023.
> - [4] Diagrama de caso de uso UML: O que é, como fazer e exemplos. Disponível em: <https://www.lucidchart.com/pages/pt/diagrama-de-caso-de-uso-uml>.

## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 18/06/2023 | `1.0`  | Documentação da execução da verificação | [Clara Ribeiro](https://github.com/clara-ribeiro) | [Natan Santana](https://github.com/Neitan2001) |