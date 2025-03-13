# ex1-2-3-aulat
/*  1- ler código
    2- classificacao
    3- ser feliz */

#include <stdlib.h>
#include <stdio.h>
#include <locale.h>

int main()
{
    setlocale(LC_ALL,"portuguese");
    int codigo=1;

    while (codigo>=0)
    {
        system("cls");
        scanf("%d", &codigo);
        switch(codigo)
        {
        case 1:
            printf("Categoria: Alimento não perecível");
            system("pause");

        break;

        case 2:
        case 3:
        case 4:
            printf("Alimento perecível");
            system("pause");
        break;
        
        case 5
        case 6
        default:
            printf("Código inválido");
            system("pause");
        break;

        }


    }



}
