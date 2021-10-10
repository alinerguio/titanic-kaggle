# Titanic Kaggle

[Desafio](https://www.kaggle.com/c/titanic/data) do Kaggle para descobrir se um passageiro sobreviveu ao desastre a partir de suas características.

Utilizamos as bibliotecas de análise e estruturas de dado [pandas](https://pandas.pydata.org/) e [numpy](https://numpy.org/), ferramenta de predição [sklearn](https://scikit-learn.org/stable/) - com o algoritmo [KNN](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm). Além disso, a biblioteca [seaborn](https://seaborn.pydata.org/) para alguns plots básicos para avaliação do resultado.

## Requistos

Para rodar o código você precisará dos seguintes requisitos:  

[![Python Version](https://img.shields.io/badge/python-3.8.2-green)](https://www.python.org/downloads/release/python-382/)

Além disso, rodar essas linhas de código na pasta onde estão os arquivos (quando for a primeira vez) para criação do virtual environment e instalação dos requisitos.
```
$ python3 -m venv env
$ source env/bin/activate
$ pip install -r requirements.txt
  ```
  
## Execução

Para ativar o virtual environment, utilizar a seguinte linha de comando:
```
$ source env/bin/activate
```  

Com o virtual environment ativado, para rodar o notebook, utilizar a seguinte linha de comando:
```
$ jupyter notebook
```

Para sair do jupyter notebook, utilizar Ctrl + c, e para desativar o virtual environment:
```
$ deactivate
```
