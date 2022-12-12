# homework3


1-)

#include <stdio.h>
int main() {

  int num1, num2, sum;

  printf("Enter two integers: ");
  //Storing user input into variable num1 & num2
  scanf("%d %d", &num1, &num2);

  // Adding two input numbers
  sum = num1 + num2;

  printf("Sum of %d and %d is: %d", num1, num2, sum);
  return 0;
}

2-)

#include <stdio.h>
int main(){
   int r = 8;
   float area = (3.14)*r*r;
   printf("The area of the circle is %d",area);
   return 0;
}

3-)


#include <stdio.h>
#include <math.h>

int main(void)
{
    int sayi;
    printf("Bir sayi giriniz : ");
    scanf("%i",&sayi);
    if( sayi % 2 == 0 )
	printf("\n%i bir cift sayidir.", sayi);
    else
	printf("\n%i bir tek sayidir.", sayi);
    return 0;
}

4-)

#include <stdio.h>
#include <math.h>

int main(void)
{         
    int sayi;
    printf(Bir sayi giriniz : ");
    scanf("%i",&sayi),
    if( sayi < 0 )
             printf("\n<i donma noktasındadır.", sayi);
    else
             printf("\n<i donma naktasında değildir.", sayi);
    return 0;
}

5-)

#include <stdio.h>

int main()
{
    float celsius, fahrenheit;

    /* Input temperature in celsius */
    printf("Enter temperature in Celsius: ");
    scanf("%f", &celsius);

    /* celsius to fahrenheit conversion formula */
    fahrenheit = (celsius * 9 / 5) + 32;

    printf("%.2f Celsius = %.2f Fahrenheit", celsius, fahrenheit);

    return 0;
}

6-)

#include 
//#include 

void main() {

  float cm;
  float feet;
  

//    clrscr();

	printf(" Program to convert Feet to Centimeter:  ");

	printf("\n\n Enter Length in Feet  : ");
	scanf("%f", &feet);
    
    cm = (feet/3.26)*100;
    
    printf("\n\n %f Feet in Meter = %f  \n",feet,cm);

}


10-)

#include <stdio.h>

int main() {

  double n1, n2, n3;

  printf("Enter three different numbers: ");
  scanf("%lf %lf %lf", &n1, &n2, &n3);

  // if n1 is greater than both n2 and n3, n1 is the largest
  if (n1 >= n2 && n1 >= n3)
    printf("%.2f is the largest number.", n1);

  // if n2 is greater than both n1 and n3, n2 is the largest
  if (n2 >= n1 && n2 >= n3)
    printf("%.2f is the largest number.", n2);

  // if n3 is greater than both n1 and n2, n3 is the largest
  if (n3 >= n1 && n3 >= n2)
    printf("%.2f is the largest number.", n3);

  return 0;
}

