# Basic Input
- scanf()
```C
#include <stdio.h>

int main()
{
    char favFruit;
    printf("What is your favorite fruit?\n"
    "[S]trawberry, [O]range, [A]pple, [P]ear: ");
    scanf(" %c", &favFruit); //input O for Orange
    
    printf("So, your favorite fruit is:\n"
    "   |Strawberry|  Orange |  Apple |  Pear  |\n"
    "   |     %d    |    %d    |    %d   |    %d   |\n", 
    favFruit == 'S',  
    favFruit == 'O',  
    favFruit == 'A',  
    favFruit == 'P');
    
    return 0;
}
```
output
```
What is your favorite fruit?
[S]trawberry, [O]range, [A]pple, [P]ear: A
So, your favorite fruit is:
   |Strawberry|  Orange |  Apple |  Pear  |
   |     0    |    0    |    1   |    0   |
```
