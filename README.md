# Histogram-FiltersOpenCv
Importar las siguientes librerias:
```
import cv2
import matplotlib.pyplot as plt
import numpy as np
```
## Histogramas
1. Histograma en RGB de la imagen original
2. Imagen a escala de grises y su histograma  
3. Rotacion de 37 grados a la imagen original e histograma solo para el canal *Blue*.

## Filtros
1. Crear una copia de la imagen original y aplicar un **filtro de Gauss** de tamaño *25 × 25*
2. Crear otra copia de la imagen original y aplicar un **filtro de Gauss** de tamaño *29 × 29*
3. Crear otra copia de la imagen original y aplicar un **filtro de Gauss** de tamaño *37 × 37*
4. Crear una copia de la imagen original pero en escala de *grises*.
5. Aplicar a la imagen en escala de grises un **filtro bilateral** con *diámetro de 39*.
6. Aplicar a la imagen en escala de grises un **filtro de mediana** con *kernel de 27*.
7. Aplicar a la imagen en escala de grises un **filtro de caja** con una profundidad de −1,
normalizado y un *tamaño de 30*.
