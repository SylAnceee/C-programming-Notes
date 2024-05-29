# Basic Data Types

In C, various types of variables are supported, each designed for storing specific kinds of data types:

- Integers
- Non-integral numerical values
- Characters

Examples of basic data types in C include:
- `int`
- `float`
- `double`
- `char`
- `_Bool`

These types differ in the amount of memory they occupy and the range of values they can hold.

The amount of storage allocated for a particular type of data depends on the computer being used (machine-dependent). For example, an integer might take up 32 bits on one computer and 64 bits on another.

## Enums

To declare a variable of type `enum`, such as `primaryColor`, use the following syntax:

```c
enum primaryColor {
    red,
    yellow,
    blue
};
```
![FireShot Capture 010 - Course_ C Programming For Beginners - Master the C Language - Udemy_ - www.udemy.com](FireShot%20Capture%20010%20-%20Course_%20C%20Programming%20For%20Beginners%20-%20Master%20the%20C%20Language%20-%20Udemy_%20-%20www.udemy.com.jpeg)

## Format Specifiers

# C Format Specifiers

In C programming, format specifiers are used in functions like `printf()` and `scanf()` to specify the type of data to be printed or read. Each format specifier starts with a percent sign (%) followed by a character that specifies the data type.

## Common Format Specifiers

- `%d` or `%i`: Signed decimal integer
- `%u`: Unsigned decimal integer
- `%f`: Decimal floating point
- `%lf`: Double floating point
- `%e` or `%E`: Scientific notation (mantissa/exponent) of a floating-point number
- `%g` or `%G`: Use the shortest representation: `%e` or `%f`
- `%x` or `%X`: Unsigned hexadecimal integer
- `%o`: Unsigned octal integer
- `%c`: Character
- `%s`: String of characters
- `%p`: Pointer address
- `%n`: Number of characters written by this `printf`

## Example

### Integer

```c
int num = 42;
printf("Number: %d\n", num); // Output: Number: 42
```
## Command Line Arguments  
Command line arguments in C are parameters passed to the main() function of a program when it is executed from a command line interface (CLI). They allow users to provide input values directly from the command line when running the program.

## main() Function Signature

The `main()` function in C can take two arguments:
1. `int argc`: This represents the number of command line arguments passed to the program.
2. `char *argv[]`: This is an array of strings representing the command line arguments.




