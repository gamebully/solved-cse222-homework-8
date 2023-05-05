Download Link: https://assignmentchef.com/product/solved-cse222-homework-8
<br>
<strong>Q1: </strong>

<ul>

 <li>Represent the graphs above using adjacency lists. Draw the corresponding data structure.</li>

 <li>Represent the graphs above using an adjacency matrix. Draw the corresponding data structure.</li>

 <li>For each graph above, what are the IVI=n, the IEI=m, and the density? Which representation is better for each graph? Explain your answers.</li>

 <li>Draw DFS tree starting from vertex 2 and traversing the vertices adjacent to a vertex in descending order (largest to smallest).</li>

 <li>Draw BFS tree starting from vertex 2 and traversing the vertices adjacent to a vertex in descending order (largest to smallest).</li>

</ul>

Show your work step by step and make your explanation. Write your solution by latex, word or handwriting (scan or take picture) and upload it as a single <em>StudentNumber.pdf</em> file.




<strong>Q2:  </strong>

Extend the graph ADT defined in the book so that it includes the following operations.




<ul>

 <li>Deletion of an individual edge.</li>

 <li>Insertion and deletion of an individual vertex. Give proper definition of the operations. Note that if you can delete a node, node IDs cannot be from 0…(n-1) anymore. – Perform breadth-first search of the graph – Perform depth-first search of the graph.</li>

</ul>

Implement the extended graph ADT using 2-D linked-list structure. In 2-D linked-list structure, each node has two row links (<strong>rprev</strong> to row-predecessor and <strong>rnext</strong> to row-successor) and two column links (<strong>cprev</strong> to column-predecessor and <strong>cnext</strong> to column-successor). In our graph representation, each row linked-list represents adjacent vertices to a vertex and each column linked-list represents vertices adjacent to a vertex. Consider the example graph below;










2-D linked-list representation is given below. Note that predecessor links are not shown for simplicity. The first column represents the source vertices (in accesding order) and the first row represents the destination vertices (in accesding order). Each edge is represented by a node which belong to two linked lists; a row linked-list and a column linked-list.







Write a program which tests your implementation using a randomly created directed and undirected graphs. You may create random adjacency matrices and convert it to your representation. You can also use random vertices and edges to test your operations.




<strong>Q3:</strong>

Create a MazeSolver which solves a maze. It should read a rectangular maze as a sequence of lines consisting of Os and 1s, where a 0 represents an open square and a 1 represents a closed one. You can find a maze below as an example. This maze created based on the below input file. After reading the input in this format, your program should convert it to a <strong>weighted graph</strong> (where the vertices are junction squares and the weight of an edge is the distance defined by the number of squares from the junction square represented by the source vertex to the next junction square represented by the destination vertex) and should find the shortest path from upper-left corner to lower-right corner. You should prefer the best graph representation for your graph and required operations.

<strong> </strong>

<strong> </strong>

011111111111111111111111

000000000000000000000001

011111111111111011111101

011111100000001011111101

011111101111111011000001

000000000000000011011011

110111101101111011011011

110111101101111011011011

110111101101000011011011

110111101101111111011011

110111101100000000011011

110000001101111111111011

111101111100000000001011

111101111111111111101000

111100000000000000001110

111111111111111111111110<strong>  RESTRICTIONS: </strong>

<ul>

 <li>Use only specified data types</li>

 <li>Can be only one main class in each question</li>

 <li>Don’t use any other third part library</li>

</ul>