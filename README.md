 implementing a Genetic Algorithm for clustering using the Iris dataset.
Project Description: This project focuses on applying a Genetic Algorithm to perform clustering using the Iris dataset. The goal is to find an optimal clustering solution by minimizing the total distance between data points and their cluster centroids.
 The project utilizes a Genetic Algorithm, a metaheuristic optimization technique inspired by natural selection, to find the best clustering solution.
 Genetic Algorithm Properties: The project specifies properties such as the number of clusters (k), population size, mutation rate, and selection size.
Evaluation (Objective Function): The objective function evaluates the fitness of each chromosome (clustering solution) by calculating the total distance between data points and their cluster centroids.
Population Initialization: The initial population of chromosomes is randomly generated, where each chromosome represents a clustering solution.
Population Selection: The selection process chooses individuals from the population based on their fitness (evaluated by the objective function). The selection size determines the number of individuals selected.
Crossover: Crossover is performed between pairs of selected parents to create offspring (children). A random index is chosen, and the genes (clusters) are exchanged between parents to create two children.
Mutation: Mutation is applied to the children, where each gene (cluster assignment) has a probability of being randomly changed to a different value.
Genetic Algorithm Execution: The genetic algorithm is executed for a specified number of generations. In each generation, selection, crossover, and mutation are performed to evolve the population.
Best Solution: The best chromosome (clustering solution) with the minimum distance (maximum fitness) is selected as the final solution.
 