# Example "Hello World!" in C

This is an example of how to write C code to print out "Hello World! and how use scanf, printf, declaration variable and another implementations ".

##Program to Print an Integer
#include <stdio.h>
int main()
{
    int number;

    // printf() dislpays the formatted output 
    printf("Enter an integer: ");  
    
    // scanf() reads the formatted input and stores them
    scanf("%d", &number);  
    
    // printf() displays the formatted output
    printf("You entered: %d", number);
    return 0;
}
