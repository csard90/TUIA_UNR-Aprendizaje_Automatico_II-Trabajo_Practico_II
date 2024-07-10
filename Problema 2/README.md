# Problema 2 - TP N°2 - AAII

## **Enunciado**
En el siguiente problema, se presenta un conjunto de datos correspondientes a resúmenes de artículos de noticias. El objetivo del problema es crear un modelo capaz de generar resúmenes ficticios de forma aleatoria.

#### Dataset:
https://www.tensorflow.org/datasets/catalog/ag_news_subset

El dataset proporcionado incluye 120000 artículos correspondientes a 4 categorías distintas. En este caso, la categoría no es relevante, sólo utilizaremos el dataset como un cuerpo de texto para entrenar un modelo recurrente de generación de texto.

#### Objetivo:
Utilizando el dataset construido, el objetivo es construir modelos de generación de texto utilizando redes neuronales que puedan generar noticias ficticias.

Se solicita experimentar con los siguientes tipos de modelos:

* Caracter a caracter: entrenar un modelo de generación de texto a nivel de caracteres como el correspondiente al Lab10 mencionado anteriormente.

* Palabra a palabra: entrenar un modelo de generación de texto a nivel de palabras, adecuando los procesos de entrenamiento e inferencia según sea necesario.
  
Generar artículos al azar y seleccionar 5 para cada modelo que resulten de interés. Comparar cualitativamente el tipo de resultado que se obtiene para cada tipo de modelo.

*No se requiere un análisis de métricas para este problema, se espera un análisis cualitativo de los resultados obtenidos.*

## **Recursos**
### 'Problema 2a.ipynb'
Contiene el algoritmo correspondiente al modelo de generaecion de texto caracter a caracter.

### 'Problema 2b.ipynb'
Contiene el algoritmo correspondiente al modelo de generaecion de texto palabra a palabra.
