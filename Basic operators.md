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

## Compare (==, !=, <, >, <=, >=)
- 0 is False
- other numbers is True

```C
#include <stdio.h>

int main() {
    // Write C code here
    char letter = 'a';
    printf("letter equals to a? %d", letter == 'a');

    return 0;
}
```
output
```
letter equals to a? 1
```

## AND OR (&&, ||)
- OR operator: 0 || 1 -> 1 (true when either one is true)
- AND operator: 0 && 1 -> 0 (false when either one is false)

- OR can be FALSE when all items are FALSE
- AND can only be TRUE when all items are TRUE
