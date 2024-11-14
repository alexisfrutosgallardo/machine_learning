# machine_learning

# Predicción de Calidad del Vino

Este proyecto tiene como objetivo predecir la calidad del vino basándose en características físico-químicas. Se ha utilizado el **Wine Quality Dataset** y se aplicaron técnicas de **clasificación supervisada** para construir modelos predictivos que puedan clasificar la calidad del vino en función de variables como acidez, cloruros, pH, alcohol, entre otros.

## Propósito del Proyecto
El propósito principal de este proyecto es poner en práctica técnicas de aprendizaje automático en un problema de clasificación multiclase. Este ejercicio abarca varios aspectos clave, como:
- Selección y preprocesamiento de datos.
- Entrenamiento y evaluación de modelos de clasificación.
- Optimización de modelos mediante búsqueda de hiperparámetros.
- Análisis de resultados utilizando métricas de evaluación y visualización de curvas ROC/AUC.

## Técnicas y Herramientas Utilizadas
A continuación se describen las principales técnicas y herramientas utilizadas en este proyecto:

- **Preprocesamiento de Datos**: Se realizó limpieza de datos, selección de características, y escalado de datos para garantizar que todos los modelos reciban datos homogéneos y optimizados.
- **Modelos de Clasificación**: Se entrenaron tres modelos diferentes de clasificación:
  - **K-Nearest Neighbors (KNN)**
  - **Random Forest**
  - **Regresión Logística**
- **Optimización de Hiperparámetros**: Utilizamos `GridSearchCV` para optimizar los hiperparámetros de cada modelo y seleccionar la mejor configuración.
- **Evaluación de Modelos**: Se evaluaron los modelos mediante métricas como exactitud, precisión, recall, F1-Score y matriz de confusión.
- **Curvas ROC y AUC**: Para el mejor modelo (Random Forest), se generaron curvas ROC y se calcularon los valores de AUC para evaluar el rendimiento en cada clase.

## Estructura del Proyecto

* Predicción de Calidad del Vino (Core).ipynb # Código principal del proyecto
* WineQT.csv # Dataset utilizado para entrenar y evaluar los modelos
* README.md # Descripción del proyecto


## Instrucciones para Ejecutar el Código

### 1. Clonar el Repositorio
Clona este repositorio en tu máquina local:
```bash
git clone https://github.com/alexisfrutosgallardo/machine_learning.git
cd machine_learning

Dentro de la carpeta se encontrará el archivo Predicción de Calidad del Vino (Core).ipynb donde se puede acceder para visualizar el código