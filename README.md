# Democratizando los LLMs: Un enfoque práctico para principiantes

# Informe de Avances del Proyecto

## Resumen

Este proyecto se enfoca en desarrollar notebooks interactivas accesibles para personas sin experiencia técnica, utilizando Google Colab y Jupyter sin necesidad de APIs de terceros. El objetivo es facilitar el fine-tuning/personalización de LLMs y el resumen automático de textos, permitiendo a los usuarios trabajar con conjuntos de datos propios manteniendo la privacidad. Se proporcionará un entorno pedagógico para el ajuste de hiperparámetros, preprocesamiento y evaluación sistemática de modelos, diseñado para facilitar la experimentación rápida con modelos de lenguaje avanzados sin necesidad de grandes infraestructuras.

## Hipótesis

La creación de notebooks interactivas y accesibles sobre LLMs permitirá a usuarios sin experiencia técnica:

1. Comprender y aplicar efectivamente técnicas de fine-tuning en modelos de lenguaje para tareas específicas como el resumen automático de textos.
2. Trabajar con sus propios conjuntos de datos de manera segura y privada, sin depender de APIs o servicios externos.
3. Experimentar y evaluar rápidamente la utilidad de los LLMs para sus necesidades específicas, fomentando una toma de decisiones informada sobre el uso de estas tecnologías.
4. Adquirir habilidades prácticas en el manejo de datasets, tokenización, entrenamiento y evaluación de modelos de lenguaje, superando las barreras de entrada tradicionalmente asociadas con estas tecnologías.

## Objetivos preliminares

1. Introducir a los usuarios en el uso de Hugging Face y las librerías necesarias para interactuar con modelos de lenguaje.
2. Enseñar a cargar y preprocesar datasets, incluyendo la tokenización de textos.
3. Capacitar a los usuarios para entrenar y hacer fine-tuning de un modelo LLM con sus propios datasets.
4. Proporcionar herramientas y metodologías para evaluar el rendimiento de los modelos ajustados.
5. Crear documentación clara y accesible para cada notebook.
6. Fomentar la interactividad mediante ejemplos prácticos y ejercicios.
  
## Relación entre Hipótesis y Objetivos Iniciales y el Estado Actual

- **Progreso en relación a los objetivos:** Gran parte de los objetivos han sido alcanzados: la notebook 1 (Hugging Face y Librerías) y notebook 2 (Datasets y Tokenización) están terminadas. La notebook 3 (Entrenamiento y Prueba del Modelo Nuevo) está en su fase final de pruebas. Hemos logrado crear documentación clara y accesible para cada notebook, así como fomentar la interactividad a través de ejemplos prácticos y ejercicios. 

## Relación entre la Planificación Inicial y la Ejecución Efectiva
- **Planificación inicial:** 
  - Semana 1: Notebook 1 - Hugging Face y Librerías.
  - Semana 2: Notebook 2 - Datasets y Tokenización.
  - Semana 3: Notebook 3 - Entrenamiento y Prueba del Modelo Nuevo.
  - Semana 4: Documentación de las notebooks.
  - Semana 5: Incorporación de devoluciones de otros grupos.
- **Desviaciones:** No se han presentado desviaciones significativas, y el desarrollo avanza según lo planificado. Hemos trabajado en la documentación de los notebooks en paralelo con la implementación del código, anticipando el estado final de los mismos. Como resultado de esta estrategia, el notebook 3 aún no está finalizado. 
  
## Exploración de Librerías y Codebases
- **Librerías / Codebases investigadas:** Hugging Face (transformers, datasets), Google Colab, PyTorch.
- **Elecciones finales y justificación:**
  - Hugging Face fue seleccionada por su robustez y comunidad activa, lo que facilita su adopción por principiantes.
  - Google Colab ofrece un entorno gratuito y fácil de usar para personas sin acceso a hardware especializado.
  - PyTorch fue elegido debido a su integración con Hugging Face y su flexibilidad en tareas de aprendizaje automático.
