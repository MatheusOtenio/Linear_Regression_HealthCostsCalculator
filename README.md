## Linear Regression Health Costs Calculator

Este projeto foi desenvolvido como parte do currículo "Machine Learning with Python" da freeCodeCamp, com o objetivo de prever os custos de saúde utilizando um algoritmo de **Regressão Linear**. O modelo foi construído utilizando **Machine Learning** e a biblioteca **scikit-learn**.

O modelo foi treinado utilizando um conjunto de dados que contém informações sobre diferentes pessoas, incluindo seus custos de saúde. O objetivo é prever os custos de saúde com base em novas informações fornecidas. O conjunto de dados foi dividido em **80%** para treinamento e **20%** para testes.

### Exemplo de execução:

O código foi treinado utilizando o dataset de treinamento e avaliado com o dataset de teste. A função final verifica se o **MAE** do modelo é inferior a **3500**, o que significa que ele faz previsões com um erro menor que **$3500**.

### Pré-processamento dos dados:
Para garantir a qualidade das previsões, os dados categóricos foram convertidos em valores numéricos e o conjunto de dados foi dividido em **train_dataset** e **test_dataset**. A coluna "expenses" foi separada para formar os **train_labels** e **test_labels**.

## Resultado

No meu projeto, consegui criar um modelo de regressão linear funcional que prevê os custos de saúde com um erro absoluto médio abaixo de **3500 dólares**, o que demonstra a capacidade do modelo em generalizar e fazer previsões precisas.
![Gráfico](RegressaoLinear.png)
## Referências

- [freeCodeCamp](https://github.com/freeCodeCamp)  
- [Mephistopheles-0](https://github.com/Mephistopheles-0)
