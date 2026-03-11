# Análisis de Fuga de Clientes (Churn) - TelecomX

Este repositorio contiene un análisis de datos de extremo a extremo y un modelo predictivo para identificar los factores que influyen en la deserción de clientes en la empresa de telecomunicaciones **TelecomX**.

## 📋 Resumen del Proyecto
El objetivo principal es entender por qué los clientes abandonan el servicio y proponer estrategias basadas en datos para mejorar la retención. El análisis cubre desde la ingesta de datos JSON hasta la implementación de modelos de Machine Learning.

## 🛠️ Tecnologías Utilizadas
* **Python** (Pandas, NumPy)
* **Visualización:** Matplotlib, Seaborn
* **Machine Learning:** Scikit-Learn (Random Forest, Logistic Regression)
* **API/Data:** Requests (Extracción de JSON remoto)

## 📊 Hallazgos Principales
* **Tasa de Churn Global:** 26.54%.
* **Contratos:** Los clientes con contrato 'Mes a mes' tienen una tasa de fuga del **42.7%**, comparado con solo el **2.8%** en contratos de dos años.
* **Impacto Económico:** Los clientes que se fugan pagan en promedio **$13.17 más** mensualmente que los que permanecen.
* **Factores Predictivos:** Según el modelo Random Forest, las variables más críticas son el **Costo Total**, la **Antigüedad (tenure)** y el **Costo Mensual**.

## 🚀 Estructura del Análisis
1. **Extracción y ETL:** Limpieza y aplanado de datos anidados.
2. **Análisis Exploratorio (EDA):** Visualización de patrones de comportamiento.
3. **Preprocesamiento:** Codificación de variables (One-Hot Encoding) y escalado de datos.
4. **Modelado:** Entrenamiento de modelos de clasificación y evaluación de métricas (Precision, Recall).
5. **Conclusiones Estratégicas:** Recomendaciones de negocio basadas en la importancia de las variables.

## 📈 Recomendaciones de Negocio
1. **Migración Contractual:** Incentivar el paso de contratos mensuales a anuales mediante descuentos.
2. **Programas de Lealtad Temprana:** Enfocarse en clientes con baja antigüedad para reducir el riesgo inicial.
3. **Optimización de Pagos:** Promover el débito automático sobre el cheque electrónico para reducir fricción mensual.
