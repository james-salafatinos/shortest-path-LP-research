# shortest-path-LP
The Shortest Path Problem: A linear programming comparison to graph-based Algorithms

# Results
- Each dual formulation was much faster than the corresponding base formulation
- Gurobi outperformed PuLP
- The graph algorithms were exponentially faster (see vertical scales on the graphs)
- Dijkstra finished the entire experiment in less time than the PuLP base algorithm took on average to complete a single trial out of 4096
- Dijkstra outperformed A* 

![Histogram of Processing Times for all implementations](https://github.com/james-salafatinos/shortest-path-LP/blob/master/Images/Histogram_of_processing_times.png)
