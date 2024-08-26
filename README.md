![cover](https://github.com/selincocarca/Traduccion_Automatica/assets/168861192/5c3992ee-d004-430e-b5ec-451e4f558b2f)

# Traducción Automática/Automatic Translation

En este repositorio se encuentra un proyecto de traducción automática que utiliza técnicas avanzadas de Procesamiento de Lenguaje Natural. Utilizamos el modelo MarianMT de Helsinki-NLP para traducir entre español, inglés y euskera. La aplicación incluye una interfaz interactiva con widgets de IPython para ingresar texto y seleccionar idiomas. 
/ 
This repository contains an automatic translation project that uses advanced Natural Language Processing techniques. We use the MarianMT model from Helsinki-NLP to translate between Spanish, English, and Basque. The application includes an interactive interface with IPython widgets for entering text and selecting languages.

## Resultados/Results

Los resultados de la experimentación se pueden ver en detalle en el panel de control de Weights & Biases. Esto incluye varias métricas de rendimiento, como la precisión, junto con los hiperparámetros utilizados en cada experimento.
/
The results of the experimentation can be viewed in detail on the Weights & Biases dashboard. This includes various performance metrics, such as accuracy, along with the hyperparameters used in each experiment.

## Descripción del problema/Problem Description

La tarea que abordamos es un ejemplo clásico y significativo de un problema de traducción automática. Nuestro objetivo es traducir texto entre los idiomas español, inglés y euskera utilizando modelos avanzados de procesamiento de lenguaje natural. Este proyecto se apoya en los modelos MarianMT de Helsinki-NLP, reconocidos por su eficacia y precisión en la comunidad de aprendizaje automático.
/
The task we are addressing is a classic and significant example of a machine translation problem. Our goal is to translate text between Spanish, English, and Basque using advanced natural language processing models. This project leverages the MarianMT models from Helsinki-NLP, recognized for their effectiveness and accuracy in the machine learning community.

## Dataset

El conjunto de datos de traducción automática es un dataset de acceso público que contiene múltiples muestras de texto en español, inglés y euskera, con diversos atributos como longitud del texto, estructura gramatical y contexto semántico. Existen tres clases, representando los pares de idiomas a traducir (español-inglés, inglés-euskera, y español-euskera). Este conjunto de datos es ideal para experimentos de traducción automática.
/
The machine translation dataset is a publicly available dataset containing multiple text samples in Spanish, English, and Basque, with various attributes such as text length, grammatical structure, and semantic context. There are three classes, representing the language pairs to be translated (Spanish-English, English-Basque, and Spanish-Basque). This dataset is ideal for machine translation experiments.

## Experimentación/Experimentation

Para este proyecto, utilizamos el modelo de traducción automática MarianMT de Helsinki-NLP, reconocido por su eficacia en el procesamiento de lenguaje natural. Este modelo es particularmente efectivo para tareas de traducción entre múltiples idiomas.

Para encontrar la mejor solución, exploramos diversas combinaciones de hiperparámetros como la tasa de aprendizaje, la longitud máxima de las secuencias y el tamaño del lote. A través de una experimentación sistemática, buscamos entender el efecto de estos hiperparámetros en el rendimiento del modelo y encontrar la combinación que ofrezca los mejores resultados.

Implementamos la solución utilizando widgets de IPython, lo que permite una interfaz interactiva para ingresar texto y seleccionar idiomas. Esto facilita la experimentación y evaluación del modelo, permitiendo a los usuarios probar diferentes configuraciones de manera eficiente y observar los resultados de la traducción en tiempo real.
/
For this project, we used the MarianMT machine translation model from Helsinki-NLP, recognized for its effectiveness in natural language processing. This model is particularly effective for translation tasks between multiple languages.

To find the best solution, we explored various combinations of hyperparameters such as learning rate, maximum sequence length, and batch size. Through systematic experimentation, we aimed to understand the effect of these hyperparameters on the model's performance and identify the combination that offers the best results.

We implemented the solution using IPython widgets, providing an interactive interface for entering text and selecting languages. This facilitates experimentation and model evaluation, allowing users to efficiently test different configurations and observe translation results in real time.

## Ajuste de Hiperparámetros y Mejor Modelo/Hyperparameter Tuning and Best Model

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
/
During the experimentation process, we conducted an exhaustive search in the hyperparameter space. A total of 10 epochs were used to train the model. The hyperparameters we adjusted include:

Learning rate: 0.0001
Maximum sequence length: 128
Batch size: 2
This search allowed us to explore a wide range of models and configurations to optimize performance in the automatic translation task between Spanish, English, and Basque.

The model with the best score achieved an average accuracy of 0.504166 on the training set and 0.498065 on the validation set, according to macro accuracy metrics. These results indicate that the model is capable of performing translations with significant accuracy, although there is room for improvement and further refinement of the hyperparameters to achieve better results.

The hyperparameters of the best model, which contributed to these results, are as follows:

Learning rate: 0.0001
Maximum sequence length: 128
Batch size: 2
This combination of hyperparameters enabled the MarianMT model to effectively capture linguistic patterns and perform accurate translations between the analyzed languages.

## Ejecutando el Código/Running the Code

Para ejecutar el código, primero asegúrate de tener instaladas todas las dependencias necesarias.
/
To run the code, first make sure that all necessary dependencies are installed.










