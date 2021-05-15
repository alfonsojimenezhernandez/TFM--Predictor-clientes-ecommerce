# Predictor-clientes-ecommerce
Repositorio que contiene todo el código que se ha desarrollado en el desarrollo del TFM del Master Ciencia de Datos de la Universidad Oberta de Catalunya

## Data
En este directorio se encuentran todos los dataset que se han utilizado en el desarrollo del trabajo. Desde los originales hasta el final, pasando por los dataset limpios.

## Catálogos
En el directorio se encuentran los catálogos que agregan información a nuestro dataset final, que permiten generar nuevas variables.

## Informes de análisis
En formato HTML podemos encontrar los informes generados sobre los diferntes datasets utilizados en el análisis de la información. Generados por la librería *pandas_profile*

## Notebooks de Análisis:
* **Análisis y Limpieza - CONSUMOS.ipynb**  --> Notebook en el que se analizan y se realiza un filtrado de la información correspondiente a los consumos de los usuarios del e-commerce.
* **Análisis y Limpieza - USUARIOS.ipynb**  --> Notebook en el que se analizan y se realiza un filtrado de la información correspondiente a los usuarios de los usuarios del e-commerce.
* **Dataset Final - USUARIOS & CONSUMOS.ipynb**  --> Notebok que tras la limpieza de los datasets originales, realiza la unión de los datasets y la generación de las nuevas variables, que incluye la unión con los catálogos de información.
* **Análisis Dataset Final.ipynb**  --> Notebok que tras la limpieza del dataset final, realiza un análisis de variables, para ver laimportancia de estas, tanto variables numéricas como categóricas.

## Notebooks de Modelo:
* **Modelo_1.ipynb**  --> Notebook con una propuesta inicial, que consta en la aplicación de un modelo de ML, en este caso el elegido fue Random Forest (RF), sobre el que se aplican diferentes técnicas para salvar el problema presente en el dataset, del desbalanceo.
* **Modelo_2- PF.ipynb**  --> Notebook basado en la misma estructura que el notebook *Modelo_1.ipynb*, con la difernecia que el dataset está acotado a los usuarios del tipo Personas Físicas.
* **Modelo_2- PJ.ipynb**  --> Notebook basado en la misma estructura que el notebook *Modelo_1.ipynb*, con la difernecia que el dataset está acotado a los usuarios del tipo Personas Jurídicas.
* **Modelo_3- ALTAS.ipynb**  --> Notebook basado en la misma estructura que el notebook *Modelo_1.ipynb*, con la difernecia que el dataset no busca los potenciales clientes, sino los potenciales usuarios que se darán de alta.
* **Modelo_4- XGBoost.ipynb**  --> Notebook similar a la propuesta del Notebook *Modelo_1.ipynb*, cambiando el algoritmo implementado, en lugar de RF un clasificador de XGBoost.
* **Modelo_5- XGBoost.ipynb**  --> Notebook similar a la propuesta del Notebook *Modelo_1.ipynb*, cambiando el algoritmo implementado, en lugar de RF un clasificador de XGBoost.
* **Modelo_5- XGBoost.ipynb**  --> Notebook similar a la propuesta del Notebook *Modelo_1.ipynb*, cambiando el algoritmo implementado, en lugar de RF un clasificador de XGBoost.
