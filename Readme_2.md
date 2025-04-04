#include <stdio.h>

int main() {
    int num;
    scanf("%d", &num);
    printf("%s\n", &"Even\0Odd"[num % 2 * 5]);
    return 0;
}
