#include <stdio.h>
#define TAMANHO 10

typedef struct{
	int no[TAMANHO];
}Pilha;

void init(Pilha *p){
	p->no[0] = 0;
}

int lenghtPilha(Pilha *p){
	return(p->no[0] == 0)
}

int push(Pilha *p, int item){
	if(p->no[0] + 1 <= TAMANHO - 1 ){
		p->no[++p->n[0]] = item;
		return(1);
	}
	printf("Erro de inserção");
	return(0);
}

int pop(Pilha *p){
	int aux = p->no[p->no[0]]
	if (!lenghtPilha(p)){
		p->no[0] - 1;
		return(aux);
	}
	return(p->no[0]);
}

int STACKTOP(Pilha *p){
	int aux = pop(p);
	push(p, aux);
	return(aux);
}
int main(void){
	Pilha p;

	init(p);

	push(p, 50);

	
return(0);
}
