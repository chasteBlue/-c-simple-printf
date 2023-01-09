# Simple Printf 
printf in in their respective data type
#include <stdio.h>

int main ()
{
	int price,age,middle_name;
	age= 18;
	char c;
	middle_name = 'M';
	float x1,x2,x3,x4,x5 ;
	x1=19.99;
	x2=100.25;
	x3= 84.75;
	x4=40.24;
	x5=34.80;
	printf("Name: Dynnhiel Chastline %c. Talisayan\n",middle_name);
		printf("Age: %d\n",age);
	printf("Grocery List:\n");
			printf("%d %s %.2f\n",1,"Chippy",x1);
			printf("%d %s %.2f\n",5,"Lucky Me",x2);
			printf("%d %s %.2f\n",2,"Head and Shoulders",x3);
			printf("%d %s %.2f\n",2,"Green Cross Alchohol",x4);
			printf("%d %s %.2f\n",1,"Colgate Toothpaste",x5);
}
