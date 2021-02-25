#include <stdio.h>
#include <stdlib.h>
#include <conio.h>
void main()
{
    int risposta,a=10,b=20,c;
    printf("Tasta 1 per fare la somma\nTasta 2 per fare il prodotto\nTasta 3 per fare la sottrazione");
    scanf("%d",&risposta);
    switch(risposta)
    {
    case 1:
        {
            c=a+b;
            printf("\n%d",c);
        }break;
    case 2:
        {
            c=a*b;
            printf("\n%d",c);;
        }break;
    case 3:
        {
            c=a-b;
            printf("\n%d",c);
        }break;
    default:
        {
            printf("Risposta non valida");
        }
    }
    getch();
}


