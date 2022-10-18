#include<stdio.h>
int main()
{
	int a,b=0;
	printf("Enter the amount :");
	scanf("%d",&a);
	if(a>500){
		b=a/500;
		a=a%500;
		printf("number of 500(s)\n:%d",b);
	}
	if(a>=100){
		b=a/100;
		a=a%100;
		printf("number of 100(s)\n:%d",b);
	}
	if(a>=50){
		b=a/50;
		a=a%50;
		printf("number of 50(s)\n:%d",b);
	}
	if(a>=20){
		b=a/20;
		a=a%20;
		printf("number of 20(s)\n:%d",b);
	}
	if(a>=10){
		b=a/10;
		a=a%10;
		printf("number of 10(s)\n:%d",b);
	}
	if(a>=5){
		b=a/5;
		a=a%5;
		printf("number of 5(s)\n:%d",b);
	}
	if(a>=2){
		b=a/2;
		a=a%2;
		printf("number of 2(s)\n:%d",b);
	}
	if(a>=1){
		b=a/1;
		a=a%1;
		printf("number of 1(s)\n:%d",b);
	}
	return 0;
}
