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
    <td>1</td>
    <td>Graphs using Matplotlib</td>
    <td><a href="#program-1-graphs-using-matplotlib">Program 1</a></td>
  </tr>

  <tr>
    <td>2</td>
    <td>Time Execution</td>
    <td><a href="#program-2-time-execution">Program 2</a></td>
  </tr>

  <tr>
    <td>3</td>
    <td>Memory Used</td>
    <td><a href="#program-3-memory-used">Program 3</a></td>
  </tr>

  <tr>
    <td>4</td>
    <td>Time Complexity</td>
    <td><a href="#program-4-time-complexity">Program 4</a></td>
  </tr>

  <tr>
    <td>5</td>
    <td>Linear Search</td>
    <td><a href="#program-5-linear-search">Program 5</a></td>
  </tr>

  <tr>
    <td>6</td>
    <td>Largest Element</td>
    <td><a href="#program-6-largest-element">Program 6</a></td>
  </tr>

  <tr>
    <td>7</td>
    <td>Smallest Element</td>
    <td><a href="#program-7-smallest-element">Program 7</a></td>
  </tr>

  <tr>
    <td>8</td>
    <td>Bubble Sort - Ascending Order</td>
    <td><a href="#program-8-bubble-sort---ascending-order">Program 8</a></td>
  </tr>

  <tr>
    <td>9</td>
    <td>Bubble Sort - Descending Order</td>
    <td><a href="#program-9-bubble-sort---descending-order">Program 9</a></td>
  </tr>

  <tr>
    <td>10</td>
    <td>Insert Element at the End</td>
    <td><a href="#program-10-insert-element-at-the-end">Program 10</a></td>
  </tr>

  <tr>
    <td>11</td>
    <td>Insert Element at a Specified Position</td>
    <td><a href="#program-11-insert-element-at-a-specified-position">Program 11</a></td>
  </tr>

  <tr>
    <td>12</td>
    <td>Delete Element from a Specified Position</td>
    <td><a href="#program-12-delete-element-from-a-specified-position">Program 12</a></td>
  </tr>

  <tr>
    <td>13</td>
    <td>Delete Element by Value</td>
    <td><a href="#program-13-delete-element-by-value">Program 13</a></td>
  </tr>

  <tr>
    <td>14</td>
    <td>Factorial using Recursion</td>
    <td><a href="#program-14-factorial-using-recursion">Program 14</a></td>
  </tr>

  <tr>
    <td>15</td>
    <td>Sum of Numbers using Recursion</td>
    <td><a href="#program-15-sum-of-numbers-using-recursion">Program 15</a></td>
  </tr>

  <tr>
    <td>16</td>
    <td>Fibonacci Series using Recursion</td>
    <td><a href="#program-16-fibonacci-series-using-recursion">Program 16</a></td>
  </tr>

  <tr>
    <td>17</td>
    <td>Graph Representation using Classes and Objects</td>
    <td><a href="#program-17-graph-representation-using-classes-and-objects">Program 17</a></td>
  </tr>

  <tr>
    <td>18</td>
    <td>Represent the Given Directed Graph (Q18)</td>
    <td><a href="#program-18-represent-the-given-directed-graph-q18">Program 18</a></td>
  </tr>

  <tr>
    <td>19</td>
    <td>Represent the Given Directed Graph (Q19)</td>
    <td><a href="#program-19-represent-the-given-directed-graph-q19">Program 19</a></td>
  </tr>

  <tr>
    <td>20</td>
    <td>Graph Creation Using User Input</td>
    <td><a href="#program-20-graph-creation-using-user-input">Program 20</a></td>
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

# Program 1: Graphs using Matplotlib

## Aim

To write a Python program using Matplotlib to plot and display single-line and multiple-line graphs with appropriate labels, title, and legend.

## Flowchart

<p align="center"><img src="images/program01_flowchart.png" alt="Program 1 flowchart" width="560"></p>

## Program

```python
import matplotlib.pyplot as plt

x = [1, 2, 3, 4, 5]
y1 = [2, 4, 6, 8, 10]
y2 = [1, 4, 9, 16, 25]

# ---------- Single-line graph ----------
plt.figure(figsize=(6, 4))
plt.plot(x, y1, color="blue", marker="o", label="y = 2x")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.title("Single Line Graph")
plt.legend()
plt.grid(True)
plt.show()

# ---------- Multiple-line graph ----------
plt.figure(figsize=(6, 4))
plt.plot(x, y1, color="blue", marker="o", label="y = 2x")
plt.plot(x, y2, color="red", marker="s", label="y = x^2")
plt.xlabel("X-axis")
plt.ylabel("Y-axis")
plt.title("Multiple Line Graph")
plt.legend()
plt.grid(True)
plt.show()
```

