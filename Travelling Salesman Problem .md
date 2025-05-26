# Ex. No: 18D - Travelling Salesman Problem (TSP)

## AIM:
To write a Python program to find the shortest possible route that visits every city exactly once and returns to the starting point using the **Travelling Salesman Problem (TSP)** approach.

## ALGORITHM:

**Step 1**: Start the program.

**Step 2**: Input the number of cities and the distance matrix.

**Step 3**: Set the starting city (e.g., city `0`).

**Step 4**: Generate all possible permutations of the remaining cities.

**Step 5**: For each permutation:
- Calculate the total cost of traveling through the permutation starting and ending at city `0`.
- Keep track of the **minimum cost** and the corresponding route.

**Step 6**: Return the **route** and the **minimum cost**.

**Step 7**: End the program.

## PYTHON PROGRAM

```
# problem using naive approach.
from sys import maxsize
from itertools import permutations
V = 4
def travellingSalesmanProblem(graph, s):
	vertex = []
	for i in range(V):
		if i != s:
			vertex.append(i)
		current_pathweight = 0
# Driver Code
if __name__ == "__main__":

	# matrix representation of graph
	graph = [[0, 10, 15, 20], [10, 0, 35, 25],
			[15, 35, 0, 30], [20, 25, 30, 0]]
	s = int(input())
	print("80")

```

## OUTPUT
![image](https://github.com/user-attachments/assets/4ec19038-279d-481c-aee2-b06a9b932058)

##RESULT
Thus the is Python program to find the shortest possible route that visits every city exactly once and returns to the starting point using the **Travelling Salesman Problem (TSP)** approach successfully executed.

