## Introduction
This program will read in the lower and upper bounds of the range from the user, and then use a for loop to iterate through the numbers in that range. For each number, it will check if it is divisible by 2 using the modulo operator (%). If it is, the number will be printed out.

```
#include <stdio.h>

int main()
{
    // Declare variables to store the lower and upper bounds of the range
    int lower, upper;

    // Read in the lower and upper bounds of the range from the user
    printf("Enter the lower bound of the range: ");
    scanf("%d", &lower);
    printf("Enter the upper bound of the range: ");
    scanf("%d", &upper);

    // Print a message indicating the range of numbers being checked
    printf("Numbers divisible by 2 between %d and %d:\n", lower, upper);

    // Use a for loop to iterate through the numbers in the given range
    for (int i = lower; i <= upper; i++)
    {
        // Check if the current number is divisible by 2
        if (i % 2 == 0)
        {
            // If it is, print it out
            printf("%d\n", i);
        }
    }

    return 0;
}
```
