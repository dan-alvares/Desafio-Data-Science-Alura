
![Logo](https://www.alura.com.br/assets/img/challenges/bi/challenges-logo-2.svg)


# 1º Challenge de Data Science da Alura

Nesse challenge, será desenvolvido para o Alura Voz um conjunto de análises e modelos de machine learning supervisionados, para auxiliar na fidelização dos seus clientes de maneira mais assertiva.

Após uma reunião com a equipe de vendas, você recebeu a base de dados dos clientes e sua tarefa será analisar estas informações e desenvolver seus primeiros modelos, de maneira a atender esta empresa.


## Base de Dados e Dicionário de Dados

 - [Base de Dados Original](https://github.com/dan-alvares/Desafio-Data-Science-Alura/blob/main/Telco-Customer-Churn.json)
 - [Dicionário da Base de Dados](https://github.com/sthemonica/alura-voz/blob/main/dicionario.md)
 
## Cronograma do Challenge

 - [Lançamento da Semana 1](https://www.alura.com.br/challenges/data-science/semana-01-primeiros-passos-data-science): 09/05/2022
 - Lançamento da Semana 2: 16/05/2022
 - Lançamento da Semana 3 e 4: 23/05/2022

## Trabalho realizado na Semana 1
Primeiros passos em Data Science - limpeza dos dados trazidos de uma API.

Notebook da semana 1: acesse clicando [aqui](https://github.com/dan-alvares/Desafio-Data-Science-Alura/blob/main/Desafio_Semana_1.ipynb).
 - Tradução e padronização dos rótulos das colunas do Data Frame: todos agoram escritos em minúsculo, usando underscore como separador
 - Normalização dos demais campos presentes no arquivo json, facilitando sua exploração e visualização
 - Tradução para PT-BR de todos os valores presentes na base de dados limpa
 - Limpeza de dados nulos na coluna 'churn'
 - Substituição dos valores 0/1 para a coluna 'idoso' para Sim/Não, seguindo o padrão das demais colunas
 - Conversão de valores do tipo string para float na coluna 'custo_total'
 - Remoção de valores nulos presente na coluna 'custo_total'
 - Criação da coluna 'custo_diario', inserido na posição 18 da base de dados organizada
 - Por fim, tudo foi salvo num [novo arquivo json](https://github.com/dan-alvares/Desafio-Data-Science-Alura/blob/main/dados_churn_clean.json) com os dados limpos, padronizados e traduzidos
## Autores

- [@dan-alvares](https://www.github.com/dan-alvares)

