#include <stdio.h>

// Function to find smallest divisor (other than 1)
int smallestDivisor(int n) {
    if(n <= 1)
        return -1;  // no valid divisor

    for(int i = 2; i <= n; i++) {
        if(n % i == 0)
            return i;
    }
    return -1;
}

// Function to find GCD using Euclid's Algorithm
int gcd(int a, int b) {
    while(b != 0) {
        int temp = b;
        b = a % b;
        a = temp;
    }
    return a;
}

int main() {
    int a, b;

    printf("Enter two numbers: ");
    scanf("%d %d", &a, &b);

    // Smallest divisors
    int sd1 = smallestDivisor(a);
    int sd2 = smallestDivisor(b);

    if(sd1 != -1)
        printf("Smallest divisor of %d = %d\n", a, sd1);
    else
        printf("No valid smallest divisor for %d\n", a);

    if(sd2 != -1)
        printf("Smallest divisor of %d = %d\n", b, sd2);
    else
        printf("No valid smallest divisor for %d\n", b);

    // GCD
    int result = gcd(a, b);
    printf("GCD of %d and %d = %d\n", a, b, result);

    return 0;
}
