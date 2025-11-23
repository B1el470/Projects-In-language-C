#include <stdio.h>
#include <math.h>
#include <locale.h>
int main() {
	setlocale(LC_ALL, "portuguese");

	float nota1, nota2, nota3;
	float maior1, maior2, maior3;
	float media;
	int a;

	printf("insira a nota do aluno:\n");
	scanf_s("%d", &a, "%f",  & maior1, &maior2, &maior3);
	printf("insira a primeira nota do aluno:\n");
	scanf_s("%f", &nota1);

	printf("insira a segunda nota do aluno:\n");
	scanf_s("%f", &nota2);

	printf("insira a terceira nota do aluno:\n");
	scanf_s("%f", &nota3);

	printf("Nota 1 = %f\n", nota1);

	printf("nota 2 = %f\n", nota2);

	printf("nota 3 = %f\n", nota3);

	media = (maior1 * nota1 + nota2 * maior2 + nota3 * maior3) / (float)(maior1 + maior2 + maior3);

	printf("Numero = %d\n", a);
	printf("A média do aluno:%f\n", media);

	if (media < 10) {
		printf("Reprovado");
	}
	else if (media >= 10) {
		printf("Aprovado");

	}
	return 0;
}
