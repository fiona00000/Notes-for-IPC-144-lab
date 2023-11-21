# Basic operators
## ++ / --
- short hand for += 1 or -= 1
```C
#include <stdio.h>

int main()
{
    int y; //declaration
    int x = 3; // initialization
    
    printf("x is originally %d\n\n", x);
    
    printf("++x is %d\n", ++x);
    printf("x is %d\n\n\n", x);
    
    
    x = 3; //assignment
    printf("x is originally %d\n\n", x);
    
    printf("x++ is %d\n", x++);
    printf("x is %d after x++\n", x);


    return 0;
}
```

output
```
x is originally 3

++x is 4
x is 4


x is originally 3

x++ is 3
x is 4 after x++
```
