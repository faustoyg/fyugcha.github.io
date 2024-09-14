---
title:  "Entrenamiento"
mathjax: true
layout: post
categories: media
---

X_train tiene un tamaño de 26x61 y y_train de 26. De las 26 oraciones se tiene una proporción de (8,6,7,5) correspondientes a consumo, reducir_planilla, reportar_corte y saludo.

## Red Neuronal
Se utilizó una red neuronal de 3 capas y una tasa de aprendizaje de 0.001. Se utiliza CrossEntropyLoss  para predecir las categorías.

![Red](https://raw.githubusercontent.com/faustoyg/fyugcha.github.io/master/red.jpg)

El modelo se guarda en el archivo modelo.pth


