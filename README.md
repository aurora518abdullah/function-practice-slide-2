//even odd

#include<stdio.h>

int isEven(int n)
{
    if(n%2==0)
    {
         return 1;
    }
    else {
        return 0;
    }
}
int main()

{
    int n;
    printf("Enter the number: ");
    scanf("%d",&n);
    if (isEven(n))
        printf("Even\n");
    else
        printf("Odd\n");

return 0;
}

