# Regresión logística y validación cruzada

**Actividad:** A2.1 — Inteligencia Artificial  
**Alumno:** Emiliano Pascual Pinales Sánchez  
**Matrícula:** 657657

## Descripción

Se trabaja con microdatos de hogares de la ENIGH 2024. El modelo clasifica hogares según el nivel de gasto corriente monetario. Incluye preparación de variables, validación cruzada de cinco particiones, matriz de confusión, curvas ROC y análisis de umbrales.

## Resultado principal

En el conjunto de prueba se obtuvo un accuracy de 0.7805, un F1-score de 0.7811 y un ROC-AUC de 0.8665.

## Archivos

- [`A2_1_657657.ipynb`](A2_1_657657.ipynb) — notebook original en Jupyter, con resultados y gráficas guardadas.
- [`reporte.html`](reporte.html) — versión HTML para consultar los resultados sin ejecutar Python.
- [`index.html`](index.html) — página del proyecto dentro del portafolio.

## Datos y reproducción

Fuente: [INEGI — ENIGH 2024](https://www.inegi.org.mx/programas/enigh/nc/2024/). La actividad utiliza el archivo `concentradohogar.csv`, que debe estar disponible en la misma carpeta del notebook para volver a ejecutar las celdas.

Para ejecutar el notebook se necesita Python y Jupyter Notebook, además de las librerías utilizadas en el código. Se recomienda utilizar un entorno virtual y revisar el archivo `requirements.txt` del repositorio. Para A3.1 también se necesitan `seaborn` y `fancyimpute`.

Los resultados incluidos en los archivos corresponden a las ejecuciones guardadas en el notebook; esta publicación no vuelve a entrenar los modelos.

[Volver al portafolio](../index.html)
