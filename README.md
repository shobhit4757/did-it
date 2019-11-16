//*1121123211234321123454321
#include<stdio.h>
#include<conio.h>
main()
{
    int i,j,k,l,n;

    printf("enter the range=");
    scanf("%d",&n);
    for(i=1;i<=n;i++)
    {
        for(j=1;j<=n-i;j++)
            printf(" ");
        {
            for(k=1;k<=i;k++)
                printf("%d",l);
        }
        printf("\n");
    }

    getch();
}
