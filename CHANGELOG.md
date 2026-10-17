# Reporte Final / CHANGELOG - Actividad 5

## [1.0.0] - 2026-10-17
### Resumen de Fases Completadas:
- **Fase 1 (Arquitectura y Repositorio):** Se diseñó la estructura modular del proyecto (`datos/`, `fuentes/`) y se inicializó el versionado de código conectándolo con GitHub.
- **Fase 2 (Configuración de MLflow):** Se instaló e inicializó el entorno de seguimiento local para registrar parámetros, métricas y artefactos de forma automatizada.
- **Fase 3 (Entrenamiento y Validación):** 
  - Se implementaron dos algoritmos de clasificación: **Regresión Logística** y **Random Forest**.
  - Se definieron métricas estandarizadas (`Accuracy`, `Precision`, `Recall`, `F1-Score`).
  - Se ejecutó validación cruzada de 5 particiones (K-Fold) para asegurar la robustez de los resultados.
  - Se guardaron y versionaron los modelos mediante MLflow.
- **Fase 4 & 5 (Documentación y Cierre):** Se documentó la guía de reproducción en el archivo `README.md` y este reporte de cambios en el `CHANGELOG.md`.
