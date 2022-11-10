//# Absolute-value.c//
#include<stdio.h>
int main ()
{
    int n;
    printf("Enter a number");
    scanf("%d",&n);
    if(n<0)
    n=-n;
    {
        printf("absolute value=%d",n);
    }
    return 0;
}
