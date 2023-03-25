# Lista-2-Exercicio-2-
#include <stdio.h>
#include <stdlib.h>
#include <locale.h>

int main() { 
		
		float salario, emprestimo;
		
		printf("Escreva o seu salário: ");
		scanf("%f", &salario);
		
		printf("Informe o valor da prestacao do emprestimo: ");
		scanf("%f", &emprestimo);
		
		if (emprestimo<=(salario*20)/100) {
			printf("\n\nO Emprestimo CONCEDIDO.\n");
    }
		if (emprestimo>(salario*20)/100){
			printf("\n\nO Emprestimo NAO CONCEDIDO.\n");
		}
return(0);				
}
		
	
