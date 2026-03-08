# Predicción de Abandono de Clientes (Churn) - TelecomX 🎯

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/NicoPerotto/challenge2-data-science-LATAM-Parte-2/blob/main/TelecomX_part2_LATAM.ipynb)

Este repositorio contiene un análisis avanzado de **Data Science** y **Machine Learning** aplicado a la industria de las telecomunicaciones. El objetivo es identificar patrones de comportamiento y desarrollar modelos predictivos para anticipar la cancelación de servicios por parte de los clientes.

## 📋 Objetivo del Proyecto
Desarrollar y evaluar modelos de clasificación capaces de prever qué clientes tienen mayor probabilidad de abandonar la compañía, permitiendo la implementación de estrategias de retención basadas en datos.

## 🛠️ Tecnologías Utilizadas
* **Lenguaje:** Python (Google Colab)
* **Análisis de Datos:** `Pandas`, `NumPy`
* **Visualización:** `Seaborn`, `Matplotlib`
* **Machine Learning:** `Scikit-learn` (Logistic Regression, KNN, Decision Trees, Random Forest)
* **Balanceo de Clases:** `Imbalanced-learn` (SMOTE, Undersampling)
* **Estadística:** `Statsmodels` (VIF para análisis de multicolinealidad)

## ⚙️ Flujo de Trabajo
1. **Limpieza y Preprocesamiento:** Manejo de valores nulos, eliminación de variables altamente correlacionadas y codificación de variables categóricas.
2. **Análisis de Multicolinealidad:** Uso del Factor de Inflación de la Varianza (VIF) para asegurar la estabilidad del modelo.
3. **Tratamiento de Datos Desbalanceados:** Aplicación de técnicas de sobremuestreo y submuestreo para mejorar la detección de la clase minoritaria (Churn).
4. **Entrenamiento y Evaluación:** Comparación de múltiples algoritmos utilizando métricas como Precision, Recall, F1-Score y Matrices de Confusión.

## 📈 Hallazgos Clave
A través del modelo, se identificaron los principales factores de riesgo:
* **Contratos Mensuales:** Son el principal indicador de abandono.
* **Antigüedad:** El riesgo es máximo durante los primeros 6 meses de relación.
* **Método de Pago:** Los pagos manuales (Electronic Check) presentan mayor tasa de cancelación que los automáticos.
* **Tipo de Servicio:** Los usuarios de Fibra Óptica muestran una mayor tendencia al churn en comparación con DSL.

## 🚀 Estrategias de Retención Propuestas
* **Programa de "Aterrizaje Seguro":** Contacto proactivo y beneficios durante el primer semestre de contrato.
* **Incentivos de Migración:** Promover el paso de planes mensuales a contratos de 1 o 2 años.
* **Fomento de Pagos Automáticos:** Bonificaciones por adherirse al débito automático.

---
**Autor:** Nicolás Perotto Ghi
