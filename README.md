Predicción de Abandono de Clientes - TelecomX LATAM 🎯
Este repositorio contiene el desarrollo de modelos de Machine Learning diseñados para predecir la probabilidad de que un cliente cancele sus servicios (Churn) en una empresa de telecomunicaciones. El proyecto abarca desde el análisis exploratorio de datos (EDA) hasta la implementación de estrategias de retención basadas en hallazgos del modelo.

📋 Objetivo del Proyecto
El objetivo principal es desarrollar modelos predictivos capaces de identificar clientes con alto riesgo de cancelación para permitir que la empresa ejecute acciones proactivas de fidelización.

🛠️ Stack Tecnológico
Lenguaje: Python 3 (Ejecutado en Google Colab).

Librerías principales: * Pandas y NumPy para manipulación de datos.

Scikit-learn para modelado, preprocesamiento y métricas.

Seaborn y Matplotlib para visualización de datos.

Imbalanced-learn (SMOTE, Undersampling) para el manejo de clases desbalanceadas.

Statsmodels para análisis de multicolinealidad (VIF).

⚙️ Metodología
Extracción de Datos: Carga de un dataset con 7,043 registros y 22 columnas iniciales (datos demográficos, servicios contratados y cargos financieros).

Preparación y Limpieza:

Eliminación de columnas redundantes tras análisis de correlación (ej. cargo_diario vs cargo_mensual).

Codificación de variables categóricas mediante OneHotEncoder y LabelEncoder.

Análisis de multicolinealidad utilizando el Factor de Inflación de la Varianza (VIF).

Modelado: Se evaluaron y compararon múltiples algoritmos:

Regresión Logística.

K-Nearest Neighbors (KNN).

Árboles de Decisión.

Random Forest (Modelo final seleccionado por su rendimiento).

Evaluación: Uso de matrices de confusión, reportes de clasificación (Precision, Recall, F1-Score) e importancia de variables.

📈 Resultados y Conclusiones
El modelo identificó factores críticos que impulsan la cancelación:

Antigüedad: Los clientes nuevos tienen mayor riesgo de abandono.

Tipo de Contrato: Los contratos mes a mes presentan una tasa de cancelación significativamente más alta.

Método de Pago: Los pagos manuales (cheques electrónicos) están correlacionados con una menor lealtad comparado con los automáticos.

Estrategias Sugeridas 🚀
Programa de "Aterrizaje Seguro": Campañas proactivas durante los primeros 6 meses del cliente.

Incentivos de Migración: Descuentos para pasar de planes mensuales a contratos anuales.

Fomento de Pagos Automáticos: Bonificaciones por adherirse al débito automático.

📂 Estructura del Repositorio
TelecomX_part2_LATAM.ipynb: Notebook principal con todo el flujo de trabajo.

dataFrame.csv: Dataset utilizado para el entrenamiento y prueba (enlace externo).

Autor: Nicolás Perotto Ghi
