The Code_analysis excel workbook data was manually collected from going through the finiteelementanalysis code. Gephi was then used to visualize the resulting network.

Directed edges represent calls without returns, while return values are expected for calls represented by undirected edges.

Each node is colored according to the module it belongs to, and each edge is given the source node's color.
The size of each node is determined by its weighted degree.

With this approach, one code imagine expanding each node into a subnetwork such that variables become subnodes and inputs and output variables of the node are connected to the corresponding inputs and outputs of other nodes. This would capture the flow of the variables within the code and their interactions.

![Network Graph](code_analysis.png "Call-based Network Graph of finiteelementanalysis")

![Legend](code_analysis_legend.png "Graph Node Color Legend")