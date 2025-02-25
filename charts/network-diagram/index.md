---
title:  network diagram
  
functions:
- network of relationships

visualizationTechniques:
  - techniqueId: CON
    informationType: relationships between entities


related:


tools:

examples:

  - title:  Chart of Neural Networks
    author: Fjodor Van Veen
    link:   http://www.asimovinstitute.org/neural-network-zoo/
    image:  types-of-neural-networks.png

  - title: The Strengths of Nations
    author: Kevin Boyack, Dick Klavans, W. Bradford Paley
    link: http://wbpaley.com/brad/mapOfScience/index.html
    image: the-strengths-of-nations.jpg
    
  - title: How Scientific Paradigms Relate
    author: Kevin Boyack, Dick Klavans, W. Bradford Paley
    link: http://wbpaley.com/brad/mapOfScience/index.html
    image: how-scientific-paradigms-relate.jpg

  - title: Most Common Family Types in America
    author: Nathan Yau
    link: https://flowingdata.com/2016/07/20/modern-family-structure/
    image: family-types.png
 

    
synonyms:
  - node-link diagram
  - vertex-edge diagram
  - network graph

order: 340

---
is a visualization of entities and their relationships that together form a network structure. Each entity is a node, and each connection between nodes is a link. Any node can connect to any other node. There is no limit on the number of connects a node can have.

<!--more-->
A network diagram consists of any number of ***nodes*** that visually appear as symbols or as blocks of text and the ***links*** between them that appear as connecting lines. A node can have an unlimited number of connections. 

A node can reflect the number of its incoming and outgoing connects though its size. In this case it is called a ***weighed node***. Similarly, ***weighted links*** reflect the strength of the connection through their thickness. 
 
In undirected network diagrams connectors only show relationships and not their direction.  *Directed network diagrams* can show one-way relationships or two-way reciprocal relationships represented by arrows.

Nodes link to similar nodes forming groups by similarity. This kind of grouping follows the first law of geography: near things are more alike than distant things. Therefore, any two nodes should be linked via the shortest route. Clusters of similar nodes can form larger groups that can be marked with color, for example. [^saket]

Both nodes and links can have a weight that represents a value. 

Any network diagram can be represented as a matrix. The relative effectiveness of network diagrams versus matrices is a matter of a long-standing debate. In short, network diagrams are more useful for showing connections and clusters. The matrix is better for group analysis and finding specific values. [^okoe]

[//]: # (TODO: Maybe add bubble network diagram, where nodes are weighted?)


## Further reading
- [Graph drawing](https://en.wikipedia.org/wiki/Graph_drawing) article on Wikipedia.

## References
[^saket]: Node-link diagrams with nodes in groups were found more effective in Saket, Bahador, et al. ["Node, node-link, and node-link-group diagrams: An evaluation."](https://arxiv.org/pdf/1404.1911.pdf) *IEEE Transactions on Visualization and Computer Graphics* 20.12 (2014): 2231-2240.
[^okoe]: Comparison of human performance in 14 different tasks with network diagrams and matrices Okoe, Mershack, Radu Jianu, and Stephen G. Kobourov. ["Node-link or Adjacency Matrices: Old Question, New Insights."](https://www2.cs.arizona.edu/~kobourov/NL-AM-TVCG18.pdf) *IEEE transactions on visualization and computer graphics* (2018).
