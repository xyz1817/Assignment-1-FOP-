#include <stdio.h>
#include <math.h>

// to check prime
int isPrime(int n) {
    if(n <= 1)
        return 0;
    for(int i = 2; i <= n/2; i++) {
        if(n % i == 0)
            return 0;
    }
    return 1;
}

// factorial
long long factorial(int n) {
    long long fact = 1;
    for(int i = 1; i <= n; i++) {
        fact *= i;
    }
    return fact;
}

int main() {
    int n;
    
    printf("Enter a number: ");
    scanf("%d", &n);

    // Square root
    if(n >= 0)
        printf("Square root = %.2f\n", sqrt(n));
    else
        printf("Square root not defined for negative numbers\n");

    // Square
    printf("Square = %d\n", n * n);

    // Cube
    printf("Cube = %d\n", n * n * n);

    // Prime check
    if(isPrime(n))
        printf("It is a Prime number\n");
    else
        printf("It is NOT a Prime number\n");

    // Factorial
    if(n >= 0)
        printf("Factorial = %lld\n", factorial(n));
    else
        printf("Factorial not defined for negative numbers\n");

    // Prime factors
    printf("Prime factors: ");
    int temp = n;

    for(int i = 2; i <= temp; i++) {
        while(temp % i == 0) {
            printf("%d ", i);
            temp = temp / i;
        }
    }

    if(n <= 1)
        printf("None");

    printf("\n");

    return 0;
}
