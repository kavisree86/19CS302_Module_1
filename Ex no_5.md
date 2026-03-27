# EX 5 C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
## DATE:
## AIM:
To write a C program to calculate the total marks, average, and percentage of marks obtained in seven subjects.

## Algorithm
1.Start.
Declare three variable value of type int for marks.
Prompt the user to enter a value.
Read the value using scanf.
Find total and average.
Print the result
End.

## Program:
```
/*
Program to calculate the total marks, average, and percentage of marks obtained in seven subjects.
Developed by: 
RegisterNumber:  
*/
```

```
#include <stdio.h> 
int main() { 
    int sub1, sub2, sub3, total; 
    float average; 
    scanf("%d %d %d", &sub1,&sub2,&sub3); 
    total = sub1 + sub2 + sub3; 
    average = total / 3.0; 
    printf("\nTotal : %d\n", total); 
    printf("Average : %.2f\n", average); 
    return 0; 
}
```

## Output:

<img width="398" height="170" alt="image" src="https://github.com/user-attachments/assets/46941818-ae5d-4d6b-be6c-6b6ba8b43a68" />


## Result:
Thus the program was executed and the output was verified successfully.
