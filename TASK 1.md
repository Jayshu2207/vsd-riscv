This repository contains a simple C program that calculates the sum of numbers from 1 to n. 
The program demonstrates basic looping (for loop),arithmetic operations, and formatted output in C. 
It is useful for beginners learning C programming and command-line compilation.

![20250324_192855](https://github.com/user-attachments/assets/7e368f61-e72f-48fa-928b-5d6847b71a67)


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

![20250324_200215](https://github.com/user-attachments/assets/b7869d51-6d1c-462e-bf32-00f2efbeef61)


![20250328_043336](https://github.com/user-attachments/assets/52ab4134-13eb-4d26-939f-1256a177ac93)



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



