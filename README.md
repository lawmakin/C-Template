# Template for .c programs

Template.c is a simple formatting template I use for
writing C programs, based on NASA's style guide document 
from August 1994.

## Program Details
```
/**********************************************************
 * PROGRAM NAME:                                          *
 *                                                        *
 * PURPOSE:                                               *
 *                                                        *
 * AUTHOR:                                                *
 * DATE:                                                  *
 *********************************************************/
```

Relatively self-explanatory; Program Name depicts [name].c,
Purpose describes the purpose of the program, Author lists
the author name, and Date the creation date of the program.


## Pre-Processor Directives

```
/* Pre-Processor Directives */
```

Includes, defines, ifdefs, typedefs, pragmas etc.

## Function Prototypes
```
/* Function Prototypes */
```

Declaration of functions i.e. their return type, name, 
paramaters.

## Function Definitions
```
/* Function Definitions */
int main(int argc, char *argv[])
{

}
```

Definitions of functions i.e. the body of each function,
starting with main.

### To-Do List

I plan on getting to grips with Erik O'Shaugnessy's guide, [How to write a good C main function](https://opensource.com/article/19/5/how-write-good-c-main-function), and incorporating it, in a fashion, into this template.