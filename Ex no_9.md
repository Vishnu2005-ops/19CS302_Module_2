# EX 9 C program to find the sum of odd digits using do while loop.
## AIM:
To write a C program to find the sum of odd digits using do while loop.

## Algorithm
1. Start
2. Declare variables: num, digit, and sum = 0
3. Read the number num from the user
4. Use a do-while loop to extract digits:  
   a. Get the last digit using digit = num % 10  
   b. If digit is odd, add it to sum  
   c. Remove the last digit using num = num / 10  
5. Repeat the loop until num becomes 0
6. Print the sum
7. End

## Program:
```
#include<stdio.h>  
int main()  
{  
    int num ,sum = 0;  
    scanf("%d",&num);
    for(int i=1;i<=num;i++)
    {
        if(i%2!=0)
        {
            sum=sum+i;
            i++;
        }
        else
        {
            continue;    
        }
    }    
    printf("%d", sum); 
    return 0;  
}  
```

## Output:

![image](https://github.com/user-attachments/assets/b321c491-42d6-4bc8-99fa-e7ebd25f857e)


## Result:
Thus the program was executed and the output was verified successfully.
