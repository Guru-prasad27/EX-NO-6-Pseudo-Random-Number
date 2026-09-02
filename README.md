# EX-NO-6-Pseudo-Random-Number
## Name:Guru Prasad DR
## RegNo:212225040104

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
<img width="677" height="346" alt="image" src="https://github.com/user-attachments/assets/76c98eaa-9a12-4eca-95ac-43e99f9d1714" />

# RESULT:
Thus, the implementation of Pseudo Random Number Generation using the standard library functions was successfully executed and verified.
