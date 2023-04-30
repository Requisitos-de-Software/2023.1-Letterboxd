# Requisitos Elicitados

## Introdução

Este documento apresenta uma lista completa de requisitos do aplicativo Letterboxd, obtidos através da utilização de diversas técnicas de elicitação de requisitos. As técnicas utilizadas incluem [análise de documentos](analise.md), [entrevistas com usuários](entrevista.md), [introspecção](introspeccao.md), [questionários com usuários](perfil.md) e [storytelling](storytelling.md). Os requisitos repetidos foram eliminados.

Os requisitos elicitados abrangem tanto funcionalidades já implementadas no aplicativo, como também requisitos que ainda não foram implementados. Esta lista é uma importante ferramenta para o desenvolvimento futuro do Letterboxd, pois permite entender as necessidades e expectativas dos usuários e, assim, aprimorar a experiência do usuário e agregar valor ao aplicativo.

A partir da análise dos requisitos elicitados, é possível identificar as principais demandas dos usuários, tanto em relação às funcionalidades já existentes quanto às que ainda não foram implementadas. A lista de requisitos aqui apresentada é, portanto, um recurso valioso para orientar o planejamento e desenvolvimento do aplicativo Letterboxd, visando a sua melhoria contínua e satisfação dos usuários.

## Requisitos elicitados

