prog
====

Francesco Sannini.
copyright 2014.


-----------------------------------------------------------------------------------------------------------------------------


#include <stdio.h>
#include <stdlib.h>

int main(int argc, char *argv[])
{
    int i, s, n, nu[1000], me;
    
    s=0;
    
    do
    {
        printf("Quanti numer vuoi inserire ?");
        scanf("%d", &n);
    }
    while(n<=0);
    
    i=0;
    while(i<n)
    {
        printf("Dammi un numero : ");
        scanf("%d", &nu[i]);
        s=s+nu[i];
        i++;
    }
        
    printf("La somma e' : %d\n", s);
    me=s/n;
    printf("La media e' : %d\n", me);
    
    i=0;
    while(i<n)
    {
        printf("L'array e': %d\n", n);
        i++;
    }
    
    system("PAUSE");	
    return 0;
}
