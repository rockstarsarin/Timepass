#include<stdio.h>
int main()
{
int d,n,s=0;
printf("enter a 4 digit no.");
scanf("%d",&n);
if ( n>999 && n<10000)
{
d=n%10;
s=s+d;
n=n/10;
d=n%10;
s=s+d;
n=n/10;
d=n%10;
s=s+d;
n=n/10;
d=n%10;
s=s+d;
n=n/10;
d=n%10;
s=s+d;
n=n/10;
printf("%d",s);
}
else 
printf("invalid input");
}

