# Actividad 5: Entrenamiento, Validación y Registro de Modelos con MLflow

## 1. Descripción del Proyecto
Este proyecto implementa un flujo completo de Machine Learning (MLOps básico) utilizando un dataset de clasificación. El objetivo es comparar el rendimiento de dos algoritmos (`Regresión Logística` y `Random Forest`), aplicando métricas estandarizadas, validación cruzada y el registro de experimentos con **MLflow**.

## 2. Estructura del Repositorio
- `datos/`: Contiene los datos originales (`datos_ini`) y limpios (`datos_limp`).
- `fuentes/`: Contiene el notebook de Colab (`entrena.ipynb`) y los scripts de apoyo.
- `README.md`: Guía de reproducción del proyecto.
- `CHANGELOG.md`: Bitácora y reporte final de los resultados.

## 3. Instrucciones de Reproducción
1. Clona este repositorio en tu máquina local.
2. Abre el archivo `fuentes/entrena.ipynb` en **Google Colab**.
3. Ejecuta las celdas secuencialmente para realizar la carga del dataset, el entrenamiento de los algoritmos y la validación cruzada.
4. Visualiza los registros generados localmente por **MLflow** (parámetros, métricas y modelos).
