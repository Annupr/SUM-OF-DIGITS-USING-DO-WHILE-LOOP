# SUM-OF-DIGITS-USING-DO-WHILE-LOOP
Here is the program to find sum of number entered untill 0 is entered using do while loop
#include<stdio.h>
int main()
{
	int n=0,i,sum=0;
		
		printf("\nEnter a number:");
		do{
			scanf("%d",&n);
			sum=sum+n;
			
		}
		while(n!=0);
		printf("Sum=%d",sum);
		return 0;
}
