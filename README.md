#Adjacency Matrix to Edge List

This is a simple Python script to convert any given [adjacency matrix](http://en.wikipedia.org/wiki/Adjacency_matrix) into an edge list.
The tool can be interesting for anyone working with graph analysis. The git also includes an IPython Notebook file (***.ipynb**) with the script.

Convert Tables
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

1.  Use an adjacency matrix with a structure as provided in **matrix.csv**
2.  Make sure **matrix.csv** is in the same folder as **adjacencymatrix_to_edgelist.py**
3.  Open Terminal and navigate to your folder
5.  run ```python adjacencymatrix_to_edgelist.py```
6.  Voilà. Open **edge_list.csv** and be happy :)
