#include <stdio.h>

int main() {
    int n;
    scanf("%d", &n);
    int result = (n > 0) * ((n & (n - 1)) == 0);
    printf("%d\n", result);
    return 0;
}
