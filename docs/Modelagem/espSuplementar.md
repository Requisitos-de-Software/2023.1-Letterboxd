# Especificação Suplementar

## 1. Introdução

A Especificação Suplementar, segundo Milene Serrano e Maurício Serrano[¹](#ancora1), trata-se de um documento em linguagem natural, no qual são descritos os requisitos não funcionais de um sistema ou software. O principal objetivo desse documento é capturar requisitos do sistema que não são prontamente capturados em outros artefatos de requisitos comportamentais, como as especificações de caso de uso.

Além disso, o documento pode auxiliar na identificação de outros requisitos[³](#ancora3) , como:

- Requisitos legais e de regulamentação e padrões de aplicativo;
- Atributos de qualidade do sistema a ser criado, incluindo requisitos de usabilidade, confiabilidade, desempenho e suportabilidade;
- Requisitos para os sistemas e ambientes operacionais, compatibilidade com outro software e restrições de design.

## 2. Metodologia

Para a elaboração da Especificação Suplementar, foi utilizado o modelo FURPS+[²](#ancora2) para organizar e abordar os requisitos do sistema. Esse modelo permite categorizar os requisitos em:

- Funcionalidade (Functionality): refere-se aos requisitos funcionais do sistema, ou seja, relacionados às funcionalidades e comportamentos específicos do sistema;

- Usabilidade (Usability): refere-se aos requisitos de usabilidade do sistema. Estão relacionados a facilidade de uso e experiência do usuário e podem incluir fatores como: estética, consistência na interface, ajuda on-line, documentação, matreinamento;

- Confiabilidade (Reliability): refere-se aos requisitos de confiabilidade e estabilidade do sistema. Inclui aspectos de frequência e gravidade de falha, possibilidade de recuperação de falhas e tempo exato e médio entre falhas;

- Desempenho (Performance): Envolve os requisitos relacionados ao desempenho e eficiência do sistema. Isso inclui tempos de resposta, capacidade de processamento, utilização de recursos.

- Suportabilidade (Supportability): Refere-se aos requisitos relacionados ao suporte e manutenção do sistema. Isso inclui aspectos como extensibilidade, adaptabilidade, manutenibilidade, compatibilidade, configurabilidade, escalabilidade, instalabilidade, localizabilidade (ex.: internacionalização) e testabilidade.

- "+" (Plus): Refere-se a restrições de Design (restrições relacionadas ao projeto da arquitetura de software), Implementação (refere-se a restrições sobre a construção do sistema), Interface (são restrições de formatos, tempos ou outros fatores usados por tal interação) e Físicas (limitações quanto ao hardware que deve ser suportado).

## 3. Especificação Suplementar
A seguir, são apresentados os requisitos do aplicativo letterboxd para cada categoria: Funcionalidade, Usabilidade, Confiabilidade, Desempenho e Suportabilidade. Cada categoria de requisito é apresentada em uma tabela, onde cada linha representa um requisito. Cada requisito é identificado por um identificador único, no formato CXX, UXX, DXX, SXX ou FXX, onde C é a abreviação de Confiabilidade, U é a abreviação de Usabilidade, D é a abreviação de Desempenho, S é a abreviação de Suportabilidade e F é a abreviação de Funcionalidade e XX é um número sequencial. Além disso, cada requisito possui uma descrição e um requisito relacionado, que pode ser um requisito funcional ou não funcional. 
### 3.1. Funcionalidade (Functionality)
A categoria funcionalidade enfoca os requisitos funcionais que foram elicitados utilizando as técnicas de análise de documento, introspecção, entrevista e questionário e podem ser conferidos [aqui](https://requisitos-de-software.github.io/2023.1-Letterboxd/Elicitação/requisitos/).
### 3.2. Usabilidade (Usability)
| Identificador | Descrição | Requisito Relacionado |
| :---: | :---: | :---: |
| U01 | Deve ser indicado ao usuário através da cor branca que o filme ainda não foi assistido | DOC31 |
| U02 | Deve ser indicado ao usuário através da cor verde que o filme foi assistido | DOC32 |
| U03 | Deve ser indicado ao usuário através da cor azul que o filme está na sua lista de filmes | DOC33 |
| U04 | Os dados do usuário devem ser atualizados em tempo real, sem a necessidade de atualizar a página ou fechar e abrir o aplicativo novamente | DOC71 |
| U05 | Aceitar diversas opções de pagamento, como cartões de crédito, PayPal e transferências bancárias	 | DOC76 |
| U06 | Traduzir interface do usuário para português	 | ENT04 |
| U07 | Registro no diário mais intuitivo e com menos cliques	 | ENT05 |
| U08 | O usuário deve ser capaz de realizar algumas atividades sem ter um cadastro, como ver filmes e suas estatísticas, listas, notícias e resenhas	 | IT20 |
| U09 | Verificação de onde assistir o filme de acordo com o país do usuário	 | QST05 |


### 3.3. Confiabilidade (Reliability)
| Identificador | Descrição | Requisito Relacionado |
| :---: | :---: | :---: |
| C01 | Deve garantir que o acesso à conta desativada seja impedido | DOC61 |
| C02 | Deve garantir que o acesso à conta excluida seja impedido | DOC62 |
| C03 | Deve garantir que os dados associados a contas desativadas sejam protegidos durante o período de desativação e exclusão permanente | DOC63 |
| C04 | Deve ser garantido que a conta seja desativada, excluída permanentemente e reativada de acordo com as solicitações do usuário e sem interrupções no serviço | DOC65 |
| C05 | Deve ser enviado um e-mail de confirmação para garantir que o endereço de e-mail associado à conta é válido | DOC68 |
| C06 | Deve ter moderação para remover o conteúdo que viole a política de comunidade, sendo contra à diversidade e inclusão, com discursos de ódio e marginalização | DOC69 |
| C07 | Deve ser mantida a privacidade das listas ou watchlists definidas como privadas, exceto para o próprio usuário | DOC73 |
| C08 | Quando a assinatura expirar, todos os benefícios das contas Pro e Patron devem ser bloqueados | DOC77 |

### 3.4. Desempenho (Performance)
| Identificador | Descrição | Requisito Relacionado |
| :---: | :---: | :---: |
| D01 | Deve ser enviado o link de reativação e o link de exclusão permanente imediatamente após a solicitação do usuário | DOC64 |
| D02 | Deve ser atualizado automaticamente a avaliação do filme quando uma nova avaliação for adicionada | DOC67 |
| D03 | O tempo de resposta do servidor deve ser rápido o suficiente para oferecer uma experiência de usuário satisfatória | DOC72 |
| D04 | Deve ser limitado o tamanho máximo do arquivo de upload para 1 MB | DOC72 |

### 3.5. Suportabilidade (Supportability)
| Identificador | Descrição | Requisito Relacionado |
| :---: | :---: | :---: |
| S01 | Deve ser exigido que os usuários insiram sua senha ao desativar a conta | DOC11 |
| S02 | Deve existir a opção de solicitar a exclusão permanente da conta e de todos os dados associados | DOC12 |
| S03 | Deve ser possível desativar contas de usuários | DOC13 |
| S04 | Deve ser possível o usuário ter uma assinatura paga Pro | DOC34 |
| S05 | Deve ser possível o usuário ter uma assinatura paga Patron | DOC35 |
| S06 | Deve ser possível exportar todos os dados da conta do usuário, incluindo conteúdo excluído e avaliações para filmes excluídos, em um único arquivo zip de documentos CSV | DOC38 |
| S07 | Deve ser possível importar filmes, classificações e listas de outros serviços por meio do formato CSV do Letterboxd | DOC39 |
| S08 | Para usuários Patron ou Pro, não deve haver nenhuma publicidade no aplicativo | DOC42 |
| S09 | Os dados de filmes do Letterboxd devem ser retirados do The Movie Database (TMDb), uma base de dados colaborativa de informações relacionadas a filmes | DOC75 |

## 4. Referências Bibliográficas

> - <a id="ancora1"></a>[1] SERRANO, Maurício; SERRANO, Milene; Requisitos - Aula 13. Páginas 28 - 30 Disponível em: Aprender3. Acesso em: 13 de maio de 2023.
> - <a id="ancora2"></a>[2] CARLOS EDUARDO VAZQUEZ; GUILHERME SIQUEIRA SIMÕES. Engenharia de Requisitos. [s.l.] Brasport, 2016. p. 167–168
> - <a id="ancora3"></a>[3] Artefato: Especificações Suplementares. Disponível em: <https://www.cin.ufpe.br/~gta/rup-vc/core.base_rup/workproducts/rup_supplementary_specification_F5ACAA22.html>. Acesso em: 14 maio. 2023.
‌

## 5. Histórico de Versão

|    Data    | Versão |                            Descrição                             |                        Autores                        |                      Revisor                      |
| :--------: | :----: | :--------------------------------------------------------------: | :-------------------------------------------------: | :-----------------------------------------------: |
| 13/05/2023 | `1.0`  | Criação do documento de especificação suplementar | [Maciel Júnior](https://github.com/macieljuniormax), [ArtAssLou](https://github.com/ArtAssLou)  | [Gustavo Barbosa](https://github.com/brbsg) |






