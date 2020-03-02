# Generic-Algorithm-for-Robot-Controller
Problems: The problem is to design the robot controller to walk through the maze and arrive the destination in the end without crashing into the wall. The robot can be controlled by six different direction sensors, three on the front, one on the left, one on the right and one on the back. Each route can be one solution and can be scored, our purpose is to find the fittest solution by comparing the scores until it reaches the termination we set. We choose the highest fitness solution in each generation and change it by crossover and mutate for the next generation. The final solution will be found until the number of generations reach the maximum we set.