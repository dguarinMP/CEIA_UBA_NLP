<img src="https://github.com/hernancontigiani/ceia_memorias_especializacion/raw/master/Figures/logoFIUBA.jpg" width="500" align="center">

<br>

# **Procesamiento de Lenguaje Natural**
# **Trabajo Práctico Integrador**

> **Carrera de Especialización en Inteligencia Artificial, Facultad de Ingeniería**
>
> **Universidad de Buenos Aires, Agosto de 2024**
>
> Edgar David Guarin Castro (davidg@marketpsychdata.com)

## Introducción

Este repositorio contiene una serie de dasfíos propuestos durante el curso de Procesamiento de Lenguaje Natural (*Natural Language Processing*, NLP) de la Carrera de Especialización en Inteligencia Artificial.

Los desafíos muestran cómo solucionar dferentes tareas de NLP que van desde el procesamiento de texto hasta el entrenamiento de modelos de aprendizaje de máquina para predicción de palabras y análisis de sentimiento. 

Cada desafío fue solucionado usando Jupyter Notebooks y librerías de Python como Keras/Tensorflow.

## ¿Cómo usarlo?



## Contenido

### Desafio 1: Similaridad coseno

Empleando un dataset en ingles, se midio la similaridad entre los documentos usando la similaridad coseno.

[Embeddings de palabras](desafio_2/desafio_2.ipynb)

### Desafío 2: Embeddings de caracteres y palabras

![Embeddings de palabras](./images/words_embeddings.png)

[Embeddings de palabras](desafio_2/desafio_2.ipynb) 
#### Objetivo
Empleando como documento un libro escrito en español se generaron embeddings de caracteres y palabras.

### Desafío 3: Tokenización

![Modelo Lenguaje Char](./images/tokenizacion.png)

- [Preprocesamiento de datos](desafio_3/1_preprocesamiento.ipynb) 
- [Modelo Lenguaje Char](desafio_3/2_modelo_lenguaje_char.ipynb) 
- [Modelo Lenguaje Word](desafio_3/2_modelo_lenguaje_word.ipynb) 

#### Objetivo
Empleando como documento un libro escrito en español se generó la tokenización de caractéres y palabras.

### Desafío 4: LSTM Bot QA

![LSTM Bot QA](./images/bot_qa.png)

- [LSTM Bot QA](desafio_4/desafio_4_bot.ipynb) 

#### Objetivo
Utilizando datos disponibles del challenge ConvAI2 (Conversational Intelligence Challenge 2) de conversaciones en inglés se contruiyó un BOT para responder a preguntas del usuario (QA).

### Desafío 5: Análisis de sentimientos usando Bert

![Sentimientos Bert](./images/analisis_sentimientos.png)

[Bert Sentiment Analysis](desafio_5/desafio_5_bert_sentiment_analysis.ipynb) 
#### Objetivo
Empleando el modelo preentrenado de BERR se implemento una clasificación de reviews de aplicaciones basados en los sentimientos de los usuarios.