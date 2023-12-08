# NotUber

Used: KD-Tree implementation for matching drivers and passengers to nearest nodes, Grid Partitioning, A* search algorithm, Dijkstra's algorithm, Euclidian and Manhattan Distance, Theoretical and Practical Time Complexity, Priority Queues, Heuristic Functions.

We design and implement several classes to model this ride service on the road network in New York City. We implement a matching algorithm that assigns drivers to passengers and simulates their rides through the city, and at each step in this case study, we introduce further complexity to the algorithm to improve its simulation accuracy while maintaining scalability and efficiency. In particular, we improve the algorithm in three main areas:
- Efficiency of locating drivers and passengers in relation to the road network (i.e. assigning drivers and passengers to nearest nodes/possible pickup locations)
- Finding the nearest driver to a given passenger
- Finding the shortest path between two points on the network (for pickups and dropoffs)

We find that there exists a tradeoff between accuracy of simulation and runtime efficiency. However, with the proper space partitioning and graph traversal methods, we can maintain a reasonably scalable simulation with a high degree of accuracy.

