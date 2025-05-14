# EX 10 C program to find the factorial of a given number using a function with arguments and return type.
## AIM:
To write a C program to find the factorial of a given number using a function with arguments and return type.

## Algorithm
1. Start
2. Define a function factorial() with return type and no arguments
3. Inside factorial() function:  
   a. Declare an integer variable n and fact = 1  
   b. Ask the user to enter a number and store it in n  
   c. Use a loop from 1 to n to multiply the values and store in fact  
   d. Return fact to the calling function  
4. In main() function, call factorial() and store the result
5. Print the factorial
6. End
## Program:
```
#include <stdio.h>
int fact();
int main()
{
    int y;
    y=fact();
    printf("Factorial value is: %d",y);
    return 0;
}
int fact()
{
    int x,pro = 1;
    scanf("%d",&x);
    for(int i=1;i<=x;i++)
    {
        pro=pro*i;
    }
    return (pro);
}
```

## Output:
![image](https://github.com/user-attachments/assets/e13af873-d80c-4b3e-b110-f86f00678d69)


## Result:
Thus the program was executed and the output was verified successfully.
