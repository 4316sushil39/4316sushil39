#include <stdio.h>
#include <string.h>
int main()
{
    char s1[50],s2[20];
    printf("enter s1 : ");
    gets(s1);
     printf("enter s2 : ");
    gets(s2);
    strcat(s2,s1);
    printf("after concatination s2 is = %s", s2);
    return 0;
}
