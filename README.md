### <p align=right> Ashqar Ahamed S T
### <p align=right> 212224240018
### <p align=right> 10.02.2026

# EX-NO-6-Pseudo-Random-Number

## AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

## ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

## PROGRAM:
```
#include<stdio.h>
#include<stdlib.h>
#include<time.h>
int main()
{
    int count, min, max;
    printf("Enter the number of random number to generated: ");
    scanf("%d",&count);

    printf("\nEnter the minimum value: ");
    scanf("%d", &min);

    printf("\nEnter the Maximum value: ");
    scanf("%d",&max);
    
    srand(time(NULL));
    for(int i=0;i<count;i++)
    {
            int rand_number = (rand() % (min - max + 1)) + min;
            printf("\n%d",rand_number);
    }
    return 0;
}
```

## OUTPUT:

<img width="1557" height="405" alt="output" src="https://github.com/user-attachments/assets/752d4375-49ae-451e-a9e7-fb873d571506" />


## RESULT:
Thus, a C program is written and executed successfully to implemente of Pseudorandom Number Generation Using Standard library

