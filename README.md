# Swaping-Values
#include<stdio.h>
int main()
{
    int aa;
    int bb;
    int d;

    printf("Enter a value for aa :");
    scanf("%d",&aa);
    printf("Enter a value for bb :");
    scanf("%d",&bb);

    d=aa;
    aa=bb;
    bb=d;

    printf("The value of aa: %d\n", aa);
    printf("The value of bb: %d", bb);

    return 0;
}
