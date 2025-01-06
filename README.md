# Proyectos

Lista de Proyectos que he venido realizando, sobre todo en mi Máster en Ciencia de Datos
- **Detección del estado de terror en EEG gracias a la estimulación del cerebro a través de contenidos audiovisuales** (TFM_Acuna_2.ipynb)

  Mi TFM se centraba en la detección del estado de terror mediante datos de electroencefalografía (EEG) inducido por estímulos audiovisuales (videojuegos). Identificar el terror tiene potencial en campos como la neurociencia, la psicología y la seguridad, con posibles   aplicaciones en el tratamiento de trastornos de ansiedad y en el desarrollo de experiencias personalizadas.
  
  El trabajo aborda la identificación del estado de terror en individuos a través de datos de EEG, utilizando el dataset público GAMEEMO (https://doi.org/10.1016/j.bspc.2020.101951), que incluye datos de 28 sujetos expuestos a videojuegos categorizados en cuatro emociones (aburrido, calma, terror y diversión). Estos datos fueron procesados y utilizados para entrenar modelos de Machine Learning (SVM, KNN, RFC, MLP) enfocados en la detección del terror.

  Los resultados mostraron que, aunque KNN tuvo un buen rendimiento en algunas métricas, su capacidad para generalizar fue limitada. Por otro lado, RFC y MLP demostraron ser más efectivos y consistentes en la detección del terror (exactitud de 76,28% y 81,46%, respectivamente), especialmente en datos no vistos (exactitud de 76,15% y 77,03%, respectivamente).

- **Análisis y Preparación de Datos para el Cáncer de Mama: Desde ETL y EDA hasta la Predicción con XGBClassifier** (Cancer_mama_Acuna.ipynb)

  Este proyecto, desarrollado como parte de la asignatura de Adquisición y Preparación de Datos, se centró en aplicar técnicas fundamentales para el manejo y análisis de un dataset sobre el cáncer de mama ([https://www.kaggle.com/datasets/reihanenamdari/breast-cancer/data]). El trabajo incluyó las etapas de data source and acquisition, explorando la obtención y comprensión inicial de los datos, seguidas por un proceso estructurado de ETL (extracción, transformación y carga) para limpiar y organizar la información. Posteriormente, se realizó un EDA (análisis exploratorio de datos) para identificar patrones, distribuciones y relaciones entre las variables categóricas y variables numéricas, lo que facilitó una comprensión más profunda del conjunto de datos.

  Como parte del proceso de preparación, se emplearon técnicas de Feature Engineering para seleccionar y crear nuevas variables que mejoraran la capacidad predictiva del modelo. Finalmente, se implementó una predicción del estado de los pacientes (vivo/muerto) utilizando el algoritmo XGBClassifier. Aunque el código para la predicción fue proporcionado por el maestro debido a nuestra falta de experiencia en Machine Learning en ese momento, el proyecto nos permitió entender la integración de todas estas etapas y sentó las bases para futuras aplicaciones en problemas reales.

- **Clasificación de Imágenes con Deep Learning y Transfer Learning en el Dataset CIFAR-10**

  Este proyecto, desarrollado como parte de la asignatura de Machine Learning Avanzado, tuvo como objetivo aplicar técnicas de Deep Learning para la clasificación de imágenes utilizando el dataset CIFAR-10. Este conjunto de datos consta de 60,000 imágenes en color de 32x32 píxeles, distribuidas equitativamente en 10 clases de objetos. Para abordar el problema, se emplearon 40,000 imágenes etiquetadas para el entrenamiento, 10,000 para validación y 10,000 no etiquetadas para pruebas, garantizando una evaluación independiente del rendimiento de los modelos.

El proyecto incluyó la implementación de un modelo desde cero y el uso de tres arquitecturas preentrenadas de Transfer Learning (VGG19, ResNet18 y ResNet34). Durante el proceso, se evaluaron los enfoques mediante métricas clave obtenidas del conjunto de validación, como loss, accuracy y la confusion matrix, asegurando que las imágenes de validación no se utilizaran para el entrenamiento. Una vez identificado el mejor modelo, se reportaron los resultados finales en el conjunto de prueba para medir su rendimiento de manera independiente. Finalmente, se documentaron todas las pruebas, experimentos y mejoras realizadas en cada paso, destacando los avances logrados mediante el análisis comparativo de métricas y gráficos detallados.
