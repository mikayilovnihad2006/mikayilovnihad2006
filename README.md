#include <stdio.h>

int main() {
    printf("Tek Sayılar:\n");
    for (int i = 1; i <= 100; i += 2) {
        printf("%d ", i);
    }

    printf("\nÇift Sayılar:\n");
    for (int i = 2; i <= 100; i += 2) {
        printf("%d ", i);
    }

    return 0;

