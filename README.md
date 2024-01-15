Disponible en DATACAMP

La generación de recuperación aumentada, o RAG, es una técnica que se utiliza con modelos de lenguaje grandes para proporcionar contexto adicional sin ajustes ni reentrenamiento. Mejora la capacidad de los modelos lingüísticos para proporcionar respuestas objetivas, lo cual es una limitación de las configuraciones clásicas.

El objetivo de este proyecto es crear un robot de respuesta a preguntas relacionadas con películas. Para lograr esto, usaremos RAG para proporcionar información objetiva al modelo de lenguaje. Cargaremos descripciones de películas en una base de datos vectorial y la usaremos para buscar contexto relevante para el modelo de lenguaje.

Usaremos las siguientes herramientas y modelos:

Modelo gpt-3.5-turbo de OpenAI para terminaciones rápidas
Modelo text-embedding-ada-002 de OpenAI para crear incrustaciones vectoriales
Pinecone como base de datos vectorial para almacenar las incrustaciones.
langchain como herramienta para interactuar con OpenAI y Pinecone
El conjunto de datos utilizado para este proyecto proviene del conjunto de datos de Kaggle Películas/Programas IMDb con _Descripciones_.
