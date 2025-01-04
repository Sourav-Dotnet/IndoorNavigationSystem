# Indoor Navigation System (INS)

To build this console application in C# for an indoor navigation system, we will structure it with the following components:

1) Room class: To represent rooms in the system.
2) Path class: To represent paths between rooms, with a bidirectional relationship and path length.
3) Navigation system: To manage rooms, paths, and perform the shortest path calculation using Dijkstra's algorithm.
4) User interface: To interact with the user, allowing them to view rooms, select rooms, and display the shortest route between two rooms.


# Explanation of the Code:
1) Room class: Each room has an Id (unique identifier) and a Name.
2) Path class: Represents a bidirectional path between two rooms with a specified Length.
3) IndoorNavigationSystem class:
   1) Manages rooms and paths.
   2) Allows adding and removing rooms and paths.
   3) Implements Dijkstra’s algorithm to find the shortest path between two rooms.
4) User Interface: A console menu allows users to view rooms, add/remove rooms and paths, and find the shortest path between two rooms.

# Key Features:
1) Dijkstra's Algorithm: This is used to find the shortest route between two rooms.
2) User Interaction: Users can interact with the system via the console to manage rooms and paths and query the shortest path.

# Example Use Case:
1) User views all available rooms.
2) User adds a new room or removes an existing room.
3) User adds or removes paths between rooms.
4) User asks for the shortest path between two rooms.

# Testing:
Ensure that the following cases are handled correctly:

1) Finding the shortest path between connected rooms.
2) Handling non-existent rooms or paths.
3) Adding/removing rooms and paths.

This basic structure provides a good starting point for a more advanced indoor navigation system!
