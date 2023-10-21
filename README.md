# Projeto de Machine Learning I

Projeto final do curso de Machine Learning I da Turma Santander Coders 2023 - Trilha de Data Science - Turma 1008.

Integrantes:
- Anna Clara Amâncio
- [Karen Almeida](https://github.com/KarenAlmeida23)
- [Manusa Leal](https://github.com/manusaleal)
- [Rhayza](https://github.com/RhayzaPinto)
- Raphael

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

**ALTERAR AS INFORMAÇÕES ABAIXO DE ACORDO COM O QUE FIZERMOS NO PROJETO**

1. **Preparação dos Dados e Verificação de Consistência**: Neste tópico deve ser feita a verificação da consistência dos dados e caso necessário efetuar eventuais modificações na base de dados. Alguns dos procedimentos que podemos fazer aqui são: Remoção e/ou tratamento de valores faltantes, remoção de duplicatas, ajustes dos tipos de variáveis, análise de _outliers_ entre outras;

2. **Análise Exploratória dos Dados**: Para fazermos a modelagem, precisamos conhecer muito bem os dados que estamos trabalhando. Por isso, nesta parte do projeto vocês desenvolveram análises e gráficos a respeito dos dados que estão utilizando. Tente tirar ao máximo informações sobre as variáveis em si e suas relações com as demais;

3. **Modelagem dos dados**: Nessa parte, deve ser definido o tipo de problema (classificação/regressão). Vocês precisam **treinar pelo menos três (3) modelos** (pode ser testado mais que três modelos distintos) e de acordo com alguma métrica de avaliação (escolhida pelo grupo), decidir qual será o melhor modelo a ser utilizado!;

4. **Otimização do Modelo**: A partir do modelo escolhido no tópico anterior, vamos tentar aprimorar e garantir um melhor desempenho no modelo, seja fazendo validação cruzada, otimização de parâmetros com _GridSearchCV_ ou _RandomizedSearchCV_ e até mesmo testar diferentes _thresholds_ (ao invés de utilizar a função _predict_ do modelo, utilize a função _predict_proba_ do modelo e a partir das probabilidades determinar qual vai ser o limiar onde será considerado um caso positivo ou negativo);

5. **Conclusões sobre o Projeto**: Para finalizar, descreva as suas conclusões sobre o desenvolvimento do modelo e os resultados obtidos.

[Acesso ao Projeto](Churn_Telco.ipynb)

