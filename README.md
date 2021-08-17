# Simple-school-exam-grade
/*Here you'll see how to start programming using a easy example about grades at school. YOU CAN USE IT AS BASIS TO PROGRAM YOURS!!!/*

#include <stdio.h>

int main(void){

  float nota1, nota2, nota3, media;
 
  printf("Insira a nota da primeira prova: ");
  scanf("%f", &nota1);
  printf("Insira a nota da segunda prova: ");
  scanf("%f",&nota2);
  printf("Insira a nota da terceira prova: ");
  scanf("%f",&nota3);

  media = (nota1 + nota2 + nota3) / 3;

  printf("Media final do aluno(a): %.1f", media);

  return 0;
}
