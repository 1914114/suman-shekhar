# PROGRAMING OF PROBLEM SOLVING

NAME- SAUMAN SHEKHAR 

ROLL NUMBER-1914114

BRANCH-CIVIL

SECTION-B2
![logo](https://www.google.com/imgres?imgurl=https%3A%2F%2Fnptel.ac.in%2Fcontent%2Fcollege_assets%2Fcollege_logo%2F1078_logo.jpg&imgrefurl=https%3A%2F%2Fnptel.ac.in%2FLocalChapter%2Fstatistics%2F1078%2F&docid=V-oHLfQu67pOUM&tbnid=JFcVDY2zdQXI7M%3A&vet=1&w=948&h=1040&client=ubuntu&bih=771&biw=1533&ved=2ahUKEwi_g_7X_8XlAhVaiHAKHQ9WC68QxiAoAHoECAEQFA&iact=c&ictx=1
COLLEGE NAME- GURU NANAK DEV ENGINEERING COLLEGE, LUDHIANA)






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
