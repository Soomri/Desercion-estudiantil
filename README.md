# 🎓 Predicción de deserción estudiantil en educación superior

Este proyecto tiene como objetivo desarrollar un sistema predictivo de deserción estudiantil utilizando técnicas de **aprendizaje automático**. Fue desarrollado en el marco de un curso de **Minería de Datos Estructurados** de la carrera **Ingeniería en Ciencia de Datos** de la Universidad Pontificia Bolivariana.

## 🧠 Objetivo

> Identificar a tiempo a los estudiantes con riesgo de abandonar sus estudios mediante modelos supervisados de clasificación, facilitando así la toma de decisiones por parte de instituciones educativas.

---

## ⚙️ Tecnologías y herramientas utilizadas

- **Lenguaje:** Python 3.10
- **Librerías principales:**  
  `pandas`, `scikit-learn`, `xgboost`, `matplotlib`, `seaborn`, `imbalanced-learn`, `joblib`, `streamlit`
- **Entorno de desarrollo:** Jupyter Notebook en [Deepnote](https://deepnote.com/)
- **Despliegue web:** [Streamlit Community Cloud](https://streamlit.io/cloud)
- **Repositorio de datos:** [UCI Machine Learning Repository - Student Dropout Dataset](https://archive.ics.uci.edu/)

---
## 📊 Modelos implementados

Se entrenaron y evaluaron los siguientes algoritmos:

- Árbol de decisión
- Red neuronal (MLP)
- SVM (Support Vector Machines)
- KNN (k-vecinos más cercanos)
- Random Forest
- XGBoost
- Voting Soft (Ensamble)

**Mejor modelo:**  
🔹 `XGBoost` optimizado con `GridSearchCV`  
🔹 F1-Score ~ 0.91  
🔹 Alta precisión y generalización

---

## 🔁 Pipeline y despliegue
El despliegue se puede consultar en el repositorio: https://github.com/lau2413/Despliegue_Desercion_Estudiantil

El modelo final fue encapsulado en un pipeline que incluye:

- Preprocesamiento de variables (escalado selectivo)
- Modelo XGBoost con hiperparámetros optimizados
- Serialización con `joblib`
- Aplicación web interactiva con `Streamlit` impulsada por Replit

## 👩‍💻 Autoras
* Laura Sofía Jiménez Moreno
* Sofía Mejía Rivas

Universidad Pontificia Bolivariana — Facultad de Ingeniería
Ingeniería en Ciencia de Datos | Medellín, 2025-1


  

