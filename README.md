# trabalho1-Marcio-das-Chagas-dev
Calculadora em C
#include <stdio.h>
 main ()
{
  float N1, N2, N3, N4, N5, N6;  
 
  printf("Digite o Primeiro Numero:\n");
  scanf("%f", &N1);
  
  printf("Digite o Segundo Numero:\n");
  scanf("%f", &N2);  
    	
  	N3=N1/N2;
  	
  	printf("valor da Divisao e: %.2f\n", N3);  
  	
  
  	N4=N1*N2;
  	
  	printf("valor da multiplicacao e: %.2f\n", N4);
  
  	N5=N1+N2;
    
	printf("valor da Soma e: %.2f\n", N5);  
  
  	N6=N1-N2;
  	
  	printf("valor da subtracao e: %.2f\n", N6);
  
  	return 0;
  }
