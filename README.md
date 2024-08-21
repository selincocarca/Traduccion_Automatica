![cover](https://github.com/selincocarca/Traduccion_Automatica/assets/168861192/5c3992ee-d004-430e-b5ec-451e4f558b2f)

# Traducción Automática

En este repositorio se encuentra un proyecto de traducción automática que utiliza técnicas avanzadas de Procesamiento de Lenguaje Natural. Utilizamos el modelo MarianMT de Helsinki-NLP para traducir entre español, inglés y euskera. La aplicación incluye una interfaz interactiva con widgets de IPython para ingresar texto y seleccionar idiomas.

## Resultados

Los resultados de la experimentación se pueden ver en detalle en el panel de control de Weights & Biases. Esto incluye varias métricas de rendimiento, como la precisión, junto con los hiperparámetros utilizados en cada experimento.

## Descripción del problema

La tarea que abordamos es un ejemplo clásico y significativo de un problema de traducción automática. Nuestro objetivo es traducir texto entre los idiomas español, inglés y euskera utilizando modelos avanzados de procesamiento de lenguaje natural. Este proyecto se apoya en los modelos MarianMT de Helsinki-NLP, reconocidos por su eficacia y precisión en la comunidad de aprendizaje automático.

## Dataset

El conjunto de datos de traducción automática es un dataset de acceso público que contiene múltiples muestras de texto en español, inglés y euskera, con diversos atributos como longitud del texto, estructura gramatical y contexto semántico. Existen tres clases, representando los pares de idiomas a traducir (español-inglés, inglés-euskera, y español-euskera). Este conjunto de datos es ideal para experimentos de traducción automática.

## Experimentación

Para este proyecto, utilizamos el modelo de traducción automática MarianMT de Helsinki-NLP, reconocido por su eficacia en el procesamiento de lenguaje natural. Este modelo es particularmente efectivo para tareas de traducción entre múltiples idiomas.

Para encontrar la mejor solución, exploramos diversas combinaciones de hiperparámetros como la tasa de aprendizaje, la longitud máxima de las secuencias y el tamaño del lote. A través de una experimentación sistemática, buscamos entender el efecto de estos hiperparámetros en el rendimiento del modelo y encontrar la combinación que ofrezca los mejores resultados.

Implementamos la solución utilizando widgets de IPython, lo que permite una interfaz interactiva para ingresar texto y seleccionar idiomas. Esto facilita la experimentación y evaluación del modelo, permitiendo a los usuarios probar diferentes configuraciones de manera eficiente y observar los resultados de la traducción en tiempo real.

## Ajuste de Hiperparámetros y Mejor Modelo

Durante el proceso de experimentación, realizamos una búsqueda exhaustiva en el espacio de hiperparámetros. Se probaron un total de 10 épocas para entrenar el modelo. Los hiperparámetros que ajustamos incluyen:

Tasa de aprendizaje: 0.0001
Longitud máxima de las secuencias: 128
Tamaño del lote: 2
Esta búsqueda nos permitió explorar una amplia gama de modelos y configuraciones para optimizar el rendimiento en la tarea de traducción automática entre los idiomas español, inglés y euskera.

El modelo con el mejor puntaje alcanzó una precisión promedio de 0.504166 en el conjunto de entrenamiento y 0.498065 en el conjunto de validación, según las métricas de precisión macro. Estos resultados indican que el modelo es capaz de realizar traducciones con una precisión significativa, aunque hay espacio para mejorar y refinar los hiperparámetros para obtener mejores resultados.

Los hiperparámetros del mejor modelo, que contribuyeron a estos resultados, son los siguientes:

Tasa de aprendizaje: 0.0001
Longitud máxima de las secuencias: 128
Tamaño del lote: 2
Esta combinación de hiperparámetros permitió que el modelo MarianMT capturara eficazmente los patrones lingüísticos y realizara traducciones precisas entre los idiomas analizados.

## Ejecutando el Código

Para ejecutar el código, primero asegúrate de tener instaladas todas las dependencias necesarias.


## Contribuciones

Las contribuciones a este repositorio son bienvenidas. Asegúrate de que el código siga las mejores prácticas y esté bien documentado.


