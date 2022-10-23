# Traverse the maze problem

Consider the ’traverse the maze problem’. Suppose:

• The maze is a n × n rectangle stored in a two-dimensional array M[0..n − 1][0..n − 1], rows and
columns are numbered from 0 to n − 1;

• M[i][j] = 1 indicates (i, j) is an accessible position, M[i][j] = 0 indicates we cannot stay or pass
through (i, j);

• The starting point is (0, 0), the goal point is ( n − 1, n − 1);

• We can traverse the maze by moving up/down/left/right each step, providing that we are moving
into an accessible position.

# Algorithm thinking
(a) Explain, in English, how we may model this problem using a graph. Your answer should at least
include what is considered to be a vertex/edge in the graph, how to store the graph, etc.

(b) Explain, in English, how to determine whether there is a path from the starting point to the goal
point. Use Big-Oh notation to express the worst case complexity of your approach, in terms of n.

(c) Explain, in English, how to find a shortest path (minimal number of movements) from the starting
point to the goal point.

