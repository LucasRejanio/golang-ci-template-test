<img alt="Go" src="https://img.shields.io/badge/go-%2300ADD8.svg?&style=for-the-badge&logo=go&logoColor=white"/> <img alt="GitHub Actions" src="https://img.shields.io/badge/github%20actions%20-%232671E5.svg?&style=for-the-badge&logo=github%20actions&logoColor=white"/>

[![build](https://img.shields.io/wercker/build/wercker/go-wercker-api.svg)](https://github.com/LucasRejanio/golang-ci-template-test/actions)


# Lint and Coverage actions template

## Informações

Este repositório serve como modelo para projetos go integrados ao github-actions. Ele consiste em um `hello, world!` utilizando o golang no arquivo de origem `main.go` que é testado de maneira automatizada pela actions `linter_and_codecoverage.yml`. O CI executa alguns linters no código, antes que os testes de unidade sejam executados. Quando o estágio de construção foi bem-sucedido, os artefatos do codecovereage são carregados e disponibilizados como um comentario no seu pull request.

#### Exemplo 

![test-linter-and-codecoverage](https://user-images.githubusercontent.com/52427398/113367382-3b736c00-9332-11eb-8d7f-a9a2cbcd1075.png)

