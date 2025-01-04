# Indoor Navigation System (INS)

To build this console application in C# for an indoor navigation system, we will structure it with the following components:

a) Room class: To represent rooms in the system.
b) Path class: To represent paths between rooms, with a bidirectional relationship and path length.
c) Navigation system: To manage rooms, paths, and perform the shortest path calculation using Dijkstra's algorithm.
d) User interface: To interact with the user, allowing them to view rooms, select rooms, and display the shortest route between two rooms.


#Explanation of the Code:
a) Room class: Each room has an Id (unique identifier) and a Name.
b) Path class: Represents a bidirectional path between two rooms with a specified Length.
c) IndoorNavigationSystem class:
   1) Manages rooms and paths.
   2) Allows adding and removing rooms and paths.
   3) Implements Dijkstra’s algorithm to find the shortest path between two rooms.
d) User Interface: A console menu allows users to view rooms, add/remove rooms and paths, and find the shortest path between two rooms.

#Key Features:
a) Dijkstra's Algorithm: This is used to find the shortest route between two rooms.
b) User Interaction: Users can interact with the system via the console to manage rooms and paths and query the shortest path.

#Example Use Case:
a) User views all available rooms.
b) User adds a new room or removes an existing room.
c) User adds or removes paths between rooms.
d) User asks for the shortest path between two rooms.

#Testing:
Ensure that the following cases are handled correctly:

a) Finding the shortest path between connected rooms.
b) Handling non-existent rooms or paths.
c) Adding/removing rooms and paths.

This basic structure provides a good starting point for a more advanced indoor navigation system!
