#Adjacency Matrix to Edge List

This simple Python script that helps to convert any given [adjacency matrix](http://en.wikipedia.org/wiki/Adjacency_matrix) into an edge list.

As most data visualization tools require edge lists as an input, this is a handy tool if you need a fast solution or can't find a suitable function in the library of your choice. That being said, the script is recommended for complementary use outside of MATLAB or R/Python libraries such as [igraph](http://igraph.org/r/doc/conversion.html) or [networkx](http://networkx.github.io/documentation/latest/reference/convert.html), as they are well-provided with data conversion functionalities.

Converting Tables
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

Use
-----

1.  Use an adjacency matrix with a structure as provided in **matrix.csv**
2.  Make sure **matrix.csv** is in the same folder as **adjacencymatrix_to_edgelist.py**
3.  Open Terminal and navigate to your folder
5.  run ```python adjacencymatrix_to_edgelist.py```
6.  Voilà. Open **edge_list.csv** and be happy :)

The repository comes with an IPython Notebook file (**.ipynb*).
