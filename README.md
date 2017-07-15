# Senior-Thesis

One of the most amazing capabilities of human beings is to extract common spatial patterns from observations and use these patterns to make inferences - recognizing a car by summarizing the important components of cars, like rims, windows, trunks etc., and their spatial relationship while ignoring the specific design of different cars.

In our work, we turn a set of spatial representations into a set of attributed relational graphs (ARGs), which consist of nodes and edges with a vector representing their individual features. We then train a probabilistic parametric model that extract the common sub-graph of the ARGs set.

Our key contributions are 1) introducing a stochastic process to the graph matching step which utilizes a graduated assignment algorithm, 2) adding a null node network in each ARG to avoid matches among background nodes (i.e. nodes not in the pattern). We also apply the model to crystallography protein structure data to learn the common structure among proteins that share a certain function. To utilize the general algorithm to our protein data and model the structure data as ARG, we 3) introduce an additional term in our objective function rep- resenting the protein backbone, and 4) use a local substitution vector to model the similarity between two different amino acids based on their specific local environment.

Graph is a powerful representation and can be used to model a lot of things like neuron morphologies and social networks. Utilizing such algorithm can help machines to understand many of the patterns in real life, and human to mine pattern in large scale.

[Link to the thesis.](http://bir.brandeis.edu/handle/10192/33730)
