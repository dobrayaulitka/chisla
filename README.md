#include <stdio.h>

main()
{
    int a, b, c = 0, d = 1, e = 0;

    printf("Input number: ");
    scanf("%i", &a);

        for (; a > d; d *= 10 ) e++ ;


        while ( e-- ){
            b = a / ( d / 10 );
            d /= 10;
            c++;
            b  %= 10;
            printf("\n%i figure is %i", c, b);
        }

    return 0;
}
