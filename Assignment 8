#include <stdio.h>

int main() {
    int m1, m2, m3, m4, m5;
    float total, percentage;

    
    printf("Enter marks of 5 subjects:\n");
    scanf("%d %d %d %d %d", &m1, &m2, &m3, &m4, &m5);

    
    if (m1 < 40 || m2 < 40 || m3 < 40 || m4 < 40 || m5 < 40) {
        printf("Result: Fail\n");
    } else {
        total = m1 + m2 + m3 + m4 + m5;
        percentage = total / 5;

        printf("Result: Pass\n");
        printf("Percentage = %.2f%%\n", percentage);

        
        if (percentage >= 75) {
            printf("Grade: Distinction\n");
        } else if (percentage >= 60 && percentage < 75) {
            printf("Grade: First Division\n");
        } else if (percentage >= 50 && percentage < 60) {
            printf("Grade: Second Division\n");
        } else if (percentage >= 40 && percentage < 50) {
            printf("Grade: Third Division\n");
        }
    }

    return 0;
}
