
#include <stdio.h>

int main() {
    int N;

    // Take input from the user
    printf("Enter a number: ");
    scanf("%d", &N);

    // Print the number
    printf("You entered: %d\n", N);

    return 0;
}


#include <stdio.h>

int main() {
    int num1, num2, sum;

    // Take input from the user
    printf("Enter first integer: ");
    scanf("%d", &num1);
    
    printf("Enter second integer: ");
    scanf("%d", &num2);

    // Calculate the sum
    sum = num1 + num2;

    // Print the sum
    printf("The sum is: %d\n", sum);

    return 0;
}

//To Print the First 3 multiples of the given number "N"

#include<stdio.h>
int main(){
     int N;
     scanf("%d",&N);
     printf("%d %d %d",N,N*2,N*3);
     return 0;
}

 //To Find the length of its circumference.

#include<stdio.h>
int main(){
      const PI =3.14;
      double radius,result;

      scanf("%lf",&radius);
      if(radius>=0){
      result =2*PI*radius*radius;
      printf("%.2lf",result);
      }
      return 0;
}

//To Convert this into  Meters and  Centi-Metres.

#include<stdio.h>
int main(){
    int kilometer,centi,meter;
    scanf("%d",&kilometer);

    kilometer *=1000;
    centi = kilometer*100;
    printf("%d %d %d",kilometer,centi,meter); 

    return 0;
}

//To print a*b mod c.

#include<stdio.h>

int main(){

    int a,b,c;

    scanf("%d %d %d",a,b,c);

    print("%d",a*b%c);
    return 0;
}

//To find the sum and average of the three given integers.

#include<stdio.h>
int main(){
      int a,b,c;
      float sum;
      scanf("%d %d %d",&a,&b,&c);
      sum =a+b+c;
    print("The sum is :%.0f",sum);
    printf("The average is:%f",sum/3);
    return 0;
}

//Find the Simple interest and print it up to two decimal places.

#include<stdio.h>
int main(){
    double simipleinterest,principalamount,interestrate,time;
    scanf("%lf %lf %.0lf",&principalamount,&interestrate,&time);

    simipleinterest = (principalamount*time*interestrate)/100;

    printf("The simple interest is:%.2lf",simipleinterest);

    return 0;
}

//Write a program to convert this into Fahrenheit.

#include<stdio.h>
int main(){
   int celcius;
   double Fahrenheit;
  Fahrenheit = ((5/9*celcius)-32);  
   printf("The conversion  is:%.2lf",Fahrenheit);
   return 0;
}

//Print a single integer, the maximum number of customers Chef can serve in Y minutes

#include<stdio.h>
int main(){
    int X,Y,R;
    scanf("%d %d",&X,&Y);
    R = X*Y;
  printf("%d",R);
   return 0;
    }

    //Output on a single line the total number of courses in the section.

#include<stdio.h>
int main(){

     int N,C;
     scanf("%d",&C);
     C = N*2;
     printf("%d",C);
    return 0;
}

//Write a program to read an uppercase character from standard input and to convert it
//into its corresponding lowercase character.

#include <stdio.h>

int main() {
    char uppercase, lowercase;

    printf("Enter an uppercase character: ");
    scanf("%c", &uppercase);
 if (uppercase >= 'A' && uppercase <= 'Z') {
        // Converting uppercase to lowercase
        lowercase = uppercase + ('a' - 'A'); // Difference between ASCII values of 'a' and 'A'
        printf("The lowercase equivalent of %c is %c\n", uppercase, lowercase);
    } else {
        printf("The entered character is not an uppercase letter.\n");
    }

    return 0;
}

#include <stdio.h>

