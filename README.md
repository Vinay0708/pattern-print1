# pattern-print1
#include<stdio.h>
int main()
{   int row,space,star,n,x;
   printf("Enter the row you want to print these pattern:\n");
   scanf("%d",&n);
    x=2*n-1;
    for(row=1;row<=n;row++)
    {
        for(space=0;space<=row-1;space++)
        printf(" ");
        for(star=1; star<=x; star++)
        printf("*");
        printf("\n");
         x=x-2;
    }
   return 0;
}
