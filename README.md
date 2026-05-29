# UGR_IdS_TP_GRUPO_11

## Docentes

- Ing. Ignacio Sanseovich
- Lic. Briant Gauna

## Integrantes

- Amuchástegui, Octavio
- Cabral, Luciano Federico
- Flament, Paola Vanesa
- Franco, Francisco
- Martinez, Oscar Aníbal
- Moyano, José Hernán
- Olivo, Gabriel
- Tofalo, Tobías

## Clasificación de riesgo hídrico en la Provincia de Buenos Aires

Trabajo práctico de la asignatura Ingeniería del Software de la Universidad del Gran Rosario. El proyecto aborda la priorización de riesgo hídrico por partido en la Provincia de Buenos Aires a partir de variables físico-territoriales y un enfoque de minería de datos basado en CRISP-DM.

El objetivo es construir un modelo de clasificación que permita asignar un nivel de vulnerabilidad a inundaciones y generar evidencia visual para apoyar decisiones de Defensa Civil, municipios y áreas de obras públicas.

## Objetivos

- Clasificar partidos en riesgo bajo, medio o alto.
- Analizar el aporte de variables como impermeabilización del suelo, elevación y pendiente.
- Producir visualizaciones que faciliten la interpretación del riesgo territorial.
- Generar insumos útiles para priorizar inversiones y acciones de mitigación.

## Contenido del proyecto

- Notebook principal con el flujo completo de análisis: comprensión del negocio, comprensión de los datos, preparación, modelado y visualización.
- Mapas y gráficos exportados como resultados del análisis exploratorio y geoespacial.
- HTML interactivos con visualizaciones GIS para explorar el riesgo por partido.

## Estructura del repositorio

- [UGR_IdS_TP_GRUPO_11.ipynb](UGR_IdS_TP_GRUPO_11.ipynb): notebook principal del trabajo.
- [riesgo_hidrico_pba.html](riesgo_hidrico_pba.html): visualización HTML principal del proyecto.
- [reports/eda_histograms.png](reports/eda_histograms.png): histogramas del análisis exploratorio.
- [reports/eda_boxplots.png](reports/eda_boxplots.png): boxplots del análisis exploratorio.
- [reports/eda_correlation_matrix.png](reports/eda_correlation_matrix.png): matriz de correlación.
- [reports/confusion_matrix.png](reports/confusion_matrix.png): matriz de confusión del modelo.
- [reports/gis_heatmap_risk.html](reports/gis_heatmap_risk.html): mapa de calor GIS del riesgo por partido.
- [reports/gis_bubble_risk.html](reports/gis_bubble_risk.html): mapa de burbujas GIS del riesgo por partido.

## Fuente de datos

El notebook trabaja con un dataset local llamado `porc de suelo impermeable, elevacion y pendiente.csv`, que incluye variables territoriales para cada partido. También contempla una estrategia de carga compatible con Windows y Google Colab, con detección automática de rutas y descarga por URL si el archivo no está disponible localmente.

## Metodología

El desarrollo sigue las fases de CRISP-DM:

1. Comprensión del negocio.
2. Comprensión de los datos.
3. Preparación de los datos.
4. Modelado con Random Forest.
5. Evaluación y visualización de resultados.

## Requisitos sugeridos

- Python 3.10 o superior.
- Jupyter Notebook o VS Code con soporte para notebooks.
- Paquetes habituales de análisis de datos: pandas, numpy, scikit-learn, matplotlib, seaborn y plotly.

## Cómo ejecutar

1. Abrir [UGR_IdS_TP_GRUPO_11.ipynb](UGR_IdS_TP_GRUPO_11.ipynb) en Jupyter o VS Code.
2. Ejecutar las celdas en orden.
3. Verificar que el archivo CSV del dataset esté disponible en la ruta esperada o permitir que el notebook lo descargue automáticamente.
4. Revisar los resultados generados en la carpeta [reports](reports).

## Resultados

El proyecto genera salidas gráficas y geoespaciales para interpretar el riesgo hídrico por partido, incluyendo histogramas, boxplots, correlaciones, matriz de confusión y dos mapas GIS interactivos.


