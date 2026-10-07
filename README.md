//increment.c
//this is the code for the increment of a value in C
#include<stdio.h>
int main()
{
    int x=5;
    int a=x++;
    int b=++x;
    printf("%d %d %d",x,a,b);
    return 0;
}
