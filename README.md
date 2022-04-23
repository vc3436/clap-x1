#include<stdio.h>
int main()
{
int sum=0,n,r,pro=1;
printf("Enter the number:");
scanf("%d",&n);
while(n!=0)
{
r=n%10;
sum=sum+r;
pro=pro*r;
n=n/10;
}
if(pro==sum)
printf("\n Number is spy");
else
printf("\n Number is not spy");
return 0;
}

