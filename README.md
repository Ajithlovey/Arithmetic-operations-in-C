# Arithmetic-operations-in-C
#include <stdio.h>

int main() {
    int a = 10, b = 5;
    int sum, difference, product, quotient, remainder;

    sum = a + b;            // Addition
    difference = a - b;     // Subtraction
    product = a * b;        // Multiplication
    quotient = a / b;       // Division
    remainder = a % b;      // Modulus (remainder of division)

    printf("Sum: %d\n", sum);
    printf("Difference: %d\n", difference);
    printf("Product: %d\n", product);
    printf("Quotient: %d\n", quotient);
    printf("Remainder: %d\n", remainder);

    return 0;
}
