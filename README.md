#include<stdio.h>
int main(void)
{
	int a,b,t;
	scanf("%d%d",&a,&b);
	if(a<b)
	{
		t=a;
		a=b;
		b=t;	
	}
	while(a%b)
	{
		t=a%b;
		a=b;
		b=t;
	}
	printf("最大公约数%d",b);
	return 0;
 } 
