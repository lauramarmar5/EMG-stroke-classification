# EMG-stroke-classification

Pipeline desarrollado en Python para el procesamiento y clasificación de señales electromiográficas (sEMG) de sujetos sanos y pacientes con secuelas de ictus.

## 📌 Sobre el proyecto
Este repositorio contiene un trabajo inicial desarrollado de forma autónoma durante mis prácticas de Ingeniería Biomédica, con vistas a posibles mejoras en el futuro. El objetivo fue explorar el procesamiento de datos biomédicos de acceso público y evaluar la viabilidad de modelos sencillos de Machine Learning para caracterizar el comportamiento muscular.

## 🛠️ Tecnologías y Librerías
* **Entorno de programación:** Jupyter Notebook
* **Lenguaje:** Python 3.x
* **Librerías utilizadas:**
  * `pandas` y `numpy` (manipulación y análisis de datos)
  * `scikit-learn` (modelado y métricas de Machine Learning)
  * `matplotlib` y `seaborn` (visualización de resultados)

## 📁 Estructura del Proyecto
* `ictus_main.ipynb`: carga de datos, preprocesado y extracción de métricas en el dominio del tiempo de la señal sEMG.
* `ictus_training.ipynb`: entrenamiento del clasificador (Decision Tree) y evaluación de métricas de rendimiento por músculo.
* `docs/`: informe técnico completo en PDF con el desarrollo detallado de la metodología.

## 📊 Datos
Los datos utilizados provienen de una base de datos pública (Israely et al., 2018) enfocado en la evaluación de los diferentes músuculos miembro superior mediante la Contracción Voluntaria Máxima (MVC) medida mediante señales de EMG.

## 🚀 Perspectivas a futuro
Mi objetivo es desarrollar una versión que  alcance mejores resultados, mejorando, entre otros, los siguientes aspectos:
* **Emplear una base de datos mayor**, ya que el pequeño tamaño del repositorio empleado ha limitado la capacidad de entrenamiento y test del modelo.
* **Uso de señales de EMG en crudo**, ya que los registros empleados estaban preprocesados y almacenados como una envolvente, lo que dificultaba el preprocesado y su generalización para otros registros con los que se quiera emplear el modelo.
* **Posibilidad de incluir métricas en el dominio de la frecuencia** que proporcionen mayor precisión.

---
*Nota: Proyecto de iniciación y aprendizaje personal.*
