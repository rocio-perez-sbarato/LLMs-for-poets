# Democratizando los LLMs: Un enfoque práctico para principiante

# Informe de Avances del Proyecto

## Resumen

Este proyecto se enfoca en desarrollar notebooks interactivas accesibles para personas sin experiencia técnica, utilizando Google Colab y Jupyter sin necesidad de APIs de terceros. El objetivo es facilitar el fine-tuning/personalización de LLMs y el resumen automático de textos, permitiendo a los usuarios trabajar con conjuntos de datos propios manteniendo la privacidad. Se proporcionará un entorno pedagógico para el ajuste de hiperparámetros, preprocesamiento y evaluación sistemática de modelos, diseñado para facilitar la experimentación rápida con modelos de lenguaje avanzados sin necesidad de grandes infraestructuras.

## Relación entre Hipótesis y Objetivos Iniciales y el Estado Actual

- **Hipótesis:** Las notebooks interactivas permitirán a usuarios sin experiencia técnica comprender, aplicar y evaluar los LLMs, trabajando con sus propios datos y manteniendo la privacidad.
- **Objetivos:** 
  1. Introducir a los usuarios en Hugging Face y el uso de modelos pre-entrenados.
  2. Enseñar carga y preprocesamiento de datasets, incluyendo tokenización.
  3. Facilitar el fine-tuning de modelos LLM con datasets propios.
  4. Proporcionar herramientas para evaluar el rendimiento de los modelos.
  5. Crear documentación accesible y fomentar la interactividad.
- **Progreso en relación a los objetivos:** Los primeros dos objetivos están casi completos: la notebook 1 (introducción a Hugging Face) y notebook 2 (preprocesamiento de datasets y tokenización) están terminadas, y la notebook 3 (finetuning) está en su fase final de pruebas. Se prevé cumplir los objetivos restantes a tiempo.

## Relación entre la Planificación Inicial y la Ejecución Efectiva
- **Planificación inicial:** 
  - Semana 1: Notebook 1 (Hugging Face).
  - Semana 2: Notebook 2 (Tokenización).
  - Semana 3: Notebook 3 (Fine-tuning).
  - Semana 4: Documentación.
  - Semana 5: Incorporación de devoluciones.
- **Desviaciones:** No ha habido grandes desviaciones. El desarrollo sigue el cronograma previsto. Fuimos haciendo el paso de documentación de los notebooks a la par de la implementación del código, por una cuestión de preveer el estado final de los notebooks. Esto hizo que el notebook 3 aún no esté terminado.
- **Adaptaciones:** A partir de las devoluciones recibidas, adoptamos la filosofía de **"menos es más"**, apostando por simplificar los ejemplos y conceptos en lugar de sobrecargar a los usuarios con demasiada información. Nos centramos en lo esencial para evitar confusión y asegurar la comprensión. Brindamos enlaces a otros recursos educativos. 
  
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
  - Se planea recibir las devoluciones en la próxima fase del proyecto.
  - Se prevé que los comentarios estarán centrados en la accesibilidad y claridad de la documentación, así como la forma de evaluar el éxito del proyecto.
- **Implementación de sugerencias:** Las críticas que recibimos influyeron en la simplificación del contenido, adoptando un enfoque minimalista para evitar sobrecargar a los usuarios. Además, se propuso la creación de formularios para recoger feedback sobre la experiencia del usuario.

### Evaluación del Éxito del Proyecto
- **Críticas recibidas:** Los comentarios más relevantes que recibimos giraron en torno a **cómo vamos a evaluar el éxito del proyecto**. Se nos sugirió que necesitábamos una estrategia clara para medir la efectividad de los notebooks y la comprensión de los usuarios.
- **Respuesta a las críticas:** Decidimos implementar **formularios de feedback** al final de cada notebook para que los usuarios puedan evaluar su experiencia, dificultades y comprensión de los conceptos. Estos formularios recogerán datos cuantitativos y cualitativos, que usaremos para ajustar las notebooks en la fase final.
- **Criterios de éxito:** El éxito del proyecto se medirá principalmente a través de:
  - **Nivel de comprensión:** Evaluar si los usuarios pueden seguir los ejemplos y ejecutar las tareas propuestas sin mayor dificultad.
  - **Satisfacción del usuario:** Recoger opiniones sobre la claridad, utilidad y facilidad de uso de los notebooks.

## Próximos Pasos y Planificación hacia la Presentación Final
- **Tareas pendientes:**
  - Completar la tercera notebook (fine-tuning y evaluación de modelos).
  - Finalizar la documentación interactiva.
  - Realizar pruebas con usuarios para evaluar la comprensión y usabilidad de los notebooks.
  - Incorporar devoluciones de otros grupos.
- **Plazos:** 
  - Semana 4 (del 1 al 8 de noviembre): finalización de la tercera notebook.
  - Semana 5 (del 9 al 16 de noviembre): pruebas con usuarios.
  - Semana 6 (del 17 al 24 de noviembre): incorporación de devoluciones y pulido final de las notebooks. Redacción del informe final.
  - Semana 7 (del 25 al 1 de diciembre): revisión final y entrega.

## Conclusión
- **Conclusión provisional:** El proyecto está progresando según lo planeado. Se ha avanzado significativamente en la creación de notebooks accesibles y comprensibles, con dos de tres notebooks casi completas. Las pruebas con usuarios y los formularios de feedback serán clave para evaluar la comprensión y usabilidad de las herramientas desarrolladas.

