# hollow-full-pyramid
c program for hollow full pyramid
#include <stdio.h>

int main()
{
    int i,j,n,k;
	scanf("%d",&n);
	for(i=1;i<=n;i++)
	{
	    if(i<n)
	    {
	        for(k=1;k<=n-i;k++)
	        {
	            printf("\t");
	        }
	    }
	    for(j=1;j<=i;j++)
	    {
	        if(j==1)
	        {
	         printf("1\t");
	        }
	         else if(j==i)
	         {
	             printf("\t%d\t",i);
	         }
	         else if(i==n)
	         {
	             printf("\t%d\t",j);
	         }
	         else
	         {
	             printf("\t\t");
	         }
	    }
	    printf("\n");
	}

    return 0;
}
