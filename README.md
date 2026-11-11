# Verificador de Idade

Programa simples em Python que pergunta a idade da pessoa e diz se ela é menor de idade, adulta ou idosa.

## Como funciona

O programa mostra um menu em que você pode informar uma idade quantas vezes quiser. Para cada idade, ele responde:

| Idade | Resultado |
|-------|-----------|
| Menor que 0 | "Você não nasceu ainda?" |
| De 0 a 17 | Menor de idade |
| De 18 a 59 | Adulto |
| 60 ou mais | Idoso |

Se você digitar algo que não seja um número, o programa avisa e volta para o menu.

## Como rodar

1. Instale o [Python 3](https://www.python.org/downloads/).
2. Baixe este repositório.
3. No terminal, dentro da pasta do projeto, execute:

```bash
python nome_do_arquivo.py
```

(troque `nome_do_arquivo.py` pelo nome real do seu arquivo)

## O que usei

- `input()` e `int()` para ler a idade
- `if / elif / else` para as faixas de idade
- `while` e `try/except` para o menu e a validação

## Autor

Feito por [meninomalucodemais](https://github.com/meninomalucodemais) como projeto de estudo.
