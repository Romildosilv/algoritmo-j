# algoritmo-j
Aposentadoria //

#include <stdio.h>

int idade;
float trab;
int main (){
	printf ("digite a idade :");
	scanf ("%d",&idade);
	printf ("digite o tempo de trabalho :");
	scanf ("%f",&trab);
	if (idade>=65 || trab>=30 || (idade>=60 && trab>=25)){

	printf ("\nAposentadoria liberada\n");
}
else {

printf ("\nAposentadoria nao aprovada\n");
}
	
	return 0;
}

