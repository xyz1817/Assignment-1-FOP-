#include <stdio.h>

//factorial
long long factorial(int n) {
    long long fact = 1;
    int i;
    for(i = 1; i <= n; i++) {
        fact *= i;
    }
    return fact;
}

int main() {
    int choice;
    double x, y, result;
    int n, i;

    printf("===== Simple Calculator =====\n");
    printf("1. Addition (x + y)\n");
    printf("2. Subtraction (x - y)\n");
    printf("3. Multiplication (x * y)\n");
    printf("4. Division (x / y)\n");
    printf("5. Power (x^y)\n");
    printf("6. Factorial (x!)\n");

    printf("Enter your choice: ");
    scanf("%d", &choice);

    switch(choice) {
        case 1:
            printf("Enter two numbers: ");
            scanf("%lf %lf", &x, &y);
            result = x + y;
            printf("Result = %.2lf\n", result);
            break;

        case 2:
            printf("Enter two numbers: ");
            scanf("%lf %lf", &x, &y);
            result = x - y;
            printf("Result = %.2lf\n", result);
            break;

        case 3:
            printf("Enter two numbers: ");
            scanf("%lf %lf", &x, &y);
            result = x * y;
            printf("Result = %.2lf\n", result);
            break;

        case 4:
            printf("Enter two numbers: ");
            scanf("%lf %lf", &x, &y);
            if(y != 0)
                printf("Result = %.2lf\n", x / y);
            else
                printf("Error! Division by zero.\n");
            break;

        case 5:
            printf("Enter base and exponent: ");
            scanf("%lf %lf", &x, &y);
            result = 1;
            for(i = 1; i <= (int)y; i++) {
                result *= x;
            }
            printf("Result = %.2lf\n", result);
            break;

        case 6:
            printf("Enter a number: ");
            scanf("%d", &n);
            if(n < 0)
                printf("Factorial not defined for negative numbers.\n");
            else
                printf("Factorial = %lld\n", factorial(n));
            break;

        default:
            printf("Invalid choice!\n");
    }

    return 0;
}
