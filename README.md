// C Program to Swap Two Numbers using a Temporary Variable
#include <stdio.h>

int main() {
    int a = 5, b = 10, temp;
    printf("Before swapping: a = %d, b = %d\n", a, b);

    // Swapping values of a and  b
    temp = a;
    a = b;
    b = temp;

    printf("After swapping: a = %d, b = %d\n", a, b);
    return 0;
}
# Swap-Two-Numbers