| Identificador | Requisito | Tipo
| ------ | ------ | ------ |
| DOC01 | Deve ser possível registrar usuários e criar contas | RF |
| DOC02 | Deve ser possível adicionar filmes assistidos | RF |
| DOC03 | Deve ser possível avaliar filmes | RF |
| DOC04 | Deve ser possível fazer a resenha de filmes | RF |
| DOC05 | Deve ser possível marcar filmes como favoritos | RF |
| DOC06 | Deve ser possível criar listas de filmes | RF |
| DOC07 | Deve ser possível seguir outros usuários | RF |
| DOC08 | Deve ser possível receber notificações sobre lista de filmes para assistir | RF |
| DOC09 | Deve ser possível filtrar resultados por serviço de streaming | RF |
| DOC10 | Deve ser possível que os usuários desativem suas contas | RF |
| DOC11 | Deve ser exigido que os usuários insiram sua senha ao desativar a conta| RF |
| DOC12 | Deve existir a opção de solicitar a exclusão permanente da conta e de todos os dados associados| RF |
| DOC13 | Deve ser possível a remoção de um filme da lista de assistidos| RF |
| DOC14 | Deve ser possível a adição de entradas retrospectivas no diário para filmes marcados como assistidos| RF |
| DOC15 | Deve ser possível a classificação de um filme como "gostei"| RF |
| DOC16 | Deve ser possível a classificação de um filme com uma nota de avaliação entre 1 e 5 | RF |
| DOC17 | Deve ser possível a edição de uma entrada de diário | RF |
| DOC18 | Deve ser possível a adição de uma avaliação para um filme já registrado | RF |
| DOC19 | Deve ser exibido uma média ponderada de avaliações de filmes| RF |
| DOC20 | Deve ser exibido a lista de filmes semelhantes a um título específico| RF |
| DOC21 | Deve ser exibido os temas e "nanogêneros" de um filme | RF |
| DOC22 | Deve ser possível que o usuário siga outros usuários| RF |
| DOC23 | Deve ser possível que o usuário veja os filmes que seus amigos adicionem| RF |
| DOC24 | Deve ser possível que o usuário veja os comentários que seus amigos façam| RF |
| DOC25 | Deve ser possível a busca por contas para seguir| RF |
| DOC26 | Deve ser possível bloquear outros membros| RF |
| DOC27 | Deve ser possível que o usuário remova comentários feitos por outros membros em seu conteúdo| RF |
| DOC28 | Deve ser possível a formatação básica de texto em avaliações, como negrito, itálico, link e citação| RF |
| DOC29 | Deve ser possível ver as avaliações do usuário em atividades de amigos| RF |
| DOC30 | Para usuários Patron, deve ser possível editar os posters dos filmes | RF |
| DOC31 | Deve ser indicado ao usuário através da cor branca que o filme ainda não foi assistido| RF |
| DOC32 | Deve ser indicado ao usuário através da cor verde que o filme foi assistido| RF |
| DOC33 | Deve ser indicado ao usuário através da cor azul que o filme está na sua lista de filmes| RF |
| DOC34 | Deve ser possível o usuário ter uma assinatura paga Pro| RF |
| DOC35 | Deve ser possível o usuário ter uma assinatura paga Patron| RF |
| DOC36 | Permitir que o usuário presenteie outra pessoa com uma assinatura| RF |
| DOC37 | Deve ser possível a transferência de assinaturas entre contas| RF |
| DOC38 | Deve ser possível exportar todos os dados da conta do usuário, incluindo conteúdo excluído e avaliações para filmes excluídos, em um único arquivo zip de documentos CSV| RF |
| DOC39 | Deve ser possível importar filmes, classificações e listas de outros serviços por meio do formato CSV do Letterboxd| RF |
| DOC40 | Para usuários Patron ou Pro, deve ser possível fixar até duas críticas no perfil| RF |
| DOC41 | Para usuários Patron ou Pro, deve ser possível fixar até duas listas de filmes no perfil| RF |
| DOC42 | Para usuários Patron ou Pro, não deve haver nenhuma publicidade no aplicativo| RF |
| DOC43 | Para usuários Patron ou Pro, deve haver uma página de status, contando com dados quantitativos de todos os filmes assistidos| RF |
| DOC44 | Para usuários Patron ou Pro, deve ser possível definir seus serviços de streaming preferidos| RF |
| DOC45 | Para usuários Patron ou Pro, deve ser possível filtrar os filmes com base nos serviços de streaming definidos| RF |
| DOC46 | Para usuários Patron ou Pro, deve ser enviado um e-mail quando um filme da sua lista de filmes ficar disponível em algum serviço de streaming que esteja definido| RF |
| DOC47 | Para usuários Patron ou Pro, deve ser possível filtrar o feed com base no tipo da atividade | RF |
| DOC48 | Para usuários Patron ou Pro, deve ter a opção de fixar críticas de filmes no perfil| RF |
| DOC49 | Para usuários Patron ou Pro, deve ser possível alterar o nome de usuário a cada 90 dias | RF |
| DOC50 | Deve ser possível sincronizar os dados de serviços de streamings com os dados do aplicativo (quando um filme for assistido em um desses serviços, ele será automaticamente marcado como "Assistido" no aplicativo)| RF |
| DOC51 | Deve ser possível fazer o acompanhamento de séries no aplicativo| RF |
| DOC52 | Deve ser possível avaliar os atores dos filmes | RF |
| DOC53 | Deve ser possível avaliar o diretor dos filmes | RF |
| DOC54 | Deve ser possível reagir com uma emoção sentida no filme (chocado, frustrado, triste, reflexivo, comovido, entretido, assustado, entediado, empolgada, confusa, tensa)| RF |
| DOC55 | Deve ser possível gerar uma lista de recomendações de filmes em comum do usuário e de mais um amigo | RF |
| DOC56 | Deve ser exibido a trilha sonora de cada filme | RF |
| DOC57 | Deve ser possível que os usuários criem e participem de grupos de discussão sobre temas específicos, como gêneros cinematográficos, diretores e filmes clássicos | RF |
| DOC58 | Deve ser exibido no perfil do usuário a quantidade de filmes assistidos pelo usuário | RF |
| DOC59 | Deve ser exibido no perfil do usuário a quantidade de horas assistidas pelo usuário | RF |
| DOC61 | Deve garantir que o acesso à conta desativada seja impedido | RNF |
| DOC62 | Deve garantir que o acesso à conta excluida seja impedido | RNF |
| DOC63 | Deve garantir que os dados associados a contas desativadas sejam protegidos durante o período de desativação e exclusão permanente | RNF |
| DOC64 | Deve ser enviado o link de reativação e o link de exclusão permanente imediatamente após a solicitação do usuário | RNF |
| DOC65 | Deve ser garantido que a conta seja desativada, excluída permanentemente e reativada de acordo com as solicitações do usuário e sem interrupções no serviço | RNF |
| DOC66 | A média ponderada de avaliações de filmes deve considerar apenas uma avaliação por usuário | RNF |
| DOC67 | Deve ser atualizado automaticamente a avaliação do filme quando uma nova avaliação for adicionada | RNF |
| DOC68 | Deve ser enviado um e-mail de confirmação para garantir que o endereço de e-mail associado à conta é válido | RNF |
| DOC69 | Deve ter moderação para remover o conteúdo que viole a política de comunidade, sendo contra à diversidade e inclusão, com discursos de ódio e marginalização | RNF |
| DOC70 | Deve ser limitado a exposição de atividades de amigos de filmes assistidos há mais de duas semanas | RNF |
| DOC71 | Os dados do usuário devem ser atualizados em tempo real, sem a necessidade de atualizar a página ou fechar e abrir o aplicativo novamente | RNF |
| DOC72 | O tempo de resposta do servidor deve ser rápido o suficiente para oferecer uma experiência de usuário satisfatória | RNF |
| DOC73 | Deve ser mantida a privacidade das listas ou watchlists definidas como privadas, exceto para o próprio usuário | RNF |
| DOC74 | Deve ser limitado o tamanho máximo do arquivo de upload para 1 MB | RNF |
| DOC75 | Os dados de filmes do Letterboxd devem ser retirados do The Movie Database (TMDb), uma base de dados colaborativa de informações relacionadas a filmes | RNF |
| DOC76 | Aceitar diversas opções de pagamento, como cartões de crédito, PayPal e transferências bancárias | RNF |
| DOC77 | Quando a assinatura expirar, todos os benefícios das contas Pro e Patron devem ser bloqueados | RNF |
| ENT01 | Aba "Perto de você" que mostre as críticas de usuários na região a fim de facilitar a busca por amigos  | RF |
| ENT02 | Ao clicar no ícone da plataforma disponível, o usuário é redirecionado para o site ou aplicativo com o filme para assistir | RF |
| ENT03 | Poder buscar filmes registrados no diário  | RF |
| ENT04 | Traduzir interface do usuário para português | RNF |
| ENT05 | Registro no diário mais intuitivo e com menos cliques | RNF |
| ENT06 | Botão de traduzir nas críticas que estejam em um idioma diferente do usuário  | RF |
| IT01 | Deve existir um tutorial exibindo as principais funcionalidades da plataforma quando o usuário acessá-la pela primeira vez | RF |
| IT02 | O aplicativo deve permitir que o usuário se registre na plataforma com um email, um nome de usuário e uma senha | RF |
| IT03 | O aplicativo deve permitir que o usuário faça login em sua conta usando seu nome de usuário ou email e senha | RF |
| IT04 | O usuário deve ser capaz de redefinir sua senha | RF |
| IT05 | A plataforma deve permitir que o usuário pesquise e encontre filmes pelo seu nome ou nome do diretor | RF |
| IT06 | A plataforma deve permitir que o usuário pesquise e encontre listas, resenhas, atores, estúdios, outros membros, artigos de jornal e podcas | RF |
| IT07 | O usuário deve poder avaliar os filmes que assiste, em uma escala de classificação de 0 a 5 estrelas, e adicionar comentários e opiniões sobre os filmes | RF |
| IT08 | O usuário deve poder adicionar comentários sobre os filmes | RF |
| IT09 | O aplicativo deve permitir que os usuários criem suas próprias listas de filmes, como "Curtidos", "Assistir mais tarde", ou uma lista personalizada | RF |
| IT10 | O usuário deve poder compartilhar filmes, resenhas, listas e notícias em outras redes sociais, como Facebook, Twitter e Instagram | RF |
| IT11 | O usuário deve poder visualizar e editar seus perfil, adicionar informações como foto de perfil, biografia, localização e filmes preferidos | RF |
| IT12 | O usuário deve poder seguir e ser seguido por outros usuários | RF |
| IT13 | O usuário deve ser capaz de ver suas listas, curtidas, likes, filmes assistidos, seguidores e pessoas que seguem | RF |
| IT14 | O usuário deve ter as opções de sair, desativar e deletar sua conta | RF |
| IT15 | O aplicativo deve exibir estatísticas de um filme, como listas e notícias em que aparece, média das avaliações e membros que já asssitiram | RF |
| IT16 | O aplicativo deve exibir informações um filme, como sinopse, trailer, atores, gênero, linguagem, estúdio e filmes relacionados | RF |
| IT17 | O aplicativo exibir as atividades do usuário e de seus amigos na plataforma | RF |
| IT18 | O usuário deve ser capaz de redefinir sua senha | RF |
| IT19 | O usuário deve ser capaz de personalizar as notificações que recebe no aplicativo e em seu e-mail | RF |
| IT20 | O usuário deve ser capaz de realizar algumas atividades sem ter um cadastro, como ver filmes e suas estatísticas, listas, notícias e resenh |RNF |
| IT21 | Deve existir uma tela principal contento os filmes populares da semana | RF |
| IT22 | Deve existir uma tela exibindo as resenhas populares | RF |
| IT23 | Deve existir uma tela exibindo as listas populares da semana | RF |
| IT24 | Deve existir uma tela exibindo notícias | RF |
| IT25 | O aplicativo deve ter uma versão paga para não exibir anúncios | RF |
| IT26 | O usuário deve conseguir ler os termos de uso e políticas de privacidade pelo aplicativo | RF |
| QST01 | Aba para visualizar listas curtidas, para ter fácil acesso à elas. | RF |
| QST03 | Mover um filme de uma lista para outra | RF |
| QST04 | Adicionar categorias para filmes, séries e animes | RF |
| QST05 | Verificação de onde assistir o filme de acordo com o país do usuário | RNF |
| QST06 | Mandar mensagens para outros usuários | RF |
| QST07 | Sugestão de amigos de acordo com gostos em comum, exclusivo para usuários "Pro" | RF |
| QST08 | Encontrar filmes em comum na "watchlist" de dois ou mais usuários, exclusivos para usuários "Pro" | RF |
| QST09 | Sorteios de pôsteres assinados por elenco de filmes recentes, exclusivo para usuários "Pro" | RF |
| QST10 | Notificar usuários sobre artigos de filmes que estiverem em suas listas | RF |
| QST11 | Colocar artigos relacionados na tela de detalhes do filme | RF |
| QST12 | Refatorar a criação de listas para diminuir a quantidade de cliques necessária e ficar mais intuitiva | RNF |
| QST13 | Sortear filme da watchlist | RF |
| ST01 | Eu, como usuário, desejo poder visualizar um catálogo de filmes, para poder visualizar os filmes que a plataforma tem | RF |
| ST02 | Eu, como usuário, desejo poder pesquisar novos filmes na aba de pesquisa, para poder encontrar filmes que já sei o nome | RF |
| ST03 | Eu, como usuário, desejo poder visualizar a críticas de outros usuários, para poder ter um conhecimento prévio sobre o filme | RF |
| ST04 | Eu, como usuário, desejo poder adicionar comentários para as críticas de outros usuários | RF |
| ST08 | Eu, como usuário, desejo poder compartilhar minhas críticas em outras redes socias, para poder gerar mais visualização para minha crítica | RF |


<div style="text-align: center">
<p>Tabela 1: requisitos elicitados</p>
</div>

## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 27/04/2023 | `1.0`  | Unificação dos requisitos elicitados | [Clara Ribeiro](https://github.com/clara-ribeiro) |  |