<div align="center">

# MODY UNIVERSITY OF SCIENCE AND TECHNOLOGY

## School of Engineering and Technology

<br>
<img width="154" height="157" alt="logo" src="https://github.com/user-attachments/assets/d1434cb0-111a-4b53-9c25-2b025b8f17a1" />


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
</table>

---

<div style="page-break-after: always;"></div>

# Program 1: Graphs using Matplotlib

## Aim

To write a Python program using Matplotlib to plot and display single-line and multiple-line graphs with appropriate labels, title, and legend.

## Flowchart

<img width="1157" height="2344" alt="program01_flowchart" src="https://github.com/user-attachments/assets/60c19dc2-ef98-40fb-bdce-a734f3bd35bc" />

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

<img width="584" height="430" alt="program01_output1" src="https://github.com/user-attachments/assets/038a1cbd-c32d-4f04-adba-0dd705f76b92" />
<img width="584" height="430" alt="program01_output2" src="https://github.com/user-attachments/assets/e1c0903d-e492-42cc-ae8d-2c6aa4d5ab58" />

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 2: Time Execution

## Aim

To write a Python program to calculate and display the execution time of a program using the time and timeit modules.

## Flowchart

*Main*

<img width="1091" height="1933" alt="program02_flowchart_main" src="https://github.com/user-attachments/assets/e9a16df5-1aa5-4720-8c51-ac75c6daf001" />

*Function sum_of_squares*
<img width="712" height="1237" alt="program02_flowchart_function1" src="https://github.com/user-attachments/assets/451467ee-4533-49d6-a89e-40ae429e11a2" />


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
<img width="882" height="2077" alt="program03_flowchart" src="https://github.com/user-attachments/assets/5eb4ebd5-ed21-48dc-9956-f179c2153db7" />



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
<img width="1521" height="2061" alt="program04_flowchart" src="https://github.com/user-attachments/assets/5bd1a519-a5f8-4c79-8d5b-879dd786bf2a" />


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
<img width="850" height="600" alt="program04_output1" src="https://github.com/user-attachments/assets/a3861429-bd78-4a3c-ada6-8509329e3a94" />

