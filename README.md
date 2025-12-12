# 🫀 Predicción de Enfermedad Cardíaca (Heart Disease Prediction)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1D4A9coGt7Bf8e5nB2eKP73B89EceEHi1?usp=sharing)

### 📋 Descripción del Proyecto
Este proyecto tiene como objetivo apoyar el triaje clínico mediante la detección temprana de pacientes con alto riesgo de enfermedad cardiovascular. Se desarrolló un modelo estadístico interpretable para identificar patrones de riesgo en variables clínicas y demográficas.

### 🛠️ Tecnologías y Técnicas
* **Lenguaje:** Python 🐍
* **Modelo:** Regresión Logística (Logistic Regression) - Seleccionado por su alta interpretabilidad en el ámbito médico.
* **Metodología:** * Análisis Exploratorio de Datos (EDA) profundo.
    * Manejo de Outliers (Valores atípicos clínicos).
    * Validación Cruzada (`cross_val_score`) para asegurar la robustez.

### 📊 Resultados Clave
El modelo prioriza la sensibilidad (Recall) para minimizar los falsos negativos (pacientes enfermos no detectados):

| Métrica | Resultado | Interpretación |
| :--- | :--- | :--- |
| **Recall (Sensibilidad)** | **0.88** | El modelo detecta al 88% de los pacientes con enfermedad. |
| **Accuracy** | 86% | Alta precisión general en el diagnóstico. |
| **AUC Promedio** | Alto | Excelente capacidad de distinción entre sanos y enfermos. |

---
*Autor: Luis Mauricio Aguirre Stornaiuolo* *[LinkedIn](https://www.linkedin.com/in/mauriciostornaiuolope)*
