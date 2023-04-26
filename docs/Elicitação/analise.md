# Análise de Documentos

## Introdução

A elicitação de requisitos é uma atividade fundamental no processo de desenvolvimento de software, que visa entender as necessidades e expectativas dos usuários e stakeholders para identificar e especificar os requisitos que o sistema deve atender. Existem diversas técnicas e metodologias para realizar essa atividade, e uma delas é a análise de documentos.

A análise de documentos é uma técnica que consiste na revisão de documentos existentes para extrair informações relevantes sobre o domínio do problema e os requisitos do sistema. Esses documentos podem incluir manuais, relatórios, especificações técnicas, normas, regulamentos, entre outros.

A utilização da técnica de análise de documentos para elicitação de requisitos apresenta diversas vantagens. Em primeiro lugar, ela permite que a equipe de desenvolvimento tenha uma visão mais ampla do domínio do problema, compreendendo as particularidades do contexto em que o sistema será utilizado. Além disso, a análise de documentos pode ajudar a identificar requisitos que não foram inicialmente considerados, bem como a validar requisitos já especificados.

Outro benefício da análise de documentos é a possibilidade de reduzir custos e tempo na elicitação de requisitos, uma vez que muitas informações relevantes já podem estar documentadas e prontamente disponíveis. Isso pode acelerar o processo de desenvolvimento e aumentar a eficiência da equipe.

Por essas razões, a análise de documentos é uma técnica amplamente utilizada para elicitação de requisitos, especialmente em projetos complexos e em que há grande quantidade de informações documentadas. Nós optamos por utilizar tanto técnicas que não precisam de interação com o usuário, como a de análise de documentos, quanto técnicas feitas em conjunto com o usuário, como entrevistas, para enriquecer o processo de elicitação de requisitos e garantir a qualidade e a completude da especificação dos requisitos.

## Metodologia

A fonte utilizada para a análise de documentos foi o site [Letterboxd](https://letterboxd.com/). O site contém uma grande quantidade de documentação, incluindo informações sobre suas funcionalidades, sua interface de usuário e seus recursos.

Ao examinar a documentação existente de um sistema ou aplicativo, é possível identificar seus recursos, funcionalidades, limitações e problemas existentes. Essa análise forneceu informações valiosas sobre o que os usuários querem e precisam, bem como sobre como aprimorar ou expandir um sistema ou aplicativo.

No caso do Letterboxd, a análise de documentos foi extremamente útil. O site é uma plataforma madura e estabelecida, com uma ampla base de usuários e muita documentação disponível. Isso permitiu que fossem identificadas funcionalidades importantes para os usuários, bem como opiniões e sugestões para melhorias no site. Além disso, a análise também possibilitou a identificação de recursos e funcionalidades em potencial que ainda não foram implementados no aplicativo, mas que poderiam ser valiosos para os usuários.

A análise de documentos do Letterboxd permitiu obter uma compreensão mais aprofundada do que os usuários esperam e precisam de uma plataforma de avaliação e compartilhamento de filmes. A partir dessas informações, será possível desenvolver um aplicativo mais completo e satisfatório para os usuários.

## Resultados

Os resultados obtidos com a análise de documentos foi registrada na Tabela 1, exibida abaixo, em que *Identificador* é um código para marcar que a fonte desse requisito foi a análise de documentos e o *Tipo* se refere a requisitos funcionais (RF) ou requisitos não funcionais (RNF).

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

<div style="text-align: center">
<p>Tabela 1: requisitos levantados com a análise de documentos</p>
</div>

## Bibliografia

CARLOS EDUARDO VAZQUEZ; GUILHERME SIQUEIRA SIMÕES. Engenharia de Requisitos. [s.l.] Brasport, 2016.

Guia facetado de técnicas elicitação de requisitos. Disponível em: <https://retraining.inf.ufsc.br/guia/app/classificacoes/tecnicas-de-elicitacao-de-requisitos/entidades/tecnicas-de-elicitacao-de-requisitos-analise-de-documentos>. Acesso em: 21 abr. 2023.

Letterboxd Frequent questions. Disponível em: <https://letterboxd.com/about/faq/>. Acesso em: 21 abr. 2023.


## Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 25/04/2023 | `1.0`  | Elicitação por análise de documentos | [Clara Ribeiro](https://github.com/clara-ribeiro) | [Natan Santana](https://github.com/Neitan2001) |