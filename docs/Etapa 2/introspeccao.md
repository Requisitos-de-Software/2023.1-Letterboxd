# Introspecção

## 1. Introdução

A introspecção, segundo Milene Serrano e Maurício Serrano[¹](#ancora1)  é uma técnica de elicitação de requisitos que requer que o engenheiro de requisitos imagine o que ele gostaria de experimentar ao realizar uma determinada tarefa com os equipamentos e recursos disponíveis. O objetivo é identificar quais características o sistema deve ter para ser bem-sucedido nessa tarefa, permitindo que o engenheiro obtenha uma compreensão mais profunda das necessidades e expectativas do usuário final.

## 2. Elicitação de requisitos

Na tabela 1 estão registrados os cenários de utilização e o comportamento esperado pelo aplicativo Letterboxd, coletados através da técnica de introspecção. Essas informações são importantes para compreender como o aplicativo funciona e quais as expectativas do usuário em relação ao seu funcionamento. Além disso, esses dados podem ajudar a identificar lacunas nos requisitos atuais e orientar para a criação de novos requisitos.

|Cenário|                                      Descrição                                       |           Observação            |  
|:-----:| :--------------------------------------------------------------------------: | :----------------------------: |
|01| Primeiro acesso ao aplicativo | Deve aparecer uma sequência de cards contendo um tutorial das principais funções da plataforma. O último card da lista conterá  botões para entrar ou realizar cadastro na plataforma e outro para ir até as funções que não necessitam de cadastro.   |
|02| Acesso sem cadastro | Deve aparecer uma página com opções para entrar, criar uma conta na plataforma ou ver o tutorial. Na parte inferior da tela deve aparecer um menu para navegar por funções da plataforma que não necessitam de cadastro. |
|03| Ao clicar em Sign in| Deve haver os campos e-mail e senha e o botão para confirmar e entrar na plataforma. Além desses, deve ter um botão para realizar o cadastro, caso o usuário não possua uma conta, e um botão para recuperar a senha. |
|04| Ao clicar em Create account| Deve aparecer os campos endereço de e-mail, username e senha. Além dos campos para aceite dos termos de uso e política de privacidade. Deve haver também um botão para entrar, caso o usuário já tenha conta, e outro para recuperar a senha. Após preencher os campos, o usuário deve confirmar o cadastro através de um botão específico. |
|05| Página principal sem cadastro | Nesta tela deve aparecer uma lista contendo os filmes populares da semana. Acima dessa lista deve conter um menu para ver resenhas e listas de filmes de outros usuários e notícias sobre filmes.    |
|06| Página de pesquisa | Na parte superior deve aparecer uma barra de pesquisa, ao ser selecionada pode-se selecionar, logo abaixo, o que deseja pesquisar, como filmes, resenhas, listas, etc. Abaixo da barra de pesquisa deve ser exibido filtros para a pesquisa, como data de lançamento, gênero, idioma, etc.   |
|07| Ao entrar na plataforma | Deve aparecer um pop up perguntando ao usuário se ele gostaria de navegar pelos filmes populares e avaliá-los. Se clicar em sim, aparecererá uma lista de filmes, na qual para cada um deles o usuário poderá marcar se já o assistiu o filme, dar like, dar uma nota em estrelas e adicionar a lista de assistidos. Se clicar em não, o usuário será redirecionado para a página principal do aplicativo.     |
|08| Página principal com cadastro | Assim como na tela principal sem cadastro, deve aparecer uma lista de filmes e um menu superior para que o usuário possa navegar entre filmes, resenhas, listas e notícias. Deve haver também um botão de adicionar um filme e um menu inferior no qual o usuário pode navegar entre a página principal, página de pesquisa, atividades e perfil.    |
|09| Ao clicar no botão adicionar um filme | O usuário poderá pesquisar por um filme específico e então pode classificá-lo, escrever uma crítica e adicionar outros detalhes, como a data em que assistiu, a avaliação em estrelas, deixar um like, marcar que já o assistiu antes, adicionar tags e marcar se sua resenha contém spoilers.  |
|10| Página de resenhas | Deverá ser exibida uma lista com diversas resenhas de filmes. Ao clicar no filme deverá abrir uma página contento a resenha e cometários de outros usuários, deverá aver um botão permitindo curtir um filme (não funcionará se o usuário estiver deslogado) e uma opção para ir para o filme (mesma página do cenário 13)  |
|11| Página de atividades | Deve aparecer atividades dos usuários ou de seus amigos na plataforma. Deve aparecer na parte superior um menu para navegar entre essas atividades.   |
|12| Perfil do usuário | Ao clicar no perfil do usuário deve ser exibidos atalhos para os filmes que ele já interagiu, resenhas feitas, listas, likes, seguidores, pessoas seguidas, tags e lista de desejos. E um menu superior onde o usuário pode navegar para seu diário, listas e lista de desejo. Acima desse menu deve hacer um botão de configurações e outro de compartilhar.  |
|13| Ao clicar em um filme | Deve ser exibido uma página contendo mais informações sobre o filme, como sinopse, um botão para visualizar o trailer no youtube, elenco e outros detalhes, como país de produção, diretores, idioma, estúdio, etc. Além disso, o usuário poderá visualizar outros membros que assistiram o filme, resenhas sobre o filme e listas em que ele aparece. Ao clicar nos membros que viram o filme, poderão ser adicionados filtros, como usuários que curtiram o filme, usuários que são amigos e fãs do filme. As listas e resenhas também poderão ser filtradas entre de amigos e do usuário. Deve haver também um botão para avaliar um filme (cenário 15)|
|14| Ao clicar no botão para avaliar um filme | Deve ser exibido ao usuário um card com as opções de marcar um filme como visto, curtir, adicionar a lista de desejos, avaliar com estrelas, adicionar à alguma lista e compartilhar o filme. Pode-se também clicar para adicionar umaresenha (mesma página do cenário 09) |
|15| Ao clicar no botão de configurações | Devem ser exibidas ao usuário diversas configurações, como alterar senha, nome, sobrenome, e-mail, localização, website, biografia e pronome que deseja ser chamado. Deve aparecer também opções para adicionar filmes favoritos e adicionar um avatar, com opções de se conectar ao Twitter e ao Facebook. Além disso há opções de notificações, ler políticas de privacidade e termos de uso, desativar e deletar conta.  |

<div style="text-align: center">
<p>Tabela 1: Registro da introspecção. Fonte: Autoria Própria</p>
</div>

## 3. Referências

> - <a id="ancora1"></a>[1] SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 07. Disponível em: Aprender3. Acesso em: 22 de abril de 2023.


## 4. Histórico de Versão

|    Data    | Versão |                                                   Descrição                                                    |                      Autor(es)                      |                 Revisor(es)                 |
| :--------: | :----: | :------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------: | :-----------------------------------------: |
| 22/04/2023 |  `0.1`   | Registro da introspecção e requisitos elicitados a partir dessa. | [Maciel Júnior](https://github.com/macieljuniormax) |  |