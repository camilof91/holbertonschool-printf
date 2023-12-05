<a href="https://ibb.co/NynDLsL"><img src="https://i.ibb.co/G53YV0V/printf.jpg" alt="printf" border="0"></a>

<h1>Description</h1>


This Project Implements A Version Of The _printf Function In C, Which Produces Output According To A Specific Format. The Function Is Designed To Handle Various Conversion Specifiers And Provides Additional Features As Described Below.


<h1>Requeriments</h1>

- Allowed editors:  vi ,  vim ,  emacs
- All your files will be compiled on Ubuntu 20.04 LTS using  gcc , using the options  -Wall -Werror -
Wextra -pedantic -std=gnu89
- All your files should end with a new line
- A  README.md  file, at the root of the folder of the project is mandatory
- Your code should use the  Betty  style. It will be checked using betty-style.pl (https://github.com/hs-
hq/Betty/blob/master/betty-style.pl) and betty-doc.pl (https://github.com/hs-
hq/Betty/blob/master/betty-doc.pl)
- You are not allowed to use global variables
- No more than 5 functions per file
- In the following examples, the  main.c  files are shown as examples. You can use them to test your functions, but you don’t have to push them to your repo (if you do we won’t take them into account).
- We will use our own  main.c  files at compilation; do not push your own  main.c  file. Our  main.c files might be different from the one shown in the examples
- The prototypes of all your functions should be included in your header file called  main.h
- Don’t forget to push your header file
- All your header files should be include guarded
- Note that we will not provide the  _putchar  function for this project

<h1>Function Prototype</h1>

> int _printf(const char *format, ...);

<h1>Compilation 💻</h1>

-Your code will be compiled this way:

>  $ gcc -Wall -Werror -Wextra -pedantic *.c

<h1>Return Value</h1>


The function returns the number of characters printed (excluding the null byte used to terminate output in strings). Supported Conversion Specifiers


The format string is composed of zero or more directives. The following conversion specifiers are handled:

<h1>Format Specifiers</h1>

Lets have a look at some of the important format specifiers

|  Format Specifier | Description  |
| ------------ | ------------ |
| %c | A single character |
| %s | string of characters  |
| %%  | Percent sign   |
| %d & %i  | A decimal (base 10) number  |
| %u   | An unsigned decimal (base 10) number  |
| %o  | A number in octal (base 8)   |
|%x | A number in hexadecimal (base 16)  |
| %b  | Binary (custom specifier) |
| %r  | Prints a reversed string |
| %R | Prints the Rot13 |
| %f | A floating-point number |


<h1>Example Usage</h1>


Here is an example demonstrating the use of the _printf function:


![](https://media.geeksforgeeks.org/wp-content/cdn-uploads/20191009172738/n-in-printf.jpg)

<h1>Repository</h1>

The code for this project is hosted on GitHub:

https://github.com/CamiloFetecua/holbertonschool-printf

<h1>Members</h1>

<a href="https://www.linkedin.com/in/brayan-salazar-perdomo-07a4321b1/">
  <img src="https://static-00.iconduck.com/assets.00/linkedin-icon-2048x2048-ya5g47j2.png" width="50"<p>  Brayan Steven Salazar</p>
</a>

------------


<a href="https://www.linkedin.com/in/camilo-fetecua-406a70298/">
  <img src="https://static-00.iconduck.com/assets.00/linkedin-icon-2048x2048-ya5g47j2.png" width="50"<p>  Camilo Fetecua</p>
</a>

<footer><img src="https://wisynco.com/wp-content/uploads/2014/12/footer-background-011.jpg"></footer>
