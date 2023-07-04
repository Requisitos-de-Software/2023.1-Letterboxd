# Elos de Rastreabilidade

## Introdução

Os elos de rastreabilidade, também conhecidos como links de rastreabilidade, são as conexões ou relações estabelecidas entre os artefatos e os requisitos de um sistema. Esses elos fornecem um meio de rastrear a interdependência entre os elementos do projeto, permitindo compreender como os requisitos são implementados, testados e validados ao longo do ciclo de vida do sistema. Nessa página serão exibidos os elos de rastreabilidade do nosso projeto.

## Metodologia

O meta-modelo utilizado como base para a realização dos elos classifica as informações rastreadas em quatro categorias: ambiental, organizacional, gerencial e desenvolvimento (TORANZO, 2002). Para a realização desse projeto da disciplina de requisitos, todas as informações rastreadas pertencem à categoria de desenvolvimento.

Neste meta-modelo, o suporte à rastreabilidade identifica os seguintes tipos:

- satisfação: indica que a classe de origem tem dependência de satisfação com classe de destino;
- recurso: indica que a classe de origem tem dependência de recurso com classe de destino;
- responsabilidade: registra a participação, responsabilidade e ação de pessoas sobre artefatos (no caso do nosso projeto, não se aplica);
- representação: captura a representação ou modelagem dos requisitos em outras linguagens;
- alocado: classe de origem está relacionada à classe de destino, que representa um subsistema;
- agregação: indica composição de elementos.

Os elos de rastreabilidade foram aplicados apenas nos requisitos não implementados pelo aplicativo Letterboxd, estando a maioria prototipados.

### Elo de Rastreabilidade 1
<details>
  <summary>Requisito: Encontrar filmes em comum na "watchlist" de dois ou mais usuários, exclusivos para usuários "Pro"</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
      <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/perfil/" target='_blank'>QST08</a></td>
      <td>Desenvolvimento</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/casoUso/#uc12_1">Casos de Uso 12</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/espSuplementar/#35-suportabilidade-supportability">Especificação Suplementar S04</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/espSuplementar/#35-suportabilidade-supportability">Especificação Suplementar S05</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us01-encontrar-filmes-em-comum-na-watchlist-de-usuarios-pro">História de Usuário US01</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Verifica%C3%A7%C3%A3o%20e%20Valida%C3%A7%C3%A3o/Valida%C3%A7%C3%A3o/2-prototipacao/#22-prototipo-02-filmes-em-comum">Protótipo 02</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#31-tema-1-watchlist">Tema: Watchlist</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-2-watchlist">Léxico 2</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 2
<details>
  <summary>Requisito: Sortear filme da watchlist</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
      <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/perfil/" target='_blank'>QST13</a></td>
      <td>Desenvolvimento</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/casoUso/#uc13_1">Casos de Uso 13</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us07-sortear-filme-da-watchlist">História de Usuários 07</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Verifica%C3%A7%C3%A3o%20e%20Valida%C3%A7%C3%A3o/Valida%C3%A7%C3%A3o/2-prototipacao/#21-prototipo-01-sortear-filme">Protótipo 01</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#31-tema-1-watchlist">Tema: Watchlist</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-2-watchlist">Léxico 2</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 3
<details>
  <summary>Requisito: Mandar mensagens para outros usuários</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
      <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/perfil/" target='_blank'>QST06</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us06-enviar-mensagens-para-outros-usuarios">História de Usuários US06</a></td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#32-tema-2-interacao-social">Tema: Interação Social</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-8-followers">Léxico 8</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 4
<details>
  <summary>Requisito: Deve ser possível que os usuários criem e participem de grupos de discussão sobre temas específicos, como gêneros cinematográficos, diretores e filmes clássicos</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
      <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/analise/#3-resultados" target='_blank'>DOC57</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us09-criar-e-participar-de-grupos-de-discussao">História de Usuários US09</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Verifica%C3%A7%C3%A3o%20e%20Valida%C3%A7%C3%A3o/Valida%C3%A7%C3%A3o/2-prototipacao/#23-prototipo-03-grupos-de-discussao">Protótipo 03</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#32-tema-2-interacao-social">Tema: Interação Social</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td>-</td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 5

<details>
  <summary>Requisito: Comentar críticas feitas por outros usuários</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
      <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/perfil/" target='_blank'>QST02</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us05-sorteios-de-posteres-assinados-por-elenco-de-filmes-recentes-para-usuarios-pro">História de Usuários US18</a></td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#32-tema-2-interacao-social">Tema: Interação Social</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-6-comment">Léxico 6</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 6
