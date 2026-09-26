# Análise de Crédito com Regressão Linear

Projeto acadêmico desenvolvido para aplicação de conceitos de Aprendizado de Máquina utilizando Python e Regressão Linear.

## Objetivo

Desenvolver um modelo de Regressão Linear capaz de estimar o valor de um empréstimo com base nas características de um cliente.

## Dados utilizados

O projeto utiliza o arquivo `base_credito.csv`, contendo informações históricas de clientes e os respectivos valores de empréstimo.

As variáveis utilizadas são:

- `idade` — idade do cliente
- `renda_mensal` — renda mensal do cliente
- `score_credito` — score de crédito
- `historico_pagamentos` — histórico de pagamentos
- `valor_emprestimo` — valor do empréstimo, utilizado como variável alvo

## Tecnologias

- Python
- Google Colab
- Pandas
- Matplotlib
- Scikit-learn

## Etapas do projeto

1. Carregamento e visualização dos dados
2. Identificação das variáveis de entrada e da variável alvo
3. Análise inicial dos dados e visualização gráfica
4. Divisão dos dados em treinamento e teste
5. Criação e treinamento do modelo de Regressão Linear
6. Geração de previsões
7. Avaliação do modelo utilizando MAE e MSE
8. Comparação entre valores reais e previstos
9. Previsão do valor de empréstimo para um novo cliente
10. Análise dos resultados e limitações do modelo

## Avaliação

O modelo foi avaliado utilizando:

- **MAE (Mean Absolute Error):** mede o erro absoluto médio entre os valores reais e previstos.
- **MSE (Mean Squared Error):** calcula a média dos erros ao quadrado, atribuindo maior peso aos erros maiores.

## Resultado

O modelo apresentou um MAE de aproximadamente **R$ 3.001,04**, indicando que, em média, as previsões diferiram dos valores reais em aproximadamente R$ 3.000 no conjunto de teste.

Também foi realizada uma análise visual comparando os valores reais com os valores previstos pelo modelo.

## Observação

Os resultados obtidos são estimativas baseadas no conjunto de dados utilizado. O desempenho do modelo pode variar caso sejam utilizados dados diferentes ou que não representem adequadamente novos clientes.