[Back to Index](#index)

---

<div style="page-break-after: always;"></div>

# Program 5: Linear Search

## Aim

To write a Python program to search for a given element in an array using Linear Search.

## Flowchart
<img width="1662" height="2688" alt="program05_flowchart" src="https://github.com/user-attachments/assets/db94661b-6f8c-42df-9b8b-f50cdae0b78b" />


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

<img width="1134" height="2158" alt="program06_flowchart" src="https://github.com/user-attachments/assets/3eb343b4-2251-471f-a407-e50bea04186e" />

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

<img width="1192" height="2158" alt="program07_flowchart" src="https://github.com/user-attachments/assets/bf995db2-c94f-4ee2-a75f-d7dbad10a93a" />

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

<img width="658" height="1270" alt="program08_flowchart" src="https://github.com/user-attachments/assets/04d68675-c854-4c12-965e-24531244a63b" />

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

<img width="1506" height="2991" alt="program09_flowchart" src="https://github.com/user-attachments/assets/7ec17fdf-9069-4def-a852-33d494c5a2db" />

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

<img width="361" height="919" alt="program10_flowchart" src="https://github.com/user-attachments/assets/a0fb20cc-5cb5-4572-a208-c7f730382f02" />

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

<img width="361" height="1270" alt="program11_flowchart" src="https://github.com/user-attachments/assets/25a7333b-5a76-4771-8ba9-7a5533c2096f" />

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

<img width="1477" height="2719" alt="program12_flowchart" src="https://github.com/user-attachments/assets/ed69d18a-2d42-4806-b398-335ac7f2e11a" />

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

<img width="1700" height="3666" alt="program13_flowchart" src="https://github.com/user-attachments/assets/2dee308b-5340-434c-b2f3-786818feb4c8" />

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

<img width="307" height="352" alt="program14_flowchart_main" src="https://github.com/user-attachments/assets/61e8b368-99cb-4bd0-b347-af1a3cee301b" />

*Function factorial*

<img width="442" height="424" alt="program14_flowchart_function1" src="https://github.com/user-attachments/assets/6b3e0638-5ef6-4d5b-9368-39280f812e7e" />


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

<img width="271" height="334" alt="program15_flowchart_main" src="https://github.com/user-attachments/assets/0ccfecf1-9ea4-4049-820f-af4103ba4ac9" />

*Function sum*

<img width="397" height="406" alt="program15_flowchart_function1" src="https://github.com/user-attachments/assets/a8ea299b-25be-49da-be15-1cfaee5623a1" />


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

<img width="922" height="541" alt="program16_flowchart" src="https://github.com/user-attachments/assets/67970165-8934-4668-abfe-8fcf4f2cec18" />

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

<img width="894" height="1761" alt="program17_flowchart_main" src="https://github.com/user-attachments/assets/6ff51f70-1b08-47d9-9f18-76977712d0d6" />

*Function add_vertex*
<img width="852" height="762" alt="program17_flowchart_function1" src="https://github.com/user-attachments/assets/a39d871d-ea56-44bd-9691-8a811eb7ef8b" />


*Function add_edge (undirected)*

<img width="653" height="954" alt="program17_flowchart_function2" src="https://github.com/user-attachments/assets/e772534e-a32d-4613-b2f5-df8c7201dbc3" />


*Function display*

<img width="1085" height="1082" alt="program17_flowchart_function3" src="https://github.com/user-attachments/assets/d79b5f52-107f-4dba-9359-0f3f6fdca0a7" />


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

<img width="993" height="1761" alt="program18_flowchart_main" src="https://github.com/user-attachments/assets/e6a0e0b9-c49f-41a3-a36b-8e7b4e3797ce" />

*Function add_vertex*

<img width="852" height="762" alt="program18_flowchart_function1" src="https://github.com/user-attachments/assets/7892c38d-89a4-4ed4-8e98-dadf29478243" />


*Function add_edge (directed)*

<img width="793" height="521" alt="program18_flowchart_function2" src="https://github.com/user-attachments/assets/254d10c3-4379-4792-82c8-f3b414cf0dd8" />

*Function display*

<img width="1068" height="1082" alt="program18_flowchart_function3" src="https://github.com/user-attachments/assets/f5182482-f8b8-4f8d-b182-61b81e2fe998" />


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

<img width="869" height="1761" alt="program19_flowchart_main" src="https://github.com/user-attachments/assets/5d608a09-36dd-48a0-a888-84b3b3432bdf" />

*Function Node.add_edge*

<img width="581" height="521" alt="program19_flowchart_function1" src="https://github.com/user-attachments/assets/594dac64-8337-4d2e-984e-5212e54395e5" />


*Function display*

<img width="1084" height="1082" alt="program19_flowchart_function2" src="https://github.com/user-attachments/assets/6de82f91-11d0-4422-bf5d-1d9622e7fe6d" />

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

<img width="1576" height="2441" alt="program20_flowchart_main" src="https://github.com/user-attachments/assets/4b7125d9-80f9-43d8-adc7-137a6bae7c33" />


*Function add_vertex*

<img width="852" height="762" alt="program20_flowchart_function1" src="https://github.com/user-attachments/assets/12b7e7c8-4ff7-4f45-9f38-2d843634fbc4" />

*Function add_edge (undirected)*

<img width="704" height="665" alt="program20_flowchart_function2" src="https://github.com/user-attachments/assets/f8154d95-37d6-4bfb-bf73-f0fecbca7828" />
*Function display*

<img width="1085" height="1082" alt="program20_flowchart_function3" src="https://github.com/user-attachments/assets/38a3798c-efd9-42e4-86da-9310cfa41ff4" />

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
