# YuotubeComments-Processing

Análisis de Comentarios de YouTube con NLTK, Transformers y Scikit-learn
Este repositorio contiene un notebook para el análisis de comentarios de un video de YouTube. El proceso incluye la descarga de comentarios, preprocesamiento de texto, generación de embeddings utilizando la librería Transformers, y la agrupación de los comentarios en clusters usando scikit-learn.

Estructura del Proyecto
notebook.ipynb: Contiene todo el análisis del proyecto. Desde la obtención de los comentarios hasta el análisis de clusters usando técnicas de NLP.
Requisitos del Proyecto
Este proyecto utiliza las siguientes librerías:

NLTK: Para preprocesamiento de texto, como la eliminación de stopwords y tokenización.
Transformers: Para la generación de embeddings a partir de los comentarios de YouTube.
scikit-learn: Para el análisis y clustering de los comentarios.

Las librerías principales que necesitas son:
- nltk
- transformers
- scikit-learn
- pandas
- matplotlib (opcional para visualizaciones)
## Preprocesamiento del Texto
El notebook utiliza NLTK para limpiar y preprocesar los comentarios:
- Tokenización: Separar el texto en palabras.
- Eliminación de stopwords: Eliminar palabras comunes y no significativas.
- Lematización: Convertir las palabras a su forma base.
  
## Generación de Embeddings

Se utiliza la librería Transformers para generar embeddings multilingües de los comentarios, lo que permite representar semánticamente los comentarios de manera eficiente.

- Modelo utilizado: intfloat/multilingual-e5-small.
  
## Clustering de Comentarios
Usando scikit-learn, los comentarios se agrupan en clusters según sus características semánticas:

KMeans: Agrupación de los comentarios en clusters.
Evaluación de los clusters: Interpretación y análisis de los grupos de comentarios similares.