- **Desarrollo técnico:** 
  - La estructura del codebase está orientada a la modularidad, separando claramente la carga de datasets, tokenización, y entrenamiento de modelos.
  - La interactividad es clave, permitiendo a los usuarios modificar parámetros y observar los resultados de manera inmediata.

## Referencias
- [Using pretrained LLM for text classification](https://colab.research.google.com/drive/1h3hQ8anuKjoWJXz12p-OgwduBpYQB7rI?usp=sharing)
- [Taller: Modelos de lenguaje a tu medida](https://colab.research.google.com/github/nanom/llm_adaptation_workshop/blob/main/Taller_Modelos_de_lenguaje_a_tu_medida_13_de_septiembre_2023.ipynb)
- [Social Impacts of Artificial Intelligence](https://colab.research.google.com/drive/1bSo9oXpB7fHjPB5UZGKJAcyA0zXHGjZO?usp=sharing#scrollTo=7JMLkzn24hnm)
- [Hands On Large Language Models](https://github.com/HandsOnLLM/Hands-On-Large-Language-Models/tree/main)

## Devoluciones y Comentarios de Otros Grupos
- **Revisión de otros grupos:** 
  - Se planteó que el proyecto es una propuesta interesante, pero es fundamental definir criterios específicos de éxito y las herramientas para medir la efectividad de los notebooks y la comprensión de los usuarios. Además, se sugirió aclarar el público objetivo y considerar la inclusión de recursos adicionales, como tutoriales y ejercicios prácticos, para enriquecer el aprendizaje y facilitar la comprensión de los LLMs.
  - **Implementación de sugerencias:** Para abordar estas críticas, incluiremos recursos adicionales, principalmente de Jay Alammar, como tutoriales y ejercicios prácticos, ya que consideramos que estas mejoras son fundamentales para facilitar el aprendizaje y adaptar el contenido a las necesidades de los usuarios, especialmente aquellos sin experiencia previa. Además, se propuso la creación de formularios para recoger feedback sobre la experiencia del usuario.

### Evaluación del Éxito del Proyecto
- **Respuesta a las críticas:** Decidimos implementar **formularios de feedback** al final de cada notebook para que los usuarios puedan evaluar su experiencia, dificultades y comprensión de los conceptos. Estos formularios recogerán datos cuantitativos y cualitativos, que usaremos para ajustar las notebooks en la fase final.
- **Criterios de éxito:** El éxito del proyecto se medirá principalmente a través de:
  - **Nivel de comprensión:** Evaluar si los usuarios pueden seguir los ejemplos y ejecutar las tareas propuestas sin mayor dificultad.
  - **Satisfacción del usuario:** Recoger opiniones sobre la claridad, utilidad y facilidad de uso de los notebooks.

## Próximos Pasos y Planificación hacia la Presentación Final
- **Tareas pendientes:**
  - Completar la tercera notebook (fine-tuning y evaluación de modelos).
  - Finalizar la documentación interactiva.
  - Incorporar formularios al final de cada notebook, a modo de recopilación de feedback y evaluación de comprensión.
  - Realizar pruebas con usuarios para evaluar la comprensión y usabilidad de los notebooks.
  - Incorporar devoluciones de otros grupos.
- **Plazos:** 
  - Semana 4 (del 1 al 8 de noviembre): finalización de la tercera notebook.
  - Semana 5 (del 9 al 16 de noviembre): formularios y pruebas con usuarios.
  - Semana 6 (del 17 al 24 de noviembre): incorporación de devoluciones, pulido final de las notebooks y redacción del informe final.
  - Semana 7 (del 25 al 1 de diciembre): revisión final y entrega.

## Conclusión
- **Conclusión provisional:** El proyecto está progresando según lo planeado. Se ha avanzado significativamente en la creación de notebooks accesibles y comprensibles, con dos de tres notebooks casi completas. Las pruebas con usuarios y los formularios de feedback serán clave para evaluar la comprensión y usabilidad de las herramientas desarrolladas.

