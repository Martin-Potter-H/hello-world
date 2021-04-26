# hello-world
//I want to do something amazing.

#include<stdio.h>

int MIN(int a, int b)
{	
	int result;
	if (a > b)
		result = b;
	if (a == b)
		printf("最大公约数是%d", a);
	else
		result = a;
	return result;

}

int main() {
	int m, n;
	printf("请输入任意两个整数！\n");
	scanf_s("%d %d", &m, &n);
	int i, c, d, ref, nref;
	for (i = 1; i <= MIN(m, n); i++)
		if (m % i == 0 && n % i==0)
		{
			ref = i;
			
		}	
		else
		{
			nref = i;
		}
	printf("最大公约数是： %d\n", ref);
		
}
