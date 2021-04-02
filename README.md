[![build](https://img.shields.io/wercker/build/wercker/go-wercker-api.svg)](https://github.com/LucasRejanio/apply-label-pr-actions/actions)


# Lint and Coverage actions template

## Informações

Este repositório serve como modelo para projetos go integrados ao github-actions. Ele consiste em um `hello, world!` utilizando o goland no arquivo de origem `main.go` que é testado de maneira automatizada pela actions `linter_and_codecoverage.yml`. O CI executa alguns linters no código, antes que os testes de unidade sejam executados. Quando o estágio de construção foi bem-sucedido, os artefatos do codecovereage são carregados e disponibilizados como um comentario no seu pull request.

#### Exemplo 

![test-linter-and-codecoverage](https://user-images.githubusercontent.com/52427398/113367382-3b736c00-9332-11eb-8d7f-a9a2cbcd1075.png)

