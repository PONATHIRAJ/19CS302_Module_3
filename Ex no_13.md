# EX 13 To write a C program to read the elements and print only the odd elements in the 2D array.
## DATE:04/05/2025
## AIM:
To write a C program to read the elements and print only the odd elements in the 2D array.

## Algorithm
1. Start. 
2. Define a variables i,j,n,a. 
3. Write program to find n x n matrix. 
4. Read the value using scanf. 
5. Ask the user to make an input 
6. Print out the answer. 
7. End.  

## Program:
```
#include<stdio.h> 
int main() 
{ 
int i,j,n,a[10][10]; 
scanf("%d",&n); 
for(i=0;i<n;i++) 
{ 
for(j=0;j<n;j++) 
{ 
scanf("%d",&a[i][j]); 
} 
}for(i=0;i<n;i++) 
{ 
for(j=0;j<=n;j++) 
{ 
if(a[i][j]%2==1) 
{ 
printf("a[%d][%d] is %d \n",i,j,a[i][j]); 
} 
} 
printf("\n"); 
 SAVEETHA ENGINEERING COLLEGE  
} 
return 0; 
}
```

## Output:
![image](https://github.com/user-attachments/assets/12bdd5e8-faea-469a-9e83-659d3cf42b34)

## Result:
Thus the program was executed and the output was verified successfully.
