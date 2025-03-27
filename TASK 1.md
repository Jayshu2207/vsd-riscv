This repository contains a simple C program that calculates the sum of numbers from 1 to n. 
The program demonstrates basic looping (for loop),arithmetic operations, and formatted output in C. 
It is useful for beginners learning C programming and command-line compilation.









1. Opening the Source Code File in a Text Editor

leafpad sumiton.c &

Opens the sumiton.c file in Leafpad, a graphical text editor.

The & at the end runs the command in the background, allowing the user to continue using the terminal.


2. Compiling the C Program Using GCC

gcc sumiton.c

This command compiles the sumiton.c file using the GNU Compiler Collection (GCC).


3. Running the Compiled Program

./a.out

This executes the compiled binary file a.out.

The first run shows:

Sum of numbers from 1 to 5 is 15

The second run shows:

Sum of numbers from 1 to 1000 is 500500

This confirms that the program successfully calculates the sum from 1 to n.












Program Explanation

C Code (sumiton.c)

#include<stdio.h>

int main() {
    int i, sum = 0, n = 1000; // Change n to calculate sum for different values

    for (i = 1; i <= n; ++i) {
        sum += i;
    }

    printf("Sum of numbers from 1 to %d is %d\n", n, sum);
    return 0;
}

Example Output

Sum of numbers from 1 to 1000 is 500500



