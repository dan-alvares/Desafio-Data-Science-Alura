![Logo](https://www.alura.com.br/assets/img/challenges/bi/challenges-logo-2.svg)


# 1º Challenge de Data Science da Alura

Nesse challenge, será desenvolvido para o Alura Voz um conjunto de análises e modelos de machine learning supervisionados, para auxiliar na fidelização dos seus clientes de maneira mais assertiva.

Após uma reunião com a equipe de vendas, você recebeu a base de dados dos clientes e sua tarefa será analisar estas informações e desenvolver seus primeiros modelos, de maneira a atender esta empresa.


## Base de Dados e Dicionário de Dados

 - [Base de Dados Original](https://github.com/dan-alvares/Desafio-Data-Science-Alura/blob/main/Telco-Customer-Churn.json)

## Dicionário da Base de Dados

#### Cliente:
* `gender`: gênero (masculino e feminino) 
* `SeniorCitizen`: informação sobre um cliente ter ou não idade igual ou maior que 65 anos 
* `customerID`: número de identificação único de cada cliente
* `Partner`:  se o cliente possui ou não um parceiro ou parceira
* `Dependents`: se o cliente possui ou não dependentes

#### Variável Target:
* `Churn`: se o cliente deixou ou não a empresa 

#### Serviço de Telefonia:
* `tenure`:  meses de contrato do cliente
* `PhoneService`: assinatura de serviço telefônico 
* `MultipleLines`: assisnatura de mais de uma linha de telefone 

#### Serviço de Internet:
* `InternetService`: assinatura de um provedor internet 
* `OnlineSecurity`: assinatura adicional de segurança online 
* `OnlineBackup`: assinatura adicional de backup online 
* `DeviceProtection`: assinatura adicional de proteção no dispositivo 
* `TechSupport`: assinatura adicional de suporte técnico, menos tempo de espera
* `StreamingTV`: assinatura de TV a cabo 
* `StreamingMovies`: assinatura de streaming de filmes 

#### Contrato:
* `Contract`: tipo de contrato
* `PaperlessBilling`: se o cliente prefere receber online a fatura
* `PaymentMethod`: forma de pagamento
* `Charges.Monthly`: total de todos os serviços do cliente por mês
* `Charges.Total`: total gasto pelo cliente
 
## Cronograma do Challenge

 - [Lançamento da Semana 1](https://www.alura.com.br/challenges/data-science/semana-01-primeiros-passos-data-science): 09/05/2022
 - [Lançamento da Semana 2](https://www.alura.com.br/challenges/data-science/semana-02-explorando-os-dados): 16/05/2022
 - Lançamento da Semana 3 e 4: 23/05/2022

## Trabalho realizado na Semana 1
Primeiros passos em Data Science - limpeza dos dados trazidos de uma API.

Notebook da semana 1: acesse clicando [aqui](https://github.com/dan-alvares/Desafio-Data-Science-Alura/blob/main/Desafio_Semana_1.ipynb).
 - Tradução e padronização dos rótulos das colunas do Data Frame: todos agoram escritos em minúsculo, usando underscore como separador
 - Normalização dos demais campos presentes no arquivo json, facilitando sua exploração, visualização e análise
 - Tradução para PT-BR de todos os valores presentes na base de dados limpa
 - Limpeza de dados nulos na coluna `churn`, representando aproximadamente 3% dos dados originais
 - Substituição dos valores 0/1 para a coluna `idoso` para Sim/Não, seguindo o padrão das demais colunas
 - Conversão de valores do tipo `string` para `float` na coluna `custo_total`
 - Cálculo para os valores inexistentes na coluna `custo_total`, obtidos de 11 clientes que ainda não haviam completado 1 mês de contrato com a Alura Vox
 - Criação da coluna `custo_diario`, inserido antes das colunas `custo_mensal` e `custo_total`
 - Por fim, tudo foi salvo num [novo arquivo json](https://github.com/dan-alvares/Desafio-Data-Science-Alura/blob/main/dados_churn_clean.json) com os dados limpos, padronizados e traduzidos
 
## Trabalho realizado na Semana 2

Work in Progress:
Em breve será atualizado!
 
## Autores

- [@dan-alvares](https://www.github.com/dan-alvares)

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)