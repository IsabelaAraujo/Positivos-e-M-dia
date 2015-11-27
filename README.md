#include <stdio.h>
  
int main() {
       int a, b=0;
       float c, m, p=0;
        
       for(a=0; a<6; a++) { // Aqui foi declarada a função que o programa irá seguir. O valor de a iniciará o programa sendo gual a 0, deve ser respeitado enquanto o valor de a for menor que 6 e sempre acrecentar mais 1 quando o programa rodar novamente. 
       scanf("%f", &c); // Lê e guarda o valor fornecido pelo usuario.
        
       if(c>0) { // Define que C sempre terá que ser maior que 0.
       p = p+c; //os valores de P e C serão somados para assim cacular a quantidade de valores positivos.
       b++; // sempre será acrescentado 1 quando o programa voltar a rodar. 
       }
    }
       m = (p/b); // Cacular  a média.
       printf("%d valores positivos\n" ,b); //Resultado impresso na tela.
       printf("%.1f\n" ,m);
        
       system ("pause");
       }
