#include <stdio.h>

int main() {
    int a, b, r;

    printf("Entrer deux entiers : ");
    scanf("%d %d", &a, &b);

    while (b != 0) {
        r = a % b;
        a = b;
        b = r;
    }

    printf("Le PGCD est : %d\n", a);

    return 0;
}
