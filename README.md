#include <stdio.h>
 
void main()
{
    double f, c;
     
    printf("\n Nhap do F:");
    scanf("%lf", &f);
     
    if(f != 32.0)
    {
        c = 5.0 * (f - 32.0)/9.0;
        printf("C = %5.2lf", c);
         
    }
    getch();
}
