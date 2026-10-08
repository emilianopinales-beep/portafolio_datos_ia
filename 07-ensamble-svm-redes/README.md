# Modelos de ensamble, SVM y redes neuronales

**Actividad:** A2.3 — Inteligencia Artificial  
**Alumno:** Emiliano Pascual Pinales Sánchez  
**Matrícula:** 657657

## Descripción

Se entrena y compara Random Forest, Gradient Boosting, un SVM lineal y una red neuronal sencilla empleando la misma partición de la ENIGH 2024. Se analizan métricas, matrices de confusión y diferencias entre entrenamiento y prueba.

## Resultado principal

Random Forest alcanzó accuracy de 0.7836, F1-score de 0.7856 y ROC-AUC de 0.8675. Los cuatro enfoques obtuvieron desempeños cercanos.

## Archivos

- [`A2_3_657657.ipynb`](A2_3_657657.ipynb) — notebook original en Jupyter, con resultados y gráficas guardadas.
- [`reporte.html`](reporte.html) — versión HTML para consultar los resultados sin ejecutar Python.
- [`index.html`](index.html) — página del proyecto dentro del portafolio.

## Datos y reproducción

Fuente: [INEGI — ENIGH 2024](https://www.inegi.org.mx/programas/enigh/nc/2024/). La actividad utiliza el archivo `concentradohogar.csv`, que debe estar disponible en la misma carpeta del notebook para volver a ejecutar las celdas.

Para ejecutar el notebook se necesita Python y Jupyter Notebook, además de las librerías utilizadas en el código. Se recomienda utilizar un entorno virtual y revisar el archivo `requirements.txt` del repositorio. Para A3.1 también se necesitan `seaborn` y `fancyimpute`.

Los resultados incluidos en los archivos corresponden a las ejecuciones guardadas en el notebook; esta publicación no vuelve a entrenar los modelos.

[Volver al portafolio](../index.html)
