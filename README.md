# EX-NO-6-Pseudo-Random-Number

## PROGRAM DONE BY: Moushmitha B (212225230189)

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h> 
#include <stdlib.h> 
#include <time.h> 
int main() { 
    int i, n; 
    srand(time(0)); 
    printf("Enter how many pseudorandom numbers you want to generate: "); 
    scanf("%d", &n); 
    printf("Generating %d pseudorandom numbers between 0 and 99:\n", n); 
    for (i = 0; i < n; i++) { 
        int randomNumber = rand() % 100; 
        printf("%d ", randomNumber); 
    } 
    printf("\n"); 
    return 0; 
}
```
# OUTPUT:
<img width="695" height="230" alt="Screenshot 2026-10-28 230615" src="https://github.com/user-attachments/assets/29ea49de-56d5-4e66-9db1-047520373598" />


# RESULT:
Thus, Implementation of Pseudorandom Number Generation Using Standard library is created successfully.
