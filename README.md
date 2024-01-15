# RestaurarIA

Es un proyecto que experimenta con la inteligencia artificial para restaurar cine y video Mexicano.
A partir de un video antiguo, se extraen los fotogramas y se restauran con la ayuda de la inteligencia artificial.

El proceso de restauración utiliza
    * Un modelo de super resolución para aumentar la resolución de los fotogramas
    * Un modelo de eliminación de ruido para eliminar el ruido de los fotogramas
    * Un modelo de interpolación de fotogramas para aumentar la cantidad de fotogramas por segundo
    * Un modelo de colorización para agregar color a los fotogramas

El resultado es un video restaurado con mayor resolución, sin ruido, con más fotogramas por segundo y a color.

Este repositorio incluye los Jupyter Notebooks que se utilizaron en el proceso y una web que recopila 
resultados de este experimento y otros similares.

Para la restauración de la pelicula del "Brazo Fuerte" se utilizó una tarjeta gráfica Nvidia Tesla V100 con 16GB de memoria. 