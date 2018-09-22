#include <stdio.h>
#include <math.h>

int main()
{
	float Height;
	float Base;
	
	printf("Triangle");
	
	printf("\nEnter Height : ");
	scanf("%f", &Height);
	
	printf("Enter Base : ");
	scanf("%f", &Base);
	
	printf("\nArea of Triangle = %.2f\n", 0.5*Base*Height);
	
	printf("\n----------------------------------");
	float Radius;
	
	printf("\nCircle");
	printf("\nEnter Radius : ");
	scanf("%f", &Radius);
	
	printf("\nArea of Triangle = %.2f",M_PI*Radius*Radius);
	
	printf("\n----------------------------------");
	float Side;
	
	printf("\nSquare");
	
	printf("\nEnter Side : ");
	scanf("%f", &Side);
	
	printf("\nArea of Triangle = %.2f\n", Side*Side);
	
	return 0;
}