<details>
  <summary>Requisito: Sorteios de pôsteres assinados por elenco de filmes recentes, exclusivo para usuários "Pro"</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/perfil/" target='_blank'>QST09</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us05-sorteios-de-posteres-assinados-por-elenco-de-filmes-recentes-para-usuarios-pro">História de Usuários 05</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Verifica%C3%A7%C3%A3o%20e%20Valida%C3%A7%C3%A3o/Valida%C3%A7%C3%A3o/2-prototipacao/#29-prototipo-09-sorteio-de-posteres">Protótipo 09</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#32-tema-2-interacao-social">Tema: Interação Social</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td>-</td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 7
<details>
  <summary>Requisito: Sugestão de amigos de acordo com gostos em comum, exclusivo para usuários "Pro"</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/perfil/" target='_blank'>QST07</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us02-sugestao-de-amigos-com-gostos-em-comum-para-usuarios-pro">História de Usuários 02</a></td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#32-tema-2-interacao-social">Tema: Interação Social</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-8-followers">Léxico 8</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 8
<details>
  <summary>Requisito: Aba "Perto de você" que mostre as críticas de usuários na região a fim de facilitar a busca por amigos </summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/entrevista/" target='_blank'>ENT01</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us17-aba-perto-de-voce-para-facilitar-a-busca-por-amigos-com-base-em-criticas-de-usuarios-locais">História de Usuários US17</a></td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#32-tema-2-interacao-social">Tema: Interação Social</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-8-followers">Léxico 8</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 9

<details>
  <summary>Requisito: Colocar artigos relacionados na tela de detalhes do filme</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/perfil/" target='_blank'>QST11</a></td>
      <td>Desenvolvimento</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/casoUso/#uc11">Casos de Uso 11</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us03-adicionar-artigos-relacionados-a-tela-de-detalhes-do-filme"> </a>História de Usuários US03 </a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Verifica%C3%A7%C3%A3o%20e%20Valida%C3%A7%C3%A3o/Valida%C3%A7%C3%A3o/2-prototipacao/#210-prototipo-10-artigos-relacionados">Protótipo 10</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#33-tema-3-midias">Tema: Mídias</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-3-review">Léxico 3</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 10
<details>
  <summary>Requisito:  Deve ser possível reagir com uma emoção sentida no filme</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/analise/#3-resultados" target='_blank'>DOC54</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us04-reagir-com-diferentes-emocoes-aos-filmes">História de Usuários US04</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Verifica%C3%A7%C3%A3o%20e%20Valida%C3%A7%C3%A3o/Valida%C3%A7%C3%A3o/2-prototipacao/#26-prototipo-06-emocoes">Protótipo 06</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#33-tema-3-midias">Tema: Mídias</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-15-rate">Léxico 15</a>td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 11
<details>
  <summary>Requisito: Deve ser possível fazer o acompanhamento de séries no aplicativo</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/analise/#3-resultados" target='_blank'>DOC51</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us11-possibilidade-de-fazer-o-acompanhamento-de-series-no-aplicativo
      ">História de Usuários US11</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Verifica%C3%A7%C3%A3o%20e%20Valida%C3%A7%C3%A3o/Valida%C3%A7%C3%A3o/2-prototipacao/#24-prototipo-04-acompanhamento-de-series">Protótipo 04</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#33-tema-3-midias">Tema: Mídias</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-5-watched">Léxico 5</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 12
<details>
  <summary>Requisito: Adicionar categorias para filmes, séries e animes</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/perfil/" target='_blank'>QST04</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us12-adicionar-categorias-para-filmes-series-e-animes">História de Usuários US12</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Verifica%C3%A7%C3%A3o%20e%20Valida%C3%A7%C3%A3o/Valida%C3%A7%C3%A3o/2-prototipacao/#24-prototipo-04-acompanhamento-de-series">Protótipo 04</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#33-tema-3-midias">Tema: Mídias</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-5-watched">Léxico 5</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 13

<details>
  <summary>Requisito: Refatorar a criação de listas para diminuir a quantidade de cliques necessária e ficar mais intuitiva</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
      <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/perfil/" target='_blank'>QST12</a></td>
      <td>Desenvolvimento</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/casoUso/#uc04_1">Casos de Uso 04</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/casoUso/#uc10_1">NFR Usabilidade</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/espSuplementar/#31-funcionalidade-functionality">Especificação Suplementar U08</a><br/> <a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/espSuplementar/#31-funcionalidade-functionality">Especificação Suplementar U03</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/espSuplementar/#33-confiabilidade-reliability">Especificação Suplementar C07</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/espSuplementar/#35-suportabilidade-supportability">Especificação Suplementar S07</a><br/></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us16-refatoracao-da-criacao-de-listas-para-maior-intuitividade-e-reducao-de-cliques">História de Usuários US16</a><br/></td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#34-tema-4-registro-de-filmes">Tema: Registro de filmes</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-7-list">Léxico 7</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 14

