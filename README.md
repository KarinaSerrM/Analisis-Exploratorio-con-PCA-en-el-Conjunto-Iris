# Análisis Exploratorio con PCA en el Conjunto Iris

Este repositorio documenta un proyecto de análisis exploratorio sobre el clásico conjunto de datos Iris, utilizando técnicas de preprocesamiento y reducción de dimensionalidad con Análisis de Componentes Principales (PCA). El objetivo es identificar patrones de agrupación entre especies y comprender cómo las variables originales se relacionan con los componentes principales.

## Objetivo

Explorar relaciones entre especies de flores y sus características numéricas mediante reducción de dimensionalidad y visualizaciones interpretativas.

## Flujo de trabajo

### 1. Preparación de datos
- Carga del conjunto de datos Iris
- Separación entre variables predictoras y variable objetivo
- Estandarización con `StandardScaler` para homogenizar escalas

### 2. Aplicación de PCA
- Cálculo de varianza explicada por cada componente
- Selección de PC1 y PC2 con base en varianza acumulada
- Interpretación de los pesos y correlaciones entre variables originales y componentes

### 3. Visualización e interpretación
- Gráfico de observaciones: dispersión en el plano PC1 vs PC2
- Gráfico de factores: dirección e influencia de cada variable
- Análisis de casos específicos que ilustran diferencias entre especies

## Herramientas utilizadas

- Python 3.x  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib / Seaborn

## Conclusiones

- El PCA permite reducir las dimensiones conservando más del 95% de la información original en las dos primeras componentes.
- Las visualizaciones ayudan a entender cómo se agrupan las especies y cómo influyen las variables como `petal length` y `sepal width`.
- El análisis de casos específicos refuerza la interpretación cuantitativa con evidencias visuales.
