---
title: "Preprocesamiento"
layout: post
---

## Introducción
Como proyecto final de clase se ha implementado un Chatbot con temática de atención al cliente de una empresa eléctrica.

Los datos de texto para el entrenamiento están en un archivo json y consisten de 26 oraciones y 4 categorías:

* Saludos
* Curva de consumo
* Reducir planilla
* Reportar corte

Se probó distintos procesamientos de la variable "all_words"

|       Técnica       |   Número palabras   |
|---------------------|---------------------|
| Tokenización        |         129         | 
| Stemming NLTK       |         61          |
| Lematizacion NLTK   |         58          |
| Lematizacion Stanza |         57          |

Se trabajó con Stemming de NLTK utilizando como stemmer SnowballStemmer

```python
stemmer = SnowballStemmer("spanish")
def stem(word):
    return stemmer.stem(word.lower())
```

Con estas consideraciones se forma Bag of Words de donde se obtiene los datos de entrenamiento.


