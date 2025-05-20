# EX 21 C program to calculate the area of a triangle using pointer.
## DATE:
## AIM:
To write a C program to calculate the area of a triangle using pointer.

## Algorithm
1. Start.
2. Declare three variable value of type float.
3. Prompt the user to enter values.
4. Read the values using scanf and find the area of triangle using formula
5. End.

## Program:
```
/*
C program to calculate the area of a triangle using pointer.
Developed by: JAYASHREE S
RegisterNumber:  212223060103

#include <stdio.h>
int main() {
 float base, height, area;
 float *pBase = &base, *pHeight = &height;
 scanf("%f", pBase);
 scanf("%f", pHeight);
 area = 0.5 * (*pBase) * (*pHeight);
 printf("%.2f\n", area);
}
*/
```

## Output:

![438864829-62110244-5177-4f81-8450-a5fb6ebde48c](https://github.com/user-attachments/assets/eb5fbe9c-7a31-48af-973b-c41e9b98e591)

## Result:
Thus the program was executed and the output was verified successfully.
