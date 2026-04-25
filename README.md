readme_pozos = """# 🛢️ Análisis de Rentabilidad y Riesgo: Nuevos Pozos Petroleros - OilyGiant

## 📋 Descripción del Proyecto
Este proyecto utiliza técnicas de **Machine Learning** y **análisis estadístico** para identificar la región más rentable para la apertura de 200 nuevos pozos petroleros para la compañía **OilyGiant**. El desafío principal radica en maximizar el beneficio neto mientras se mantiene el riesgo de pérdidas por debajo del **2.5%**.

## 🎯 Objetivos
* Desarrollar un modelo de **Regresión Lineal** para predecir el volumen de reservas en nuevos pozos.
* Calcular el beneficio potencial de las reservas predichas en tres regiones distintas.
* Utilizar la técnica de **Bootstrapping** para evaluar el riesgo de pérdidas y el intervalo de confianza de los beneficios.

---

### 🛠️ Herramientas y Librerías
* **Python 3.x**
* **Pandas & NumPy:** Para manipulación de datos y cálculos matriciales.
* **Scikit-learn:** Implementación del modelo de Regresión Lineal y métricas de error (RMSE).
* **Bootstrapping:** Para estimación de riesgos y distribuciones de beneficios.

---

### ⚙️ Metodología
1.  **Preparación de Datos:** * Carga y limpieza de tres datasets regionales (`geo_data_0`, `geo_data_1`, `geo_data_2`).
    * Análisis de correlación entre características geológicas y volumen de reservas.
2.  **Entrenamiento del Modelo:**
    * División de datos (75/25) y entrenamiento de modelos independientes por región.
    * Evaluación mediante **RMSE** para medir la precisión de las predicciones.
3.  **Cálculo de Beneficios:**
    * Definición de variables económicas: Presupuesto total (**100 millones USD**), ingresos por unidad de producto y punto de equilibrio.
4.  **Análisis de Riesgo (Bootstrapping):**
    * Simulación de 1,000 muestras para obtener la distribución de beneficios.
    * Cálculo del beneficio promedio, el intervalo de confianza del 95% y la **probabilidad de pérdida**.

---

### 🚀 Resultados Clave
* **Región Seleccionada:** [Completar con tu región ganadora, ej: Región 1]
* **Beneficio Promedio Estimado:** [Completar con tu resultado]
* **Evaluación de Riesgo:** Se logró identificar una región con un riesgo de pérdida inferior al **2.5%**, cumpliendo con los requisitos de negocio.

---

### 👤 Autor
**Miguel Navarro**
* [LinkedIn](https://www.linkedin.com/in/miguelnavarroromo/)

---

### 📂 Estructura del Repositorio
* `analisis_pozos.ipynb`: Notebook con el desarrollo completo.
* `datasets/`: Carpeta con los archivos CSV (geo_data_0, 1 y 2).
* `README.md`: Descripción del proyecto.
"""

with open("README_OilyGiant.md", "w", encoding="utf-8") as f:
    f.write(readme_pozos)
