# C - printf

## Description

 This project is a collaboration between **CHIKEZIE SUCCESS** and **SULAIMAN OYEDEJI**. A team project which is part of the first year curriculum of **ALX Africa SE School**. `_printf` replicates the C standard library `printf()` function. It contains some of the basic features and functions found in the manual 3 of `"printf"`. 


> What you should learn from this project:
 >  - How to use git in a team setting
 >  - Applying variadic functions to a big project
 >  - The complexities of printf
 >  - Managing a lot of files and finding a good workflow

* ## Prototype
`int _printf(const char *format, ...);` 

* ## Usage
    - Prints a string to the standard output, according to a given format
    - All files were created and compiled on `Ubuntu 14.04.4 LTS` using `GCC 4.8.4` with the command `gcc -Wall -Werror -Wextra -pedantic *.c`
    - Returns the number of characters in the output string on success, -1 otherwise
    - Call it this way: `_printf("format string", arguments...)` where `format string` can contain conversion specifiers and flags, along with regular characters

* ## Examples
    - `_printf("Hello, ALX\n")` prints "Hello, ALX", followed by a new line
    - `_printf("%s", "Hello")` prints "Hello"
    - `_printf("This is a number: %d", 98)` prints "This is a number: `98`"


## File Functions 📃

**[_printf.c](./_printf.c)**
- Own Printf Function That Performs Formatted Output Conversion And Print Data.

**[main.h](./main.h)**
- Header File Where All Prototypes Are Saved.

**[get_print_func.c](./get_print_func.c)**
- Pointer To A Function That Selects The Correct Function To Perform The Operation.

**[print_buf.c](./print_buf.c)**
- Function That Prints The Buffer.

**[handl_buf.c](./handl_buf.c)**
- Function That Concatenates The Buffer Characters.

**[print_chr.c](./print_chr.c)**
- Function That Writes The Character C To Stdout. /* Indetifier : %c */

**[print_str.c](./print_str.c)**
- Function That Writes The String To Stdout. /* Indetifier : %s */

**[print_int.c](./print_int.c)**
- Function That Prints An Integer. /* Indetifier : %i or %d */

**[print_bnr.c](./print_bnr.c)**
- Function That Prints Decimal In Binary. /* Indetifier : %b */

**[print_oct.c](./print_oct.c)**
- Function That Prints Decimal In Octal. /* Indetifier : %o */

**[print_hex.c](./print_hex.c)**
- Function That Prints Decimal In Hexadecimal. /* Indetifier : %x */

**[print_upx.c](./print_upx.c)**
- Function That Prints Decimal In Uppercase Hexadecimal. /* Indetifier : %X */

**[print_usr.c](./print_usr.c)**
- Function That Prints A String And Values Of Non-Printed Chars. /* Indetifier : %S */

**[print_unt.c](./print_unt.c)**
- Function That Prints An Unsigned Integer. /* Indetifier : %u */

**[print_rev.c](./print_rev.c)**
- Function That Writes The String To Stdout In Reverse. /* Indetifier : %r */

**[print_rot.c](./print_rot.c)**
- Function That Writes The String To Stdout In Rot13. /* Indetifier : %R */

**[print_add.c](./print_add.c)**
- Function That Prints The Address Of An Input Variable. /* Indetifier : %p */

**[print_long_oct.c](./print_long_oct.c)**
- Function That Prints Long Decimal Number In Octal. /* Indetifier : %lo */

**[print_long_hex.c](./print_long_hex.c)**
- Function That Prints Long Decimal Number In Hexadecimal. /* Indetifier : %lx */

**[print_long_int.c](./print_long_int.c)**
- Function That Prints A Long Integer. /* Indetifier : %li */

**[print_long_upx.c](./print_long_upx.c)**
- Function That Prints A Long Decimal In Uppercase Hexadecimal. /* Indetifier : %lX */

**[print_long_unt.c](./print_long_unt.c)**
- Function That Prints A Long Unsigned Integer. /* Indetifier : %lu */

**[print_short_oct.c](./print_short_oct.c)**
- Function That Prints Short Decimal Number In Octal. /* Indetifier : %ho */

**[print_short_hex.c](./print_short_hex.c)**
- Function That Prints Short Decimal Number In Hexadecimal. /* Indetifier : %hx */

**[print_short_int.c](./print_short_int.c)**
- Function That Prints A Short Integer. /* Indetifier : %hi */

**[print_short_upx.c](./print_short_upx.c)**
- Function That Prints A Short Decimal In Uppercase Hexadecimal. /* Indetifier : %hX */

**[print_short_unt.c](./print_short_unt.c)**
- Function That Prints A Short Unsigned Integer. /* Indetifier : %hu */

**[print_num_hex.c](./print_num_hex.c)**
- Function That Print A Number In Hexadecimal Begining With 0 And x. /* Indetifier : %#x */

**[print_num_oct.c](./print_num_oct.c)**
- Function That Prints A Number In Octal Begining With 0 And o. /* Indetifier : %#o */

**[print_num_upx.c](./print_num_upx.c)**
- Function That Prints A Number In Uppercase Hexadecimal. /* Indetifier : %#X */

**[print_plus_int.c](./print_plus_int.c)**
- Function That Prints An Integer With Plus Symbol. /* Indetifier : %+i */

**[print_space_int.c](./print_space_int.c)**
- Function That Prints An Integer Begining With 0 And u. /* Indetifier : % i */

**[ev_print_func.c](./ev_print_func.c)**
- Function That Returns The Amount Of Indetifiers.

> **Authors**

> CHIKEZIE SUCCESS and SULAIMAN OYEDEJI

**End**

Success & Sulaiman @ ALX software engineering programme 2022.
