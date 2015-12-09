# Artificial_Inteligence
### The main goal is to find the best way to go from a point to another.  
To do so, i decided to find a good heuristic that i could use in my A* algorithm.  
My heuristic function considers the current position and the target position and what it does is:  
- Calculates the manhattan distance to the target;  
- Evaluates the number of obstacles between those two points.  
  
And the A* algorithm does the rest of the job.  
### Time of execution in a considerably large map: 0,021 secs
