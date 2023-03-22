# porojet-1
#include <stdio.h>
{
float T[5];

void remplirT()
{
int i;
printf("\n");
printf("veuillez saisir les éléments du tableau :");
printf("\n");
for (i=0;i<=4;i++){
printf("T[%d]=",i+1);
scanf("%f",&T[i]);
}
}
void afficher T() {
int i;
for (i=0;i<=4;i++){
printf ("%.2f",T[i]);
}
}
void trierT()
{
int i,j;
float tmpo;
for (i=0;i<=4;i++){
for (j=i+1;j<=4;i++){
if (T[i]<T[j]){
T[i]=tmpo;
T[i]=T[j];
T[j]=tmpo;
}
}
}
}
printf ("\n");
printf ("les éléments par ordre décroissant :");
printf ("\n");
afficher T();
int main()
{
remplir T();
trier T();
}
}




