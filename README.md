_printf is a custom implementation of the C programming function printf.
This project is an application of the C programming knowledge that Alx School cohort 5 students have learned since the beginning of the program.

Prototype: int _printf(const char *, ...);

i.e :
String

Input: _printf("%s\n", 'This is a string.');
Output: This is a string.
Character
Input: _printf("The first letter in the alphabet is %c\n", 'A');
Output: The first letter in the alphabet is A.

Integer.
Input: _printf("There are %i dozens in a gross\n", 12);
Output: There are 12 dozens in a gross

Decimal:
Input: _printf("%d\n", 1000);
Output: 1000

Project Requirements:

All files will be compiled on Ubuntu 14.04 LTS
Programs and functions will be compiled with gcc 4.8.4 using flags -Wall -Werror -Wextra and -pedantic
Code must follow the Betty style.
Global variables are not allowed.

Authorised functions and macros:
 -write (man 2 write)
 -malloc (man 3 malloc)
 -free (man 3 free)
 -va_start (man 3 va_start)
 -va_end (man 3 va_end)
 -va_copy (man 3 va_copy)
 -va_arg (man 3 va_arg)

File Descriptions.

_printf.c: - contains the function _printf, which uses the prototype int _printf(const char *format, ...);. The format string is composed of zero or more directives.
See man 3 printf for more detail. _printf will return the number of characters printed (excluding the null byte used to end output to strings)
 and will write output to stdout, the standard output stream.

_putchar.c: - contains the function _putchar, which writes a character to stdout.

main.h: - contains all function prototypes used for _printf.

man_3_printf: - manual page for the custom _printf function.

print_numbers.c: - contains the functions print_i and print_d, which handle the conversion specifiers i and d, respectively.

