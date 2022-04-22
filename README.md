# C - printf

## Description

> This project is a collaboration between **CHIKEZIE SUCCESS** and **SULAIMAN OYEDEJI**. A team project which is part of the first year curriculum of **ALX Africa SE School**. `_printf` replicates the C standard library `printf()` function. It contains some of the basic features and functions found in the manual 3 of "printf". 


What you should learn from this project:
    - How to use git in a team setting
    - Applying variadic functions to a big project
    - The complexities of printf
    - Managing a lot of files and finding a good workflow

## Prototype
`int _printf(const char *format, ...);` 

## Usage
    - Prints a string to the standard output, according to a given format
    - All files were created and compiled on `Ubuntu 14.04.4 LTS` using `GCC 4.8.4` with the command `gcc -Wall -Werror -Wextra -pedantic *.c`
    - Returns the number of characters in the output string on success, -1 otherwise
    - Call it this way: `_printf("format string", arguments...)` where `format string` can contain conversion specifiers and flags, along with regular characters

## Examples
    - `_printf("Hello, ALX\n")` prints "Hello, ALX", followed by a new line
    - `_printf("%s", "Hello")` prints "Hello"
    - `_printf("This is a number: %d", 98)` prints "This is a number: `98`"


## File Functions

**_printf.c**
- Own Printf Function That Performs Formatted Output Conversion And Print Data.


