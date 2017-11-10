# Generador de Textos con RNN

En este proyecto trataremos de crear textos nuevos a partir de algunos documentos ya escritos, es decir,
textos ya elaborados en donde la Red Neuronal Recurrente (RNN), tratara de imitar la forma en como
escribe cierto autor.


## ¿Qué es una RNN?

Básicamente es una red neuronal que se puede utilizar cuando tus datos se tratan como una secuencia, 
donde el orden de los datos es importante y esta secuencia de datos puede ser de una longitud arbitraria.


Tenemos una serie temporal de números, donde el objetivo principal es predecir el siguiente valor 
conociendo los valores previos. La entrada al RNN en cada paso de tiempo es el valor actual, así como 
un vector de estado que representa lo que la red ha "visto" en pasos de tiempo anteriores.
Este vector de estado es la memoria codificada del RNN, inicialmente configurada a cero.

![](img/RNN_img.png)

