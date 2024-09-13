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

![Flower](https://user-images.githubusercontent.com/4943215/55412447-bcdb6c80-5567-11e9-8d12-b1e35fd5e50c.jpg)

[Flower](https://unsplash.com/photos/iGrsa9rL11o) by Tj Holowaychuk

## Lists

### Unordered

* First item
* Second item
* Third item
    * First nested item
    * Second nested item

### Ordered

1. First item
2. Second item
3. Third item
    1. First nested item
    2. Second nested item
