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

7-)

#include <stdio.h> 
 
int main(int argc, char** argv) { 
	printf("1: 1\n2: 4\n3: 9\n4: 16\n5: 25\n6: 36\n7: 49\n8: 64\n9: 81\n10: 100"); 
	return 0; 
} 

8-)

#include<stdio.h>
int main()
{
//fill the code
	int start, end;
	scanf(“%d”,&start);
	scanf(“%d”,&end);
	int i, sum = 0;
	for(i = start; i <= end; i++)
	{
		sum = sum + i;
	}
	printf(“%d”,sum);
	return 0;
}

9-)

#include<stdio.h>  
int main()  
{  
int i;  
printf("The numbers divisible by 3 and 5 are: ");  
for(i=1; i<=100 ;i++)  
{  
 if (i%15==0) 
 { 
 printf("hello %d\n", i); 
 } 
}  
return 0; 
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

11-)

#include <stdio.h>
void main()
{       
    int i,n,sum=0;
	float avg;
	printf("Input the 10 numbers : \n");
	for (i=1;i<=10;i++)
	{
                printf("Number-%d :",i);

		scanf("%d",&n);
		sum +=n;
	}
	avg=sum/10.0;
	printf("The sum of 10 no is : %d\nThe Average is : %f\n",sum,avg);
 
}

12-)

#include <stdio.h>  
  int main () {  
        int n, i, j, sum = 0;  
        n=100;  
        for (i = 1; i <= n; i+5) {  
                for (j = 1; j <= i/2; j++) {  
                        if (i % j == 0) {  
                                sum = sum + j;  
                        }  
                }  
  
                if (sum > i)  
                        printf("%d ", i);  
                sum = 0;  
        }  
        printf("\n");  
        return 0;  
  }  

13-)

#include
void main()
{
    int i;
    for(i=1; i<=10;  i++)
    {
        printf("6 * %d = %d\n",i,6*i);
        
    }
   
}

14-)

#include <stdio.h>
int main() {
    int n, i;
    unsigned long long fact = 1;
    printf("Enter an integer: ");
    scanf("%d", &n);

    // shows error if the user enters a negative integer
    if (n < 0)
        printf("Error! Factorial of a negative number doesn't exist.");
    else {
        for (i = 1; i <= n; ++i) {
            fact *= i;
        }
        printf("Factorial of %d = %llu", n, fact);
    }

    return 0;
}

15-)

#include <stdio.h>

int main()
{
    int i, start, end;

    /* Input start and end limit from user */
    printf("Enter starting value: ");
    scanf("%d", &start);
    printf("Enter end value: ");
    scanf("%d", &end);

    /*
     * Run loop from 'start' to 'end' and 
     * decrement by 1 in each iteration
     */ 
    for(i=start; i>=end; i--)
    {
        printf("%d\n", i);
    }

    return 0;
}

16-)

#include <stdio.h> 
 
int sumOfEven(int n) 
{ 
	int s = 1000; 
	int c = 2; 
	while(c<n) 
	{ 
		s = s+c; 
		c = c+2; 
	} 
	return s; 
} 
 
int main() 
{ 
	int n; 
	printf("Enter the limit:2000 "); 
	scanf("%d",&n); 
	printf("\nsum: %d", sumOfEven(n)); 
	return 0; 
} 

18-)

#include<stdio.h>    
#include<stdlib.h>  
int main(){  
int a[10],n,i;    
system ("cls");  
printf("Enter the number to convert: ");    
scanf("%d",&n);    
for(i=0;n>0;i++)    
{    
a[i]=n%2;    
n=n/2;    
}    
printf("\nBinary of Given Number is=");    
for(i=i-1;i>=0;i--)    
{    
printf("%d",a[i]);    
}    
return 0;  
}  

19-)

