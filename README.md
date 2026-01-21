# Análisis de Datos con Python

## Objetivo
Analizar un conjunto de datos para extraer conclusiones útiles mediante limpieza, exploración y visualización.

## Tecnologías
- Python
- pandas
- numpy
- matplotlib

## Contenido
- Limpieza de datos
- Análisis exploratorio
- Visualización de resultados
- Conclusiones finales

# Análisis de Ventas Farmacéuticas

## Descripción del proyecto
Este proyecto consiste en el análisis de datos de ventas farmacéuticas mensuales con el objetivo de identificar tendencias temporales y comparar el rendimiento de distintas categorías de medicamentos. El análisis se ha realizado utilizando Python y librerías de análisis de datos.

El proyecto está orientado a demostrar habilidades propias de un perfil **Junior Data Analyst**, incluyendo limpieza de datos, análisis exploratorio, visualización y extracción de conclusiones.

---

## Dataset
Se utiliza el archivo `salesmonthly.csv`, que contiene información agregada de ventas mensuales de diferentes categorías de medicamentos clasificadas según códigos ATC.

- Periodo analizado: varios años
- Número de registros: 70
- Variables:
  - `datum`: fecha (mes)
  - Categorías de medicamentos (M01AB, M01AE, N02BA, N02BE, N05B, N05C, R03, R06)

---

## Tecnologías utilizadas
- Python
- pandas
- matplotlib
- Jupyter Notebook

---

## Análisis realizado
- Conversión y tratamiento de la columna de fechas.
- Creación de una métrica de ventas totales mensuales.
- Análisis de la evolución temporal de las ventas.
- Comparación del volumen de ventas entre distintas categorías de medicamentos.
- Identificación de las categorías con mayor impacto en las ventas totales.
- Visualización de resultados mediante gráficos.

---

## Principales conclusiones
- Las ventas presentan variaciones a lo largo del tiempo, con picos más elevados en determinados meses.
- La categoría **N02BE** concentra el mayor volumen de ventas totales, seguida de **N05B** y **R03**.
- El análisis permite identificar patrones de consumo y puede servir de apoyo para la toma de decisiones comerciales y de planificación de stock.

---

## Estructura del repositorio
- `pharma_sales_analysis.ipynb`: notebook con el análisis completo.
- `salesmonthly.csv`: dataset utilizado para el análisis.
