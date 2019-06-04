# Analise_de_Filmes

Dados adquiridos no site da "Kaggle", na pasta "Movie industry"

## Importando bibliotecas

    import numpy as np
    import pandas as pd
    import matplotlib.pyplot as plt
    import seaborn as sb

## Selecionando o arquivo csv (excel)

    filmes = pd.read_csv('movies.csv')

### Verificando a tabela do excel

    filmes.head()

## Analisando paises que mais produzem filmes

Vendo o log de valores pelo pandas usando o codigo

    plt.style.use("ggplot")
    print(filmes['country'].unique())


