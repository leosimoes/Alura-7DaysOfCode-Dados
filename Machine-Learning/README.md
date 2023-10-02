# Alura - 7 Days of Code - Dados - Machine Learning
![7DayOfCode-Logo](../imgs/7DaysOfCode-Logo.jpg)

Instrutora: Letícia Pires

Durante os 7 Days of Code de Machine Learning, você vai treinar suas habilidades de manipulação, 
visualização e análise de dados utilizando Machine Learning. 


## Objetivo
O objetivo será analisar dados do Spotify, 
e aplicar técnicas de Machine Learning para prever a popularidade das músicas e, para isso, 
você passará por diversas etapas de um projeto de Machine Learning, 
desde a coleta de dados e análise exploratória até a validação dos modelos.


## Atividades
Dia 1:
- Baixar os dados de [Kaggle - Spotify Tracks Dataset](https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-datase)
- Carregar os dados em um Jupyter Notebook.
- Fazer análise exploratória dos dados.
- Gerar Profile dos dados em um arquivo html.
- Instalações:
  * `pip install "pydantic==1.*"` (fazer downgrade para que o Profile funcione)
  * `pip install ydata-profiling`
  * `pip install ipywidgets` (se necessário)

Dia 2:
- Pré-Processamento de features.
- Criar coluna 'eh_popular' que substitui 'popularidade'.
- Selecionar apenas algumas das colunas numéricas.
- Normalizar o dataframe.

Dia 3:
- Divisão dos dados em treino (80%) e teste (20%).

Dia 4:
- Criar modelo de linha de base com a regressão logística.
- Exibir coeficientes do modelo.
- Exibir os scores do modelo para dados de treino e dados de teste.
- Exibir a matriz de confusão para dados de treino e dados de teste.

Dia 5:
- Instalar a biblioteca yellowbrick: 
    * `pip install yellowbrick`.
- Plotar as importâncias das features para o modelo.
- Exibir os valores para as métricas precision, recall, f1 e support usando os dados de treino e os de teste.

Dia 6:
- Instalar a biblioteca imbalanced-learn:
    * `pip install imbalanced-learn`
- Realizar a reamostragem de dados com diferentes técnicas.
- Treinar um DecisionTreeClassifier com dados reamostrados e GridSearchCV como otimizador de hiperparâmetros.
- Exibir os valores para as métricas precision, recall, f1 e support usando os dados de treino e os de teste.
- Plotar os nós do modelo DecisionTreeClassifier.

Dia 7:
- Remover e alguns avisos desnecessários.
- Exportar o modelo para um arquivo.
- Revisar o código.
- Adicionar de comentários.


## Referências
Alura - 7 Days of Code - Dados - Machine Learning:
https://7daysofcode.io/matricula/machine-learning
 , acessado em 20/09/2023.

Kaggle - Spotify Tracks Dataset:
https://www.kaggle.com/datasets/maharshipandya/-spotify-tracks-datase
 , acessado em 21/09/2023.

Spotify for Developers:
https://developer.spotify.com/documentation/web-api/reference/get-track
 , acessado em 02/10/2023.

Github - letpires - 7DaysOfCodeSpotifyML:
https://github.com/letpires/7DaysOfCodeSpotifyML
 , acessado em 02/10/2023.

Alura - Conhecendo o Jupyter Notebook: 
https://www.alura.com.br/artigos/conhecendo-o-jupyter-notebook
 , acessado em 02/10/2023.

Google Colab: 
https://colab.research.google.com/
 , acessado em 02/10/2023.

Pandas: 
https://pandas.pydata.org/docs/user_guide/index.html
 , acessado em 23/09/2023.


Linkedin - Traduzindo dados no Pandas.DataFrame() com Google Translate:
https://www.linkedin.com/pulse/traduzindo-dados-pandasdataframe-com-google-translate-romerito-morais/
 , acessado em 21/09/2023.

HastagTreinamentos - Pandas Profiling no Python – Análise de dados rápida:
https://www.hashtagtreinamentos.com/pandas-profiling-no-python-ciencia-dados
 , acessado em 21/09/2023.

Medium - DataHackers: https://medium.com/data-hackers/normalizar-ou-padronizar-as-vari%C3%A1veis-3b619876ccc9
 , acessado em 23/09/2023.


Yellowbrick - Visualizers and API » Model Selection Visualizers » Feature Importances:
https://www.scikit-yb.org/en/latest/api/model_selection/importances.html
, acessado em 27/09/2023.

Medium - DataHackers - Pré-processamento de dados com Python: 
https://medium.com/data-hackers/pr%C3%A9-processamento-de-dados-com-python-53b95bcf5ff4
 , acessado em 02/10/2023.

Medium - Validação Cruzada: Uma abordagem Intuitiva:
https://medium.com/tentando-ser-um-unic%C3%B3rnio/valida%C3%A7%C3%A3o-cruzada-uma-abordagem-intuitiva-697bb001a0ec 
 , acessado em 02/10/2023.

Didática Tech - Underfitting e Overfitting:
https://didatica.tech/underfitting-e-overfitting/
 , acessado em 02/10/2023.

Didática Tech - Como encontrar a melhor performance – Machine Learning:
https://didatica.tech/como-encontrar-a-melhor-performance-machine-learning/
 , acessado em 02/10/2023.

Towards Data Science - Understanding AUC - ROC Curve - Sarang Narkhede:
https://towardsdatascience.com/understanding-auc-roc-curve-68b2303cc9c5
 , acessado em 02/10/2023.

Alura - Como escrever um README incrível no seu Github:
https://www.alura.com.br/artigos/escrever-bom-readme
 , acessado em 02/10/2023.

Joblib:
https://joblib.readthedocs.io/en/latest/
 , acessado em 02/10/2023.

Pickle - 
https://docs.python.org/pt-br/3/library/pickle.html
 , acessado em 02/10/2023.