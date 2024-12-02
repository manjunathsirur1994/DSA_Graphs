 # Graphs
[ppt link: https://docs.google.com/presentation/d/1JcNlQ7_zT3DtHajeQjk3zfRzE-KHL1gLGwBmiEI6d34/edit?usp=sharing]



All the graphs are based out of general graph algorithms like depicted below:

![image](https://github.com/user-attachments/assets/03013147-b1d8-49e2-885c-e274e3c29d9e)
Rather than studying individual graph algorithms, study the general graph algorithms. 

-----------

![image](https://github.com/user-attachments/assets/c27938e4-3d2d-4a71-ba34-e2893035f36d)

## Graph [vertices and edges]


![image](https://github.com/user-attachments/assets/0e165ee6-88bf-4def-881c-4d8aed1a804a)

In the above diagram:
--------------
a,b,c,d are vertices

c-d is a path [which is also called an edge]

c-b is not a valid path

a-b-c-d is a cycle


Examples of directed graph:

1. googles webcorpus where each webpage is a vertex and an edge from webpage a to webpage b, if a has a hyperlink to b
2. twitter, where edge if from person a to b if a follows b on twitter.
3. a road network within  a city with lots of one way streets. 

Below is not a directed graph, it is an undirected graph:

a graph of social media, edge from person a to b if 

-------------
## Degree of vertex

![image](https://github.com/user-attachments/assets/ca3db2ef-bcf1-47d9-ac3f-8b10656be161)

Degree of vertex: Total number of edges sticking out of the vertex. 

If there are multiple edges in a vertex, then it is called a multigraph. 

An undirected graph is complete if there is an edge between every pair of vertices. If there are V vertices in such a graph, the degree of each vertex will be V-1. 

------------


G = (V,E)

v = set of all vertices

e = set of all edges


the sum of the degrees of all the vertices in an undirected graph = G=(V,E) is 2|E| example vertices is 4, then edges will be 8. 
![image](https://github.com/user-attachments/assets/f2b4a88b-4f06-4280-aacb-8a08d3c7cd97)


the sum of the degrees of all the vertices in an directed graph = G=(V,E) is |E| (total number of edges) example vertices is 4, then edges will be 4. 

![image](https://github.com/user-attachments/assets/74146ca3-fb10-4b15-8d67-d663f1c9f580)


An undirected airport graph has 200 airports, and each airport has a direct flight connection to at least 5 other airports. Which of the following is the most precise statement we can make about the number of edges?

Answer: |E| is at least 500. 

If we add up the degrees of all vertices, that value would be at least 200 X 5 = at least 1000. So the number of edges must be at least 1000/2 = 500. 


----------------

## Eulerian path and Eulerian cycle

![image](https://github.com/user-attachments/assets/ae7e23ea-2b54-4e44-8ed2-2448af217566)

A - every other vertex exactly once - A

every Eulerian cycle is eulerian path, but not every eulerian path will be a eulerian cycle. 

![image](https://github.com/user-attachments/assets/9da3270b-eafa-4f98-90da-8e117f7f7ae2)


If we model every edges as vertices and every vertices as edges it becomes a entirely different problem which is called Hamiltonian cycle problem. 


![image](https://github.com/user-attachments/assets/7ff01d6a-ca23-4b20-8454-011671c48d3a)


If we consider the below graph, with n vertices, lets see what the graph has ? 

![image](https://github.com/user-attachments/assets/d533f6f9-927f-4503-9e05-e7e3bc113e85)

It traverses through every vertices and returns back to the same vertex covering all the vertices exactly once. so this is an eulerian cycle, every eulerian cycle is eulerian path. It is also Hamiltonian cycle, since it traverses through every vertex, and reaches back to the starting vertex, and every hamiltonian cycle is hamiltonian path. 

-------------

![image](https://github.com/user-attachments/assets/1749c541-71c7-4c55-8456-f62a2fd0f9aa)

Eulerian cycle: every time we enter a vertex, we can exit it along some unused edge. so the degree of every vertex must be even. 

### If the degree of any vertex is odd, the graph cannot have an Eulerian cycle. 

![image](https://github.com/user-attachments/assets/7de46ca5-57e5-42a6-9d72-fa4c1a855a26)

![image](https://github.com/user-attachments/assets/7166d66a-76cb-41ce-b368-83860c176dfa)


![image](https://github.com/user-attachments/assets/e137c0c0-6beb-4395-866b-732496ea3954)

![image](https://github.com/user-attachments/assets/16021ce1-3072-4942-9a23-8c41a9e1b0e4)

![image](https://github.com/user-attachments/assets/66212df9-1c0b-4d1b-b919-c334e73babc7)

![image](https://github.com/user-attachments/assets/675385ed-0a6d-4162-8841-7c3584c05981)

![image](https://github.com/user-attachments/assets/006e3e7e-1eb4-45ab-be01-4822fefb038e)

![image](https://github.com/user-attachments/assets/6535e71b-c527-41f7-b263-d03172332b38)


![image](https://github.com/user-attachments/assets/cda574f9-682f-436e-823d-792fc44e7286)

![image](https://github.com/user-attachments/assets/06bf2162-fc1b-4bf5-81ab-a180745fd2ca)
























