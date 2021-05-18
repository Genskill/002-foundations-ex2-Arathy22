#include <stdio.h>
#include <cs50.h>
int main(void){
int a=get_int("Enter type of pattern (1 or 2) ");
if(a==1){
int ht=get_int("Number of rows: ");
for(int i=1;i<=ht;i++)
{
	for(int j=ht; j>=i;j--)
	{
		printf("#");
		}
		printf("\n");
	}
}
else
{
int ht=get_int("Number of rows: ");
	for(int m=1;m<=ht;m++)
{
	for(int n=1; n<=m;n++)
	{
		printf("#");
		}
		printf("\n");
	}
	}
int x=get_int("Side 1 : ");
int x=get_int("Side 1 : ");
int x=get_int("Side 1 : ");
if(x*x+y*y==z*z)
{
	printf("Yes");
	}
else
{
	printf("No");
	}
}
