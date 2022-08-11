# easy_graph_side_tool  
This project is a side tool to benchmark the performance of [Easy Graph](https://github.com/easy-graph/Easy-Graph)  
We use small, medium and large datasets to measure the runtime on dijkstra search of Easy Graph and [Graph Tool](https://graph-tool.skewed.de/)  
easy-graph-benchmark.ipynb contains the code to load datasets and run dijkstra_search() from Easy Graph. 
graph_tool_utilization.ipynb contains the code to load datasets and run dijkstra_search() from Graph Tool.  
The datasets from small to large are ENZYMES_g1, econ-mahindas and bio-CE-CX. They all come from  
Rossi, R. A., & Ahmed, N. K. (2015). The Network Data Repository with Interactive Graph Analytics and Visualization. Proceedings of the Twenty-Ninth AAAI Conference on Artificial Intelligence. Ανακτήθηκε από http://networkrepository.com
