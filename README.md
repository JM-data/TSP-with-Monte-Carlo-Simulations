# TSP-with-Monte-Carlo-Simulations
#### Second Year project for the Monte Carlo class at ENSAE ParisTech

What is the shortest way to travel once through all the Tour de France stops ?

![alt text](https://github.com/JM-data/TSP-with-Monte-Carlo-Simulations/blob/master/Tour%20de%20France_b4.png?raw=true)

Using Monte Carlo Simulations, this project goes in depth to solving the Traveling Salesman Problem in the case of the Tour de France.

We consider a distance matrix between all cities, and a path first obtained at random. From there, we build a Markov Chain linking different cities, and we gratify shorter paths with higher transition probabilities between the given cities, and decrease the transition probabilities otherwise.

Starting at random, the transition matrix soon converges to a permutation matrix, which gives us the best way to link the cities in order to minimize the journey.

![alt text](https://github.com/JM-data/TSP-with-Monte-Carlo-Simulations/blob/master/Tour%20de%20France.png?raw=true)
