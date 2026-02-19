#include <stdio.h>
int main() {
    int i, j, space;
    int height = 6;

    for(space = 1; space <= height; space++)
        printf(" ");
    printf("*\n");

    for(i = 1; i <= height; i++) {
        for(space = 1; space <= height - i; space++)
            printf(" ");

        for(j = 1; j <= (2*i - 1); j++)
            printf("*");

        printf("\n");
    }

    for(i = 1; i <= 2; i++) {
        for(space = 1; space <= height - 1; space++)
            printf(" ");
        printf("***\n");
    }

    return 0;
}
