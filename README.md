#include<stdio.h>
main()
{
int a,b,c;
printf("enter two numbers");
scanf("%d%d",&a,&b);
printf("before swapping first number=%d, second number=%d",a,b);
c=a;
a=b;
b=c;
printf("after swapping first number=%d, second number=%d",a,b);
}
