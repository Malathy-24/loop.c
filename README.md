#include<stdio.h>
int main()
{
   int n,i,j;
   printf("enter number of rows:");
   scanf("%d",&n);
   for(i=1;i<=n;i++)
   {
      for(j=i;j>=1;j--)
      {
         printf("%d",j%2);
      }
      printf("\n");
      }
      retrun 0;
  }    
