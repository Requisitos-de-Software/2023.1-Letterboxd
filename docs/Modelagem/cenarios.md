# Cenários

## Introdução

No campo da Engenharia de Requisitos, cenários são descrições evolutivas de situações num ambiente, sendo compostas por um conjunto ordenado de interações entre seus paryicipantes. No qual a interação se dá entre o sistema em desenvolvimento e os atores externos.[¹](#ancora1) 

## Metodologia

Após a definição dos requisitos na etapa passada, baseado nos requisitos elicitado pela metodologia do Storytelling, foram criados 5 cenários representados pelas tabelas 1 à 5.[²](#ancora2)

## Cenários

### C01 - Visualizar catálogo de filmes

| Elementos | Respostas |
| --------- | --------- |
| **Objetivo** | Acessar catálago de filmes |
| **Contexto** | - Local: Qualquer tela da aplicação; <br> - Tempo: menos de 1 min; <br> - Pré-condição: Estar logado no app e possuir acesso a internet. |
| **Atores** | Usuários |
| **Recursos** | - Smartphone; <br> - Internet; <br> - Acesso ao app. |
| **Exceção** | - Smartphone descarregado; <br> - Perda de conexão com a internet. |
| **Episódios** | - Usuário abre a aplicação; <br> - Usuário clica no ícone de catálogo (primeiro da esquerda para direita) <br> - Usuário clica em "Polpular this week". |
| **Rastreabilidade** | ST01 |

<div style="text-align: center">
<p>Tabela 1: Cenário C01 (Fonte: Autor,2023)</p>
</div>

### C02 - Pesquisar novos filmes na aba de pesquisa

| Elementos | Respostas |
| --------- | --------- |
| **Objetivo** | Encontrar dados sobre o filme desejado. |
| **Contexto** | - Local: Qualquer tela da aplicação; <br> - Tempo: entre 1 e 2 min; <br> - Pré-condição: Estar logado no app, possuir acesso a internet e saber o nome do filme que deseja encontrar. |
| **Atores** | Usuários |
| **Recursos** | - Smartphone; <br> - Internet; <br> - Acesso ao app; <br> - Saber o nome do filme. |
| **Exceção** | - Smartphone descarregado; <br> - Perda de conexão com a internet; <br> - Não saber o nome do filme. |
| **Episódios** | - Usuário abre a aplicação; <br> - Usuário clica no ícone de pesquisa (segundo da esquerda para direita); <br> - Usuário clica na barra de pesquisa na parte superio da tela; <br> - Usuário digita o nome do filme que deseja encontar. |
| **Rastreabilidade** | ST02 |

<div style="text-align: center">
<p>Tabela 2: Cenário C02 (Fonte: Autor,2023)</p>
</div>

### C03 - Visualizar críticas de outros usuários

| Elementos | Respostas |
| --------- | --------- |
| **Objetivo** | Visualizar as críticas de outros usuários sobre determinado filme |
| **Contexto** | - Local: Qualquer tela da aplicação; <br> - Tempo: entre 2 e 3 min; <br> - Pré-condição: Estar logado no app, possuir acesso a internet e saber o nome do filme que deseja visualizar as críticas. |
| **Atores** | Usuários |
| **Recursos** | - Smartphone; <br> - Internet; <br> - Acesso ao app; <br> - Saber o nome do filme. |
| **Exceção** | - Smartphone descarregado; <br> - Perda de conexão com a internet; <br> - Não saber o nome do filme. |
| **Episódios** | - Usuário abre a aplicação; <br> - Usuário clica no ícone de pesquisa (segundo da esquerda para direita); <br> - Usuário clica na barra de pesquisa na parte superio da tela; <br> - Usuário digita o nome do filme que deseja visualizar as críticas; <br> - Usuário clica no filme escolhido; <br> - Usuário clica no botão "Reviews". |
| **Rastreabilidade** | ST03 |

<div style="text-align: center">
<p>Tabela 3: Cenário C03 (Fonte: Autor,2023)</p>
</div>

### C04 - Adicionar comentários para as críticas de outros usuários

| Elementos | Respostas |
| --------- | --------- |
| **Objetivo** | Comentar as críticas feitas por outros usuários |
| **Contexto** | - Local: Qualquer tela da aplicação; <br> - Tempo: entre 2 e 3 min; <br> - Pré-condição: Estar logado no app, possuir acesso a internet e saber o nome do filme que deseja visualizar as críticas. |
| **Atores** | Usuários |
| **Recursos** | - Smartphone; <br> - Internet; <br> - Acesso ao app; <br> - Ter o email verificado pelo app; <br> - Saber o nome do filme. |
| **Exceção** | - Smartphone descarregado; <br> - Perda de conexão com a internet;  <br> - Não ter o email verificado pelo app; <br> - Não saber o nome do filme. |
| **Episódios** | - Usuário abre a aplicação; <br> - Usuário clica no ícone de pesquisa (segundo da esquerda para direita); <br> - Usuário clica na barra de pesquisa na parte superio da tela; <br> - Usuário digita o nome do filme que deseja visualizar as críticas; <br> - Usuário clica na aba "Reviews" (abaixo da barra de pesquisa); <br> - Usuário clica na Crítica desejada <br> - Usuário adiciona seu comentário na caixa de pesquisa na parte destinada aos comentários. |
| **Rastreabilidade** | ST04 |

<div style="text-align: center">
<p>Tabela 4: Cenário C04 (Fonte: Autor,2023)</p>
</div>


### C05 - Compartilhar minhas críticas em outras redes socias

| Elementos | Respostas |
| --------- | --------- |
| **Objetivo** | Compartilhar minha crítica no aplicativo "Instagram" |
| **Contexto** | - Local: Qualquer tela da aplicação; <br> - Tempo: entre 3 e 4 min; <br> - Pré-condição: Estar logado no app, ter o aplicativo "Instagram" intalado e logado no smartphone e possuir acesso a internet. |
| **Atores** | Usuários |
| **Recursos** | - Smartphone; <br> - Internet; <br> - Ter o aplicativo do "Instagram" instalado <br> - Estar logado no aplicativo "Instagram" <br> - Acesso ao app. |
| **Exceção** | - Smartphone descarregado; <br> - Não ter o aplicativo do "Instagram" instalado <br> - Não estar logado no aplicativo "Instagram" <br> - Perda de conexão com a internet. |
| **Episódios** | - Usuário abre a aplicação; <br> - Usuário clica no ícone de perfil (último da esquerda para direita); <br> - Usuário clica no botão do filme que fez a crítica; <br> - Usuário clica no ícone de "more" (representado pelas reticências no canto superior direito da tela); <br> - Usuário aperta na opção "Share to Instagram Stories". |
| **Rastreabilidade** | ST08 |

<div style="text-align: center">
<p>Tabela 5: Cenário C05 (Fonte: Autor,2023)</p>
</div>

## Referências Bibliográficas

> - <a id="ancora1"></a>[1] JULIO. Cenários - Rastreamento de Cenários. PUC. RIO Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acessado em: 08 mai. 2023.
> - <a id="ancora2"></a>[2] 2021.1 - DisneyPlus, Requisitos de software. Disponível em: <https://github.com/Requisitos-de-Software/2021.1-DisneyPlus/blob/main/docs/modelagem/cenarios.md>. Acesso em: 08 mai. 2023.

## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
|  11/05/2023 | `1.0`  | Criação dos Cenários  | [Rhuan Marques](https://github.com/RhuanMr) | [Clara Ribeiro](https://github.com/clara-ribeiro) |
