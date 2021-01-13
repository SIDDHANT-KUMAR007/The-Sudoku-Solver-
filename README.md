PROBLEM STATEMENT: Write a Program to create a sudoku solver of 9 X 9 matix using CPP.

WHAT SUDOKU IS ??

Sudoku is a puzzle in which players insert the numbers one to nine into a grid consisting of nine squares subdivided into a further nine smaller squares in such a way that every number appears once in each horizontal line, vertical line, and square.

PROGRAM SCOPE: This sudoku solver can solves the sudoku puzzle of 9 X 9 order.

PROGRAMMING LANGUAGE: C++

PLATFORM REQUIRED: 
Visual Studio 2019 or Code Blocks

WHERE TO GET THE REQUIRED PLATFORM :

1.Go to visualstudio.microsoft.com and download the installer.
2.Install the installer and then open it.
3.Choose Visual studio 2019 community with the C++ desktop envirnoment kit.

HEADER FILES USED: 
                   iostream
                   vector
                   array
                   algorithm

FUNCTIONS USED:
                   void print_grid
                   bool used_in_row
                   bool used_in_col
                   bool used_in_box
                   bool is_safe
                   bool solve_soduko
                   int main
CODE FEATURES:

Program contains a by default sudoku puzzle, and will solve that if the user would be Pressing 1.
This program allowing the user to input thier own 9 x 9 grid sudoku puzzle and it will solve that puzzle.

RUNNING PROCESS OF THE CODE:

1.Go to any of the like visual studio or code block.
2.Write this code and compile it.
3.Run the code.
4.It will show two massages on the console screen.
5.Use by deafult sudoku puzzle to check the code. Press 1.
6.Or input your own sudoku puzzle. Press 2.
7.If you Press 1, it will solve the inbuilt puzzle each time.
8.If you Press 2, you have to enter the all elements of the sudoku puzzle and input zero at the empty places.

OUTPUT: You will get your puzzle totally solved.
