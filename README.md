Imagine there’s a robot in a small 4x4 grid (a grid is like a checkerboard). The robot starts in one square and wants to get to another square, but there are some rules:

- The robot can move up, down, left, or right.
- The robot can’t move outside the grid. If it’s on the edge, it can’t keep going in that direction.
- There are some obstacles (like walls or blocks) on the grid. The robot can’t go into those spots.
- The robot doesn’t want to visit the same square twice — it’s a little forgetful and would get confused.
## What does this program do?
- It helps the robot find a way to go from where it starts (like (1, 1)) to where it wants to go (like (4, 4)).
- While moving, the robot will think: “Can I go this way? Is there a wall? Am I leaving the grid? Have I already been there?”
- It keeps track of all the squares it visits and prints them out as it moves.
## What happens when you run it?
- The program will show each step the robot takes, like:
- "Moving right to (2, 1)" or "Moving down to (2, 2)".
- When the robot gets to its goal, it will show you the path it took, like:
- "Path = [(1, 1), (2, 1), (3, 1), (4, 1)]".

## Initial Query
You asked the program to find a way from (1, 1) (starting point) to (4, 4) (goal point).
Steps Taken by the Robot
The robot tries different directions step by step, keeping track of its current position and avoiding obstacles or previously visited positions.

Here’s what each step means:

Moving down to (1, 2)
The robot starts at (1, 1) and moves down to (1, 2).

Moving down to (1, 3)
From (1, 2), it keeps moving down to (1, 3).

Moving down to (1, 4)
It continues moving down to (1, 4).

Moving right to (2, 4)
Now it moves right to (2, 4).

Moving up to (2, 3)
It decides to move up to (2, 3).

Moving right to (3, 3)
Then it moves right to (3, 3).

Moving up to (3, 2)
It goes up to (3, 2).

Moving up to (3, 1)
It continues moving up to (3, 1).

Moving left to (2, 1)
The robot moves left to (2, 1).

Moving right to (4, 1)
It makes a big jump, moving right to (4, 1).

Moving down to (4, 2)
It moves down to (4, 2).

Moving down to (4, 3)
It continues moving down to (4, 3).

Moving down to (4, 4)
Finally, it reaches the goal (4, 4).

