<div align="center">

# MODY UNIVERSITY OF SCIENCE AND TECHNOLOGY

## School of Engineering and Technology

<br>

<img width="154" height="157" alt="Mody_University_logo" src="images/logo.png" />

<br>

# DAA LAB

### LAB RECORD

<br><br>

**Student Name:** Priya
**Enrollment Number:** 240157

<br>

**Faculty Name:** Dr. P. K. Bishnoi

<br><br>

**Mody University of Science and Technology**
**School of Engineering and Technology**
Lakshmangarh, Rajasthan

</div>

---

<div style="page-break-after: always;"></div>

# INDEX

<table style="width:100%; border-collapse:collapse;">
  <tr>
    <th style="width:10%;">S. No.</th>
    <th style="width:65%;">Program</th>
    <th style="width:25%;">Link</th>
  </tr>

  <tr>
    <td>21</td>
    <td>Fibonacci Series using Recursion</td>
    <td><a href="#program-21-fibonacci-series-using-recursion">Program 21</a></td>
  </tr>

  <tr>
    <td>22</td>
    <td>Graph Representation using Classes and Objects</td>
    <td><a href="#program-22-graph-representation-using-classes-and-objects">Program 22</a></td>
  </tr>

  <tr>
    <td>23</td>
    <td>Represent given Directed Graph</td>
    <td><a href="#program-23-represent-given-directed-graph">Program 23</a></td>
  </tr>

  <tr>
    <td>24</td>
    <td>Graph Creation using User Input</td>
    <td><a href="#program-24-graph-creation-using-user-input">Program 24</a></td>
  </tr>
</table>

---

<div style="page-break-after: always;"></div>

# Program 21: Fibonacci Series using Recursion

## Aim

To write a Python program to generate the Fibonacci series using recursion.

## Flowchart

<p align="center"><img src="images/program21_flowchart.jpeg" alt="Program 21 flowchart" width="461"></p>

## Program

```python
def fibonacci(n):
    if n == 0:                      # base case 1
        return 0
    if n == 1:                      # base case 2
        return 1
    return fibonacci(n - 1) + fibonacci(n - 2)   # recursive case


terms = int(input("Enter the number of terms: "))

print("Fibonacci series:")
for i in range(terms):
    print(fibonacci(i), end=" ")
print()
```

## Sample Output

```text
Enter the number of terms: 10
Fibonacci series:
0 1 1 2 3 5 8 13 21 34
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 22: Graph Representation using Classes and Objects

## Aim

To write a Python program to represent a graph using Node and Graph classes and objects, add the given vertices and edges to the graph, and display the graph using an adjacency list.

## Flowchart

*Main*

<p align="center"><img src="images/program22_flowchart_main.png" alt="Program 22 flowchart" width="447"></p>

*Function add_vertex*

<p align="center"><img src="images/program22_flowchart_function1.png" alt="Program 22 flowchart" width="426"></p>

*Function add_edge (undirected)*

<p align="center"><img src="images/program22_flowchart_function2.png" alt="Program 22 flowchart" width="326"></p>

*Function display*

<p align="center"><img src="images/program22_flowchart_function3.png" alt="Program 22 flowchart" width="542"></p>

## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []              # list of adjacent Node objects


class Graph:
    def __init__(self):
        self.nodes = {}                  # vertex name -> Node object

    def add_vertex(self, data):
        if data not in self.nodes:
            self.nodes[data] = Node(data)

    def add_edge(self, u, v):            # undirected edge u -- v
        self.nodes[u].neighbors.append(self.nodes[v])
        self.nodes[v].neighbors.append(self.nodes[u])

    def display(self):
        print("Adjacency List:")
        for data, node in self.nodes.items():
            names = ", ".join(str(n.data) for n in node.neighbors)
            print(data, "->", names)


g = Graph()

# Change the vertices and edges below to match the given graph
vertices = ["A", "B", "C", "D", "E"]
edges = [("A", "B"), ("A", "C"), ("B", "D"), ("C", "D"), ("D", "E")]

for v in vertices:
    g.add_vertex(v)

for u, v in edges:
    g.add_edge(u, v)

g.display()
```

## Sample Output

