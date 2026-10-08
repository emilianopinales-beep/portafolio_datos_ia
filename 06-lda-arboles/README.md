# LDA y árboles de decisión

**Actividad:** A2.2 — Inteligencia Artificial  
**Alumno:** Emiliano Pascual Pinales Sánchez  
**Matrícula:** 657657

## Descripción

Se comparan el análisis discriminante lineal (LDA) y los árboles de decisión con poda por complejidad de costo. Ambos enfoques se evalúan con la misma división de entrenamiento y prueba y métricas de clasificación.

## Resultado principal

LDA obtuvo accuracy de 0.7757, F1-score de 0.7776 y ROC-AUC de 0.8573; el árbol de decisión obtuvo accuracy de 0.7759, F1-score de 0.7754 y ROC-AUC de 0.8575.

## Archivos

- [`A2_2_657657.ipynb`](A2_2_657657.ipynb) — notebook original en Jupyter, con resultados y gráficas guardadas.
- [`reporte.html`](reporte.html) — versión HTML para consultar los resultados sin ejecutar Python.
- [`index.html`](index.html) — página del proyecto dentro del portafolio.

## Datos y reproducción

Fuente: [INEGI — ENIGH 2024](https://www.inegi.org.mx/programas/enigh/nc/2024/). La actividad utiliza el archivo `concentradohogar.csv`, que debe estar disponible en la misma carpeta del notebook para volver a ejecutar las celdas.

Para ejecutar el notebook se necesita Python y Jupyter Notebook, además de las librerías utilizadas en el código. Se recomienda utilizar un entorno virtual y revisar el archivo `requirements.txt` del repositorio. Para A3.1 también se necesitan `seaborn` y `fancyimpute`.

Los resultados incluidos en los archivos corresponden a las ejecuciones guardadas en el notebook; esta publicación no vuelve a entrenar los modelos.

[Volver al portafolio](../index.html)
