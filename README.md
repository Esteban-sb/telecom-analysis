## ConnectaTel User Analysis - Sprint 7

Este repositorio contiene el análisis realizado durante el Sprint 7 del caso ConnectaTel.


Se analizaron 3 datasets `users`, `usage` y `plans`. El dataset `users` cuenta con 4000 registros sobre informacion de los usuarios como su nombre, fecha de resgitro, ciudad, edad y plan, ademas cuenta con valores ausentes en la columna ciudad y valores irreales en la columna reg_date. El dataset `usage` cuenta con 4000 registros sobre el uso movil de los usuarios como cantidad de mensajes enviados, llamadas realizadas, minutos en llamadas, ademas cuenta con valores extremos que podrian deberse a usuarios de uso alto. El dataset `plans` cuenta con 2 registros sobre los planes ofrecidos, no cuenta con valores ausentes o outliers.

## Contenido del repositorio

- `notebooks/Project-ConnectaTel.ipynb`
  → Notebook principal con limpieza, EDA, distribuciones, outliers y conclusiones.

## ▶ Cómo abrir el notebook en Google Colab

Haz clic en el siguiente link:

(https://colab.research.google.com/drive/15ZR_IxqXCFq9kTyIlCeGf-eS5Gbv8wwd?usp=sharing)](Project_ConnectaTel.ipynb)

O:

1. Abre el archivo `.ipynb` en GitHub
2. Haz clic en **Open in Colab**

##  Cómo reproducir el análisis

1. Abre `notebooks/Project-ConnectaTel.ipynb`
2. Ejecuta las celdas en orden
3. El notebook carga automáticamente el dataset desde `/data/` o desde un enlace público (según corresponda)

##  Objetivo del análisis

- Identificar problemas de calidad de datos
- Analizar comportamientos, distribuciones y outliers
- Generar un nuevo dataset con datos de los tres datasets cargados.
- Generar visualizaciones para analizar el comportamiento de los usuarios
- Generar insights para el equipo de Estrategia e Integración de EverPeak
