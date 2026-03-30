#include <stdio.h>
int fact(int n)
{
    if(n==1 || n==0)
    {
        return 1;
    }
    else
    {
        return n*fact(n-1);
    }
}
void main()
{
    int n;
    printf("Enter a number:");
    scanf("%d",&n);
    if(n<0)
    {
        printf("Factorial for negative no. is not possible");
    }
    else
    {
        printf("Factorial of number:%d",fact(n));
    }
}
