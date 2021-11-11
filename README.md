# Análise e predição do tipo de cobertura vegetal (Roosevelt National Forest)

Os dados usados neste projeto foram baixados da seguinte base de dados presente no Kaggle: [https://www.kaggle.com/uciml/forest-cover-type-dataset/download](https://www.kaggle.com/uciml/forest-cover-type-dataset/download), cuja documentação oficial pode ser encontrada em [https://archive.ics.uci.edu/ml/datasets/covertype](https://archive.ics.uci.edu/ml/datasets/covertype). Os dados se referem aos tipos de cobertura vegetal presentes em quatro áreas selvagens localizadas na Floresta Nacional Roosevelt, no norte do Colorado, Estados Unidos.

## Exploração e análise do dados

Nesta parte foi feita a exploração dos dados a fim de conhecer melhor a base de dados utilizada, conhecendo não só aspectos teóricos acerca de como cada exemplo foi coletado, mas também aspectos relevante a uma análise de dados, como quantidade de atributo, se havia dados faltantes, o tipo dos atributos e a forma como os atributos qualitativos foram codificados, depois foram feitos gráficos de visualização dos dados com o objetivo de conhecer a distribuição de cada atributo. Todo esse procedimento de conhecimento é necessário para verificar que tipo de tarefa de Aprendizado de Máquina é sugestiva para o problema de predição das coberturas vegetais.

Esta parte está em [Conhecendo o Conjunto de Dados.ipynb](https://github.com/elloa-uea/projeto-pratico-3-rna-pp3-team-equilibrium/blob/main/notebooks/PP3.2%20-%20Conhecendo%20o%20Conjunto%20de%20Dados.ipynb).

## Testes com redes neurais

Apoś o conhecimento e análise dos dados foram utilizados modelos de redes neurais artificiais do tipo feedforward multilayer perceptron para o problema da classificação multi-classe da cobertura florestal em uma área do Roosevelt National Forest utilizando os atributos quantitativos da base de dados. Foram feitos testes com vários parâmetros diferentes e cada rede testada iterou por 10 vezes, a fim de se obter um resultado mais representativo de cada rede testada. [Proposição e Avaliação de Arquiteturas de Redes Neurais.ipynb](https://github.com/elloa-uea/projeto-pratico-3-rna-pp3-team-equilibrium/blob/main/notebooks/PP3.3%20-%20Proposi%C3%A7%C3%A3o%20e%20Avalia%C3%A7%C3%A3o%20de%20Arquiteturas%20de%20Redes%20Neurais.ipynb).

## Busca do melhor modelo de rede neural

Utilizando as 6 melhores Redes Neurais para o problema da classificação multi-classe da cobertura florestal no conjunto de dados selecionado na etapa anterior foi feita uma busca em grade para a obtenção dos melhores parâmetros para cada uma dos modelos, a fim de descobrir no final qual o melhor modelo encontrado e quais os melhores parâmetros desse modelo no problema da predição do tipo de cobertura vegetal. [Validação Cruzada e Busca em Grade do Melhor Modelo.ipynb](https://github.com/elloa-uea/projeto-pratico-3-rna-pp3-team-equilibrium/blob/main/notebooks/PP3.4%20-%20Valida%C3%A7%C3%A3o%20Cruzada%20e%20Busca%20em%20Grade%20do%20Melhor%20Modelo.ipynb).
