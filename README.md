# Assignments-
The code written calculates the sum of all even numbers from 1 to N
#include<stdio.h>

int main()
{
    int count, num, sum = 0;

    printf("Enter the limit\n");
    scanf("%d", &num);

    printf("Even numbers from 1 To %d are:\n", num);
    for(count = 1; count <= num; count++)
    {
        if(count % 2 == 0)
        {
            printf("%d\n", count);
            sum = sum + count;
        }

    }

    printf("Sum of even numbers from 1 To %d is %d\n", num, sum);

    return 0;
}
