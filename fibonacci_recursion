#include <stdio.h>

long long int fib(int n)
{
	if(n<2)
		return n;
	else
		return fib(n-1)+fib(n-2);
}

int main()
{
	int n,i;
	printf("Enter number of terms: ");
	scanf("%d",&n);
	printf("fibonacci series: ");
	for(i=1;i<=n;i++)
	{
		printf("%lld, ",fib(i));
	}
	printf("\n\n");
	return 0;
}
