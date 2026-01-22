📰 Entre el Dato y el Discurso: Análisis Lingüístico del Diario Oficial El Peruano

Este repositorio documenta un ejercicio de extracción, procesamiento y análisis lingüístico de contenidos periodísticos del diario oficial El Peruano, con énfasis en el estudio del lenguaje institucional, su densidad léxica y su polaridad semántica.

El proyecto combina técnicas de scraping dinámico, limpieza de datos y análisis textual exploratorio, orientado a comprender patrones discursivos en la comunicación oficial del Estado peruano.

⸻

🎯 Objetivo del proyecto

Analizar el uso del lenguaje en titulares y resúmenes de artículos periodísticos de El Peruano, identificando:
	•	Nivel de especialización del vocabulario
	•	Tono semántico predominante (neutral, positivo, negativo)
	•	Léxico dominante por sección
	•	Temas recurrentes y énfasis discursivos

⸻

🧪 Metodología

1. Extracción de datos
	•	Fuente: Diario oficial El Peruano
	•	Fecha de análisis: 21/01/2026
	•	Metodología: Scraping dinámico
	•	Total de artículos analizados: 39

El scraping dinámico se empleó debido a que el contenido del sitio se renderiza mediante JavaScript, lo que impide su obtención completa mediante scraping estático tradicional.

⸻

2. Información extraída

Para cada artículo se recolectó la siguiente información:
	•	Título
	•	Resumen (bajada)
	•	Sección periodística
	•	Fecha de publicación

Dado que los datos extraídos inicialmente ya se encontraban limpios y estructurados, no fue necesario generar un archivo CSV intermedio adicional.

⸻

3. Procesamiento y análisis lingüístico

Sobre los textos recolectados se aplicaron las siguientes técnicas:
	•	Cálculo de longitud de títulos y resúmenes
	•	Tokenización y eliminación de stopwords
	•	Cálculo de densidad léxica
	•	Identificación de polaridad semántica (positivo, neutral, negativo)
	•	Análisis de léxico dominante por sección
	•	Conteo de frecuencia de palabras en titulares

El análisis permitió clasificar el lenguaje de El Peruano como altamente técnico, institucional y especializado.

⸻

📊 Principales hallazgos (resumen)
	•	Densidad léxica promedio: 0.996 (lenguaje técnico)
	•	71.8% de artículos con tono neutral
	•	Predominio de vocabulario legal, económico y administrativo
	•	Fuerte énfasis temático en el año 2026
	•	Cobertura multiseccional (12 secciones)

Los resultados detallados del análisis se encuentran documentados en el archivo .md incluido en el repositorio.

⸻

📁 Archivos del repositorio

Este proyecto genera únicamente dos archivos CSV, debido a que los datos iniciales ya estaban depurados:
	1.	articulos_elperuano_analizado.csv
Contiene:
	•	Datos originales
	•	Métricas añadidas:
len_titulo, len_resumen, densidad_lexica, sentimiento
	2.	top_palabras_titulos.csv
	•	Top 20 palabras más frecuentes en los títulos

Adicionalmente, se incluye:
	3.	resumen_analisis_linguistico.md
	•	Documento en Markdown con la síntesis interpretativa del análisis, resultados, tablas y conclusiones.

⸻

🛠️ Tecnologías utilizadas
	•	Python
	•	Pandas
	•	Expresiones regulares (regex)
	•	Análisis lingüístico exploratorio
	•	Scraping dinámico

⸻

📌 Nota final

Este repositorio está orientado a fines académicos y analíticos, y busca servir como ejemplo de cómo combinar técnicas de ciencia de datos, análisis del discurso y estudios de comunicación aplicada al contexto peruano.
