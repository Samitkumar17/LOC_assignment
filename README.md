#include<stdio.h>
#include<stdlib.h>

int main()
{
   char name[50];
char branch[50];
char hobbies[100];
int regd;
printf("enter your name");
gets(name);
printf("enter your branch");
gets(branch);
printf("enter your hobbies");
gets(hobbies);
printf("enter last 3 digits of registration number");
scanf("%d",&regd);
printf("Name:%s\n",name);
printf("branch:%s\n",branch);
printf("hobbies:%s\n",hobbies);
printf("registered number%d\n",regd);
return 0;
}
