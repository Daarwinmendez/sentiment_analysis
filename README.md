# Análisis de Sentimientos en Reseñas de Películas

Este proyecto se centra en el **análisis de sentimientos** aplicado a reseñas de películas, utilizando un conjunto de datos obtenido de [Kaggle](https://www.kaggle.com/datasets/fahadrehman07/movie-reviews-and-emotion-dataset). Se realiza un análisis exploratorio y se aplican técnicas de preprocesamiento de texto con **NLTK** para extraer características relevantes y clasificar las reseñas según su sentimiento.

## Características Principales

- **Dataset:** Reseñas de películas con etiquetas de sentimientos basadas en 8 emociones distintas.
- **Procesamiento del Lenguaje Natural (NLP):**
  - Tokenización y lematización con **NLTK**.
  - Eliminación de contracciones utilizando el paquete **contractions**.
  - Detección de idioma con **py3langid**.
  - Análisis de frecuencia de palabras y etiquetado gramatical (POS tagging).
- **Visualizaciones:** Uso de **matplotlib** para representar la distribución de palabras y resultados del análisis.
- **Modelo de Clasificación:** Implementación de un modelo de análisis de sentimientos (detalles del algoritmo pueden ser ajustados según el proyecto).
- **Hallazgos Principales:** Identificación de patrones de sentimiento en las reseñas y evaluación de la precisión del modelo de clasificación.

## Requisitos y Descarga de Dependencias

Para ejecutar este notebook se debe descargar el archivo `requirements.txt` que incluye todas las dependencias necesarias. Puedes instalarlas ejecutando:

```bash
pip install -r requirements.txt
```
## Uso
1. Clona este repositorio o descarga el archivo sentiment_analysis.ipynb.
2. Descarga el archivo requirements.txt y ejecuta el comando de instalación mencionado.
3. Abre el notebook y ejecuta las celdas en orden para:
  * Preprocesar los datos.
  * Entrenar el modelo de análisis de sentimientos.
  * Analizar y visualizar los resultados.
4. Ajusta los parámetros o algoritmos de clasificación según sea necesario para mejorar la precisión del análisis.

¡Explora y aprende sobre el análisis de sentimientos en reseñas de películas con este proyecto!
