#include<stdlib.h>
main()
{
    int i;
    char s[128];
    scanf("%d",&i);
    itoa(i,s,16);
    printf("[%s]\n",s);
}
