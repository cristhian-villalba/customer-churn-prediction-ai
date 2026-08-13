# 🧠 Sistema Predictivo de Fuga de Clientes (Customer Churn AI)

## 📝 Descripción del Proyecto
Este proyecto implementa una solución de analítica predictiva de extremo a extremo (*end-to-end*) orientada a identificar de forma proactiva a los clientes con alto riesgo de abandono comercial (*churn*). 

Combina el modelado estadístico y Machine Learning en **Python** con la distribución de alertas ejecutivas e interactividad en **Power BI**, permitiendo a los equipos de retención tomar decisiones fundamentadas en datos antes de que se produzca la pérdida del cliente.

---

## 📊 Impacto de Negocio y Resultados Clave

* **Precisión del Modelo:** Se alcanzó un **94% de *accuracy*** global utilizando el algoritmo *Random Forest Classifier* entrenado en entorno cloud.
* **Factores Críticos de Fuga (*Feature Importance*):**
  * **Inactividad (`Recencia_Dias`):** Constituye el factor de mayor peso con un **43,60%** de relevancia en la predicción.
  * **Fricción en Atención al Cliente (`Quejas_Soporte`):** Representa el segundo disparador clave con un **23,27%** de importancia.
* **Implementación Operativa en Power BI:** Los resultados del modelo se integraron en una arquitectura de datos corporativa. Mediante lógica **DAX avanzadas**, se automatizó una **"Lista de Salvamento Activa"** que aísla en tiempo real a los clientes activos con una probabilidad de fuga **>= 70%**.

---

## 🛠️ Stack Tecnológico Utilizado

| Área | Tecnología / Herramienta | Aplicación en el Proyecto |
| :--- | :--- | :--- |
| **Modelado de IA** | Python (Pandas, NumPy, Scikit-Learn) | Extracción, limpieza, ingeniería de variables y entrenamiento del algoritmo *Random Forest*. |
| **Entorno de Dev** | Google Colab | Ejecución del script analítico y exportación de datos transformados. |
| **Ingeniería de Datos** | Power Query | Limpieza de datos, ajuste de configuración regional y normalización de tipos de datos. |
| **Visualización & BI** | Power BI Desktop & DAX | Diseño del cuadro de mando interactivo (modo oscuro), modelado dimensional y segmentación. |

---

## 📂 Archivos del Repositorio

* `churn_prediction_model.ipynb`: Notebook de Jupyter con todo el ciclo de vida del dato: análisis exploratorio (EDA), entrenamiento, evaluación de métricas y exportación.
* `Customer_Attrition_Dashboard.pbix`: Archivo ejecutable de Power BI con el lienzo interactivo, medidas DAX y la interfaz visual final.

---

## 🚀 Cómo Replicar este Proyecto

1. **Clonar el repositorio:**
   ```bash
   git clone [https://github.com/cristhian-villalba/customer-churn-prediction-ai.git](https://github.com/cristhian-villalba/customer-churn-prediction-ai.git)
