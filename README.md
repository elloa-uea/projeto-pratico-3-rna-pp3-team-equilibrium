# Análise e predição do tipo de cobertura vegetal (Roosevelt National Forest)

Os dados usados neste projeto foram baixados da seguinte base de dados presente no Kaggle: [https://www.kaggle.com/uciml/forest-cover-type-dataset/download](https://www.kaggle.com/uciml/forest-cover-type-dataset/download), cuja documentação oficial pode ser encontrada em [https://archive.ics.uci.edu/ml/datasets/covertype](https://archive.ics.uci.edu/ml/datasets/covertype). Os dados se referem aos tipos de cobertura vegetal presentes em quatro áreas selvagens localizadas na Floresta Nacional Roosevelt, no norte do Colorado, Estado Unidos.

## Exploração e análise do dados

Nesta parte foi feita a exploração dos dados a fim de conhecer melhor a base de dados utilizada, conhecendo não só aspectos teóricos acerca de como cada exemplo foi coletado, mas também aspectos relevante a uma análise de dados, como quantidade de atributo, se havia dados faltantes, o tipo dos atributos e a forma como os atributos qualitativos foram codificados, depois foram feitos gráficos de visualização dos dados com o objetivo de conhecer a distribuição de cada atributo. Todo esse procedimento de conhecimento é necessário para verificar que tipo de tarefa de Aprendizado de Máquina é sugestiva para o problema de predição das coberturas vegetais.

Esta parte está em [Conhecendo o Conjunto de Dados.ipynb] (notebooks/PP3.2 - Conhecendo o Conjunto de Dados.ipynb).

## Testes com redes neurais

Apoś o conhecimento e análise dos dados foram utilizados modelos de redes neurais artificiais do tipo feedforward multilayer perceptron para o problema da classificação multi-classe da cobertura florestal em uma área do Roosevelt National Forest utilizando os atributos quantitativos da base de dados. Foram fetios testes com vários parâmetros diferentes e cada rede testada iterou por 10 vezes, a fim de se obter um resultado mais representativo de cada rede testada. [Proposição e Avaliação de Arquiteturas de Redes Neurais.ipynb] (notebooks/PP3.3 - Proposição e Avaliação de Arquiteturas de Redes Neurais.ipynb).

## Busca do melhor modelo de rede neural

Utilizando as 6 melhores Redes Neurais para o problema da classificação multi-classe da cobertura florestal no conjunto de dados selecionado na etapa anterior foi feita uma busca em grade para a obtenção dos melhores parâmetros para cada uma dos modelos, a fim de descobrir no final qual o melhor modelo encontrado e quais os melhores parâmetros desse modelo no problema da predição do tipo de cobertura vegetal. [Validação Cruzada e Busca em Grade do Melhor Modelo.ipynb](notebooks/PP3.4 - Validação Cruzada e Busca em Grade do Melhor Modelo.ipynb)
