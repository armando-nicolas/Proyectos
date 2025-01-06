# Proyectos

Lista de Proyectos que he venido realizando, sobre todo en mi Máster en Ciencia de Datos
- **Detección del estado de terror en EEG gracias a la estimulación del cerebro a través de contenidos audiovisuales** (TFM_Acuna_2.ipynb)
  Mi TFM se centraba en la detección del estado de terror mediante datos de electroencefalografía (EEG) inducido por estímulos audiovisuales (videojuegos). Identificar el terror
tiene potencial en campos como la neurociencia, la psicología y la seguridad, con posibles aplicaciones en el tratamiento de trastornos de ansiedad y en el desarrollo de experiencias personalizadas.

El trabajo aborda la identificación del estado de terror en individuos a través de EEG, utilizando el dataset público GAMEEMO (https://doi.org/10.1016/j.bspc.2020.101951), que incluye datos de 28 sujetos expuestos a videojuegos categorizados en cuatro emociones (aburrido, calma, terror y diversión). Estos datos fueron procesados y utilizados para entrenar modelos de Machine Learning (SVM, KNN, RFC, MLP) enfocados en la detección del terror.

Los resultados mostraron que, aunque KNN tuvo un buen rendimiento en algunas métricas, su capacidad para generalizar fue limitada. Por otro lado, RFC y MLP demostraron ser más
efectivos y consistentes en la detección del terror (exactitud de 76,28% y 81,46%, respectivamente), especialmente en datos no vistos (exactitud de 76,15% y 77,03%, respectivamente).
