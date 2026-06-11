#include <stdio.h>

int main()
{
    int i = 1, num, cube;

    printf("Enter a positive num: ");
    scanf("%d", &num);

    while (i <= num)
    {
        cube= (i * i * i);
        i++;
         printf("Number is: %d and cube of the  %d is : %d \n",i,i,cube);
    }


    return 0;
}
