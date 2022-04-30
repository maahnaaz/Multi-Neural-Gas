# Multi-Neural-Gas
Implementing a Multi-Neural-Gas with Python from scratch. The network has a total of K Neurons and M partner networks. 
The input dimension N (restricted to N < 7), the structure, and size of the partner networks, and the number of neurons K are adjustable. 
To initialize the centers Cj randomly subset of the training patterns pX is drawn. The Gaussian is the neighborhood function h(dist(i, j), t) with fixed size s. 
An exponentially decaying learning rate η = η(t) is implemented. 
