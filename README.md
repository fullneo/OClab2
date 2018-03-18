# OClab2
#include <stdio.h>

int main(void)
{
    int a, b, c;
    printf("====Discriminant calculator====\n");

    printf("Enter a: ");
    scanf("%d", &a);
    printf("Enter b: ");
    scanf("%d", &b);
    printf("Enter c: ");
    scanf("%d", &c);

    int d = b * b - 4 * a * c;
    printf("D = %d", d);

    if (d < 0) {
      printf(" (equation has no real roots)\n");
    } else if (d == 0) {
      printf(" (equation has single root)\n");
    } else {
      printf(" (equation has two roots)\n");
    }

    return 0;
}



<a href="https://ibb.co/b2MUSx"><img src="https://preview.ibb.co/jdbJLH/2018_03_18_22_54_48.png" alt="2018_03_18_22_54_48" border="0"></a>


<a href="https://ibb.co/mj067x"><img src="https://preview.ibb.co/imXxEc/2.png" alt="2" border="0"></a>
