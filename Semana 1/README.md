<img src="https://github.com/sthemonica/alura-voz/blob/main/logos-alura%20voz/Logo%20Alura%20Voz-01.png" alt="Alura Voc" height="160"/>


## Base de Dados e Dicionário de Dados

 - [Base de Dados Original](https://github.com/sthemonica/alura-voz/blob/main/Dados/Telco-Customer-Churn.json)

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
 

## Trabalho realizado na Semana 1

 - Tradução e padronização dos rótulos das colunas do Data Frame: todos estão escritos em minúsculo, usando underscore como separador
 - Normalização dos demais campos presentes no arquivo json, facilitando sua exploração, visualização e análise
 - Tradução para PT-BR de todos os valores presentes na base de dados já limpa
 - Limpeza de dados nulos na coluna `churn`, representando aproximadamente 3% dos dados originais
 - Substituição dos valores 0/1 para a coluna `idoso` para Sim/Não, seguindo o padrão das demais colunas
 - Conversão de valores do tipo `string` para `float` na coluna `custo_total`
 - Cálculo para os valores inexistentes na coluna `custo_total`, obtidos de 11 clientes que ainda não haviam completado 1 mês de contrato com a Alura Vox
 - Criação da coluna `custo_diario`, inserido antes das colunas `custo_mensal` e `custo_total`
 - Por fim, tudo foi salvo num [novo arquivo json](https://github.com/dan-alvares/Desafio-Data-Science-Alura/blob/main/Semana%201/dados_churn_clean.json) com os dados limpos, padronizados e traduzidos
 
 
## Autores

- [@dan-alvares](https://www.github.com/dan-alvares)

![Badge Job Done](http://img.shields.io/static/v1?label=STATUS&message=FINALIZADO&color=GREEN&style=for-the-badge)  :heavy_check_mark: