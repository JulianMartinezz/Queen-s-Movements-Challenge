# Queen’s Movements Challenge

This project is a console application that simulates the movements of a queen on a chessboard. The queen can move in any direction: left, right, up, down, or diagonally. The number of squares the queen can attack is determined by the size of the board and the position of any obstacles.

## Application Overview
The application takes as input the size of the chessboard, the number of obstacles, the starting position of the queen, and the positions of the obstacles. It then calculates the number of squares the queen can attack from her starting position.

The chessboard is an n x n grid, and each square is referenced by a tuple (r, c), where r is the row and c is the column. The queen can attack any square in any of the eight directions until she reaches the edge of the board or an obstacle.

## How to Test the Application
You can test the application by running it and providing different inputs. Here are some things you might want to test:

- **Different board sizes:** Try different sizes for the chessboard to see how it affects the number of squares the queen can attack.

- **Different obstacle configurations:** Place obstacles in different positions and see how they limit the queen’s movements.

- **Different starting positions for the queen:** Move the queen’s starting position and observe how it changes the number of squares she can attack.

Remember to check the output of the application after each test to see if it matches your expectations.

## How to Run the Application
Since this is a console application, you can run it directly from your terminal or command prompt. Navigate to the directory containing the application files, then use the `java` command to run the application. For example, if the main class of the application is named `QueensMovements`, you can run the application with the command `java QueensMovements`.

Please note that you need to have Java installed on your machine to run the application. If the application uses any external libraries, you might also need to include them in your classpath when running the application.
