# TrailBlazer

Using the concept of computer graphics mainly GLUT library in C++ to visualize the Dijkstara’s Algorithm and show step by step calculation of minimum distances between different cities.

![image](https://user-images.githubusercontent.com/70579831/176185507-4bd49f4d-44fb-4322-a91b-83c670fbd0be.png)

Dijkstra's Algorithm finds the shortest path between a given node (which is called the "source node") and all other nodes in a graph. This algorithm uses the weights of the edges to find the path that minimizes the total distance (weight) between the source node and all other nodes. \
This algorithm is used in GPS devices to find the shortest path between the current location and the destination. It has broad applications in industry, specially in domains that require modeling networks. This algorithm was created and published by Dr. Edsger W. Dijkstra, a brilliant Dutch computer scientist and software engineer. \
In this project I'm using this algorithm to find the shortest path between two chosen nodes. I have taken few cities in to consideration and when we enter the source and destination of from where do we want to find paths, it scans all of the present nodes i.e cities and their distances and returns the shortest path between souce and destination. We have then used the concept of computer graphics mainly GLUT library to visyalize it and display it as a visulalization of disjkstra’s shortest path algorith’s calculation. It shows step by step visualization of dijkstra’s algorithm using the concepts of opengl/glut C++. \
Each subpath is the shortest path. Djikstra used this property in the opposite direction i.e we overestimate the distance of each vertex from the starting vertex. Then we visit each node and its neighbors to find the shortest subpath to those neighbors. \
The algorithm uses a greedy approach in the sense that we find the next best solution hoping that the end result is the best solution for the whole problem.


![image](https://user-images.githubusercontent.com/70579831/176185180-b5a8ff59-551e-4db6-8210-105c4cdb9816.png)
