# ☀️ Predicción de Energía Solar con Machine Learning (XGBoost)

Este proyecto aplica técnicas avanzadas de **Data Science** y **Machine Learning** para predecir la producción de energía solar (kWh) basándose en datos históricos. El objetivo principal es optimizar la gestión energética mediante pronósticos precisos utilizando el algoritmo **XGBoost**.

## 📊 Descripción del Proyecto
La generación de energía renovable es variable por naturaleza. Este modelo analiza patrones temporales (horas del día, estacionalidad, días de la semana) para prever cuánta energía se producirá, permitiendo una mejor planificación y eficiencia en redes eléctricas.

## 🛠️ Tecnologías y Herramientas
* **Lenguaje:** Python 3.x
* **Bibliotecas Principales:**
    * `Pandas` & `NumPy`: Manipulación y limpieza de datos.
    * `XGBoost`: Algoritmo de Gradient Boosting para alta precisión.
    * `Scikit-learn`: Creación de pipelines y métricas de evaluación.
    * `Matplotlib` & `Seaborn`: Visualización de tendencias y resultados.
* **Entorno:** Jupyter Notebook.

## 🧠 Aspectos Técnicos Destacados
* **Ingeniería de Variables (Feature Engineering):** Se transformaron variables temporales en funciones cíclicas (seno/coseno) para que el modelo entienda que las 23:00 y las 00:00 son momentos cercanos.
* **Tratamiento de Series Temporales:** Limpieza de duplicados, ordenamiento cronológico y manejo de frecuencias horarias.
* **Evaluación del Modelo:** Uso de la métrica RMSE (Error Cuadrático Medio Simple) para validar la cercanía de las predicciones con los datos reales.
* **Pipeline de Procesamiento:** Estructuración de un flujo de datos limpio desde la carga hasta la predicción final.

## 📈 Resultados
El modelo logra identificar con éxito los picos de producción solar diarios y las variaciones estacionales a lo largo del año, demostrando una alta capacidad predictiva incluso frente a la intermitencia del recurso solar.

---

### 📩 Contacto y Redes

* **LinkedIn:** [linkedin.com/in/ichbinzeed](https://www.linkedin.com/in/ichbinzeed)
* **Email:** prog.gustavo@gmail.com
