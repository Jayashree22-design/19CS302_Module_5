# EX 25 C program to check whether a given character is a vowel or consonant using pointer
## DATE:
## AIM:
To write a C program to check whether a given character is a vowel or consonant using pointer

## Algorithm
1.Start. 
2.Declare a variable value of type char.
3.Read the value using scanf. 
4.Find vowel and consonants
5.End.

## Program:
```
/*
C program to check whether a given character is a vowel or consonant using pointer
Developed by: JAYASHREE S
RegisterNumber:  212223060103

#include <stdio.h>
int main() {
 char str[100];
 char *p;
 int vowels = 0, consonants = 0;
 scanf(" %[^\n]", str); 
 p = str; 
 while (*p != '\0') {
 if ((*p >= 'A' && *p <= 'Z') || (*p >= 'a' && *p <= 'z')) {
 char ch = (*p >= 'A' && *p <= 'Z') ? *p + 32 : *p;
 if (ch == 'a' || ch == 'e' || ch == 'i' || ch == 'o' || ch == 'u') {
 vowels++;
 } else {
 consonants++;
 }
 }
 p++;
 }
 printf("Vowels: %d\n", vowels);
 printf("Consonants: %d\n", consonants);
 return 0;
}
*/
```
## Output:
![438869906-2463b546-5d0c-4da0-bbec-39f37630de1e](https://github.com/user-attachments/assets/50cfe721-9c7a-4f35-a23e-5a5235cced9b)
## Result:
Thus the program was executed and the output was verified successfully.
