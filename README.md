# c-code
//A Program By AJAY SAI
// Registration no: RA2111003010096
// Class/sec: CSE-B1
#include <stdio.h>

int main()
{
    int num1, num2;
    int sum, sub, mult, mod;
    float division;
    double c=3.14;

    /*
     * Input two numbers from user
     */
    printf("Enter any two numbers: ");
    scanf("%d%d", &num1, &num2);

    /*
     * Perform all arithmetic operations
     */ 
    sum = num1 + num2;
    sub = num1 - num2;
    mult = num1 * num2;
    division = (float)num1 / num2;
    mod = num1 % num2;

    /*
     * Print result of all arithmetic operations
     */
    printf("SUM = %d\n", sum);
    printf("DIFFERENCE = %d\n", sub);
    printf("PRODUCT = %d\n", mult);
    printf("QUOTIENT = %f\n", division);
    printf("MODULUS = %d\n", mod);
    printf("Hello! I am a double floating point variable."" My value is %lf and my size is %lu bytes.\n",c, sizeof(double));

    return 0; 
}
