// ASCII-DICTIONARY

# include <stdio.h>
# include <conio.h>
int main()
{   int i ;
    printf ("ASCII DICTIONARY") ;
    for (i=0;i<256;i++)
    printf ("\n%d\t : % c\n",i,i) ;
    getch() ;
    return 0 ;
}
