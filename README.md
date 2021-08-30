# Desafio GCP Dataproc
O desafio faz parte do curso na plataforma da Digital Innovation One:

__Criando um ecossistema Hadoop totalmente gerenciado com Google Cloud Platform__

O desafio consiste em efetuar um processamento de dados utilizando o produto Dataproc do GCP. Esse processamento irá efetuar a contahem das palavras de um livro e informar quantas vezes cada palavra aparece no mesmo.

## As 10 palavras mais usadas no livro
De acordo com o relatório obtido pelo arquivo `part-00000` as seguintes palavras são as que mais foram usadas no livro:

| # | Palavra | Ocorrências |
|---|:---:|---|
| 1 | the | 4066 |
| 2 | and | 2969 |
| 3 | of | 2746 |
| 4 | I | 2719 |
| 5 | to | 2144 |
| 6 | my | 1631 |
| 7 | a | 1394 |
| 8 | in | 1129 |
| 9 | was | 994 |
| 10 | that | 986 |

Ainda segundo relatório o caractere vazio `''` apareceria em 1186 vezes, ocupando a 8ª posição. Porém, como o caractere vazio não representa uma palavra, foi descartado da lista.
