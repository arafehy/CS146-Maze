# Maze Generator & Solver
Java program that creates a perfect maze and solves it using BFS (Breadth-First Search) and DFS (Depth-First Search)

## Example
```
Enter integer maze size: 8

Perfect Maze Generated:
+ +-+-+-+-+-+-+-+
| |           | |
+ + + + +-+-+ + +
| | | | |   |   |
+ +-+ + + + +-+ +
|   | | | |   | |
+-+ + +-+ +-+ +-+
| | | |     |   |
+ + + + +-+-+-+ +
| | | | |     | |
+ + + + + +-+ + +
| | |   | | | | |
+ + + +-+ + + + +
|   |   | | |   |
+ +-+-+-+ + +-+ +
|         |     |
+-+-+-+-+-+-+-+ +

DFS Solution:
+ +-+-+-+-+-+-+-+
|0|           | |
+ + + + +-+-+ + +
|1| | | |   |   |
+ +-+ + + + +-+ +
|2 3| | | |   | |
+-+ + +-+ +-+ +-+
| |4| |     |   |
+ + + + +-+-+-+ +
| |5| | |6 7 8| |
+ + + + + +-+ + +
| |6|   |5| |9| |
+ + + +-+ + + + +
|8 7|   |4| |0 1|
+ +-+-+-+ + +-+ +
|9 0 1 2 3|    2|
+-+-+-+-+-+-+-+ +

BFS Solution:
+ +-+-+-+-+-+-+-+
|0|           | |
+ + + + +-+-+ + +
|1| | | |   |   |
+ +-+ + + + +-+ +
|2 3| | | |   | |
+-+ + +-+ +-+ +-+
|3|4| |     |   |
+ + + + +-+-+-+ +
|1|5| | |9 0 1| |
+ + + + + +-+ + +
|9|6|   |8| |2|5|
+ + + +-+ + + + +
|8 7|   |7| |3 4|
+ +-+-+-+ + +-+ +
|0 2 4 5 6|    6|
+-+-+-+-+-+-+-+ +

Hash labeled solution path:
+ +-+-+-+-+-+-+-+
|#|           | |
+ + + + +-+-+ + +
|#| | | |   |   |
+ +-+ + + + +-+ +
|# #| | | |   | |
+-+ + +-+ +-+ +-+
| |#| |     |   |
+ + + + +-+-+-+ +
| |#| | |# # #| |
+ + + + + +-+ + +
| |#|   |#| |#| |
+ + + +-+ + + + +
|# #|   |#| |# #|
+ +-+-+-+ + +-+ +
|# # # # #|    #|
+-+-+-+-+-+-+-+ +
```