int main() {
    int days, hours, minutes, seconds;
    int totalSeconds;


    printf("Enter the number of days: ");
    scanf("%d", &days);

    printf("Enter the number of hours: ");
    scanf("%d", &hours);

    printf("Enter the number of minutes: ");
    scanf("%d", &minutes);

    printf("Enter the number of seconds: ");
    scanf("%d", &seconds);


   //Write a C program to read two integer values and to print the results of various arithmetic
/*
#include <stdio.h>

int main() {
    int num1, num2;


    printf("Enter the first integer: ");
    scanf("%d", &num1);

    printf("Enter the second integer: ");
    scanf("%d", &num2);


    printf("\nResults of Arithmetic Operations:\n");
    
  
    printf("%d + %d = %d\n", num1, num2, num1 + num2);

    printf("%d - %d = %d\n", num1, num2, num1 - num2);
    

    printf("%d * %d = %d\n", num1, num2, num1 * num2);
    
  
    if (num2 != 0) {
        printf("%d / %d = %d\n", num1, num2, num1 / num2);
    } else {
        printf("Division by zero is not allowed.\n");
    }
  
    if (num2 != 0) {
        printf("%d %% %d = %d\n)
        return 0;
        }


     
//18.Write a program given original cost and net price then calculate the percent of gst

/*
#include <stdio.h>

int main() {
    float originalCost, netPrice, gstPercentage;


    printf("Enter the original cost: ");
    scanf("%f", &originalCost);

    printf("Enter the net price: ");
    scanf("%f", &netPrice);


    gstPercentage = ((netPrice - originalCost) / originalCost) * 100;

  
    printf("The GST percentage is: %.2f%%\n", gstPercentage);

    return 0;
}

*/



//Write a program given the side of a square then find the area of a Circumscribed circle around it. Formula is pi*(a/2)2
/*
#include <stdio.h>
#define PI 3.14159  // Define the value of pi

int main() {
    float side, radius, area;

   
    printf("Enter the side length of the square: ");
    scanf("%f", &side);

    radius = side / 2;


    area = PI * radius * radius;


    printf("The area of the circumscribed circle is: %.2f\n", area);

    return 0;
}

*/


/*You are given a number n, the task is to find nth octagonal number. An octagonal number is the figure number that represent octagonal. Octagonal numbers can be
formed by placing triangular numbers on the four sides of a square. Octagonal number is
calculated by using the formula (3n2 – 2n).
*/

/*
#include <stdio.h>

int main() {
    int n, octagonalNumber;

   
    printf("Enter the value of n: ");
    scanf("%d", &n);

  
    octagonalNumber = 3 * n * n - 2 * n;

   
    printf("The %dth octagonal number is: %d\n", n, octagonalNumber);

    return 0;
}

*/

//Write a program given the edge of the dodecahedron calculate its Volume. Volume is the

/*
#include <stdio.h>
#include <math.h>  // For the sqrt() function and pow() function

int main() {
    float edge, volume;

   
    printf("Enter the length of the edge of the dodecahedron: ");
    scanf("%f", &edge);

    // Calculating the volume using the formula: Volume = (15 + 7*sqrt(5)) / 4 * e^3
    volume = ((15 + 7 * sqrt(5)) / 4) * pow(edge, 3);

   
    printf("The volume of the dodecahedron is: %.2f cubic units\n", volume);

    return 0;
}

*/

//to print the profit of the agency

/*
#include <stdio.h>

int main() {
    int X;  // Number of copies sold
    float A, B, totalRevenue, totalCost, profit;
    const float fixedCost = 100.0;  // Fixed cost of Rs.100 per Sunday


    printf("Enter the number of copies sold: ");
    scanf("%d", &X);

    printf("Enter the selling price per copy (Rs): ");
    scanf("%f", &A);

    printf("Enter the cost price per copy to the agency (Rs): ");
    scanf("%f", &B);


    totalRevenue = X * A;                        // Revenue = X * A
    totalCost = (X * B) + fixedCost;             // Cost = (X * B) + fixed cost


    profit = totalRevenue - totalCost;


    printf("\nTotal revenue: Rs. %.2f\n", totalRevenue);
    printf("Total cost (including fixed costs): Rs. %.2f\n", totalCost);

    if (profit > 0) {
        printf("Profit: Rs. %.2f\n", profit);
    } else if (profit < 0) {
        printf("Loss: Rs. %.2f\n", -profit);  // Show loss as a positive value
    } else {
        printf("No profit, no loss.\n");
    }

    return 0;
}


//To Write a program given the edge of the dodecahedron calculate its surface area.


/*
#include <stdio.h>
#include <math.h>  // For sqrt() function

int main() {
    float a, surfaceArea;
    printf("Enter the length of the edge of the dodecahedron: ");
    scanf("%f", &a);

   
    surfaceArea = 3 * sqrt(25 + 10 * sqrt(5)) * a * a;

   
    printf("Surface Area of the dodecahedron:%f",surfaceArea);

*/

//To Write a program to calculate factorial without using any loop or recursion.

/*
#include <stdio.h>
#include <math.h>  // For sqrt() and pow() functions

int main() {
    int n;
    double factorial;
    printf("Enter a non-negative integer to calculate its factorial: ");
    scanf("%d", &n);

   
    if (n < 0) {
        printf("Factorial is not defined for negative integers.\n");
        return 1;  // Exit with an error code
    }

    // Using Stirling's approximation to calculate factorial
    if (n == 0 || n == 1) {
        factorial = 1;  // 0! and 1! are both equal to 1
    } else {
        factorial = sqrt(2 * M_PI * n) * pow(n / exp(1), n);
    }

   
    printf("Approximate value of %d! using Stirling's approximation: %.3f\n", n, factorial);

    return 0;
}

// To Write a program given first term (a), common ratio (r) and a integer N of the Geometric
/*
#include <stdio.h>
#include <math.h>

int main() {
    double a, r, N, nth_term;
    printf("Enter the first term (a): ");
    scanf("%lf", &a);

    printf("Enter the common ratio (r): ");
    scanf("%lf", &r);

    printf("Enter the term number (N): ");
    scanf("%lf", &N);

    // Calculating the Nth term using the formula: T_n = a * r^(N-1)
    nth_term = a * pow(r, N - 1);

    // Displaying the result
    printf("The %d-th term of the Geometric Progression is: %.3lf\n", (int)N, nth_term);

    return 0;
}

*/


//Write a C program find if a given number is odd without using % operator.
/*
#include <stdio.h>

int main() {
    int num;

    // Read a number from the user
    printf("Enter a number: ");
    scanf("%d", &num);

    if (num & 1) {
        printf("%d is an odd number.\n", num);
    } else {
        printf("%d is an even number.\n", num);
    }

    return 0;
}


//Write a program to print the total number of matchstick required to form pyramid of matchsticks of X floors.

/*
#include <stdio.h>

int main() {
    int X;
    int totalMatchsticks;

  
    printf("Enter the number of floors in the pyramid: ");
    scanf("%d", &X);

 
    totalMatchsticks = X * X;  // X^2 gives the total matchsticks needed

    
    printf("Total number of matchsticks required to form a pyramid of %d floors: %d\n", X, totalMatchsticks);

    return 0;
}
