# Clasificacion de Residuos Organico e Inorganico

Este proyecto tiene como objetivo entrenar un modelo de clasificación de imágenes que distingue entre residuos orgánicos e inorgánicos, utilizando la arquitectura DenseNet121. El modelo clasifica residuos en seis categorías: `orgánico`, `plástico`, `vidrio`, `metal`, `cartón` y `papel`.

## Descripción del Proyecto

El proyecto busca automatizar la identificación de residuos, utilizando una red neuronal convolucional (DenseNet121) preentrenada, con el fin de mejorar la precisión en la clasificación de desechos. Este sistema puede ser integrado en plataformas de reciclaje inteligente o en aplicaciones de gestión de residuos, permitiendo una separación más eficiente de los materiales.

### Características Principales:
- **Clasificación en Seis Categorías**: El modelo identifica y clasifica imágenes de residuos en las categorías `orgánico`, `plástico`, `vidrio`, `metal`, `cartón` y `papel`.
- **Entrenamiento Personalizado**: El modelo se entrena con un conjunto de datos de imágenes dividido en conjuntos de entrenamiento y prueba.
- **Arquitectura DenseNet121**: Utiliza la arquitectura DenseNet121, optimizada para la clasificación de imágenes.
- **Automatización**: El sistema facilita la clasificación automática de residuos, lo que puede ser útil en entornos de reciclaje y gestión de desechos.

## Beneficios

Este software proporciona varios beneficios clave:
- **Eficiencia**: Mejora la eficiencia en el manejo de residuos, al automatizar el proceso de clasificación.
- **Precisión**: Utiliza una red de última generación para mejorar la precisión en la identificación de tipos de residuos.
- **Escalabilidad**: El modelo es adaptable y puede ser ajustado para incluir nuevas categorías de residuos o mejorar su desempeño con más datos.
- **Impacto Ambiental**: Al facilitar una mejor clasificación de residuos, este proyecto puede contribuir a mejorar los procesos de reciclaje y reducir la contaminación ambiental.

## Instalación y Requisitos

Para utilizar este proyecto, necesitas:
- Python 3.x
- TensorFlow 2.x
- Numpy
- Matplotlib
- os
- shutil
- Pillow (PIL)

## Estructura del Proyecto

El conjunto de datos está estructurado en directorios que separan las imágenes por categorías y fases de entrenamiento y prueba. El modelo se entrena con imágenes en estas categorías para aprender a clasificar residuos correctamente.