## Sample Output

<p align="center"><img src="images/program01_output1.png" alt="Program 1 output graph 1" width="480"></p>

<p align="center"><img src="images/program01_output2.png" alt="Program 1 output graph 2" width="480"></p>

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 2: Time Execution

## Aim

To write a Python program to calculate and display the execution time of a program using the time and timeit modules.

## Flowchart

*Main*

<p align="center"><img src="images/program02_flowchart_main.png" alt="Program 2 flowchart" width="545"></p>

*Function sum_of_squares*

<p align="center"><img src="images/program02_flowchart_function1.png" alt="Program 2 flowchart" width="356"></p>

## Program

```python
import time
import timeit


def sum_of_squares():
    total = 0
    for i in range(1, 100001):
        total += i * i
    return total


# ---------- Using the time module ----------
start = time.time()
result = sum_of_squares()
end = time.time()
print("Result of function        :", result)
print("Execution time (time)     : {:.6f} seconds".format(end - start))

# ---------- Using the timeit module ----------
runs = 10
total_time = timeit.timeit(sum_of_squares, number=runs)
print("Total time for", runs, "runs (timeit): {:.6f} seconds".format(total_time))
print("Average time per run      : {:.6f} seconds".format(total_time / runs))
```

## Sample Output

```text
Result of function        : 333338333350000
Execution time (time)     : 0.005291 seconds
Total time for 10 runs (timeit): 0.049479 seconds
Average time per run      : 0.004948 seconds
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 3: Memory Used

## Aim

To write a Python program to measure and display the memory occupied during program execution using the sys and tracemalloc modules.

## Flowchart

<p align="center"><img src="images/program03_flowchart.png" alt="Program 3 flowchart" width="441"></p>

## Program

```python
import sys
import tracemalloc

# Start tracing memory allocations
tracemalloc.start()

numbers = [i for i in range(100000)]
text = "Hello" * 1000

# ---------- Using the sys module ----------
print("Size of list object   :", sys.getsizeof(numbers), "bytes")
print("Size of string object :", sys.getsizeof(text), "bytes")

# ---------- Using the tracemalloc module ----------
current, peak = tracemalloc.get_traced_memory()
print("Current memory usage  : {:.2f} KB".format(current / 1024))
print("Peak memory usage     : {:.2f} KB".format(peak / 1024))

# Stop tracing
tracemalloc.stop()
```

## Sample Output

```text
Size of list object   : 800984 bytes
Size of string object : 5041 bytes
Current memory usage  : 3904.25 KB
Peak memory usage     : 3904.43 KB
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 4: Time Complexity

## Aim

To write a Python program using Matplotlib to plot and compare different time complexities such as O(1), O(log n), O(n), O(n log n), O(n²), O(n³), O(2ⁿ), and O(n!).

## Flowchart

<p align="center"><img src="images/program04_flowchart.png" alt="Program 4 flowchart" width="560"></p>

## Program

```python
import math
import numpy as np
import matplotlib.pyplot as plt

n = np.arange(1, 11)                      # input sizes 1 to 10

o_1 = np.ones(len(n))                     # O(1)
o_logn = np.log2(n)                       # O(log n)
o_n = n                                   # O(n)
o_nlogn = n * np.log2(n)                  # O(n log n)
o_n2 = n ** 2                             # O(n^2)
o_n3 = n ** 3                             # O(n^3)
o_2n = 2.0 ** n                           # O(2^n)
o_fact = np.array([math.factorial(int(i)) for i in n], dtype=float)  # O(n!)

plt.figure(figsize=(9, 6))
plt.plot(n, o_1, label="O(1)")
plt.plot(n, o_logn, label="O(log n)")
plt.plot(n, o_n, label="O(n)")
plt.plot(n, o_nlogn, label="O(n log n)")
plt.plot(n, o_n2, label="O(n^2)")
plt.plot(n, o_n3, label="O(n^3)")
plt.plot(n, o_2n, label="O(2^n)")
plt.plot(n, o_fact, label="O(n!)")

plt.ylim(0, 500)                          # limit y-axis so slow curves stay visible
plt.xlabel("Input size (n)")
plt.ylabel("Number of operations")
plt.title("Comparison of Time Complexities")
plt.legend()
plt.grid(True)
plt.show()
```

