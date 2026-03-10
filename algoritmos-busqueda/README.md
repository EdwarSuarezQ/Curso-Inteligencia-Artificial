# Algoritmos de Busqueda en Grafos: BFS y DFS

Este proyecto implementa en Python dos algoritmos fundamentales de busqueda en grafos:

- **BFS (Breadth First Search)** – Busqueda en anchura  
- **DFS (Depth First Search)** – Busqueda en profundidad  

Ambos algoritmos permiten recorrer un grafo desde un nodo inicial y explorar todos los nodos conectados.

---

## Descripción

El programa utiliza un **grafo representado mediante un diccionario de listas de adyacencia**.

Durante la ejecucion se muestra paso a paso el proceso de recorrido, incluyendo:

- Nodo seleccionado en cada iteracion
- Lista de nodos visitados
- Contenido de la **cola** (usada por BFS)
- Contenido de la **pila** (usada por DFS)

Esto permite observar como funcionan internamente ambos algoritmos.

---

## Tecnologias utilizadas

- **Python**
- Algoritmos de grafos
- BFS (Breadth First Search)
- DFS (Depth First Search)

---

## Estructura del proyecto

```
algoritmos-busqueda/
│
├── bfs-dfs.py
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

Para ejecutar el programa:

```bash
python bfs-dfs.py
```

Luego el programa solicitara ingresar el **nodo inicial** desde el cual se realizara el recorrido.

Ejemplo:

```
Ingrese el nodo inicial: A
```

---

## Resultados

Al finalizar la ejecucion, el programa muestra:

- El recorrido completo usando **BFS**
- El recorrido completo usando **DFS**
- La cantidad de nodos visitados en cada algoritmo

---


Proyecto realizado como parte de un taller de **algoritmos de busqueda en grafos** para la asignatura de **Inteligencia Artificial**.
