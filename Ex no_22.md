# EX 22 C program to count total number of even elements in an array using calloc().
## DATE:11/05/2025
## AIM:
To write a C program to count total number of even elements in an array using calloc().

## Algorithm
1.Start. 

2.Define a variables and write program to count total number of even elements in an array using calloc().

3.Read the value using scanf.

4.Ask the user to make an input and print the answer.

5.End.

## Program:
```
/*
C program to count total number of even elements in an array using calloc().
Developed by: JAYASHREE S
RegisterNumber:  212223060103

#include<stdio.h> 
#include<stdlib.h> 
int main()
{
int *arr,n,i,count=0; 
scanf("%d",&n); 
arr=(int*)calloc(1,sizeof(int)); 
for(i=0;i<n;i++)
{
scanf("%d",&arr[i]);
}
for(i=0;i<n;i++)
if(arr[i]%2==0) 
count++;
printf("Total even elements: %d",count);
}
*/
```

## Output:

![438865932-fc17064a-f203-40f7-be85-cfac3550bfbc](https://github.com/user-attachments/assets/48afa12c-bf55-43c0-aaaf-e4599524e19e)


## Result:
Thus the program was executed and the output was verified successfully.
