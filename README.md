# 🍫 Predicting Cocoa Yields in Colombia using Machine Learning 🍫 

This repository contains the code and data used for the development of a machine learning model that predicts cocoa production yields in the department of Santander - Colombia. The project is based on historical production data and several environmental variables, with the objective of optimizing planning and decision making in cocoa agriculture.

## 📖 Description 

Este proyecto utiliza diversos modelos de machine learning, incluyendo regresión lineal, árboles de decisión y bosques aleatorios, para predecir la producción de cacao en el departamento de Santander, Colombia. El objetivo principal es desarrollar herramientas que permitan a los agricultores y tomadores de decisiones optimizar los recursos y mejorar la planificación en la agricultura cacaotera.

### 📊 Recopilación de Datos 

Para el desarrollo de este proyecto, se realizó una exhaustiva recopilación de datos de diversas fuentes:

- **Datos de Producción**: Los datos históricos de producción de cacao fueron obtenidos a través de la iniciativa gubernamental colombiana [Datos Abiertos](https://www.datos.gov.co/), que proporciona acceso a una amplia gama de datos para apoyar la toma de decisiones basada en evidencia.
- **Datos Ambientales**: Los datos ambientales, incluyendo variables climáticas y meteorológicas, fueron recopilados mediante la agencia gubernamental colombiana [IDEAM](http://www.ideam.gov.co/), que es responsable de monitorear y proporcionar información sobre el medio ambiente en Colombia.

Toda la recopilación de datos se ha almacenado y está disponible en este repositorio para su revisión y análisis. 

### 🏋️ Modelos Utilizados 

- **Regresión Lineal**: Este modelo se utiliza para establecer una relación lineal entre las variables independientes y la variable dependiente, que en este caso es la producción de cacao.
- **Árboles de Decisión**: Un modelo no lineal que divide los datos en subconjuntos más pequeños basándose en las características más importantes, creando una estructura de árbol de decisiones.
- **Bosques Aleatorios**: Un conjunto de árboles de decisión que trabajan juntos para mejorar la precisión y reducir el riesgo de sobreajuste.

### 🎆 Implementación y Resultados 🎆

El proyecto se lleva a cabo mediante el uso de Jupyter Notebooks, donde se realizan las siguientes etapas:

1. **Análisis Exploratorio de Datos (EDA)**: Se examinan y visualizan los datos para entender sus características y relaciones.
2. **Ingeniería de Características**: Se crean y seleccionan características relevantes para mejorar el rendimiento de los modelos.
3. **Entrenamiento de Modelos**: Se entrenan diferentes modelos de machine learning utilizando los datos preparados.
4. **Evaluación de Modelos**: Se evalúa el rendimiento de los modelos mediante técnicas como la validación cruzada y métricas como el error cuadrático medio (MSE).
