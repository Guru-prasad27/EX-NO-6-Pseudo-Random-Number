# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main()
{
    int n, i;

    /* Seed the random number generator */
    srand(time(0));

    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

    printf("Generated Random Numbers:\n");

    for (i = 0; i < n; i++)
    {
        printf("%d\n", rand());
    }

    return 0;
}
# OUTPUT:
<img width="677" height="346" alt="image" src="https://github.com/user-attachments/assets/5ebb0973-e443-4de7-8296-e2f7831c1b31" />

# RESULT:
