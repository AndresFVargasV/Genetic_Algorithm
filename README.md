# Genetic Algorithm for the Traveling Salesman Problem (TSP)

This project implements a genetic algorithm to attempt to find a good approximate solution to the Traveling Salesman Problem (TSP).

## Description of the TSP Problem

The Traveling Salesman Problem (TSP) involves finding the shortest possible route that visits a series of cities and returns to the original city, visiting each city only once. It is a classic problem in combinatorial optimization.

## Genetic Algorithm

Genetic algorithms are optimization techniques inspired by concepts such as natural selection and genetics. They start with an initial population of randomly generated candidate solutions. Each solution has an associated "fitness" indicating how good it is. Operations are then performed to combine and mutate these candidate solutions, generating new populations of solutions that retain the characteristics of higher fitness.

This process is repeated over several generations until solutions with sufficiently good fitness are found or until no further improvement is observed.

## Implementation Details

The implementation consists of:

- A random city generator with x, y coordinates
- A Euclidean distance function between cities
- Random generation of initial paths
- Calculation of the fitness of each path as the sum of distances traveled
- Genetic algorithm with:
  - Selection of paths with better fitness
  - Crossover of paths to generate new offspring
  - Random mutation of some paths
  - Replacement of the population with the new offspring
- Visualization of the best-found path

Key parameters such as population size, number of generations, mutation probability, etc., can be easily modified.

This project demonstrates a direct application of genetic algorithms to approximately solve a complex combinatorial optimization problem.
