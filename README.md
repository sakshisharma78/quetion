#include <stdio.h>
int main()
{
    int sum,i,n;
    
    i=1;
    sum=0;
    printf("enter value of n");
    scanf("%d",&n);
    
     while(i<=n)
    {
    sum=sum+i;
    i++;
    }
    printf("%d",sum);

    
   }

