# 📊 Telecom X – Análisis y Predicción de Cancelación (Churn)

## 📌 Descripción del Proyecto  
Este proyecto tiene como objetivo analizar y predecir la **cancelación de clientes (churn)** en la empresa **Telecom X**.  

En la **Parte 1**, se llevó a cabo un análisis exploratorio de datos (EDA) para comprender los principales factores asociados a la evasión de clientes, incluyendo el impacto de los contratos, cargos mensuales, soporte técnico y métodos de pago.  

En la **Parte 2**, se desarrollaron **modelos predictivos de Machine Learning** para anticipar qué clientes tienen mayor probabilidad de abandonar la compañía, permitiendo así generar estrategias proactivas de retención.  

---

## 🎯 Objetivos  
- Identificar los principales factores que influyen en la cancelación de clientes.  
- Construir modelos de predicción que permitan anticipar el churn.  
- Generar insights estratégicos para la **toma de decisiones empresariales**.  

---

## 🛠️ Tecnologías Utilizadas  
- **Lenguaje:** Python 3  
- **Entorno:** Google Colab / Jupyter Notebook  
- **Librerías Principales:**  
  - `pandas`, `numpy` → Procesamiento y tratamiento de datos  
  - `matplotlib`, `seaborn` → Visualización de datos  
  - `scikit-learn` → Modelado predictivo (ML)  
  - `statsmodels` → Análisis estadístico  

---

## 📂 Estructura del Proyecto  

TelecomX-Churn/
│
├── data/ # Archivos de datos (JSON / CSV)
├── notebooks/ # Notebooks de análisis y modelado
│ ├── 01_EDA.ipynb # Análisis exploratorio de datos (EDA)
│ ├── 02_Modelado.ipynb # Modelado predictivo (Machine Learning)
│
├── results/ # Resultados, gráficas e informes
│
├── README.md # Documentación del proyecto


---

## 🚀 Flujo del Proyecto  

### 🔹 Parte 1 – Análisis Exploratorio  
- Limpieza y tratamiento de datos.  
- Análisis de contratos, soporte técnico, cargos mensuales, experiencia de pago y género.  
- Identificación de patrones de fidelización vs evasión.  

### 🔹 Parte 2 – Predicción de Cancelación  
- Preprocesamiento (tratamiento, codificación y normalización).  
- Análisis de correlación y selección de variables.  
- Entrenamiento de modelos de clasificación (ej. *Logistic Regression, Random Forest, XGBoost*).  
- Evaluación de desempeño con métricas (Accuracy, Recall, Precision, F1, ROC-AUC).  
- Interpretación de la importancia de variables.  
- Generación de insights estratégicos para la retención.  

---

## 📊 Resultados Destacados  
- Los contratos de mayor duración (**1 año y 2 años**) presentan mayor fidelización.  
- La **calidad del soporte técnico** es un factor crítico en la retención.  
- Los clientes con **cargos mensuales elevados** tienen mayor propensión al churn.  
- Los métodos de pago automáticos (**tarjeta de crédito y transferencias bancarias**) se asocian con mayor lealtad.  
- El género no muestra una diferencia significativa en la tasa de cancelación.  

---

## 📌 Conclusiones Estratégicas  
Los hallazgos y modelos desarrollados permiten a **Telecom X**:  
- Anticipar con mayor precisión la cancelación de clientes.  
- Focalizar esfuerzos de retención en segmentos críticos (clientes de alto gasto, usuarios sin soporte técnico, contratos de corto plazo).  
- Implementar estrategias diferenciadas de fidelización para maximizar el valor de la base de clientes.  

---




