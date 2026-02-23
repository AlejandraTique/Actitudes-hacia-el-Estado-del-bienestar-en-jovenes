Actitudes hacia el Estado del bienestar en jóvenes

Descripción 
Estudio y análisis de las actitudes de la población joven respecto al Estado del bienestar. El proyecto realiza ingestión y limpieza de datos (encuestas, redes sociales u otras fuentes), análisis descriptivo y temporal, modelado de temas y sentimiento, y análisis relacional para identificar patrones, correlaciones y segmentos en las opiniones sobre políticas públicas y bienestar.

Objetivos

Describir y cuantificar las actitudes de jóvenes sobre el Estado del bienestar.
Identificar temas y motivos recurrentes en el discurso (empleo, educación, salud, protección social, etc.).
Evaluar polaridad y sentimiento respecto a políticas concretas.
Analizar relaciones entre variables sociodemográficas y actitudes.
Visualizar resultados y producir artefactos reproducibles para interpretación y comunicación.

Contenido sdel repositorio

actitudes_estado_bienestar_jovenes.ipynb

README.md — este documento.

Descripción del dataset

Los datos utilizados en este proyecto son datos simulados, generados para fines educativos y de demostración. No representan datos reales de encuestas ni de fuentes oficiales.
Esta simulación permite ilustrar el flujo de trabajo completo de análisis de actitudes hacia el Estado del bienestar en jóvenes, incluyendo limpieza, modelado y análisis relacional, sin comprometer la privacidad ni requerir permisos de uso de datos reales.

Requisitos 

Python 3.8+
Librerías típicas: pandas, numpy, scikit-learn, statsmodels, nltk o spaCy, gensim o transformers (opcional), matplotlib, seaborn, plotly, geopandas


Ejecución

En Kaggle: abrir el notebook principal y ejecutar las celdas en orden.
Local: abrir los notebooks en JupyterLab/Jupyter Notebook y ejecutar de 01 → 04 en la raíz del proyecto.

Flujo de trabajo recomendado

Ingesta: cargar datos y revisar metadata.
Preprocesamiento: limpieza, imputación de faltantes, codificación de variables categóricas, normalización de texto si procede.
EDA: estadísticas por edad, sexo, región; tablas cruzadas; visualización temporal y por subgrupos.
Modelado: clustering de respuestas, análisis factorial, modelos de regresión o clasificación para explicar actitudes.
NLP (si aplica): extracción de temas y sentimiento en texto libre.
Análisis relacional: redes de co-ocurrencia, correlaciones entre variables y segmentación.
Validación y evaluación: pruebas estadísticas, validación cruzada y robustness checks.
Reporte: síntesis de hallazgos, limitaciones y recomendaciones de política.

Artefactos de salida

CSV con datos procesados y variables derivadas.
Figuras en PNG/SVG y/o dashboards interactivos.
Reporte con resultados principales y metodología reproducible.


Sugerencias para ampliar el proyecto

Realizar un trabajo de WebSrapping para recopilar corpus real. 
Incluir análisis longitudinal si hay varias olas temporales.
Desagregar por subgrupos (región, nivel educativo, sector laboral).
Integrar encuestas complementarias o fuentes administrativas para triangulación.
Implementar modelos causales si hay diseño apropiado (experimentos naturales, instrumentos).

Autor: Alejandra Tique 
contacto:astrea011@gmail.com
