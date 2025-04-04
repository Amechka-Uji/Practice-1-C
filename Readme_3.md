#include <stdio.h>

int main() {
    int a, b, c;
    scanf("%d %d %d", &a, &b, &c);
    int cnt = (a < 0) + (b < 0) + (c < 0);
    int zero = (a == 0) || (b == 0) || (c == 0);
    int res = (1 - 2 * (cnt % 2)) * !zero;
    printf("%d\n", res);
    return 0;
}
