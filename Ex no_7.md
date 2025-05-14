# EX 7 C program to print the given triangular number pattern using loop.
## AIM:
To write a C program to print the given triangular number pattern using loop.
## Algorithm
1. Start
2. Declare an integer variable n
3. Ask the user to enter the number of rows n
4. Use an outer loop from i = 1 to i <= n (each row)
5. Inside the outer loop, use an inner loop from j = 1 to j <= i to print numbers from 1 to i
6. After the inner loop ends, print a newline
7. End
## Program:
```
#include<stdio.h>
int main()
{
    int i,j,a;
    scanf("%d",&a);
    for (i=a;i>=1;i--)
    {
       for (j=i;j<=a;j++)
       {
            printf("%d",i);
       }
            
        printf("\n");
    }
}
```

## Output:
![image](https://github.com/user-attachments/assets/12c522fb-f10b-43fd-ab1f-3cb076c734ad)



## Result:
Thus the program was executed and the output was verified successfully.