```text
Adjacency List:
A -> B, C
B -> A, D
C -> A, D
D -> B, C, E
E -> D
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 23: Represent given Directed Graph

## Aim

To write a Python program using classes and objects to represent the given directed graph, add all the vertices and directed edges, and display its adjacency list.

## Flowchart

*Main*

<p align="center"><img src="images/program23_flowchart_main.png" alt="Program 23 flowchart" width="496"></p>

*Function add_vertex*

<p align="center"><img src="images/program23_flowchart_function1.png" alt="Program 23 flowchart" width="426"></p>

*Function add_edge (directed)*

<p align="center"><img src="images/program23_flowchart_function2.png" alt="Program 23 flowchart" width="396"></p>

*Function display*

<p align="center"><img src="images/program23_flowchart_function3.png" alt="Program 23 flowchart" width="534"></p>

## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.adjacent = []               # nodes this vertex points to


class Graph:
    def __init__(self):
        self.nodes = {}

    def add_vertex(self, data):
        if data not in self.nodes:
            self.nodes[data] = Node(data)

    def add_edge(self, source, dest):    # directed edge source -> dest
        self.nodes[source].adjacent.append(self.nodes[dest])

    def display(self):
        print("Adjacency List:")
        for data, node in self.nodes.items():
            names = ", ".join(str(n.data) for n in node.adjacent) or "None"
            print(data, "->", names)


g = Graph()

# Change the vertices and directed edges below to match the given graph
vertices = ["A", "B", "C", "D", "E"]
edges = [("A", "B"), ("A", "C"), ("B", "D"), ("C", "D"), ("D", "E")]

for v in vertices:
    g.add_vertex(v)

for source, dest in edges:
    g.add_edge(source, dest)

g.display()
```

## Sample Output

```text
Adjacency List:
A -> B, C
B -> D
C -> D
D -> E
E -> None
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 24: Graph Creation using User Input

## Aim

To write a Python program to create a graph by taking the number of vertices and edges from the user, reading the vertices and edges, and displaying the resulting graph using an adjacency list.

## Flowchart

*Main*

<p align="center"><img src="images/program24_flowchart_main.png" alt="Program 24 flowchart" width="560"></p>

*Function add_vertex*

<p align="center"><img src="images/program24_flowchart_function1.png" alt="Program 24 flowchart" width="426"></p>

*Function add_edge (undirected)*

<p align="center"><img src="images/program24_flowchart_function2.png" alt="Program 24 flowchart" width="352"></p>

*Function display*

<p align="center"><img src="images/program24_flowchart_function3.png" alt="Program 24 flowchart" width="542"></p>

## Program

```python
class Node:
    def __init__(self, data):
        self.data = data
        self.neighbors = []


class Graph:
    def __init__(self):
        self.nodes = {}

    def add_vertex(self, data):
        if data not in self.nodes:
            self.nodes[data] = Node(data)

    def add_edge(self, u, v):            # undirected edge u -- v
        self.nodes[u].neighbors.append(self.nodes[v])
        self.nodes[v].neighbors.append(self.nodes[u])

    def display(self):
        print("Adjacency List:")
        for data, node in self.nodes.items():
            names = ", ".join(str(n.data) for n in node.neighbors) or "None"
            print(data, "->", names)


g = Graph()

v = int(input("Enter number of vertices: "))
for i in range(v):
    name = input("Enter vertex " + str(i + 1) + ": ")
    g.add_vertex(name)

e = int(input("Enter number of edges: "))
for i in range(e):
    u, w = input("Enter edge " + str(i + 1) + " (two vertices separated by space): ").split()
    if u in g.nodes and w in g.nodes:
        g.add_edge(u, w)
    else:
        print("Invalid edge! Both vertices must already exist.")

g.display()
```

## Sample Output

```text
Enter number of vertices: 4
Enter vertex 1: A
Enter vertex 2: B
Enter vertex 3: C
Enter vertex 4: D
Enter number of edges: 4
Enter edge 1 (two vertices separated by space): A B
Enter edge 2 (two vertices separated by space): A C
Enter edge 3 (two vertices separated by space): B D
Enter edge 4 (two vertices separated by space): C D
Adjacency List:
A -> B, C
B -> A, D
C -> A, D
D -> B, C
```

[Back to Index](#index)

---
