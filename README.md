# 📊 Telecom X – Análisis y Predicción de Cancelación (Churn)

## 📌 Descripción del Proyecto  
Este proyecto tiene como objetivo analizar y predecir la **cancelación de clientes (churn)** en la empresa **Telecom X**.  

Se abordó en **dos fases principales**:  

- **[Parte 1 – Análisis Exploratorio de Datos (EDA)](https://github.com/Mj-Novoa/Challenge_TelecomX_PARTE1):** limpieza, tratamiento, análisis de correlaciones y exploración de variables clave que influyen en la cancelación de clientes.  
- **Parte 2 – Modelado Predictivo:** construcción y evaluación de modelos de Machine Learning para predecir la probabilidad de churn, junto con un análisis estratégico de las variables más relevantes y recomendaciones de retención.  

---

## 🎯 Objetivos  
- Identificar los factores que más influyen en la cancelación de clientes.  
- Desarrollar modelos predictivos robustos que anticipen la probabilidad de churn.  
- Generar **insights estratégicos** que permitan diseñar acciones de retención.  

---

## 🛠️ Tecnologías Utilizadas  
- **Lenguaje:** Python 3  
- **Entorno:** Google Colab / Jupyter Notebook  
- **Librerías Principales:**  
  - `pandas`, `numpy` → Procesamiento y tratamiento de datos  
  - `matplotlib`, `seaborn` → Visualización  
  - `scikit-learn` → Modelos de Machine Learning y evaluación  
  - `imblearn` → Técnicas de balanceo de clases (SMOTE, undersampling, oversampling)  

---

## 📂 Estructura del Proyecto  

TelecomX-Churn/
│
├── data/ # Archivos de datos originales y tratados
├── notebooks/ # Jupyter Notebooks del análisis y modelado
│ ├── 01_EDA.ipynb # Análisis exploratorio de datos
│ ├── 02_Modelado.ipynb # Creación y evaluación de modelos ML
│
├── results/ # Resultados, gráficos y reportes
│
├── README.md # Documentación del proyecto


---

## 🚀 Flujo del Proyecto  

### 🔹 Parte 1 – Análisis Exploratorio  
- **Extracción y limpieza de datos** desde archivos JSON.  
- **Normalización de columnas** y creación de variables derivadas.  
- **Análisis de correlación** mediante matrices y heatmaps.  
- **Exploración dirigida**: Tenure vs Churn, Cargos vs Churn, Contratos vs Churn, Experiencia de pago y Soporte técnico.  
- Identificación de factores clave como contratos de corto plazo, altos cargos mensuales, y uso de métodos de pago electrónicos.  

### 🔹 Parte 2 – Modelado Predictivo  
- **Balanceo de clases** (undersampling, oversampling, SMOTE).  
- **Separación de datos** en train/test (70/30, estratificada).  
- Creación de **dos modelos base**:  
  - Regresión Logística (con normalización).  
  - Random Forest (sin normalización).  
- **Evaluación de desempeño** con Accuracy, Precision, Recall, F1-score y Matriz de Confusión.  
- **Análisis de importancia de variables**: coeficientes (Logística) e importancias de features (Random Forest).  

---

## 📊 Resultados Clave  

- **Regresión Logística** obtuvo mejor desempeño que Random Forest:  
  - Accuracy: 0.80 vs 0.79  
  - Recall: 0.54 vs 0.50  
  - F1-score: 0.59 vs 0.56  

- **Factores principales asociados al churn:**  
  - **Tenure (antigüedad):** clientes nuevos tienen mayor riesgo.  
  - **Tipo de contrato:** *month-to-month* es el de mayor evasión; contratos anuales y bianuales protegen contra la cancelación.  
  - **Cargos mensuales y totales:** clientes con cargos acumulados altos tienden a cancelar.  
  - **Internet Fibra Óptica y Streaming:** asociados a mayor churn.  
  - **Método de pago electrónico:** vinculado con mayor probabilidad de cancelación.  

---

## 📌 Conclusiones Estratégicas  

- **Migración de contratos:** incentivar planes anuales y bianuales mediante descuentos o beneficios adicionales.  
- **Segmentación de riesgo:** enfocar campañas en clientes con bajo tenure y altos cargos acumulados.  
- **Optimización de servicios de internet (fibra óptica):** revisar la experiencia de usuario y percepción de calidad.  
- **Experiencia de pago:** promover medios automáticos (tarjeta de crédito, transferencias bancarias) para reducir fricciones.  
- **Fortalecer servicios adicionales:** mejorar soporte técnico y paquetes de entretenimiento para incrementar la satisfacción.  

---

## 👨‍💻 Autor  
Proyecto desarrollado por **[MJ.NOVOA]**  
🔗 GitHub: [https://github.com/tu-usuario](https://github.com/tu-usuario)  



