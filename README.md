/*# for-loop-to-sum-n-numbers-
/*sum using for loop
#include<stdio.h>
#include<conio.h>
int main()
{
int a,count,sum=0;
printf("enter a integer");
scanf("%d", &a);
/*loop will terminate when num is less than count 
for (count=1;count<=a;++count)
{
sum+=count;
}
printf("sum %d", sum);
return 0;
}
