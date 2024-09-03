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

## ¿Cómo usar los notebooks?

0. Clone este repositorio

```bash
git clone https://github.com/dguarinMP/CEIA_UBA_NLP.git
cd CEIA_UBA_NLP
```

1. Se recomienda subir los notebooks a un entorno de Colab para facilitar su ejecución. 

2. Los resultados también se pueden visualizar desde el *Preview* de GitHub.


## Contenido

### [Desafio 1: Vectorización de texto](Desafio1/Desafio_1_VectorizacionTexto.ipynb)

Usando el dataset *20 newsgroups*, se realizan algunos análisis en torno a la vectorización de texto y los modelos de clasificación Naïve Bayes.

### [Desafío 2: Embeddings de palabras](Desafio2/Desafio_2_CustomEmbeddings.ipynb)

Se emplea el dataset de [notícias financieras de Reuters](https://github.com/duynht/financial-news-dataset) con el fin de generar embeddings o vectores de palabras en el contexto de noticias financieras. La forma de estos vectores es definida en función de cómo las palabras se usan en dicho contexto. 

### [Desafío 3: Modelo de lenguaje por tokenización de caracteres](Desafio3/Desafio_3_Modelo_caracteres.ipynb)

Con el dataset de [notícias financieras de Reuters](https://github.com/duynht/financial-news-dataset) se realiza:
- un pre-procesamiento para tokenizar el corpus, estructurar el dataset y separar entre datos de entrenamiento y validación.
- una implementación de un modelo de lenguaje con arquitecturas de redes neuronales basadas en unidades recurrentes.
- una generación de nuevas secuencias a partir de secuencias de contexto con las estrategias de *greedy search* y *beam search* determinístico y estocástico. En este último caso se busca observar el efecto de la temperatura en la generación de secuencias.

### [Desafío 4: QA Bot](Desafio4/Desafio_4_BotQA.ipynb)

A partir de los datos disponibles del *Second Conversational Intelligence Challenge* [ConvAI2](https://research.facebook.com/publications/the-second-conversational-intelligence-challenge-convai2/) de conversaciones en inglés, se construye un BOT que responde ciertas preguntas hechas por el usuario (QA).

### [Desafío 5: Análisis de sentimiento con Bert](Desafio5/Desafio_5_AnalisisSentimiento.ipynb)

Se entrena un modelo de clasificación de análisis de sentimiento para un dataset de recomendaciones de apps utilizando BERT como encoder.

