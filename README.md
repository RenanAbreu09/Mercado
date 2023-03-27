#include <stdio.h>
int main(void) { int a,a1,a2,a3,a4,a5,a6;
printf("||BEM VINDO AO MERCADO||\n\n");
printf("||ESCOLHA QUAL DOS PRODUTOS VOCE PRETENDE LEVAR||\n\n");
printf("(1)UMA UNIDADE DE MACA(2R$)\n");
printf("(2)UMA UNIDADE DE UVA(1R$)\n");
printf("(3)UMA UNIDADE DE MAMAO(2R$)\n");
printf("(4)UMA UNIDADE DE PERA(3R$)\n");
printf("(5)UMA UNIDADE DE ABACATE(3R$)\n");
printf("(6)UMA UNIDADE DE ABACAXI(4R$)\n");
scanf("%i",&a);

if (a ==  1){
printf("QUAL QUANTIDADE VOCE PRETENDE LEVAR DESTE PRODUTO?\n\n");
scanf("%i",&a1);
printf("VOCE LEVARA %i UNIDADES DESTE PRODUTO POR %iR$\n\n",a1,a1*2);
}else if (a ==  2){
printf("QUAL QUANTIDADE VOCE PRETENDE LEVAR DESTE PRODUTO?\n\n");
scanf("%i",&a2);
printf("VOCE LEVARA %i UNIDADES DESTE PRODUTO POR %iR$\n\n",a2,a2*1);
}else if (a ==  3){
printf("QUAL QUANTIDADE VOCE PRETENDE LEVAR DESTE PRODUTO?\n\n");
scanf("%i",&a3);
printf("VOCE LEVARA %i UNIDADES DESTE PRODUTO POR %iR$\n\n",a3,a3*2);
}else if (a ==  4){
printf("QUAL QUANTIDADE VOCE PRETENDE LEVAR DESTE PRODUTO?\n\n");
scanf("%i",&a4);
printf("VOCE LEVARA %i UNIDADES DESTE PRODUTO POR %iR$\n\n",a4,a4*3);
}else if (a ==  5){
printf("QUAL QUANTIDADE VOCE PRETENDE LEVAR DESTE PRODUTO?\n\n");
scanf("%i",&a5);
printf("VOCE LEVARA %i UNIDADES DESTE PRODUTO POR %iR$\n\n",a5,a5*3);
}else if (a ==  6){
printf("QUAL QUANTIDADE VOCE PRETENDE LEVAR DESTE PRODUTO?\n\n");
scanf("%i",&a6);
printf("VOCE LEVARA %i UNIDADES DESTE PRODUTO POR %iR$\n\n",a6,a6*4);


}
}

