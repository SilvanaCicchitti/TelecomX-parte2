📌 Predicción de Cancelación de Clientes – Telecom X

Este proyecto forma parte del desafío de Machine Learning – Parte 2: Churn Prediction.
El objetivo es desarrollar modelos predictivos capaces de anticipar qué clientes tienen mayor probabilidad de cancelar sus servicios, para que la empresa pueda diseñar estrategias de retención más efectivas.

🔎 Contenido

Preprocesamiento de datos: limpieza, codificación de variables categóricas, normalización y balanceo de clases con SMOTE.

Selección de variables: análisis de correlación y multicolinealidad (VIF), identificación de las 15 variables más relevantes.

Modelado: entrenamiento y evaluación de modelos de clasificación (Regresión Logística y Random Forest), con y sin reducción de variables.

Evaluación: métricas de accuracy, precision, recall, F1-score, matriz de confusión y curva ROC-AUC.

Insights estratégicos: identificación de los principales factores asociados a la cancelación de clientes.

🚀 Resultados principales

Regresión Logística (Top 15 variables): mejor recall en clientes que cancelan (~0.79), ideal para anticipar bajas.

Random Forest: modelo más balanceado en precision/recall, pero con menor capacidad de detección de bajas.

Variables clave: tipo de contrato, antigüedad del cliente (tenure), método de pago, servicios adicionales (seguridad online, soporte técnico).

👉 Este repositorio incluye el notebook con el pipeline completo y los resultados del análisis.