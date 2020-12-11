# Swapping-two-no

#include<stdio.h>
int main()
{
	int a,b;
	
	printf("Enter a: ");
	scanf("%d",&a);
	
	printf("Enter b: ");
	scanf("%d",&b);
	
	a=a-b;
	b=a+b;
	a=b-a;
	
	printf("Swapping Numbers Are: a=%d,b=%d",a , b);
	return 0;
}
