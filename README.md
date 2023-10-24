# Projeto de Machine Learning I

Projeto final do curso de Machine Learning I da Turma Santander Coders 2023 - Trilha de Data Science - Turma 1008.

Integrantes:
- [Anna Clara Amâncio](https://github.com/claraamancio)
- [Karen Almeida](https://github.com/KarenAlmeida23)
- [Manusa Leal](https://github.com/manusaleal)
- [Rhayza Pinto](https://github.com/RhayzaPinto)
- [Raphael](https://github.com/raphaelnfer)

Este projeto tem como objetivo a realização do estudo de previsão de Churn em uma empresa de Telecomunicações, baseado no comportamento dos clientes contido no [dataset de churn](https://www.kaggle.com/datasets/blastchar/telco-customer-churn) disponibilizado no Kaggle. 

O Churn é um tema comumente tratado no mercado, pois é desejável reter estes possíveis clientes que estão passíveis de Churn, de modo que seja criado técnicas de retenção destes clientes e, desta forma, aumentando o faturamento da empresa.

A empresa em questão comercializa os seguintes produtos:
- Serviço de Telefone (incluindo multiplas linhas caso o cliente opte por este serviço adicional);
- Serviço de Internet;
- Segurança Online;
- Backup Online;
- Serviço de proteção de dispositivo;
- Suporte Técnico;
- Streaming de TV;
- Streaming de Filmes.


O dataset possui dados de clientes que realizaram ou não o churn no período de 1 mês e seus respectivos atributos, serviços nos quais cada cliente adquiriu, informações da conta do cliente (há quanto tempo ele é cliente, contrato, forma de pagamento, conta por e-mail, cobranças mensais e cobranças totais) e informações demográficas sobre os clientes (sexo, faixa etária e se possuem companheiros e dependentes).

Os passos seguidos no notebook do projeto foram:

1. **Preparação dos Dados e Verificação de Consistência**;
2. **Análise Exploratória dos Dados**;
3. **Modelagem dos dados**: Comparação entre os modelos re Regressão Logística, XGBoost e KNN;
4. **Otimização do Modelo**: Validação cruzada, otimização de parâmetros com _GridSearchCV_ r _RandomizedSearchCV_;
5. **Conclusões sobre o Projeto**.

[Acesso ao Projeto](Churn_Telco.ipynb)

