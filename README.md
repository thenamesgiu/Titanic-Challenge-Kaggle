## DESAFIO TITANIC - KAGGLE

O repositório em questão apresenta minha submissão para o desafio **Titanic - Machine Learning from Disaster** encontrado no <a href="https://www.kaggle.com/competitions/titanic">kaggle</a>. A predição foi realizada utilizando o algoritmo **GradientBoostingClassifier**.

- Para ver como tudo funciona, faça o download do dataset _train.csv_ e _test.csv_ na guia 'Data' no desafio encontrado no kaggle.

## O que foi utilizado?

- pandas;
- seaborn;
- sklearn;
- numpy;
- catboost.

## Processo:

- Tratei alguns dados nulos, sendo **idade** o principal deles, o tratamento foi realizado através da **extração de títulos** (pronome de tratamento) de passageiros a partir da **média** dada para cada título;
- Criei colunas para o **tratamento de títulos** (favorecendo o drop da coluna de nomes) e **integrantes da família** (soma de SibSp e Parch);
- Fiz testes com algoritmos diferentes como: _RandomForestClassifier_, _LogisticRegression_, _LinearSVC_, _K-NearestNeighbors_ e _GradientBoostinClassifer_;

**Score: 0.7799**
