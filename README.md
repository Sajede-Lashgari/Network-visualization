# Network-visualization

Network visualization with igraph in R, Gephi and Cytoscape

The following algorithms have been used to visualize the network:

Kamada Kawai : One of the popular force-directed
Fruchterman Reingold :one of the most used force-directed
reingold tilford
Also, the diameter of the network in certain aspects and degree distribution is calculated.

This includes the Stack Overflow data set on the Kaggle site. The data is stored in two csv files that are equal to stacknetworklinks and stacknetworknodes, respectively. The aim is to examine how different technologies relate to each other or how to use them together. In this step, this data is visualized in the form of a network. To examine the relationship between different technologies, the degree of correlation between technology-related tags that occasionally appear together or appear separately in the Stack Overflow is considered, and tags collected from the Developer Stories section or the Professional Profiles section, CV, and Individual's resumes have been collected.

Also, different centrality are obtained for the nodes, and in the network visualized by cytoscape, the size of the network nodes is considered based on the Betweenness Centrality of each node.
