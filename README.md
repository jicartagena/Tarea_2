# Tarea_2

link video: https://www.youtube.com/watch?v=5S0jI3CF0w4

Una linea principal que comparten ambos codigos, es la instalación de la libreria PySpark. Esto debido a su uso en Google Colab.

## Page Rank

Este codigo se basa en dos bloques, en el primero se definen las variables, estructuras y funciones a usar, mientras que en el segundo se realiza el algoritmo en si.
Las variables radican en las listas de nodos y conexiones a usar, la cantidad maxima de iteraciones a trabajar (en este punto se recomienda usar una cantidad menor a 5 si se requiere un trabajo rapido, ya que el tiempo aumenta exponencialmente con cada aumento de iteración.), el umbral de convergencia y el damping factor a usar.

Para la entrega de resultados, unicamente se debe correr el segundo bloque de codigo.

## Single Source Shortest Path

Este codigo se basa en un solo bloque de codigo. la diferencia es que el proceso se realiza mediante la funcion sssp, y l a definicion de variables es al final. la funcion principal ```ssp``` se encarga de entregarnos una lista con la tupla de (nodo, costo), la cual se recorre al final de bloque de codigo. Aca solo tenemos 3 variables que se pueden interactuar: la lista de nodos y aristas, con sus respectivos costos, y el nodo inicial de donde comienza el algoritmo. cabe recalcar que al probar tantas posibilidades, el codigo puede tender a tener un tiempo de ejecución considerable.
