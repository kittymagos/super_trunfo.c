# super_trunfo.c
#include <stdio.h>

 int main(){
 char estado1[20];
 char CdC1 [20]; 
 char cidade1[20];
 int populacao1;
 float area1;
 float PIB1;
 int NDT1; 
 char estado2[20];
 char CdC2 [20]; 
 char cidade2[20];
 int populacao2;
 float area2;
 float PIB2;
 int NDT2;
  
  printf("digite o nome do estado da carta 1: \n");
    scanf("%s", estado1);
  printf("digite o codigo da carta 1: \n");
    scanf("%s", CdC1);
  printf("digite o nome da cidade da carta 1; \n");
    scanf("%s", cidade1);
  printf("digite a populacao da carta 1: \n");
    scanf("%d", &populacao1);
  printf("digite a area da carta 1: \n");
   scanf("%f", &area1);
  printf("digite o PIB da carta 1: \n");
   scanf("%f", &PIB1);
  printf("digite o numero de pontos turisticos da carta 1: \n");
  scanf("%d", &NDT1); 

  printf("digite o estado 2: \n");
  scanf("%s", estado2);
printf("digite outro codigo da carta 2 : \n");
  scanf("%s", CdC2);
printf("digite nome da cidade da carta 2; \n");
  scanf("%s", cidade2);
printf("digite a populacao da carta 2: \n");
  scanf("%d", &populacao2);
printf("digite a area da carta 2: \n");
 scanf("%f", &area2);
printf("digite o PIB da carta 2: \n");
 scanf("%f", &PIB2);
printf("digite o numero de pontos turisticos da carta 2: \n");
scanf("%d", &NDT2); 

return 0;
}
