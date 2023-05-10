# Practica 3: Implementación de un grafo dirigido

Este repositorio contiene el código necesario para implementar un grafo dirigido en el cual se crean, comprueban y enumeran vértices y uniones de un grafo

## ***Contenido del repositorio***
Este repositorio tiene varios archivos:
- **Graph.java**: clase donde se desarrollan los métodos del grafo
- **GraphTest.java**: clase donde se realizan los tests necesarios para la comprobación de los metodos del proyecto.
- **README.md**: archivo en el que se desarrolla detalladamente el proyecto
- **DiagramUML.png**: imagen que contiene el diagrama UML del proyecto de Java

## ***EXPLICACIÓN DE LOS MÉTODOS***

La clase Graph tiene multiples métodos:
- **addVertex(V v)**: crea un vertice de nombre v y lo añade al grafo
- **addEdge(V v1, V v2)**: añade una arista cuando existen 2 vértices v1 y v2
- **obtainAdjacents(V v)**: obtiene el conjunto de adyacentes a v
- **containsVertex(V v)**: devuelve un output booleano verdadero si el grafo contiene al vértice
- **onePath(V v1, V v2)**: encuentra el camino entre los vértices v1 y v2 en base al algoritmo de busqueda en anchura


## ***UML***
<img width="291" alt="Captura de pantalla 2023-05-08 121532" src="https://user-images.githubusercontent.com/125443353/236799640-6d37ac9a-d730-4170-9d0f-383ad32d8e45.png">


<sub>Copyright (c) 2012-2023 kikeh2004
Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:
The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.
 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.</sub>
