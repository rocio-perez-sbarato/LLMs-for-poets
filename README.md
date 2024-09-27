# Democratizando los LLMs: Un enfoque práctico para principiantes

## Resumen

Este proyecto se enfoca en desarrollar notebooks interactivas accesibles para personas sin experiencia técnica, utilizando Google Colab y Jupyter sin necesidad de APIs de terceros. El objetivo es facilitar el fine-tuning/personalización de LLMs y el resumen automático de textos, permitiendo a los usuarios trabajar con conjuntos de datos propios manteniendo la privacidad. Se proporcionará un entorno pedagógico para el ajuste de hiperparámetros, preprocesamiento y evaluación sistemática de modelos, diseñado para facilitar la experimentación rápida con modelos de lenguaje avanzados sin necesidad de grandes infraestructuras.

## Hipótesis

La creación de notebooks interactivas y accesibles sobre LLMs permitirá a usuarios sin experiencia técnica:

1. Comprender y aplicar efectivamente técnicas de fine-tuning en modelos de lenguaje para tareas específicas como el resumen automático de textos.
2. Trabajar con sus propios conjuntos de datos de manera segura y privada, sin depender de APIs o servicios externos.
3. Experimentar y evaluar rápidamente la utilidad de los LLMs para sus necesidades específicas, fomentando una toma de decisiones informada sobre el uso de estas tecnologías.
4. Adquirir habilidades prácticas en el manejo de datasets, tokenización, entrenamiento y evaluación de modelos de lenguaje, superando las barreras de entrada tradicionalmente asociadas con estas tecnologías.

## Objetivos preliminares

- Introducir a los usuarios en el uso de Hugging Face y las librerías necesarias para interactuar con modelos de lenguaje.
- Enseñar a cargar y preprocesar datasets, incluyendo la tokenización de textos.
- Capacitar a los usuarios para entrenar y hacer fine-tuning de un modelo LLM con sus propios datasets.
- Proporcionar herramientas y metodologías para evaluar el rendimiento de los modelos ajustados.
- Crear documentación clara y accesible para cada notebook.
- Fomentar la interactividad mediante ejemplos prácticos y ejercicios.

## Técnicas relevantes

Se utilizarán Google Colab y la librería Transformers de Hugging Face, incluyendo técnicas de fine-tuning y text-generation.
  
## Referencias
- [Using pretrained LLM for text classification](https://colab.research.google.com/drive/1h3hQ8anuKjoWJXz12p-OgwduBpYQB7rI?usp=sharing)
- [Taller: Modelos de lenguaje a tu medida](https://colab.research.google.com/github/nanom/llm_adaptation_workshop/blob/main/Taller_Modelos_de_lenguaje_a_tu_medida_13_de_septiembre_2023.ipynb)
- [Social Impacts of Artificial Intelligence](https://colab.research.google.com/drive/1bSo9oXpB7fHjPB5UZGKJAcyA0zXHGjZO?usp=sharing#scrollTo=7JMLkzn24hnm)

## Planificación (1 mes + 1 semana extra de revisión)

### Semana 1: Notebook 1 - Hugging Face y Librerías
- Introducción a Hugging Face y su ecosistema
- Instalación y configuración de las librerías necesarias (transformers, datasets, etc.)
- Exploración de modelos pre-entrenados disponibles
- Demostración básica de cómo cargar y usar un modelo pre-entrenado
- Introducción a las tareas de procesamiento de lenguaje natural (NLP)

### Semana 2: Notebook 2 - Datasets y Tokenización
- Carga y exploración de datasets usando la librería datasets
- Preparación y limpieza de datos
- Introducción a la tokenización
- Procesamiento de datos

### Semana 3: Notebook 3 - Entrenamiento y Prueba del Modelo Nuevo
- Configuración del modelo para fine-tuning
- Definición de hiperparámetros de entrenamiento
- Implementación del bucle de entrenamiento usando Trainer de Hugging Face
- Monitoreo del proceso de entrenamiento (loss, perplexity)
- Evaluación del modelo en el conjunto de prueba
- Generación de texto con el modelo fine-tuned
- Comparación de resultados entre el modelo base y el modelo adaptado
- Guardado y carga del modelo personalizado

### Semana 4
- Redacción y finalización de la documentación pedagógica para cada notebook, detallando los pasos, conceptos clave y explicaciones necesarias para que los usuarios puedan autogestionarse.

### Semana 5 en adelante
- Incorporación de críticas y devoluciones de compañeros
- Mejoras adicionales en las notebooks con base en las sugerencias recibidas
- Revisión final para asegurar que las notebooks cumplen con los objetivos del proyecto

Este proyecto busca democratizar el acceso a los LLMs, permitiendo a usuarios sin experiencia técnica comprender, aplicar y evaluar estas poderosas herramientas en sus propios proyectos y necesidades específicas.