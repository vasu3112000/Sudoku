# Sudoku

From the name itself you might have understood that I'm making a very famous mathematics game today. Sudoku is a logic-based, combinatorial number-placement puzzle. In classic sudoku, the objective is to fill a 9×9 grid with digits so that each column, each row, and each of the nine 3×3 sub grids that compose the grid contains all of the digits from 1 to 9. The game is quite complex because you need to look out at each row, column and the sub cube also. 

## Installation

Download the complete folder and save it anywhere on your desktop. Open the folder in a any python IDE such as pycharm, anaconda etc. and the file GUI.py contains the main code of the project. 

Install pygame and time libraries in your interpreter if they are not present. Once installed, you're ready to use the software.

## Basic Summary

Once you run the code, a new window will open up and software will be launched. The screen will contain the proper sudoku grid along with the numbers. This grid is set by me and it's solution is also easy to find.

You need to press on the empty squares and enter value according to the rules, i.e., number shouldn't match with any number in the row or column or in the sub grid. Once you press the number, press enter key. If the number will be correct, it's font will be changed as the permanent numbers set by me and you will see "Success" printed in the console. Otherwise, if the number is not correct, the number will be erased from the square, a red cross will appear on the bottom of the sudoku left of timer and further, you can also see "Wrong" printed in the console.

Once you've filled all the numbers correctly, the window will close automatically and you'll see "Game Over" printed in the console.


## Code Explanation

There are 2 files that I've made in this project namely: - GUI.py and solver.py. As the name suggests, GUI.py contains the basic code, i.e., giving the input numbers of grid, designing the grid, cubes and the strikes. Further it also sets the timer that will be displayed on the lower right corner. It also sets what number will be inputted on pressing the respective keys and what action will be performed on pressing the enter key. Basically, GUI.py sets the graphical user interface of the project. It controls how the overall project will look like.

The second file solver.py has the complete algorithm that will be used to check whether the sudoku is solved correctly or not. The first function is the solve function which checks whether the user has clicked on an empty cube or not and the number he has entered is correct or not. The solve function checks the above mentioned things using the valid and find_empty function. The main algorithm for finding the two things are written in their respective functions.
