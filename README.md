#Adjacency Matrix to Edge List

Simple Python script to convert an [adjacency matrix](http://en.wikipedia.org/wiki/Adjacency_matrix) into an edge list.
Interesting for anyone working with network graphs. The git also includes an IPython Notebook file with the script.

Convert
-----

Input File:

| A  | B  | C |
| :--- |:--- | :--- |
| 0 | 2 | 3 |
| 4 | 5 | 7 |
| 10 | 0 | 1 |

Output File:

| Source  | Target  | Weight |
| :--- |:--- | :--- |
| A | A | 0 |
| B | A | 4 |
| C | A | 10 |
| A | B | 2 |
| B | B | 7 |
| C | B | 0 |
| A | C | 3 |
| B | C | 5 |
| C | C | 1 |

Usage
-----

1.  Use an adjacency matrix with a structure like **matrix.csv**
2.  Make sure **matrix.csv** is in the same folder as the python script (**adjacencymatrix_to_edgelist.py**)
3.  Open Terminal and navigate to your folder
5.  run ```python adjacencymatrix_to_edgelist.py```
6.  Voilà. Open **edge_list.csv** and be happy :)
