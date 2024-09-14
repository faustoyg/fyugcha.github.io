---
title:  "Entrenamiento"
mathjax: true
layout: post
categories: media
---

X_train tiene un tamaño de 26x61 y y_train de 26. De las 26 oraciones se tiene una proporción de (8,6,7,5) correspondientes a consumo, reducir_planilla, reportar_corte y saludo.

## Red Neuronal
Se utilizó una red neuronal de 3 capas y una tasa de aprendizaje de 0.001. Se utiliza CrossEntropyLoss  para predecir las categorías.

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `large` can be used to increase the width of an image or iframe.

![Red](https://github.com/faustoyg/fyugcha.github.io/blob/3c9101d5c76a7821c7ea8e8be1b65cb40391c4ea/assets/red.jpg)

El modelo se guarda en el archivo modelo.pth

![Flower](https://github.com/faustoyg/fyugcha.github.io/blob/497441db5ee526453f4c3cacb18ce72d740d4179/red.jpg)

