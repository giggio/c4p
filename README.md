# Repositório de chamadas de palestras em português

Esse repositório se propõe a ser um local central para consultar chamadas de palestras em português (call for papers)
para a área de tecnologia. Qualquer chamada pública de palestras pode ser incluída, seja para reuniões de grupos de
usuários, eventos etc.

O documento está dividido em chamadas de palestras online e presenciais, em ordem de data de fechamento da chamada. Se o
evento permite palestras onlines e presenciais a palestra estará na seção de online, com uma observação.

Chamadas de palestras passadas estão no documento [passado.md](passado.md).

Veja como acrescentar a sua chamada no final do documento.

## Chamadas de palestras para eventos online

| Evento                                           | Abertura   | Fechamento | Híbrido | Observações |
| ------------------------------------------------ | ---------- | ---------- | ------- | ----------- |
| [TDC Future](https://thedevconf.com/call4papers) | 22/08/2022 | 25/09/2022 | x       |             |

## Chamadas de palestras para eventos presenciais

| Evento | Abertura | Fechamento | Observações |
| ------ | -------- | ---------- | ----------- |
| todo   | todo     | todo       |             |

## Contribuindo com sua chamada de palestra

Você pode usar o editor de texto que quiser, desde que rode o
[markdown lint](https://github.com/DavidAnson/markdownlint-cli2) no final. Se estiver usando o VS Code, tem
[uma extensão](https://marketplace.visualstudio.com/items?itemName=DavidAnson.vscode-markdownlint) pronta.

Para rodar o linter na linha de comando você precisa do Node.js instalado. Rode com:

```bash
npx --package=markdownlint-cli2 markdownlint-cli2-config .markdownlint.json "**/*.md" "#node_modules"
```

Ao abrir um PR um workflow vai verificar o linting, também.

## Licença

O repositório está licenciado com a licença MIT. Ao contribuir você concorda com os termos da licença.
