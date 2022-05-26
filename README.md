#include<stdio.h>
int main()
{
	int n;
	printf("Enter marks:");
	scanf("%d",&n);
	if(n>=85)
	{
	printf("Grade A");
    }
	else if(n>=70)
	{printf("Grade B");
	}
	
	else if(n>=55)
	{
	printf("Grade c");
	}
	else if(n>=40)
	{
	printf("Grade D");
	}
	else
	{printf("Grade F");
	}
	return 0;
	}
