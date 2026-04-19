#include <stdio.h>

// Function to calculate factorial
long long fact(int n) {
    long long f = 1;
    for(int i = 1; i <= n; i++)
        f *= i;
    return f;
}

int main() {
    int n;
    float x, sum = 0;
    int sign = 1;

    printf("Enter value of x (in radians): ");
    scanf("%f", &x);

    printf("Enter number of terms: ");
    scanf("%d", &n);

    for(int i = 1; i <= n; i++) {
        int power = 2*i - 1;   // 1,3,5,7...
        float term = (sign * (pow(x, power) / fact(power)));
        sum += term;
        sign = -sign; // alternate sign
    }

    printf("Sum of sine series = %f\n", sum);

    return 0;
}
