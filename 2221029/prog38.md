## Program38: To write a program using goto statement
```
#include<stdio.h>
int main()
{
	int a=7;
	begin:
		printf("\n%d",a);
		a++;
		if(a<14)goto begin;
		return 0;
		
}
```
Output:

7

8

9

10

11

12
