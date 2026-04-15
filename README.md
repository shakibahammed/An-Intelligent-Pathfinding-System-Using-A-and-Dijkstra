Project Name: An-Intelligent-Pathfinding-System-Using-A-and-Dijkstra
An exploration into Search Algorithms and Geospatial Data Visualization

Project Overview
This project is a practical application of Artificial Intelligence and Graph Theory to solve real-world route optimization problems. I developed this system to analyze and compare how different search algorithms behave when navigating a network of major Indian cities.
The core of this project lies in the comparison between Dijkstra’s Algorithm and the A* Search Algorithm , evaluating them based on efficiency, path accuracy, and computational overhead.

Motivation
As an aspiring engineer, I have always been fascinated by the logic behind navigation systems like Google Maps. This project was born out of a desire to bridge the gap between theoretical AI concepts—specifically Heuristic Search Strategies—and their practical implementation in geospatial environments.

Key Features
Dual-Algorithm Implementation: 
Dijkstra’s Algorithm: To ensure the shortest path based on edge weights.
A* Search: Enhanced with a geographical heuristic to optimize the search space.
Heuristic Optimization: Implemented the Haversine Formula to calculate the "as-the-crow-flies" distance between city coordinates, providing a mathematically sound heuristic for the A* algorithm.

Performance Benchmarking: Real-time comparison of algorithms based on: Total Distance ,Execution Time , Search Complexity (Number of nodes visited/expanded)
Rich Visualization:
Interactive UI: Built with ipywidgets for city selection.
Static & Animated Graphs: Using Matplotlib and NetworkX.
Geospatial Rendering: Dynamic map views using Folium to plot paths on a real-world map.

Technical Approach
The system models Indian cities as nodes in a weighted graph, where edges represent the distances between them.
Heuristic Logic: $f(n) = g(n) + h(n) 
where , g(n) : Actual cost from the start node to node $n$.
        h(n) : Estimated cost from $n$ to the goal (calculated via the Haversine formula).

Visualization Pipeline: The project transforms raw CSV data into a structured graph, processes the path, and then renders it through an animation layer to show the algorithm's "decision-making" process.

Technologies Used
Language: Python
Graph Theory: NetworkX
Data Analysis: Pandas, NumPy
Visualization: Matplotlib, Folium
Interface: Jupyter Widgets (ipywidgets)

Learning Outcomes
Through this project, I have deepened my understanding of:
Search Space Complexity: How heuristics can significantly reduce the number of nodes explored.
Algorithm Trade-offs: Understanding when to prioritize computational speed (A*) over exhaustive search (Dijkstra).
Data Storytelling: Presenting complex algorithmic results through intuitive visual maps.

Future Enhancements
Expanding the dataset to include global urban networks.
Integration of real-time traffic data using APIs.

Author
Developed with a passion for AI and Web Engineering.
Md Shakib Ahammed
Colab Link: https://colab.research.google.com/drive/1n9Xt_s8R7284BzLXdhnhHX8hcAwrFIB1?usp=sharing
