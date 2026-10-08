# PCA y sistemas de recomendación

**Actividad:** A3.1 — Inteligencia Artificial  
**Alumno:** Emiliano Pascual Pinales Sánchez  
**Matrícula:** 657657

## Descripción

La primera parte aplica PCA y regresión logística a datos de cáncer de mama. Después compara media, KNN y SoftImpute en datos Wine; finalmente desarrolla un recomendador de películas a partir de la matriz usuario-película de MovieLens 100k.

## Resultado principal

En la evaluación descrita en el notebook, la variante con cinco componentes tuvo F1-score de 0.9841; el sistema de recomendación obtuvo MAE de 0.7597 y RMSE de 0.9774.

## Archivos

- [`A3_1_PCA_657657.ipynb`](A3_1_PCA_657657.ipynb) — notebook original en Jupyter, con resultados y gráficas guardadas.
- [`reporte.html`](reporte.html) — versión HTML para consultar los resultados sin ejecutar Python.
- [`index.html`](index.html) — página del proyecto dentro del portafolio.

## Datos y reproducción

Fuentes: datasets integrados en scikit-learn (Breast Cancer y Wine) y [MovieLens 100k](https://grouplens.org/datasets/movielens/100k/). La sección de recomendaciones descarga el archivo `ml-100k.zip` automáticamente; requiere conexión a Internet. Para SoftImpute se necesita el paquete `fancyimpute`.

Para ejecutar el notebook se necesita Python y Jupyter Notebook, además de las librerías utilizadas en el código. Se recomienda utilizar un entorno virtual y revisar el archivo `requirements.txt` del repositorio. Para A3.1 también se necesitan `seaborn` y `fancyimpute`.

Los resultados incluidos en los archivos corresponden a las ejecuciones guardadas en el notebook; esta publicación no vuelve a entrenar los modelos.

[Volver al portafolio](../index.html)
