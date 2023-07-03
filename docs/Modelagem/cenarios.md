# Cenários

## Introdução

No campo da Engenharia de Requisitos, cenários são descrições evolutivas de situações num ambiente, sendo compostas por um conjunto ordenado de interações entre seus participantes. No qual a interação se dá entre o sistema em desenvolvimento e os atores externos.[¹](#ancora1) 

## Metodologia

Após a definição dos requisitos na etapa passada, baseado nos requisitos elicitados pela metodologia do Storytelling, foram criados os 5 cenários a seguir:

**Cenário 1: Visualizar catálogo de filmes** <br>
[Lucas Matheus](../Elicita%C3%A7%C3%A3o/personas.md) é um usuário assíduo do aplicativo Letterboxd. Ao abrir o aplicativo, ele acessa a seção de catálogo de filmes, onde pode explorar uma ampla variedade de opções. Ele navega pelas diferentes categorias e gêneros, visualizando cartazes, sinopses e informações relevantes de cada filme. Lucas pode utilizar filtros de classificação e busca para refinar sua pesquisa e encontrar filmes específicos que sejam do seu interesse.

**Cenário 2: Pesquisar novos filmes na aba de pesquisa** <br>
[Lucas Matheus](../Elicita%C3%A7%C3%A3o/personas.md) está em busca de novos filmes para adicionar à sua lista de Watchlist. Ele utiliza a função de pesquisa no aplicativo, digitando palavras-chave relacionadas aos filmes que deseja encontrar. O sistema realiza uma busca abrangente em sua base de dados e exibe os resultados relevantes. Lucas pode explorar os resultados, ler sinopses, avaliações e verificar outras informações importantes para tomar sua decisão.

**Cenário 3: Visualizar críticas de outros usuários** <br>
[Ana Luiza Santana](../Elicita%C3%A7%C3%A3o/personas.md), uma usuária experiente do Letterboxd, está interessada em saber a opinião de outros usuários sobre um filme específico. Ela acessa a página do filme e navega até a seção de críticas. Lá, Ana pode ler as avaliações e comentários deixados por outros usuários, que compartilham suas experiências e perspectivas sobre o filme. Essas críticas ajudam Ana a obter insights adicionais e a tomar decisões informadas sobre os filmes que pretende assistir.

**Cenário 4: Adicionar comentários para as críticas de outros usuários** <br>
[Mauro Júnior](../Elicita%C3%A7%C3%A3o/personas.md), um usuário engajado do Letterboxd, tem uma opinião divergente sobre um filme que assistiu recentemente. Ao ler as críticas de outros usuários, ele encontra uma avaliação que reflete sua visão e decide adicionar um comentário para expressar sua opinião. Mauro escreve um comentário construtivo, compartilhando seus pontos de vista e contribuindo para a discussão em torno do filme. Essa interação permite que Mauro se conecte com outros usuários e compartilhe suas perspectivas.

**Cenário 5: Compartilhar minhas críticas em outras redes sociais** <br>
[Ana Luiza Santana](../Elicita%C3%A7%C3%A3o/personas.md), após assistir a vários filmes e escrever suas críticas detalhadas, decide compartilhá-las com seus amigos em outras redes sociais. Ela utiliza a função de compartilhamento integrada no aplicativo Letterboxd, que permite que ela publique suas críticas diretamente em suas redes sociais favoritas, como Facebook, Twitter ou Instagram. Dessa forma, Ana amplia seu alcance e possibilita que seus amigos também tenham acesso às suas análises e recomendações de filmes.

## Cenários

### C01 - Visualizar catálogo de filmes

O cenário "Visualizar catálogo de filmes" (C01) descreve a ação de acessar e explorar o catálogo de filmes disponíveis no Letterboxd, uma plataforma de compartilhamento e descoberta de filmes. Esse cenário é essencial para os usuários, pois lhes permite explorar uma ampla variedade de filmes, descobrir novas obras, obter informações sobre elas e tomar decisões informadas sobre quais filmes assistir. Na tabela 1 a seguir, estão disponíveis as descrições detalhadas desse cenário.

| Elementos | Respostas |
| --------- | --------- |
| **Léxicos utilizados** | [Léxico 1 - Filmes](./lexicos.md#léxico-1-films)|
| **Objetivo** | Acessar catálago de filmes |
| **Contexto** | - Local: Qualquer tela da aplicação; <br> - Tempo: menos de 1 min; <br> - Pré-condição: Estar logado no app e possuir acesso a internet. |
| **Atores** | Usuários |
| **Recursos** | - Smartphone; <br> - Internet; <br> - Acesso ao app. |
| **Exceção** | - Smartphone descarregado; <br> - Perda de conexão com a internet. |
| **Episódios** | - Usuário abre a aplicação; <br> - Usuário clica no ícone de catálogo (primeiro da esquerda para direita) <br> - Usuário clica em "Polpular this week". |
| **Rastreabilidade** | ST01 |

<div style="text-align: center">
<p>Tabela 1: Cenário C01 (Fonte: Autor, 2023)</p>
</div>

### C02 - Pesquisar novos filmes na aba de pesquisa

O cenário "Pesquisar novos filmes na aba de pesquisa" (C02) descreve a ação de buscar informações sobre filmes desejados na aba de pesquisa do Letterboxd. Essa funcionalidade é fundamental para os usuários, pois lhes permite encontrar dados específicos sobre filmes que desejam assistir. Ao realizar uma pesquisa, os usuários podem digitar o nome do filme desejado e obter resultados relevantes que correspondam à sua pesquisa. Isso facilita a descoberta de novos filmes, a obtenção de informações detalhadas sobre eles e a seleção de obras de acordo com os gostos e interesses de cada usuário. Na tabela 2 a seguir, estão disponíveis as descrições detalhadas desse cenário.

| Elementos | Respostas |
| --------- | --------- |
| **Léxicos utilizados** | - [Léxico 1 - Filmes](./lexicos.md#léxico-1-films) <br> - [Léxico 10: Search](./lexicos.md#léxico-10-search)|
| **Objetivo** | Encontrar dados sobre o filme desejado. |
| **Contexto** | - Local: Qualquer tela da aplicação; <br> - Tempo: entre 1 e 2 min; <br> - Pré-condição: Estar logado no app, possuir acesso a internet e saber o nome do filme que deseja encontrar. |
| **Atores** | Usuários |
| **Recursos** | - Smartphone; <br> - Internet; <br> - Acesso ao app; <br> - Saber o nome do filme. |
| **Exceção** | - Smartphone descarregado; <br> - Perda de conexão com a internet; <br> - Não saber o nome do filme. |
| **Episódios** | - Usuário abre a aplicação; <br> - Usuário clica no ícone de pesquisa (segundo da esquerda para direita); <br> - Usuário clica na barra de pesquisa na parte superio da tela; <br> - Usuário digita o nome do filme que deseja encontar. |
| **Rastreabilidade** | ST02 |

<div style="text-align: center">
<p>Tabela 2: Cenário C02 (Fonte: Autor, 2023)</p>
</div>

### C03 - Visualizar críticas de outros usuários

O cenário "Visualizar críticas de outros usuários" (C03) descreve a ação de acessar e explorar as críticas e avaliações feitas por outros usuários no Letterboxd. Essa funcionalidade é de grande importância para os usuários, pois lhes permite obter diferentes perspectivas e opiniões sobre os filmes que desejam assistir. Ao visualizar as críticas de outros usuários, os usuários podem ter insights, recomendações e até mesmo avaliações detalhadas sobre os filmes, o que auxilia na tomada de decisões informadas sobre o que assistir. Na tabela 3 a seguir, estão disponíveis as descrições detalhadas desse cenário.

| Elementos | Respostas |
| --------- | --------- |
| **Léxicos utilizados** | - [Léxico 1 - Filmes](./lexicos.md#léxico-1-films) <br> - [Léxico 3: Review](./lexicos.md#léxico-3-review)  <br> - [Léxico 6: Comment](./lexicos.md#léxico-6-comment)  <br> - [Léxico 12: Like](./lexicos.md#léxico-12-like)|
| **Objetivo** | Visualizar as críticas de outros usuários sobre determinado filme |
| **Contexto** | - Local: Qualquer tela da aplicação; <br> - Tempo: entre 2 e 3 min; <br> - Pré-condição: Estar logado no app, possuir acesso a internet e saber o nome do filme que deseja visualizar as críticas. |
| **Atores** | Usuários |
| **Recursos** | - Smartphone; <br> - Internet; <br> - Acesso ao app; <br> - Saber o nome do filme. |
| **Exceção** | - Smartphone descarregado; <br> - Perda de conexão com a internet; <br> - Não saber o nome do filme. |
| **Episódios** | - Usuário abre a aplicação; <br> - Usuário clica no ícone de pesquisa (segundo da esquerda para direita); <br> - Usuário clica na barra de pesquisa na parte superio da tela; <br> - Usuário digita o nome do filme que deseja visualizar as críticas; <br> - Usuário clica no filme escolhido; <br> - Usuário clica no botão "Reviews". |
| **Rastreabilidade** | ST03 |

<div style="text-align: center">
<p>Tabela 3: Cenário C03 (Fonte: Autor, 2023)</p>
</div>

### C04 - Adicionar comentários para as críticas de outros usuários

O cenário "Adicionar comentários para as críticas de outros usuários" (C04) descreve a ação de interagir com as críticas feitas por outros usuários no Letterboxd, através da adição de comentários. Essa funcionalidade é essencial para os usuários, pois lhes permite expressar suas opiniões, fornecer feedbacks e iniciar discussões em torno das críticas de filmes feitas por outros usuários. Ao adicionar comentários, os usuários podem compartilhar suas perspectivas, concordar ou discordar das opiniões apresentadas e promover um diálogo construtivo sobre os filmes. Na tabela 4 a seguir, estão disponíveis as descrições detalhadas desse cenário.

| Elementos | Respostas |
| --------- | --------- |
| **Léxicos utilizados** | - [Léxico 3: Review](./lexicos.md#léxico-3-review)  <br> - [Léxico 6: Comment](./lexicos.md#léxico-6-comment)  <br> - [Léxico 12: Like](./lexicos.md#léxico-12-like)|
| **Objetivo** | Comentar as críticas feitas por outros usuários |
| **Contexto** | - Local: Qualquer tela da aplicação; <br> - Tempo: entre 2 e 3 min; <br> - Pré-condição: Estar logado no app, possuir acesso a internet e saber o nome do filme que deseja visualizar as críticas. |
| **Atores** | Usuários |
| **Recursos** | - Smartphone; <br> - Internet; <br> - Acesso ao app; <br> - Ter o email verificado pelo app; <br> - Saber o nome do filme. |
| **Exceção** | - Smartphone descarregado; <br> - Perda de conexão com a internet;  <br> - Não ter o email verificado pelo app; <br> - Não saber o nome do filme. |
| **Episódios** | - Usuário abre a aplicação; <br> - Usuário clica no ícone de pesquisa (segundo da esquerda para direita); <br> - Usuário clica na barra de pesquisa na parte superio da tela; <br> - Usuário digita o nome do filme que deseja visualizar as críticas; <br> - Usuário clica na aba "Reviews" (abaixo da barra de pesquisa); <br> - Usuário clica na Crítica desejada <br> - Usuário adiciona seu comentário na caixa de pesquisa na parte destinada aos comentários. |
| **Rastreabilidade** | ST04 |

<div style="text-align: center">
<p>Tabela 4: Cenário C04 (Fonte: Autor, 2023)</p>
</div>

### C05 - Compartilhar minhas críticas em outras redes socias

O cenário "Compartilhar minhas críticas em outras redes sociais" (C05) descreve a ação de compartilhar as críticas pessoais feitas no Letterboxd em outras plataformas de redes sociais. Essa funcionalidade é significativa para os usuários, pois lhes permite ampliar o alcance das suas opiniões sobre filmes, alcançando um público mais amplo e promovendo interações com outros usuários em diferentes comunidades online. Ao compartilhar suas críticas, os usuários podem disseminar seus insights e recomendações, além de envolver-se em discussões mais abrangentes sobre os filmes em questão. Na tabela 5 a seguir, estão disponíveis as descrições detalhadas desse cenário.

| Elementos | Respostas |
| --------- | --------- |
| **Léxicos utilizados** | - [Léxico 3: Review](./lexicos.md#léxico-3-review)  <br> - [Léxico 6: Comment](./lexicos.md#léxico-6-comment)  <br> - [Léxico 16: Share](./lexicos.md#léxico-16-share)|
| **Objetivo** | Compartilhar minha crítica no aplicativo "Instagram" |
| **Contexto** | - Local: Qualquer tela da aplicação; <br> - Tempo: entre 3 e 4 min; <br> - Pré-condição: Estar logado no app, ter o aplicativo "Instagram" intalado e logado no smartphone e possuir acesso a internet. |
| **Atores** | Usuários |
| **Recursos** | - Smartphone; <br> - Internet; <br> - Ter o aplicativo do "Instagram" instalado <br> - Estar logado no aplicativo "Instagram" <br> - Acesso ao app. |
| **Exceção** | - Smartphone descarregado; <br> - Não ter o aplicativo do "Instagram" instalado <br> - Não estar logado no aplicativo "Instagram" <br> - Perda de conexão com a internet. |
| **Episódios** | - Usuário abre a aplicação; <br> - Usuário clica no ícone de perfil (último da esquerda para direita); <br> - Usuário clica no botão do filme que fez a crítica; <br> - Usuário clica no ícone de "more" (representado pelas reticências no canto superior direito da tela); <br> - Usuário aperta na opção "Share to Instagram Stories". |
| **Rastreabilidade** | ST08 |

<div style="text-align: center">
<p>Tabela 5: Cenário C05 (Fonte: Autor, 2023)</p>
</div>

## Referências Bibliográficas

> - <a id="ancora1"></a>[1] JULIO. Cenários - Rastreamento de Cenários. PUC. RIO Disponível em: <http://www-di.inf.puc-rio.br/~julio/bnncap3.pdf>. Acessado em: 08 mai. 2023.
> - <a id="ancora2"></a>[2] 2021.1 - DisneyPlus, Requisitos de software. Disponível em: <https://github.com/Requisitos-de-Software/2021.1-DisneyPlus/blob/main/docs/modelagem/cenarios.md>. Acesso em: 08 mai. 2023.

## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
|  11/05/2023 | `1.0`  | Criação dos Cenários  | [Rhuan Marques](https://github.com/RhuanMr) | [Clara Ribeiro](https://github.com/clara-ribeiro) |
|  02/07/2023 | `2.0`  | Adição dos léxicos e textos descritivos dos cenários  | [Débora Moreira](https://github.com/deboracaires) |  |
|  02/07/2023 | `3.0`  | Adição das personas na metodologia  | [Débora Moreira](https://github.com/deboracaires) |  |
