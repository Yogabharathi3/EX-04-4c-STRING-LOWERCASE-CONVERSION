# EX-04-4c-STRING-LOWERCASE-CONVERSION
## AIM 
Write a C Program to convert the given string into lowercase. 
## ALGORITHM 
1. Start the program. 
2. Read a string variable. 
3. Using tolower( ) function convert the given string into its lowercase. 
4. Display the result. 
5. Stop the program. 
## PROGRAM 
```
#include<stdio.h> 
#include<string.h> 
#include<ctype.h> 
int main() 
{ 
 char s[50]; 
 scanf("%s",s); 
 printf("Lower case String is:"); 
 for(size_t i=0;i<strlen(s);i++) 
 printf("%c", tolower((unsigned char) s[i])); 
}
```
## OUTPUT
![image](https://github.com/Yogabharathi3/EX-04-4c-STRING-LOWERCASE-CONVERSION/assets/118899387/de139d82-2927-4768-b2f5-6976a4c02766)
## RESULT 
Thus the program to convert the given string into lowercase has been executed 
successfully
