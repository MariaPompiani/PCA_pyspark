# Análise de Clustering com PCA em Músicas do Spotify

Este projeto, desenvolvido em Jupyter Notebook, aplica técnicas de redução de dimensionalidade (PCA) e clustering usando PySpark, com foco em descobrir padrões musicais em um conjunto de dados contendo informações sobre 30.000 músicas disponíveis no Spotify.

## Objetivo 
> Aplicar PCA para reduzir a dimensionalidade dos dados musicais.
>Executar clustering (KMeans) para segmentar músicas com características similares.
>Visualizar os agrupamentos resultantes e interpretar os padrões

## Tecnologias Utilizadas
>Python
>Jupyter Notebook
>PySpark (Spark MLlib)
>Pandas / NumPy
>Matplotlib / Seaborn (para visualização)


## Etapas do Projeto
1. Leitura e pré-processamento dos dados
> Conversão para Spark DataFrame
>Seleção de colunas numéricas relevantes

2. Normalização dos dados
> Uso de StandardScaler

3. Redução de dimensionalidade com PCA
> Avaliação da variância explicada
> Seleção dos principais componentes

