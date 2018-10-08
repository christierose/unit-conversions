#include<stdio.h>

int main()
{
  double dk, df;

printf("Enter degrees Kelvin to convert to degrees Fahrenheit:\n");
scanf("%lf", &dk);

if (dk<0)
 printf("Enter positive values\n");
else
 {
 df=32+((dk-273)*1.8);;
 printf("%5.2f degrees Kelvin is %5.3f degrees Fahrenheit\n", dk, df);
 }
return 0;
}

