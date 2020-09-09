#include <stdio.h>

int fib(int n)
{
	int f[n+1];
	f[0] = 0;
	f[1] = 1;
	for(int i=2;i<=n;i++)
	{
		f[i] = f[i-1] + f[i-2];
	}
	return f[n];
}
int main()
{ 
	int i,n;
	printf("Enter no of terms: ");
	scanf("%d",&n);
	printf("Fibonacci series: ");
	for(i=1;i<=n;i++)
		printf("%d, ",fib(i));
	printf("\n\n");
	return 0;
}
