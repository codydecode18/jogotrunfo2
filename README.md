
#include <stdio.h>

int main() {
// Nesse código menciona nome da cidade
printf("O nome da cidade é %s\n", "Curitiba");

// Número da população
printf("Número da população seria %i\n", 1627); 

// Nesse código menciona número da carta 
printf("O código da carta seria %i\n", 17000);

// Nesse código menciona área da cidade 
printf("Área da cidade seria %f\n", 434.892);

// Nesse código menciona o PIB
printf("O PIB da cidade seria %f\n", 98.0000);

// Nesse código menciona pontos turísticos
printf("Número de ponto turístico seria %i\n", 50000); 

float formula1,fórmula2;
formula1=1627/434.892;
printf(" Densidade populacional : %f \n ",formula1);

fórmula2= (float)98.0000 / 1627 ;
printf(" PIB per capita : %f \n ",fórmula2);



// Nesse código menciona nome da cidade
printf("O nome da cidade é %s\n", "Bahia ");

// Número da população
printf("Número da população seria %i\n", 822939); 

// Nesse código menciona número da carta 
printf("O código da carta seria %i\n", 73838);

// Nesse código menciona área da cidade 
printf("Área da cidade seria %f\n", 8.999);

// Nesse código menciona o PIB
printf("O PIB da cidade seria %f\n", 2.383);

// Nesse código menciona pontos turísticos
printf("Número de ponto turístico seria %i\n", 50000); 

float formula3,fórmula4;
formula3=822939/8.999;
printf(" Densidade populacional : %f \n ",formula3);

fórmula4= (float)2.383 / 822939 ;
printf(" PIB per capita : %f \n ",fórmula4);

if(fórmula4>fórmula2) {
printf(" A carta 2 foi vecedora \n");

}else{
printf(" A carta 1 foi vencedora \n");
}





return 0;
}
