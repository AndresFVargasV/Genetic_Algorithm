# Algoritmo genético para el problema del viajante (TSP)

Este proyecto implementa un algoritmo genético para intentar encontrar una buena solución aproximada al problema del viajante (TSP).

## Descripción del problema TSP

El problema del viajante (Traveling Salesman Problem, TSP) consiste en encontrar la ruta más corta posible que visite una serie de ciudades y regrese a la ciudad origen, visitando una sola vez cada ciudad. Es un problema clásico de optimización combinatoria.

## Algoritmo genético 

Los algoritmos genéticos son técnicas de optimización inspiradas en conceptos como la selección natural y la genética. Parten de una población inicial de soluciones candidatas generadas aleatoriamente. Cada solución tiene asociada una "aptitud" que indica qué tan buena es. Luego, se realizan operaciones para combinar y mutar esas soluciones candidatas, generando nuevas poblaciones de soluciones que conservan las características de mayor aptitud.

Este proceso se repite durante varias generaciones hasta encontrar soluciones con aptitud suficientemente buena o hasta que no se observa más mejora.

## Detalles de implementación

La implementación consta de:

- Un generador aleatorio de ciudades con coordenadas x,y
- Una función de distancia euclidiana entre ciudades
- Generación aleatoria de caminos iniciales
- Cálculo de la aptitud de cada camino como la suma de distancias del recorrido
- Algoritmo genético con:
  - Selección de los caminos con mejor aptitud
  - Cruce de caminos para generar nuevos descendientes
  - Mutación aleatoria de algunos caminos
  - Reemplazo de la población por los nuevos descendientes
- Visualización del mejor camino encontrado

Los parámetros principales como el tamaño de la población, número de generaciones, probabilidad de mutación, etc. se pueden modificar fácilmente.

Este proyecto muestra una aplicación directa de los algoritmos genéticos para intentar resolver aproximadamente un problema complejo de optimización combinatoria.

