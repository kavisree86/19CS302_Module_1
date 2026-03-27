# EX 4 C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
## DATE:
## AIM:
To write a C program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).

## Algorithm
Start.
Declare a variable value of type char.
Prompt the user to enter a value.
Read the value using scanf.
Check eligible for marriage.
If age >= 21, print "Eligible".
If false, print " Not Eligible".
End.  

## Program:
```
/*
Program to read the age of a person and determine whether he is eligible for marriage (eligible if age ≥ 21).
Developed by: 
RegisterNumber:  
*/
```
```
#include<stdio.h> 
int main(){ 
char p1; 
scanf("%c", &p1); 
if(p1>=21) 
{ 
printf("Eligible"); 
}else{
printf("Not Eligible");
return 0; 
}
}
```

## Output:
<img width="774" height="163" alt="image" src="https://github.com/user-attachments/assets/00650e76-2e2c-487f-a105-68704f51da57" />



## Result:
Thus the program was executed and the output was verified successfully.
