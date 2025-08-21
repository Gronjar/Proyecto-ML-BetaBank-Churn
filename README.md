# 🏦 Predicción de Churn en Beta Bank

Este proyecto busca predecir la **fuga de clientes** en un banco, utilizando modelos de Machine Learning con un enfoque en mejorar la métrica **F1** y comparar resultados con **AUC-ROC**.

---

## 📊 Contenido

- Preparación y limpieza de datos  
- Análisis del balance de clases  
- Entrenamiento de modelos de clasificación  
- Uso de técnicas de balanceo (sobremuestreo y submuestreo)  
- Comparación de modelos y ajuste de hiperparámetros  
- Evaluación final con F1 y AUC-ROC  

---
## 📌 Dataset

El dataset (`Churn.csv`) incluye información como:  
- Datos demográficos: edad, género, país  
- Información financiera: crédito, saldo, salario  
- Comportamiento: uso de productos, actividad, tarjeta de crédito  
- Variable objetivo: **Exited** (1 = se fue, 0 = se quedó)

---

## 🤖 Tecnologías utilizadas

- Python 3  
- pandas / numpy  
- matplotlib / seaborn  
- scikit-learn  

---

## 🚀 Resultados

- Se logró un **F1 > 0.59** en el set de prueba  
- Se evaluaron y compararon modelos con **AUC-ROC**  
- El modelo final ayuda a identificar clientes en riesgo y mejorar estrategias de retención.
