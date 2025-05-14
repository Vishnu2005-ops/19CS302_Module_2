# EX 8 C program to perform multiplication and division of two numbers using functions (without argument and without return type).
## AIM:
To write a C program to perform multiplication and division of two numbers using functions (without argument and without return type).

## Algorithm
1. Start
2. Create multiply() function:  
   a. Ask user for two numbers  
   b. Multiply and print result  
3. Create divide() function:  
   a. Ask user for two numbers  
   b. Divide and print result  
4. In main(), call multiply() and divide()
5. End

## Program:
```
#include <stdio.h>
void readNumbers(int *num1, int *num2) 
{
    scanf("%d %d", num1, num2);
}
int multiply() 
{
    int num1, num2;
    readNumbers(&num1, &num2);
    return num1 * num2;
}
int divide() 
{
    int num1, num2;
    readNumbers(&num1, &num2);
    return (int) num1 / num2;
}
int main() 
{
    int multiplication = multiply();
    int division = divide();
    printf("Multiplication: %d\n", multiplication);
    printf("Division: %d\n", division);
    return 0;
}
```

## Output:
![image](https://github.com/user-attachments/assets/2fea9450-f16b-46d7-99f1-e3b8fcc5835d)

## Result:
Thus the program was executed and the output was verified successfully.
