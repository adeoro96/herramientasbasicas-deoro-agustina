# Análisis de Brecha Salarial y Estructura de Remuneraciones

**Autor:** Agustina de Oro  
**Curso:** Curso de Herramientas Básicas para el Análisis de Datos  
**Cohorte:** 2026  

## Objetivo
Aplicar herramientas de análisis de datos a un contexto empresarial. Se utilizó el dataset *Salary Prediction for Beginner* con una muestra de 324 registros, simulando la estructura de una PyME. Busca identificar diferencias salariales según género, nivel educativo y experiencia para facilitar la toma de decisiones.


## Preguntas de Investigación
1. **Brecha de género:** ¿Existe disparidad salarial entre hombres y mujeres?
2. **Educación:** ¿Cómo impacta el grado académico en los ingresos?
3. **Experiencia:** ¿Cómo evoluciona el salario a lo largo de la trayectoria?

## Dataset
La fuente es *Salary Prediction for Beginner* (Kaggle). Se utilizaron 324 registros para representar de forma realista la nómina de una PyME.
* **Enlace local:** [CSV en /data/raw/](./data/raw/processed_salary_data.csv)

## Metodología
1. **Obtención:** Selección de la muestra.
2. **Análisis exploratorio:** EDA en Google Colab con Python.
3. **Limpieza:** Tratamiento de valores faltantes y consistencia de variables.
4. **Transformación:** Preparación para ingesta en Power BI.
5. **Análisis:** Comparación de métricas mediante KPIs.
6. **Visualización:** Desarrollo de dashboard interactivo en Power BI.

## Resultados Principales
* **Brecha global:** Con 324 empleados (52% varones, 48% mujeres), la brecha salarial es del **7,09%** a favor de los hombres ($1,03M vs $961K).
* **Impacto educativo:** A mayor grado académico, mayor ingreso. La mayor disparidad de género ocurre en Master's (13,15%).
* **Evolución:** Crecimiento salarial constante con los años de experiencia.

## Material del Proyecto
* **Dataset Original:** [Kaggle](https://www.kaggle.com/datasets/rkiattisak/salaly-prediction-for-beginer)
* **Python (Colab):** [Notebook EDA en /notebooks/](./notebooks/analisis_salarios.ipynb)
* **Dashboard Power BI:** [Archivo .pbix](./dashboard/dashboard_agustina_deoro.pbix) | [Captura](./dashboard/dashboard_preview.png)
* **Repositorio:** [GitHub](https://github.com/adeoro96/herramientasbasicas-deoro-agustina)

## Fuentes
* **Datos:** Kaggle. *Salary Prediction for Beginner*. [Enlace](https://www.kaggle.com/datasets/rkiattisak/salaly-prediction-for-beginer)
* **Visualización:** Microsoft. *Power BI Documentation*. [Enlace](https://learn.microsoft.com/power-bi/)
* **Procesamiento:** Google. *Colaboratory*. [Enlace](https://colab.research.google.com/)
