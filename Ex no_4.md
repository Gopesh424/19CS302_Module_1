# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:07/05/2025
## AIM:To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
1. Start. 
2. Declare a variable value of type char. 
3. Prompt the user to enter a value. 
4. Read the value using scanf. 
5. Check eligible for marriage. 
6. If age >= 21, print "Eligible". 
7. If false, print " Not Eligible". 
8. End.

## Program:

Program:
```
#include<stdio.h>
int main()
{
int n;
scanf("%d",&n);
if(n>=21)
{
printf("Eligible");
}
else
{
printf("Not Eligible");
}
return 0;
}
/*
Program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
Developed by: 
RegisterNumber:  
*/
```

## Output:
23     Eligible
20     Not Eligible

## Result:
Thus the program was executed and the output was verified successfully.
