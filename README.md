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
```
#include <stdio.h> 
#include <stdlib.h>   
#include <time.h>       
int main() { 
    int n, i; 
  
        srand(time(0)); 
  
   
    printf("Enter the number of random numbers to generate: "); 
    scanf("%d", &n); 
  
    printf("Generated Pseudo-Random Numbers:\n"); 
     
     
    for(i = 0; i < n; i++) { 
        printf("%d\n", rand()); 
    } 
  
return 0; 
}
```

# OUTPUT:

<img width="695" height="349" alt="image" src="https://github.com/user-attachments/assets/e43ffbaf-0138-47a8-b859-95ecf77e9a9a" />


# RESULT:
Thus the program is implemented
