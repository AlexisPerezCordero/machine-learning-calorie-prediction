# Machine Learning - Predicción de Calorías Quemadas

Modelo de Machine Learning desarrollado para predecir la cantidad de calorías quemadas durante una actividad física utilizando variables biométricas y fisiológicas.

## Descripción

Este proyecto implementa y compara diferentes algoritmos de regresión para estimar el gasto calórico de una persona a partir de características como edad, peso, altura, duración del ejercicio, frecuencia cardíaca y temperatura corporal.

El proyecto incluye el proceso completo de ciencia de datos, desde la limpieza de datos hasta la evaluación del modelo con mejor rendimiento.

## Objetivos

- Analizar el comportamiento del dataset.
- Realizar limpieza y transformación de datos.
- Desarrollar un Análisis Exploratorio de Datos (EDA).
- Entrenar múltiples modelos de Machine Learning.
- Comparar el rendimiento de cada algoritmo.
- Seleccionar el modelo con mayor precisión.

## Dataset

Se utilizaron dos archivos CSV:

- `exercise.csv`
- `calories.csv`

Después de integrarlos se obtuvo un dataset con **15,000 registros** y las siguientes variables:

- Gender
- Age
- Height
- Weight
- Duration
- Heart_Rate
- Body_Temp
- Calories (Variable objetivo)

## Tecnologías utilizadas

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost

## Proceso del proyecto

1. Recolección e integración de datos.
2. Limpieza y preparación de datos.
3. Análisis Exploratorio de Datos (EDA).
4. Ingeniería de características.
5. Entrenamiento de modelos.
6. Optimización.
7. Evaluación de resultados.

## Modelos implementados

- Regresión Lineal
- Árbol de Decisión
- Random Forest
- Extra Trees Regressor
- XGBoost

## Métricas de evaluación

Los modelos fueron evaluados utilizando:

- MAE
- MSE
- RMSE
- R² Score

## Principales hallazgos

- La **duración del ejercicio** fue la variable con mayor influencia en la predicción.
- La **frecuencia cardíaca** presentó una fuerte correlación con las calorías quemadas.
- La **temperatura corporal** también mostró una relación positiva con el gasto energético.
- Los modelos basados en árboles obtuvieron un rendimiento superior frente a la regresión lineal.

## Estructura del proyecto

```text
Machine-Learning-Calorias/
│
├── data/
│   ├── exercise.csv
│   └── calories.csv
│
├── notebooks/
│   └── Machine_Learning_Calorias.ipynb
│
├── images/
│
├── README.md
└── requirements.txt
```

## Resultados

Se compararon cinco algoritmos de regresión, obteniendo un desempeño muy alto en la predicción del gasto calórico. Los modelos de ensamble como **Random Forest**, **Extra Trees Regressor** y **XGBoost** alcanzaron los mejores resultados, con valores de **R² cercanos a 1**, demostrando una excelente capacidad predictiva.

