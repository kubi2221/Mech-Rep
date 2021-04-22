# Mech Rep
 Zajęcia
#include <stdio.h>
int pien,choinka,spacja,rzad;
int a;
int main()
{
printf("Podaj liczbe galazek choinki \n");
scanf("%d", &a);
if(a>3)
{
for(rzad=0;rzad<a;rzad++)
{
spacja=a-rzad+5;
/*oznacza ilosc spacji przed wierszem gwiazdek uwarunkowany od 
ilosci rzedow choinki*/
for(spacja;spacja>0;spacja--)
printf(" ");

for(choinka=0;choinka<=2*rzad;choinka++)

printf("*");
printf("\n");
}

	for(rzad=0;rzad<a;rzad++)
	{
	spacja=a-rzad-4+5;
	for(spacja;spacja>0;spacja--)
	
	printf(" ");
	for(choinka=0;choinka<=2*rzad+8;choinka++)
	printf("*");
	printf("\n");
	}


	 for(rzad=0;rzad<a;rzad++)
        {
        spacja=a-rzad-4+5;
        for(spacja;spacja>0;spacja--)

        printf(" ");
        for(choinka=0;choinka<=2*rzad+10;choinka++)
        printf("*");
        printf("\n");
        }




for(a=0;a<rzad+5;a++)
{
printf(" ");
}
printf("| |\n");
}
else (printf("Zbyt mala ilosc galazek\n"));

return 0;
}