<details>
  <summary>Requisito: Notificar usuários sobre artigos de filmes que estiverem em suas listas</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/perfil/" target='_blank'>QST10</a></td>
      <td>Desenvolvimento</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/casoUso/#uc14_1">Casos de Uso 14</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us19-notificacoes-de-artigos-de-filmes-nas-listas-dos-usuarios">História de Usuários US19</a></td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#34-tema-4-registro-de-filmes">Tema: Registro de filmes</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-3-review">Léxico 3</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-7-list">Léxico 7<br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-9-notifications">Léxico 9</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 15
<details>
  <summary>Requisito: Deve ser possível sincronizar os dados de serviços de streamings com os dados do aplicativo</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/analise/#3-resultados" target='_blank'>DOC50</a></td>
      <td>Desenvolvimento</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/casoUso/#uc06_1">Casos de Uso 06</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/espSuplementar/#31-funcionalidade-functionality">Especificação Suplementar U07</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us08-sincronizar-dados-de-servicos-de-streaming-com-o-aplicativo">História de Usuários US08</a></td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#34-tema-4-registro-de-filmes">Tema: Registro de filmes</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-5-watched">Léxico 5</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 16

<details>
  <summary>Requisito: Registro no diário mais intuitivo e com menos cliques</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/entrevista/" target='_blank'>ENT05</a></td>
      <td>Desenvolvimento</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/casoUso/#uc10_1">Casos de Uso 10</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/casoUso/#uc10_1">NFR Usabilidade</a></td> <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us10-registro-no-diario-mais-intuitivo-e-com-menos-cliques"> História de Usuários 10 </a></td>  
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#34-tema-4-registro-de-filmes">Tema: Registro de filmes</a><br/><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Prioriza%C3%A7%C3%A3o/priorizacao/#first-things-first">Priorização: First Things First e Escala de Três Níveis</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-5-watched">Léxico 5</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 17
<details>
  <summary>Requisito: Deve ser exibido no perfil do usuário a quantidade de filmes assistidos pelo usuário </summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/analise/#3-resultados" target='_blank'>DOC58</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us14-exibicao-da-quantidade-de-filmes-assistidos-no-perfil-do-usuario">História de Usuários US14</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Verifica%C3%A7%C3%A3o%20e%20Valida%C3%A7%C3%A3o/Valida%C3%A7%C3%A3o/2-prototipacao/#25-prototipo-05-tempo-de-tela">Protótipo 05</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#35-tema-5-gerenciamento-da-conta">Tema: Gerenciamento da conta</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-5-watched">Léxico 5</a></td>
    </tr>
  </table>
</details>

### Elo de Rastreabilidade 18
<details>
  <summary>Requisito: Deve ser exibido no perfil do usuário a quantidade de horas assistidas pelo usuário</summary>
  <table>
    <tr>
      <th>Artefato Analisado</th>
      <th>Classificação</th>
      <th>Satisfação</th>
      <th>Recurso</th>
      <th>Representação</th>
      <th>Alocado</th>
       <th>Agregação</th>
    </tr>
    <tr>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicita%C3%A7%C3%A3o/analise/#3-resultados" target='_blank'>DOC59</a></td>
      <td>Desenvolvimento</td>
      <td>-</td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/historiaUsuario/#us15-exibicao-da-quantidade-de-horas-assistidas-no-perfil-do-usuario">História de Usuários US15</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Verifica%C3%A7%C3%A3o%20e%20Valida%C3%A7%C3%A3o/Valida%C3%A7%C3%A3o/2-prototipacao/#25-prototipo-05-tempo-de-tela">Protótipo 05</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/Metodologias%20Ageis/backlog/#35-tema-5-gerenciamento-da-conta">Tema: Gerenciamento da conta</a></td>
      <td><a href="https://requisitos-de-software.github.io/2023.1-Letterboxd/Modelagem/lexicos/#lexico-5-watched">Léxico 5</a></td>
    </tr>
  </table>
</details>

## Bibliografia

- SAYÃO, Miriam; LEITE, Julio. Rastreabilidade de Requisitos. PUC-Rio: Departamento de Informática, ISSN 0103-9741, Rio de Janeiro, 2005. Disponível em: <https://www-di.inf.puc-rio.br/~julio/rastre.pdf>. Acesso em: 04 de jul de 2023.
- Toranzo, M.; Castro, J. & Mello, E. "Uma proposta para melhorar o rastreamento de requisitos". In: WER02 - Workshop em Engenharia de Requisitos, Valencia, Espanha, Novembro 11-12, 2002.

## Tabela de Versionamento

| Data       | Versão | Descrição                     | Autor                                                                                              | Revisor                                             |
| ---------- | ------ | ----------------------------- | -------------------------------------------------------------------------------------------------- | --------------------------------------------------- |
| 03/07/2023 | `1.0`  | Adição dos elos | [Clara Ribeiro](https://github.com/clara-ribeiro) | [Natan Santana](https://github.com/Neitan2001) |
