# Procesamiento de Imágenes en Python 🖼️

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue)](https://www.python.org/) [![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org) [![OpenCV](https://img.shields.io/badge/OpenCV-4.x-green)](https://opencv.org)

Este repositorio contiene un cuaderno de Jupyter con ejemplos prácticos de procesamiento de imágenes, realizados en el marco de un módulo de formación del máster. En este proyecto se exploran diversas técnicas fundamentales utilizadas en la visión por computadora para la manipulación y análisis de imágenes.

## 📚 Contenido del proyecto

El cuaderno incluye ejemplos comentados y explicados de las siguientes técnicas:

### 📦 Importación de librerías
Se utilizan librerías populares como OpenCV, NumPy, Matplotlib y PIL para el procesamiento y visualización de imágenes.

### 📥 Carga y visualización de imágenes
- Lectura de imágenes desde disco.
- Conversión de formatos de color (BGR a RGB) para una correcta visualización.

### 🧐 Inspección básica
- Obtención de dimensiones, tamaño y número de canales.
- Visualización de canales de color individuales.
- Cálculo de histogramas de color.

### 🎨 Procesamiento básico de imágenes
- Conversión a blanco y negro y escala de grises.
- Dithering para simular tonos.
- Expansión de rango dinámico y transformación logarítmica.

### 🧠 Conversión de espacios de color
- Transformación entre diferentes espacios (RGB, HSV, etc.).

### 🎯 Umbralización (Thresholding)
- Binzarización de imágenes mediante técnicas de umbralización.

### 🧹 Operaciones morfológicas
- Aplicación de erosiones, dilataciones y otras operaciones para modificar la forma de los objetos.

### 🔎 Contornos
- Detección y visualización de contornos para el análisis estructural de objetos.

### 🧩 Ejercicios prácticos
- **Ejercicio 1:** Segmentación por color.
- **Ejercicio 2:** Conteo de objetos en la imagen.

## 🗂️ Estructura del repositorio

```
/
├── imagenes/
│   └── boat.jpeg
├── procesamiento_imagenes.ipynb
└── README.md
```

## 🎯 Objetivo educativo

Este proyecto tiene como propósito reforzar los conceptos vistos en clase, facilitando la comprensión de las bases del procesamiento de imágenes. Cada sección cuenta con código comentado que explica el por qué y el para qué de cada técnica aplicada.


### 🧪 Comparación visual de resultados

A lo largo del notebook se incluyen comparaciones visuales entre la imagen original y las procesadas, facilitando el análisis del impacto de cada técnica aplicada. Estas visualizaciones paralelas permiten comprender mejor los efectos de umbralización, conversiones de color y operaciones morfológicas.

### 💾 Requisitos mínimos de instalación

Para ejecutar el notebook necesitas tener instaladas las siguientes librerías de Python:

```bash
pip install opencv-python numpy matplotlib pillow
```


## 🚀 Futuras extensiones

Entre las extensiones posibles para proyectos más avanzados se encuentran:

- Segmentación avanzada (Watershed, K-means).
- Detección de objetos.
- Clasificación de imágenes mediante aprendizaje automático.
- Reconstrucción y restauración de imágenes.

---

> 📌 **Nota:** Este notebook se ha desarrollado en el contexto de un módulo formativo del máster, como ejercicio de clase y consolidación de los conceptos impartidos.