## Sample Output

<p align="center"><img src="images/program04_output1.png" alt="Program 4 output graph 1" width="480"></p>

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 5: Linear Search

## Aim

To write a Python program to search for a given element in an array using Linear Search.

## Flowchart

<p align="center"><img src="images/program05_flowchart.png" alt="Program 5 flowchart" width="560"></p>

## Program

```python
arr = list(map(int, input("Enter array elements separated by space: ").split()))
key = int(input("Enter the element to search: "))

for i in range(len(arr)):
    if arr[i] == key:
        print("Element", key, "found at position", i + 1, "(index", str(i) + ")")
        break
else:
    print("Element", key, "not found in the array")
```

## Sample Output

```text
Enter array elements separated by space: 10 25 30 45 60
Enter the element to search: 45
Element 45 found at position 4 (index 3)
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 6: Largest Element

## Aim

To write a Python program to find the largest element in an array.

## Flowchart

<p align="center"><img src="images/program06_flowchart.png" alt="Program 6 flowchart" width="560"></p>

## Program

```python
arr = list(map(int, input("Enter array elements separated by space: ").split()))

largest = arr[0]
for i in range(1, len(arr)):
    if arr[i] > largest:
        largest = arr[i]

print("Array            :", arr)
print("Largest element :", largest)
```

## Sample Output

```text
Enter array elements separated by space: 12 45 7 89 23
Array            : [12, 45, 7, 89, 23]
Largest element : 89
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 7: Smallest Element

## Aim

To write a Python program to find the smallest element in an array.

## Flowchart

<p align="center"><img src="images/program07_flowchart.png" alt="Program 7 flowchart" width="560"></p>

## Program

```python
arr = list(map(int, input("Enter array elements separated by space: ").split()))

smallest = arr[0]
for i in range(1, len(arr)):
    if arr[i] < smallest:
        smallest = arr[i]

print("Array             :", arr)
print("Smallest element :", smallest)
```

## Sample Output

```text
Enter array elements separated by space: 12 45 7 89 23
Array             : [12, 45, 7, 89, 23]
Smallest element : 7
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 8: Bubble Sort - Ascending Order

## Aim

To write a Python program to sort an array in ascending order using Bubble Sort.

## Flowchart

<p align="center"><img src="images/program08_flowchart.jpeg" alt="Program 8 flowchart" width="329"></p>

## Program

```python
arr = list(map(int, input("Enter array elements separated by space: ").split()))
print("Original array :", arr)

n = len(arr)
for i in range(n - 1):
    for j in range(n - i - 1):
        if arr[j] > arr[j + 1]:                  # swap if out of order
            arr[j], arr[j + 1] = arr[j + 1], arr[j]

print("Sorted (ascending) :", arr)
```

## Sample Output

```text
Enter array elements separated by space: 64 34 25 12 22 11 90
Original array : [64, 34, 25, 12, 22, 11, 90]
Sorted (ascending) : [11, 12, 22, 25, 34, 64, 90]
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 9: Bubble Sort - Descending Order

## Aim

To write a Python program to sort an array in descending order using Bubble Sort.

## Flowchart

<p align="center"><img src="images/program09_flowchart.png" alt="Program 9 flowchart" width="560"></p>

## Program

```python
arr = list(map(int, input("Enter array elements separated by space: ").split()))
print("Original array :", arr)

n = len(arr)
for i in range(n - 1):
    for j in range(n - i - 1):
        if arr[j] < arr[j + 1]:                  # swap if out of order
            arr[j], arr[j + 1] = arr[j + 1], arr[j]

print("Sorted (descending) :", arr)
```

## Sample Output

```text
Enter array elements separated by space: 64 34 25 12 22 11 90
Original array : [64, 34, 25, 12, 22, 11, 90]
Sorted (descending) : [90, 64, 34, 25, 22, 12, 11]
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 10: Insert Element at the End

## Aim

To write a Python program to insert a new element at the end of an array.

## Flowchart

<p align="center"><img src="images/program10_flowchart.jpeg" alt="Program 10 flowchart" width="300"></p>

## Program

```python
arr = list(map(int, input("Enter array elements separated by space: ").split()))
element = int(input("Enter the element to insert at the end: "))
print("Array before insertion :", arr)

arr.append(element)

