# PROGRAMING OF PROBLEM SOLVING

NAME- SAUMAN SHEKHAR 

ROLL NUMBER-1914114

BRANCH-CIVIL

SECTION-B2
![logo](






1 program to print name

#include<stdio.h>

int main()

{
printf("suman shekhar");
return 0;
}


2 sum of two number x and y
#include<stdio.h>

int main()

        {
         int x,y;
         printf("enter two number");
         scanf("%d%d",&x,&y);
         printf("sum of %d and %d is %d",x,y,x+y);
         return 0;
         } 

-------------------------------------------------------------------------------------------------------


3 write a program to find the location of a given element using linear search.
                 
                 
                 #include<stdio.h>
                 int main()
                 {
                 int array[100],search,i,n;

                printf("enter the number of elements in array:");
                       scanf("%d",&n);
                      for (i=0;i<=n;i++)

                   {
                      printf("enter[%d]element:",i);
                     scanf("%d",&array[i]);
                   }

                     printf("enter a number to search:");
                       scanf("%d",&search);
                        for(i=0;i<=n;i++)
                    {
                         if (array[i]==search)
                    {
                      printf("%d is present at location %d.\n",search,i+1);
                        break;
                    }
                      else if(i>=n)
                     printf("%d is not present in the array.\n",search);
                    }
                    return 0;
                   }
















