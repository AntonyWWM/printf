Collaboration readme
printf
printf _printf is a custom implementation of the C programming function printf. This project is an application of the C programming knowledge that Alx cohort 5 students have learned since starting the program on Feb 14th 2022.

Prototype: int _printf(const char *, ...);

Examples String

Input: _printf("%s\n", 'This is a string.'); Output: This is a string. Character

Input: _printf("The first letter in the alphabet is %c\n", 'A'); Output: The first letter in the alphabet is A Integer

Input: _printf("There are %i dozens in a gross\n", 12); Output: There are 12 dozens in a gross Decimal:

Input: _printf("%d\n", 1000); Output: 1000 Allowed editors: vi, vim, emacs All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89 All your files should end with a new line A README.md file, at the root of the folder of the project is mandatory Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl You are not allowed to use global variables No more than 5 functions per file In the following examples, the main.c files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account). We will use our own main.c files at compilation. Our main.c files might be different from the one shown in the examples The prototypes of all your functions should be included in your header file called main.h Don’t forget to push your header file All your header files should be include guarded Note that we will not provide the _putchar function for this project Mandatory Tasks Write function that produces output with conversion specifiers c, s, and %. Handle conversion specifiers d, i. Create a man page for your function. Advanced Tasks Handle conversion specifier b. Handle conversion specifiers u, o, x, X. Use a local buffer of 1024 chars in order to call write as little as possible. Handle conversion specifier S. Handle conversion specifier p. Handle flag characters +, space, and # for non-custom conversion specifiers. Handle length modifiers l and h for non-custom conversion specifiers. Handle the field width for non-custom conversion specifiers. Handle the precision for non-custom conversion specifiers. Handle the 0 flag character for non-custom conversion specifiers. Handle the custom conversion specifier r that prints the reversed string. Handle the custom conversion specifier R that prints the rot13'ed string. All above options should work well together. File Descriptions _printf.c: - contains the fucntion _printf, which uses the prototype int _printf(const char *format, ...);. The format string is composed of zero or more directives. See man 3 printf for more detail. _printf will return the number of characters printed (excluding the null byte used to end output to strings) and will write output to stdout, the standard output stream. _putchar.c: - contains the function _putchar, which writes a character to stdout. holberton.h: - contains all function prototypes used for _printf. man_3_printf: - manual page for the custom _printf function. print_chars.c: - contains the functions print_c, print_s, print_S, and print_r which handle the conversion specifiers c, s, S, and r, respectively, as well as hex_print, which prints a char's ascii value in uppercase hex print_numbers.c: - contains the functions print_i and print_d, which handle the conversion specifiers i and d, respectively print_hex.c: - contains the functions print_hex, which prints an unsigned int in hexidecimal form, print_x, print_X, and print_p, which handle the conversion specifiers x, X, and p, respectively print_unsigned_int.c: - contains the functions print_u, print_o, and print_b, which handle the conversion specifiers u, o, and b, respectively print_rot13.c - contains the function print_R, which handles the conversion specifier R Authors Antony Wanjira Maina / @antonywanjiramaina

maryliz munjiru karumba / @marylizmunjirukarumbakarumba