print("Array after insertion  :", arr)
```

## Sample Output

```text
Enter array elements separated by space: 10 20 30 40
Enter the element to insert at the end: 50
Array before insertion : [10, 20, 30, 40]
Array after insertion  : [10, 20, 30, 40, 50]
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 11: Insert Element at a Specified Position

## Aim

To write a Python program to insert a new element at a specified position in an array.

## Flowchart

<p align="center"><img src="images/program11_flowchart.jpeg" alt="Program 11 flowchart" width="300"></p>

## Program

```python
arr = list(map(int, input("Enter array elements separated by space: ").split()))
position = int(input("Enter the position (index 0 to " + str(len(arr)) + "): "))
element = int(input("Enter the element to insert: "))
print("Array before insertion :", arr)

if position < 0 or position > len(arr):
    print("Invalid position!")
else:
    arr.insert(position, element)
    print("Array after insertion  :", arr)
```

## Sample Output

```text
Enter array elements separated by space: 10 20 30 40
Enter the position (index 0 to 4): 2
Enter the element to insert: 25
Array before insertion : [10, 20, 30, 40]
Array after insertion  : [10, 20, 25, 30, 40]
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 12: Delete Element from a Specified Position

## Aim

To write a Python program to delete an element from a specified position in an array.

## Flowchart

<p align="center"><img src="images/program12_flowchart.png" alt="Program 12 flowchart" width="560"></p>

## Program

```python
arr = list(map(int, input("Enter array elements separated by space: ").split()))
position = int(input("Enter the position to delete (index 0 to " + str(len(arr) - 1) + "): "))
print("Array before deletion :", arr)

if position < 0 or position >= len(arr):
    print("Invalid position!")
else:
    removed = arr.pop(position)
    print("Deleted element       :", removed)
    print("Array after deletion  :", arr)
```

## Sample Output

```text
Enter array elements separated by space: 10 20 30 40 50
Enter the position to delete (index 0 to 4): 2
Array before deletion : [10, 20, 30, 40, 50]
Deleted element       : 30
Array after deletion  : [10, 20, 40, 50]
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 13: Delete Element by Value

## Aim

To write a Python program to delete a given value from an array by first searching for it.

## Flowchart

<p align="center"><img src="images/program13_flowchart.png" alt="Program 13 flowchart" width="560"></p>

## Program

```python
arr = list(map(int, input("Enter array elements separated by space: ").split()))
value = int(input("Enter the value to delete: "))
print("Array before deletion :", arr)

for i in range(len(arr)):
    if arr[i] == value:                  # value found at index i
        del arr[i]
        print("Value", value, "found at position", i + 1, "and deleted")
        print("Array after deletion  :", arr)
        break
else:
    print("Value", value, "not found in the array")
```

## Sample Output

```text
Enter array elements separated by space: 10 20 30 20 50
Enter the value to delete: 30
Array before deletion : [10, 20, 30, 20, 50]
Value 30 found at position 3 and deleted
Array after deletion  : [10, 20, 20, 50]
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 14: Factorial using Recursion

## Aim

To write a Python program to find the factorial of a given number using recursion.

## Flowchart

*Main*

<p align="center"><img src="images/program14_flowchart_main.jpeg" alt="Program 14 flowchart" width="300"></p>

*Function factorial*

<p align="center"><img src="images/program14_flowchart_function1.jpeg" alt="Program 14 flowchart" width="300"></p>

## Program

```python
def factorial(n):
    if n == 0 or n == 1:            # base case
        return 1
    return n * factorial(n - 1)     # recursive case


n = int(input("Enter a number: "))

if n < 0:
    print("Factorial is not defined for negative numbers")
else:
    print("Factorial of", n, "is", factorial(n))
```

## Sample Output

```text
Enter a number: 5
Factorial of 5 is 120
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 15: Sum of Numbers using Recursion

## Aim

To write a Python program to find the sum of natural numbers up to a given number using recursion.

## Flowchart

*Main*

<p align="center"><img src="images/program15_flowchart_main.jpeg" alt="Program 15 flowchart" width="300"></p>

*Function sum*

<p align="center"><img src="images/program15_flowchart_function1.jpeg" alt="Program 15 flowchart" width="300"></p>

## Program

```python
def sum_numbers(n):
    if n == 0:                      # base case
        return 0
    return n + sum_numbers(n - 1)   # recursive case


n = int(input("Enter a number: "))

if n < 0:
    print("Please enter a non-negative number")
else:
    print("Sum of numbers from 1 to", n, "is", sum_numbers(n))
```

