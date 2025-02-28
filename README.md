# Analisis-de-los-mejores-Animes-por-a-o-utilizando-NO-SQL-en-MongoDB
En este proyecto analizamos una base de datos de los mejores animes por año, para ello utilizamos NO SQL en MongoDB 

en el archivo word se encuentran todos los analisis, y en el archivo .txt se encuentra todos los codigos utilizados 

Este es el codigo para descargar el Data set desde la API de Kaggle:

import kagglehub

# Download latest version
path = kagglehub.dataset_download("dbdmobile/myanimelist-dataset")

print("Path to dataset files:", path)
