[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1R5eEstpbCGX-EqkEthoFVsG3I107P1BT?usp=sharing)

# Algoritmos de Busqueda en Grafos: BFS y DFS

Este proyecto implementa en Python dos algoritmos fundamentales de busqueda en grafos:

- **BFS (Breadth First Search)** – Busqueda en anchura  
- **DFS (Depth First Search)** – Busqueda en profundidad  

Ambos algoritmos permiten recorrer un grafo desde un nodo inicial y explorar todos los nodos conectados.

---

## Descripcion

El programa utiliza un **grafo representado mediante un diccionario de listas de adyacencia**.

Durante la ejecucion se muestra paso a paso el proceso de recorrido, incluyendo:

- Nodo seleccionado en cada iteracion
- Lista de nodos visitados
- Contenido de la **cola** (usada por BFS)
- Contenido de la **pila** (usada por DFS)

Ademas, el programa incluye:

- Representacion visual del grafo
- Medicion del consumo de memoria de cada algoritmo

Esto permite observar como funcionan internamente ambos algoritmos y comparar su comportamiento.

---

## Tecnologias utilizadas

- Python  
- NetworkX (representacion del grafo)  
- Matplotlib (visualizacion)  
- Tracemalloc (medicion de memoria)

---

## Estructura del proyecto

```
algoritmos-busqueda/
│
├── bfs_dfs.py
├── BFS_DFS.ipynb
└── README.md
```

---

## Estructura del Grafo

El grafo utilizado en el programa es el siguiente:

```
A -> B, C
B -> A, D, E
C -> A, F
D -> B
E -> B, F
F -> C, E
```

---

## Ejecucion del Programa

El programa fue desarrollado en **Google Colab**.

Para ejecutarlo:

1. Abrir el archivo `.ipynb`
2. Ejecutar las celdas del notebook
3. Ingresar el nodo inicial cuando el programa lo solicite

Ejemplo:

```
Ingrese el nodo inicial (A-F): A
```

---

## Resultados

Durante la ejecucion el programa muestra:

- Representacion visual del grafo
- Recorrido paso a paso usando BFS
- Recorrido paso a paso usando DFS
- Memoria utilizada por cada algoritmo
- Numero de nodos visitados

---

## Autor

### Edwar Suarez
### Universidad Del Pacifico
### Inteligencia Artificial

Repositorio creado como parte de un ejercicio academico sobre **algoritmos de busqueda en grafos**.