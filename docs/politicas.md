# Políticas

## 1 - Introdução
Essa página tem como objetivo definir as políticas de branch, commits e pull requests a fim de padronizar e organizar o código do projeto no github. Abaixo será especificado o padrão para cada um desses itens.

## 2 - Políticas de Branch
As branchs devem ser sempre criadas a partir da "master" onde o código mais atual se encontra (Lembre-se de sempre dar um git pull para atualizar a branch master antes de criar outra). A criação da branch deve seguir o seguinte padrão:

```
git checkout -b "X-NomeDaBranch"
```

Onde "X" é o número da issue da Branch e o nome deve estar em PascalCase, ou seja, a primeira letra de cada palavra deve estar maiúscula. O nome deve estar em português.

## 3 - Políticas de Commits
Os commits devem seguir o seguinte padrão:

```
git commit -m "X - mensagem do commit"
```
Onde "X" é o número da issue e da branch e "mensagem do commit" é uma breve descrição do que foi feito no commit em português.

## 4 - Políticas de Pull Requests
Ao finalizar a issue, deve ser aberto no github um pull request da branch para a master. O padrão da Pull Request deve ser o seguinte:

- Título do PR: "X - Nome da Issue"
- Descrição: uma listagem do que foi feito na issue e no final deve ter "Closes #X". Onde "X" é o número da issue.

Um exemplo seria:

Título: 1 - Tema da Wiki e Políticas

Descrição:

    - Mudança do nome do site para o app selecionado
    - Adição da logo do app selecionado
    - Modificação do tema de cores para a palete de cores do app selecionado
    - Adição da página de políticas
    Closes #1

## 5 - Bibliografia

<p><ul>1. KITAMURA, C. Pascal Case e Camel Case: O Que É E Como Usar. Disponível em: <a href="https://celsokitamura.com.br/pascal-case-e-camel-case/#:~:text=J%C3%A1%20Pascal%20Case%20%C3%A9%20a,Pascal%20Case%20e%20camel%20Case.">https://celsokitamura.com.br</a>. Acesso em: 10 abr. 2023.</a>. Acesso em: 10 de abril de 2023.</ul></p>

## 6 - Tabela de Versionamento

| Data | Versão | Descrição | Autor | Revisor |
| ---- | ------ | --------- | ----- | ------- |
| 10/04/2023 | `1.0`  | Criação da página de políticas | [Natan Santana](https://github.com/Neitan2001) | [Clara Ribeiro](https://github.com/clara-ribeiro)
| 15/04/2023 | `2.0`  | Adição da bibliografia | [Natan Santana](https://github.com/Neitan2001) | [Clara Ribeiro](https://github.com/clara-ribeiro)