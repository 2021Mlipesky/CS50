collection of notes in the C language

Scratch Say(hello, world)

```C
printf("hello, world\n");
```

all printed words are called strings and strings are enclosed by "string"<br>
\n tells computer to start a newline
The ; is like the period of a sentence. It tells the computer that this is the end of the statement

Scratch: Set counter to 0

```C
int counter = 0;
```

In C, you must declare the type of variable you are creating

Scratch: change counter by 1

```C
counter = counter + 1; #add any number
counter += 1; #add any number
counter++; #only adds plus 1 to counter
```

the = sign is not "equals," it means "assign" or "get."
once you create a variable you don't need to keep repeating it.

```C
if (x<y)
{
    printf("x is less than y\n");
}
```

```C
if (x<y)
{
    printf("x is less than y\n");
}
else
{
    printf("x is not less than y\n");
}
```

```C
#include <stdio.h>

int main(void)
{
     printf("hello, world\n");
}
