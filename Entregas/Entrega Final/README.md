
# Proyecto Final — Data Science I  
## Machine Learning aplicado a leads en Telecomunicaciones
**Autora:** Angela Barrutia  
**Curso:** Data Science I – Coderhouse  
**Año:** 2025

---

### Descripción

Este proyecto tiene como objetivo aplicar técnicas de ciencia de datos para analizar el comportamiento de los leads comerciales de **Nubyx**, una empresa peruana de telecomunicaciones. Se utiliza un dataset real del periodo 2023-2024 que incluye variables geográficas, comerciales, técnicas y de adquisición.

Se implementa un flujo completo de análisis que incluye:

- Limpieza y preparación de datos
- Análisis exploratorio (EDA)
- Codificación de variables
- Entrenamiento de modelos de clasificación:
  - **Random Forest**
  - **Regresión Logística**
- Evaluación de desempeño con métricas como accuracy, F1-score, matriz de confusión, etc.
- Visualización de resultados

---

### Objetivo

Predecir si un lead se convertirá en cliente, basándonos en variables como cobertura, tipo de vivienda, región, velocidad contratada, fuente de ingreso y otras características.

---

### Contenido

```
Entrega Final/
├── ProyectoFinalDSI_BarrutiaAngela.ipynb     <- Notebook principal
├── base_nubyx_leads2023-2024.csv             <- Dataset en formato CSV
```

---

### Cómo usar este proyecto

1. Abrir el notebook en Google Colab o Jupyter.
2. Asegurarse de tener las siguientes librerías instaladas:
   - pandas, numpy, matplotlib, seaborn
   - scikit-learn
3. El archivo `base_nubyx_leads2023-2024.csv` se carga directamente desde GitHub.
4. Ejecutar cada celda en orden.

---

### Notas importantes

- La variable objetivo es `OBJETIVO_CONTRATO`, que representa si un lead cerró o no contrato.
- El modelo de Random Forest mostró mejor desempeño general frente a la regresión logística.

---

### Resultado

El modelo final permite detectar con buena precisión qué leads tienen alta probabilidad de conversión, lo cual puede ser utilizado para optimizar campañas comerciales.
