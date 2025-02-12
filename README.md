# reto_9
## Que son los algoritmos sorting?
Los algoritmos de sorting (ordenamiento) son métodos que organizan los elementos de una lista o arreglo en un orden específico, generalmente ascendente o descendente. Son fundamentales en la informática porque muchas tareas, como la búsqueda eficiente de datos o la optimización de recursos, dependen de listas ordenadas.
## Tipos de algoritmos de ordenamiento:
### Algoritmos de Ordenamiento Básicos (O(n²))
#### Son sencillos de entender e implementar, pero no son eficientes para grandes volúmenes de datos.

##### Bubble Sort (Ordenamiento de burbuja) 🫧

Compara elementos adyacentes y los intercambia si están en el orden incorrecto.
Tiempo de ejecución: O(n²) en el peor caso.

##### Selection Sort (Ordenamiento por selección) 

Encuentra el mínimo y lo coloca en su posición correcta.
Tiempo de ejecución: O(n²).

##### Insertion Sort (Ordenamiento por inserción)

Inserta cada elemento en su posición correcta dentro de una parte ordenada de la lista.
Tiempo de ejecución: O(n²) (este en concreto es eficiente en listas casi ordenadas).
### Algoritmos de Ordenamiento Eficientes (O(n log n))
#### Se utilizan en aplicaciones reales debido a su alto rendimiento.

##### Merge Sort (Ordenamiento por mezcla)

Divide la lista en mitades hasta tener elementos individuales y luego los combina en orden.
Complejidad: O(n log n).

##### Quick Sort (Ordenamiento rápido)

Selecciona un pivote, divide la lista en menores y mayores, y ordena recursivamente.
Complejidad: O(n log n) en el mejor caso, pero O(n²) en el peor caso si el pivote se elige mal.

##### Heap Sort

Convierte la lista en un heap (estructura de árbol) y extrae el mínimo/máximo repetidamente.
Complejidad: O(n log n).

### Algoritmos Especializados
#### Algunos algoritmos no usan comparaciones, lo que les permite ser más rápidos que O(n log n) en ciertos casos.

##### Counting Sort

Funciona bien con numeros en un rango pequeño.
Complejidad: O(n + k) (donde k es el rango de valores).

##### Radix Sort

Ordena numeros considerando digitos de menor a mayor.
Complejidad: O(nk) (k es el número de dígitos).

##### Bucket Sort

Distribuye los valores en cubetas, los ordena individualmente y los junta.
Muy eficiente para distribuciones uniformes.

## ¿Cual usar?
Para pocos elementos → `Insertion Sort` o `Bubble Sort`
Para grandes volúmenes de datos → `Merge Sort` o `Quick Sort`
Si los valores tienen un rango pequeño → `Counting Sort` o `Radix Sort`

## **Concepto de Bubble Sort**

Bubble Sort es un algoritmo de ordenamiento basado en comparaciones que funciona intercambiando elementos adyacentes si están en el orden incorrecto. Este proceso se repite hasta que la lista está completamente ordenada.
