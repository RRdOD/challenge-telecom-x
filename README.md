# Challenge Telecom X: análise de evasão de clientes

- Este projeto tem como objetivo principal entender as razões por trás da evasão de clientes (Churn) na empresa Telecom X. Para isso, foi realizada uma análise completa dos dados de clientes para identificar padrões e comportamentos que levam ao cancelamento dos serviços. A análise visa fornecer insights claros e baseados em evidências para guiar a tomada de decisão da empresa e criar estratégias de retenção mais eficazes.

## Tecnologias Utilizadas no Projeto
```
Python: A linguagem de programação principal.

Jupyter Notebook: O ambiente de desenvolvimento para a análise.

Pandas: Biblioteca utilizada para a limpeza e manipulação dos dados.

Matplotlib & Seaborn: Bibliotecas utilizadas para a criação de visualizações e gráficos.
```
## Conclusão
- Com base na análise exploratória dos dados, foi possível identificar os principais fatores de risco para a evasão de clientes. O perfil do cliente com maior probabilidade de Churn é aquele que:
```
Possui contrato Mês-a-mês.

Utiliza o serviço de internet Fibra Ótica.

Paga com Cheque Eletrônico.

Apresenta um gasto diário mais alto.
```
```
Por essa razão, a empresa deve focar seus esforços de retenção nesses grupos de risco, oferecendo incentivos para a permanência, avaliando a qualidade dos serviços e buscando entender as necessidades específicas desses clientes.
```

#### Dicionário de dados

* `customerID`: número de identificação único de cada cliente
* `Churn`: se o cliente deixou ou não a empresa 
* `gender`: gênero (masculino e feminino) 
* `SeniorCitizen`: informação sobre um cliente ter ou não idade igual ou maior que 65 anos 
* `Partner`:  se o cliente possui ou não um parceiro ou parceira
* `Dependents`: se o cliente possui ou não dependentes
* `tenure`:  meses de contrato do cliente
* `PhoneService`: assinatura de serviço telefônico 
* `MultipleLines`: assisnatura de mais de uma linha de telefone 
* `InternetService`: assinatura de um provedor internet 
* `OnlineSecurity`: assinatura adicional de segurança online 
* `OnlineBackup`: assinatura adicional de backup online 
* `DeviceProtection`: assinatura adicional de proteção no dispositivo 
* `TechSupport`: assinatura adicional de suporte técnico, menos tempo de espera
* `StreamingTV`: assinatura de TV a cabo 
* `StreamingMovies`: assinatura de streaming de filmes 
* `Contract`: tipo de contrato
* `PaperlessBilling`: se o cliente prefere receber online a fatura
* `PaymentMethod`: forma de pagamento
* `Charges.Monthly`: total de todos os serviços do cliente por mês
* `Charges.Total`: total gasto pelo cliente