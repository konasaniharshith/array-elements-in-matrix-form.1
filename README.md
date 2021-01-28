# array-elements-in-matrix-form.1
arrays
#include<stdio.h>
int main()
{
int a[10][10]={1,2,3,4,5,6,7,8,9},i,j,k,g,h;
for(k=0;k<10;k++)
{
scanf("%d,"&a[k])
}
for(i=0;i<3;i++)
{
 for(j=0;j<3;j++)
 {
   printf("%d ",a[i][j]);
 }
  printf("\n");
 }
 g=a[0][0]+a[1][1]+a[2][2];
 h=a[0][2]+a[1][2]+a[2][0];
 printf("sum of principle diagonal elements is : %d %d",g,h);
 return 0;
 }
  
  
