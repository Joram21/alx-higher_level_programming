 There are (at least) two distinguishable kinds of errors: syntax errors and exceptions.Syntax errors, also known as parsing errors, are perhaps the most common kind of complaint you get while you are still learning Python:
The parser repeats the offending line and displays a little ‘arrow’ pointing at the earliest point in the line where the error was detected. The error is caused by (or at least detected at) the token preceding the arrow: in the example, the error is detected at the function print(), since a colon (':') is missing before it. File name and line number are printed so you know where to look in case the input came from a script.
Errors detected during execution are called exceptions and are not unconditionally fatal: Most exceptions are not handled by programs, however, and result in error messages.

0. Safe list printing
Write a function that prints x elements of a list.
1. Safe printing of an integers list
Write a function that prints an integer with "{:d}".format().
2. Print and count integers
Write a function that prints the first x elements of a list and only integers.
3. Integers division with debug
Write a function that divides 2 integers and prints the result.
4. Divide a list
Write a function that divides element by element 2 lists.
5. Raise exception
Write a function that raises a type exception.
6. Raise a message
Write a function that raises a name exception with a message.
7. Safe integer print with error message
Write a function that prints an integer.
8. Safe function
Write a function that executes a function safely.
9. ByteCode -> Python #4
Write the Python function def magic_calculation(a, b): that does exactly the same as the following Python bytecode:
10. CPython #2: PyFloatObject
Create three C functions that print some basic info about Python lists, Python bytes an Python float objects.
