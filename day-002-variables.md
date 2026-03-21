# Day 2 - Vairables
  Varaibles are allocated space in mememory used to store a value
  
## What I learned
   - declearation and initialization
   - basic data types in C

## Code i wrote
```c
#include <stdio.h>

int main()
{
    int c; //declaration
    c = 4; //init

    int a = 13; //declare and init
    float pi = 3.14;
    char f = 'F'; //single character
    //there are no strings ion C, strings are objects and C isnt OO
    //to create a string use an array of chars
    char name[] = "retzonel";

    printf("You are %d years old", a);



    return 0; //comment
}
```

## Issues i faced
  Running my code, i kept running into "cannot open output file a.exe: Permission denied" errors.
  Started running my vscode as admin and fixed it. 
  I still need to know why that error is. 
