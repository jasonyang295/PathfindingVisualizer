# Pathfinding Visualizer App

This was an application I created to visualize famous pathfinding and maze generation algorithms. It was built primarily in HTML, CSS, and JS, and it was deeply inspired by Clement Mihailescu's [Pathfinding Visualizer](https://www.youtube.com/watch?v=msttfIHHkak&ab_channel=Cl%C3%A9mentMihailescu). All instructions on how to use the application are included in the tutorial box when the app is opened. All algorithms listed below also have more detailed descriptions listed if you click the small "info" button next to the "algorithms" dropdown menu. Check it out [here](https://jasonyang295.github.io/pathfindingvisualizer/). 

## Side Note
I used the getmdl package in this app, and I've attached a license and readme in the respective folder if you're interested. Check them out [here](https://creativeit.github.io/getmdl-select/).

## Algorithms Included

### Dijkstra's Algorithm
A classic and arguably the father of pathfinding algorithms, it guarantees the shortest path. It also takes weighted nodes into account. 

### A* Algorithm
This is arguably the best pathfinding algorithm as it uses heuristics to guarantee the shortest path. It is much faster than Dijkstra's Algorithm.

### Breadth-First Search (BFS)
A classic algorithm that guarantees the shortest path. 

### Recursive Maze Generation
An algorithm that will automatically generate a seemingly-random maze via the depth-first search algorithm. Once generated, you can use the other three algorithms to find the shortest path.

## Next Steps? 
I learned a lot about front-end web dev from this project, as well as how to write the algorithms themselves in js. Possible next steps may be to implement more algorithms -- I've seen others use a wider variety (such as greedy best first search or bidirectional search) and to potentially integrate this project with a framework such as Reactjs. 
