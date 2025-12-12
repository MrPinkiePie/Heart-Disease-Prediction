# 🫀 Predicción de Enfermedad Cardíaca (Heart Disease Prediction)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](AQUÍ_PEGA_TU_ENLACE_LARGO_DE_COLAB)

### 📋 Descripción del Proyecto
Este proyecto tiene como objetivo apoyar el triaje clínico mediante la detección temprana de pacientes con alto riesgo de enfermedad cardiovascular. Se desarrolló un modelo estadístico interpretable para identificar patrones de riesgo en variables clínicas y demográficas.

### 🏥 Comprensión del Negocio
* **Objetivo:** Disminuir eventos cardíacos graves y costos hospitalarios detectando tempranamente a pacientes de alto riesgo.
* **Uso Clínico:** Herramienta de soporte para triaje que sugiere un nivel de riesgo (bajo/medio/alto) basado en signos vitales y hábitos.

### 🛠️ Tecnologías y Técnicas
* **Lenguaje:** Python 🐍
* **Modelo:** Regresión Logística (Logistic Regression) - Estándar en medicina por su interpretabilidad (Odds Ratios).
* **Validación:** Verificación de *overfitting* comparando métricas de entrenamiento vs. prueba.
* **Preprocesamiento:** Limpieza de datos (EDA), manejo de outliers clínicos y escalado de variables.

### 📊 Resultados Clave (Test Set)
El modelo prioriza la sensibilidad (Recall) para minimizar los falsos negativos, logrando a su vez una excelente capacidad de discriminación (AUC).

| Métrica | Resultado | Interpretación |
| :--- | :--- | :--- |
| **Recall (Clase 1)** | **85%** | Detectamos a 8.5 de cada 10 pacientes realmente enfermos. |
| **ROC - AUC** | **0.94** | Excelente capacidad del modelo para distinguir entre pacientes sanos y enfermos. |
| **Precisión (Clase 1)** | 91% | Cuando el modelo predice "Enfermo", acierta el 91% de las veces (pocas falsas alarmas). |
| **Accuracy Global** | 86% | Precisión general del diagnóstico. |

> **Nota de Robustez:** Se compararon las métricas de entrenamiento y prueba, observando una variación mínima, lo que descarta problemas de sobreajuste (*overfitting*).

---
*Autor: Luis Mauricio Aguirre Stornaiuolo* *[LinkedIn](https://www.linkedin.com/in/mauriciostornaiuolope)*
