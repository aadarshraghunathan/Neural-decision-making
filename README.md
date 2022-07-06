# Neural-decision-making
The aim of this project is to simulate the behaviour of neurons during our binary decision making process. This project is part of the course Intro to Neural and Cognitive Modelling. 

## Logic:
All neurons are treated as nodes in a connected graph, with the weights on the edges defining the strength of the connection between the two neurons. Some of the neurons are selected and divided into two clusters, where a cluster is a collection of nodes such that the connection between each of the nodes is stronger than the average neuron connection strength. These two clusters represent the two possible outcomes of the binary decision. Another set of nodes provides stimuli to these two clusters by changing the weights on the edges between the two clusters. Every step , all neurons are asynchronously updated and connection strength at after a few thousand steps deteremines the decision.

The global update and inhibition equations used to update the neurons are described in the following paper:
https://sci-hub.mksa.top/10.1016/j.procs.2020.09.232 