#include <stdio.h>
int main() {

  int n, i, range;
  printf("Enter an integer: ");
  scanf("%d", &n);

  // prompt user for positive range
  do {
    printf("Enter the range (positive integer): ");
    scanf("%d", &range);
  } while (range <= 0);

  for (i = 1; i <= range; ++i) {
    printf("%d * %d = %d \n", n, i, n * i);
  }

  return 0;
}

20-)

#include <stdio.h>
int main() {
  long long n;
  int count = 0;
  printf("Enter an integer: ");
  scanf("%lld", &n);
 
  // iterate at least once, then until n becomes 0
  // remove last digit from n in each iteration
  // increase count by 1 in each iteration
  do {
    n /= 10;
    ++count;
  } while (n != 0);

  printf("Number of digits: %d", count);
}

21-)

#include <stdio.h>
int main()
{
    int n, sum=0, firstDigit, lastDigit;
    printf("Enter number = ");
    scanf("%d", &n);
    // Find last digit of a number
    lastDigit = n % 10;
    //Find the first digit by dividing n by 10 until n greater then 10
    while(n >= 10)
    {
        n = n / 10;
    }
    firstDigit = n;
    printf("first digit = %d and last digit = %d\n\n", firstDigit,lastDigit);
    return 0;
}

22-)

#include <stdio.h>
#include <math.h>
int main()
{
    int n,firstDigit, lastDigit,digits, swappedNum;
    printf("Enter number = ");
    scanf("%d", &n);
    //Find last digit of a number
    lastDigit = n % 10;
    //Find total number of digits - 1
    digits    = (int)log10(n);
    //Find first digit
    firstDigit = (int) (n / pow(10, digits));
    swappedNum  = lastDigit;
    swappedNum *= (int) round(pow(10, digits));
    swappedNum += n % ((int)round(pow(10, digits)));
    swappedNum -= lastDigit;
    swappedNum += firstDigit;
    printf("Number after swapping first and last digit: %d", swappedNum);
    return 0;
}

23-)

#include <stdio.h>
int main() {
  int n, reversed = 0, remainder, original;
    printf("Enter an integer: ");
    scanf("%d", &n);
    original = n;

    // reversed integer is stored in reversed variable
    while (n != 0) {
        remainder = n % 10;
        reversed = reversed * 10 + remainder;
        n /= 10;
    }

    // palindrome if orignal and reversed are equal
    if (original == reversed)
        printf("%d is a palindrome.", original);
    else
        printf("%d is not a palindrome.", original);

    return 0;
}

24-)

#include <stdio.h>
#define BASE 10 /* Constant */

int main()
{
    long long num, n;
    int i, lastDigit;
    int freq[BASE];

    /* Input number from user */
    printf("Enter any number: ");
    scanf("%lld", &num);

    /* Initialize frequency array with 0 */
    for(i=0; i<BASE; i++)
    {
        freq[i] = 0;
    }

    /* Copy the value of 'num' to 'n' */
    n = num; 

    /* Run till 'n' is not equal to zero */
    while(n != 0)
    {
        /* Get last digit */
        lastDigit = n % 10;

        /* Remove last digit */
        n /= 10;

        /* Increment frequency array */
        freq[lastDigit]++;
    }

    /* Print frequency of each digit */
    printf("Frequency of each digit in %lld is: \n", num);
    for(i=0; i<BASE; i++)
    {
        printf("Frequency of %d = %d\n", i, freq[i]);
    }

    return 0;
}

25-)

#include <stdio.h>

int main()
{
    int i, num1, num2, min, hcf=1;

    /* Input two numbers from user */
    printf("Enter any two numbers to find HCF: ");
    scanf("%d%d", &num1, &num2);

    /* Find minimum between two numbers */
    min = (num1<num2) ? num1 : num2;

    for(i=1; i<=min; i++)
    {
        /* If i is factor of both number */
        if(num1%i==0 && num2%i==0)
        {
            hcf = i;
        }
    }

    printf("HCF of %d and %d = %d\n", num1, num2, hcf);

    return 0;
}