## Sample Output

```text
Enter a number: 10
Sum of numbers from 1 to 10 is 55
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 16: Fibonacci Series using Recursion

## Aim

To write a Python program to generate the Fibonacci series using recursion.

## Flowchart

<p align="center"><img src="images/program16_flowchart.jpeg" alt="Program 16 flowchart" width="461"></p>

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

# Program 17: Graph Representation using Classes and Objects

## Aim

To write a Python program to represent a graph using Node and Graph classes and objects, add the given vertices and edges to the graph, and display the graph using an adjacency list.

## Flowchart

*Main*

<p align="center"><img src="images/program17_flowchart_main.png" alt="Program 17 flowchart" width="447"></p>

*Function add_vertex*

<p align="center"><img src="images/program17_flowchart_function1.png" alt="Program 17 flowchart" width="426"></p>

*Function add_edge (undirected)*

<p align="center"><img src="images/program17_flowchart_function2.png" alt="Program 17 flowchart" width="326"></p>

*Function display*

<p align="center"><img src="images/program17_flowchart_function3.png" alt="Program 17 flowchart" width="542"></p>

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

# Program 18: Represent the Given Directed Graph (Q18)

## Aim

To write a Python program using classes and objects to represent the given directed graph, add all the vertices and directed edges, and display its adjacency list.

## Flowchart

*Main*

<p align="center"><img src="images/program18_flowchart_main.png" alt="Program 18 flowchart" width="496"></p>

*Function add_vertex*

<p align="center"><img src="images/program18_flowchart_function1.png" alt="Program 18 flowchart" width="426"></p>

*Function add_edge (directed)*

<p align="center"><img src="images/program18_flowchart_function2.png" alt="Program 18 flowchart" width="396"></p>

*Function display*

<p align="center"><img src="images/program18_flowchart_function3.png" alt="Program 18 flowchart" width="534"></p>

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

# Program 19: Represent the Given Directed Graph (Q19)

## Aim

To write a Python program using classes and objects to represent the given directed graph by creating nodes for all vertices, adding the directed edges, and displaying the graph using an adjacency list.

## Flowchart

*Main*

<p align="center"><img src="images/program19_flowchart_main.png" alt="Program 19 flowchart" width="434"></p>

*Function Node.add_edge*

<p align="center"><img src="images/program19_flowchart_function1.png" alt="Program 19 flowchart" width="300"></p>

*Function display*

<p align="center"><img src="images/program19_flowchart_function2.png" alt="Program 19 flowchart" width="542"></p>

## Program

```python
class Node:
    def __init__(self, name):
        self.name = name
        self.adjacent = []

    def add_edge(self, other):           # directed edge self -> other
        self.adjacent.append(other)


class Graph:
    def __init__(self):
        self.vertices = []

    def add_node(self, node):
        self.vertices.append(node)

    def display(self):
        print("Adjacency List:")
        for node in self.vertices:
            names = ", ".join(str(n.name) for n in node.adjacent) or "None"
            print(node.name, "->", names)


# Create nodes for all vertices (change to match the given graph)
n1 = Node(1)
n2 = Node(2)
n3 = Node(3)
n4 = Node(4)
n5 = Node(5)

g = Graph()
for node in (n1, n2, n3, n4, n5):
    g.add_node(node)

# Add the directed edges
n1.add_edge(n2)
n2.add_edge(n3)
n3.add_edge(n1)
n3.add_edge(n4)
n4.add_edge(n5)

g.display()
```

## Sample Output

```text
Adjacency List:
1 -> 2
2 -> 3
3 -> 1, 4
4 -> 5
5 -> None
```

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 20: Graph Creation Using User Input

## Aim

To write a Python program to create a graph by taking the number of vertices and edges from the user, reading the vertices and edges, and displaying the resulting graph using an adjacency list.

## Flowchart

*Main*

<p align="center"><img src="images/program20_flowchart_main.png" alt="Program 20 flowchart" width="560"></p>

*Function add_vertex*

<p align="center"><img src="images/program20_flowchart_function1.png" alt="Program 20 flowchart" width="426"></p>

*Function add_edge (undirected)*

<p align="center"><img src="images/program20_flowchart_function2.png" alt="Program 20 flowchart" width="352"></p>

*Function display*

<p align="center"><img src="images/program20_flowchart_function3.png" alt="Program 20 flowchart" width="542"></p>

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
