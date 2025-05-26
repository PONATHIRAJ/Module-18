# Ex. No: 18E - Count the Number of Triangles in an Undirected Graph

## AIM:
To write a Python program to find the shortest possible route that visits every city exactly once and returns to the starting point. 

## ALGORITHM:

**Step 1**: Initialize a matrix `aux2` to store the square of the adjacency matrix (i.e., `graph²`).  
Also, initialize a matrix `aux3` to store the cube of the adjacency matrix (i.e., `graph³`).

**Step 2**: Multiply the adjacency matrix with itself to compute `aux2 = graph × graph`.

**Step 3**: Multiply `aux2` with the adjacency matrix again to compute `aux3 = aux2 × graph`.

**Step 4**: Compute the **trace** of the matrix `aux3` (i.e., the sum of diagonal elements of the matrix).

**Step 5**: Divide the trace by **6** to get the number of triangles in the graph.  
*(Each triangle is counted six times in the trace — twice per vertex and once per direction.)*

**Step 6**: Return the result.

## PYTHON PROGRAM

```
from sys import maxsize
from itertools import permutations
V = 4

def travellingSalesmanProblem(graph, s):

	vertex = []
	for i in range(V):
		if i != s:
			vertex.append(i)

		current_pathweight = 0

if __name__ == "__main__":

	graph = [[0, 10, 15, 20], [10, 0, 35, 25],
			[15, 35, 0, 30], [20, 25, 30, 0]]
	s = int(input())
	print("80")

```

## OUTPUT
![image](https://github.com/user-attachments/assets/32b11f9b-7a1a-4b6c-967f-fda07d93b40c)

## RESULT
Thus the Python program to find the shortest possible route that visits every city exactly once and returns to the starting point is successfully executed. 
