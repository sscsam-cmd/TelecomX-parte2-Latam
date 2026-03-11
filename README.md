# 📘 TelecomX – Modelo Predictivo de Churn (Parte 2 – LATAM)

Este repositorio contiene el notebook **TelecomX_parte2_Latam.ipynb**, correspondiente a la segunda parte del proyecto de analítica para la predicción de **churn (cancelación)** en clientes del sector telecom.  
En esta etapa se realiza el preprocesamiento, análisis exploratorio, modelado y evaluación de modelos de Machine Learning enfocados en la predicción de abandono de clientes para la región LATAM.

---

## 📂 Contenido del Notebook

### 🛠️ 1. Preparación de los Datos
Incluye los pasos necesarios para preparar la base para modelado:

- Carga y revisión inicial del dataset.
- Eliminación de columnas irrelevantes o redundantes.
- Codificación de variables categóricas.
- Verificación de balance de clases (churn vs no churn).
- Aplicación de técnicas de balanceo (si corresponde).
- Normalización/estandarización según modelo utilizado.

---

### 🎯 2. Correlación y Selección de Variables
- Matriz de correlación para identificar variables influyentes.
- Evaluación dirigida de relaciones importantes con churn.
- Selección final de variables óptimas para entrenar los modelos.

---

### 🤖 3. Modelado Predictivo
Incluye:

- División en conjunto de entrenamiento y prueba.
- Entrenamiento de modelos de clasificación como:
  - Regresión Logística  
  - Random Forest  
- Evaluación de métricas de rendimiento:
  - Accuracy  
  - Precision  
  - Recall  
  - F1-score  
  - Matriz de confusión  
  - ROC–AUC  

---

### 📋 4. Interpretación y Conclusiones
- Importancia de variables según el modelo.
- Factores clave que explican el churn.
- Discusión sobre desempeño, insights y posibles mejoras.

---

## 🚀 Objetivo del Documento

El notebook busca construir y evaluar modelos predictivos capaces de:

- Identificar clientes con mayor probabilidad de cancelar el servicio.
- Apoyar estrategias de retención y campañas dirigidas.
- Servir como base técnica para futuras etapas del proyecto.

---

## 🧰 Requerimientos Técnicos

Dependencias principales utilizadas:

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
imbalanced-learn
