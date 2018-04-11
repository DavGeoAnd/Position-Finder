# Position Finder
Program that gets an EVO3 Robot to start from a selected position and end up in the targeted position on a grid.

1. The user puts in the starting position and places the robot in the cell

2. The robot moves to one of the horizontal black lines, turns right, and goes to the corner

3. It evaluates if it has gone to the origin or the opposite corner

4. The user puts in the targeted position

5. The robot moves forward until it matches the x position, turns and goes to the cell that matches the y position