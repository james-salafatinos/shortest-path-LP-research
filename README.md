# shortest-path-LP
The Shortest Path Problem: A linear programming comparison to graph-based Algorithms

Tested the viability of Gurobi, a commercial-licensed LP engine, and puLP, an open-source python LP package. We compare the primal and the dual to the graph algorithm benchmarks of A* and Dijkstra for the case of a directed, arbitrarily weighted graph.

**Please use the jupyter notebook titled: "final_notebook.ipynb" within /final_code**


# Results
- Each dual formulation was much faster than the corresponding base formulation
- Gurobi outperformed PuLP
- The graph algorithms were exponentially faster (see vertical scales on the graphs)
- Dijkstra finished the entire experiment in less time than the PuLP base algorithm took on average to complete a single trial out of 4096
- Dijkstra outperformed A* 

![Histogram of Processing Times for all implementations](https://github.com/james-salafatinos/shortest-path-LP/blob/master/Images/Histogram_of_processing_times.png)


![LP Times](https://github.com/james-salafatinos/shortest-path-LP/blob/master/Images/Linear_programming_processing_times.png)

![Graph Times](https://github.com/james-salafatinos/shortest-path-LP/blob/master/Images/graph_processing_times.png)

