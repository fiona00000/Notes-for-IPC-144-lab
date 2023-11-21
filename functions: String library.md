# String Library Functions
## strlen
```C
#include <stdio.h>
#include <string.h>

int main()
{
    char word[100] = {"Hello!"};
    int len = strlen(word);
    printf("len of word: %d", len);

    return 0;
}
```
```C
#include <stdio.h>
#include <string.h>

int main()
{
    char word[100] = {};
    scanf("%s", word);
    int len = strlen(word);
    printf("len of word: %d", len);

    return 0;
}
```

### strcpy
```C
#include <stdio.h>
#include <string.h>


int main()
{
    char word[100] = {"nothing"}; //can be anything
    char hello[100] = {"hello"};
    
    printf("before:\t word: %s\t hello: %s\n", word, hello);
    
    strcpy(word, hello); //puts things from hello array to word array
    printf("after:\t word: %s\t hello: %s", word, hello);

    return 0;
}
```

