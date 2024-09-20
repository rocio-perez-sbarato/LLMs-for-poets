# LLMs for poets

> **Idea general de qué cosas tendría que decir el informe**
> 
> Saqué la estructura de acá:
>> 20% Entregas preliminares del proyecto
>> propuesta de proyecto, con título, resumen, hipótesis de trabajo, objetivos preliminares, técnicas relevantes para aplicar, referencias (bibliográficas y de código), planificación

> **Lluvia de ideas de títulos**
>> - Personalización de un modelo para resumen de textos
>> - Personalizá tu modelo para resumen de textos
>> - 

## Resumen

- Proyecto enfocado en desarrollar notebooks interactivas accesibles para personas sin experiencia técnica.
- Uso de Google Colab y Jupyter sin necesidad de APIs de terceros.
- Enfoque en fine-tuning/personalización de LLMs y resumen automático de textos.
- Permitir a los usuarios trabajar con conjuntos de datos propios manteniendo la privacidad de los datos.
- Proporcionar un entorno pedagógico para el ajuste de hiperparámetros, preprocesamiento, y evaluación sistemática de modelos.
- Diseñado para facilitar la experimentación rápida con modelos de lenguaje avanzados sin necesidad de grandes infraestructuras.
- Se propone que los LLMs sean vistos como una opción más a considerar en la resolución de problemas, permitiendo a los usuarios elegir de manera informada si son adecuados para sus necesidades.

## Hipótesis
> *No sé qué habría que poner acá, me parece que tendría que ser parecido a objetivos preliminares*
  
- Es posible desarrollar notebooks que sean fácilmente comprensibles y accesibles para usuarios sin experiencia técnica.
- Los usuarios podrán realizar fine-tuning de LLMs para adaptar los modelos a sus propios datasets y aplicarlos a tareas como el resumen automático de textos.
- Se podrá garantizar que los usuarios trabajen con sus datos de forma segura, sin tener que enviarlos a APIs o servicios externos, manteniendo la privacidad de los mismos.
- Dado el crecimiento y la complejidad de los recursos en Procesamiento del Lenguaje Natural, estos notebooks permitirán a los usuarios experimentar rápidamente con LLMs y evaluar si son útiles para su problema específico.

## Objetivos preliminares

- Introducir a los usuarios en el uso de Hugging Face y las librerías necesarias para interactuar con modelos de lenguaje, proporcionando un entorno accesible y fácil de usar.
- Enseñar a los usuarios a cargar y preprocesar datasets, incluyendo la **tokenización** de textos, para preparar los datos necesarios para el entrenamiento de modelos.
- Capacitar a los usuarios para entrenar y hacer **fine-tuning** de un modelo LLM con sus propios datasets, enfocándose en la adaptación del modelo a tareas específicas, como el resumen de textos.
- Proporcionar a los usuarios las herramientas y metodologías necesarias para evaluar el rendimiento de los modelos ajustados, permitiendo una comprensión crítica de su efectividad en diferentes tareas.
- Crear una documentación clara y accesible para cada notebook, que explique los conceptos clave, pasos a seguir y recomendaciones para facilitar la autogestión y el aprendizaje autónomo de los usuarios.
- Fomentar la interactividad mediante ejemplos prácticos y ejercicios en cada notebook, permitiendo a los usuarios experimentar con los modelos y evaluar su aplicabilidad a problemas reales.

- Guiar a los usuarios en los desafíos típicos del PLN 
  - Entender qué es hugging face
  - Hacerse una cuenta en hugging face
  - Qué es fine tuning, qué es un modelo de lenguaje
  - Cómo cargar datasets
  - Tokenizar y decodificar (si usamos gpt2)
  - Entrenar el modelo
  - Evaluar el nuevo modelo
  - Compartir el modelo en hugging face

- Realizar una serie de tres Notebooks (si hacemos Text-Generation)
  - Notebook 1: HugginFace y Librerías (0,1 y 2 del nano)
    - (detalles)   
  - Notebook 2: Datasets y tokenizar (primera mitad de 4.2 de nano)
    - (detalles)   
  - Notebook 3: Entrenar y probar modelo nuevo (segunda mitad de 4.2 de nano)
    - (detalles)   

## Técnicas relevantes

- Google Colab y Jupyter como entornos de ejecución.
- Transformers: la librería de Hugging Face para cargar y ajustar LLMs.
- Modelos de lenguaje preentrenados como x y x. *(TO DO: definir modelos)*
- Resumen automático de textos utilizando LLMs.
- Fine-tuning de modelos de lenguaje.
- Evaluación sistemática de resultados y visualización. *(TO DO: elegir métricas de evaluación)*
  
## Referencias
> *No sé cómo citar código*
  
- primera aproximación que hizo Mili al proyecto de LLMs for poets:
https://colab.research.google.com/drive/1h3hQ8anuKjoWJXz12p-OgwduBpYQB7rI?usp=sharing
- ejemplo de otra notebooks educativa:
https://github.com/nanom/llm_adaptation_workshop
- como parte del curso encontrarán esta notebook:
https://colab.research.google.com/drive/1bSo9oXpB7fHjPB5UZGKJAcyA0zXHGjZO?usp=sharing#scrollTo=7JMLkzn24hnm

## Planificación (1 mes + 1 semana extra de revisión)

### Semana 1
- **Desarrollo del código del Notebook 1: Hugging Face y Librerías**  
  - Implementación del código basado en el itinerario planificado, que introduce a los usuarios en el uso de Hugging Face y las librerías necesarias para trabajar con LLMs.  
  - (Basado en los notebooks 0, 1 y 2 del taller de nano.) 
  - Incluye configuración del entorno en Colab y primeras interacciones con los modelos de lenguaje.  
  - Revisión del código y feedback interno para corregir errores.

### Semana 2
- **Desarrollo del código del Notebook 2: Datasets y Tokenización**  
  - Implementación del código para la carga de datasets y la tokenización, siguiendo el itinerario establecido.  
  - (Basado en la primera mitad del capítulo 4.2 del nano.)
  - Preprocesamiento y preparación de los datos para entrenamiento y pruebas.  

### Semana 3
- **Desarrollo del código del Notebook 3: Entrenar y Probar un Modelo Nuevo**  
  - Implementación del código para entrenar y probar un modelo LLM ajustado con datasets propios, siguiendo el itinerario establecido.
  - (Basado en la segunda mitad del capítulo 4.2 del nano.)
  - Enfoque en evaluación del modelo con un conjunto de datos específico.  

### Semana 4
- **Redacción y finalización de la documentación pedagógica**:
  - Redacción de la documentación final de cada notebook, detallando los pasos, conceptos clave y explicaciones necesarias para que los usuarios puedan autogestionarse.  

### Semana 5 (extra)
- **Incorporación de críticas y devoluciones de compañeros**:
  - Recopilación y análisis de los comentarios de los compañeros.
  - Mejoras adicionales en las notebooks con base en las sugerencias y críticas recibidas.
  - Revisión final para asegurar que las notebooks cumplen con los objetivos del proyecto.

