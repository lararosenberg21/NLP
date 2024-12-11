# Entregables de la materia NLP - Especialización en Inteligencia Artificial
Este repositorio contiene los entregables correspondientes a la materia de Procesamiento de Lenguaje Natural (NLP) de la especialización en Inteligencia Artificial realizados por Lara Rosenberg. Los trabajos realizados incluyen el análisis de documentos, clasificación de texto, análisis de embeddings, modelos de lenguaje y construcción de un chatbot, entre otros. Cada uno de los entregables se encuentra en su respectiva carpeta y se describe a continuación.

## Índice
- TP 1: Clasificación de documentos y similaridad entre documentos
- TP 2: Vectores y similitudes con Gensim
- TP 3: Modelo de lenguaje con LSTM
- TP 4: Chatbot utilizando FastText

### TP 1: Clasificación de documentos y similaridad entre documentos
Descripción:
En este trabajo práctico, se trabajó con una serie de documentos clasificados según su tipo. El objetivo fue explorar y medir la similaridad del coseno entre los documentos y entrenar modelos de clasificación utilizando el algoritmo Naïve Bayes. Se probaron dos variantes de Naïve Bayes: MultinomialNB y ComplementNB. Además, se generó una matriz término-documento (TDM) y se estudió la similaridad entre palabras.

Pasos realizados:
1. Vectorización de los documentos con CountVectorizer
2. Similaridad del coseno y análisis de resultados.
3. Modelos de clasificación: se entrenaron y evaluaron modelos de clasificación utilizando Naïve Bayes Multinomial y Naïve Bayes Complementario (ComplementNB), utilizando el CountVectorizer y el TF-IDF y se compararon los resultados de los distintos modelos con la métrica de F1-score.
4. Transposición de la Matriz Término-Documento (TDM) y medición de similaridad de palabras.

Ubicación:
El código y la notebook correspondiente se encuentran en la carpeta TP 1.

### TP 2: Vectores y similitudes con Gensim
Descripción:
En este trabajo práctico se utilizó un resumen del libro "Harry Potter y la piedra filosofal" para crear representaciones vectoriales de palabras con la biblioteca Gensim. Se entrenaron los vectores de palabras en un espacio de embeddings y se exploraron las similitudes entre palabras. Además, se plantearon y probaron diversos test de analogías utilizando los vectores generados.

Pasos realizados:
1. Se procesó el resumen del libro de Harry Potter, se eliminaron stopwords y tildes y se tokenizó.
2. Entrenamiento de Word Embeddings con Gensim: se utilizaron los modelos de Word2Vec (skipgram) en Gensim para entrenar vectores de palabras.
3. Similitud entre palabras: se calcularon las similitudes entre palabras en el espacio de embeddings utilizando el modelo entrenado.
4. Pruebas de Analogías: se plantearon y evaluaron analogías utilizando los vectores de palabras generados.

Ubicación:
El código y la notebook correspondiente se encuentran en la carpeta TP 2.

### TP 3: Modelo de lenguaje con LSTM
Descripción:
En este trabajo práctico se entrenó un modelo de lenguaje de tipo many-to-many utilizando LSTM para predecir la siguiente palabra en una secuencia. El corpus utilizado fue el libro Emma de Jane Austen. Posteriormente, se generaron secuencias de texto utilizando el modelo entrenado.

Pasos realizados:
1. Preprocesamiento de texto: se limpió el texto del libro "Emma" y luego se tokenizó.
2. Entrenamiento de LSTM: se construyó un modelo para predecir la siguiente palabra en una secuencia de texto. Este es un modelo de tipo many-to-many.
3. Generación de secuencias: se generaron nuevas secuencias de texto utilizando el modelo entrenado y se probó si el modelo aprendió a continuar el texto de manera coherente.

Ubicación:
El código y la notebook correspondiente se encuentran en la carpeta TP 3.

### TP 4: Chatbot utilizando FastText
Descripción:
En este trabajo práctico se construyó un chatbot que responde preguntas del usuario utilizando embeddings de FastText. El modelo se entrenó con un conjunto de preguntas y respuestas, y luego se testeó su capacidad de respuesta.

Pasos realizados:
1. Se realizó un preprocesamiento y se utilizaron embeddings de FastText para representar las palabras de las preguntas y respuestas.
2. Construcción del Chatbot: se entrenó un modelo basado en el esquema encoder-decoder.
3. Evaluación del chatbot: se realizaron pruebas con distintas preguntas para evaluar la capacidad del modelo de generar respuestas relevantes y coherentes.

Ubicación:
El código y la notebook correspondiente se encuentran en la carpeta TP 4.
