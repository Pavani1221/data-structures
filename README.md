# data-structures-
#include<stdio.h> 
#include<stdlib.h> 
int main(){ 
int a[10][10],b[10][10],mul[10][10],r,c,i,j,k; 
system("cls"); 
printf("S. Naveen Kumar Reddy\n191911494\n "); 
printf("enter the number of row="); 
scanf("%d",&r); 
printf("enter the number of column="); 
scanf("%d",&c); 
printf("enter the first matrix element=\n"); 
for(i=0;i<r;i++)
{ 
for(j=0;j<c;j++) 
{ 
scanf("%d",&a[i][j]); 
} 
} 
printf("enter the second matrix element=\n"); 
for(i=0;i<r;i++) 
{ 
for(j=0;j<c;j++) 
{ 
scanf("%d",&b[i][j]); 
} 
} 
 
printf("multiply of the matrix=\n"); 
for(i=0;i<r;i++) 
{ 
for(j=0;j<c;j++) 
{ 
mul[i][j]=0; 
for(k=0;k<c;k++) 
{ 
mul[i][j]+=a[i][k]*b[k][j]; 
} 
} 
} 
for(i=0;i<r;i++) 
{ 
for(j=0;j<c;j++) 
{ 
printf("%d\t",mul[i][j]); 
} 
printf("\n"); 
} 
return 0; 
}![WhatsApp Image 2022-09-21 at 13 19 32](https://user-images.githubusercontent.com/113250900/191446686-8fd67193-12dd-493c-ad69-62d1485fc321.jpeg)
