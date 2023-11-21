# String Library Functions
- inside #include <string.h> library

## strlen
- length of a string
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
![WhatsApp Image 2023-11-21 at 14 44 31](https://github.com/fiona00000/Notes-for-IPC-144-lab/assets/63148173/0b26ae56-7f68-4d0e-8896-ea17115d1602)


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
![WhatsApp Image 2023-11-21 at 14 46 05](https://github.com/fiona00000/Notes-for-IPC-144-lab/assets/63148173/b50c338e-648e-46a1-ae61-32244196f85f)


### strcpy
- copy content from the right arguments to the left one
- i.e. b = a will be strcpy(b,a)
      - assumpting a and b are string
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
![WhatsApp Image 2023-11-21 at 14 53 15](https://github.com/fiona00000/Notes-for-IPC-144-lab/assets/63148173/121ab80e-05af-4c18-bdee-857910b41cc1)

