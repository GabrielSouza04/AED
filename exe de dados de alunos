# AED2
espaço para codigos em C

// Gabriel Mantovanni de  Souza
#include <stdio.h>

 float calculamedia( float N1, float N2)
{
    float md;
    md = (N1 + N2)/2;
    return (md);
}

int main() {
    int i,x;
    float sm,a,b;
   
    printf("Quantidade de alunos: ");
    scanf("%d", &x);
    struct estruturaAluno{
             int matricula;
             float N1;
             float N2;
             float media;
    };
    struct estruturaAluno alunos[x];
   
 
    for (i=0;i<x;i++) {
       printf( "-----------------DADOS DO ALUNO--------------- \n\n");
       printf( "Matrícula do aluno: ");
       scanf ("%d" ,&alunos[i].matricula);
       printf( "Nota N1: ");
       scanf ("%f", &alunos[i].N1);
       printf( "Nota N2: ");
       scanf ("%f", &alunos[i].N2);
   
        alunos[i].media = calculamedia(alunos[i].N1,alunos[i].N2);
}

    for (i=0;i<x;i++) {
        printf( "\nBOLETIM DO ALUNO %d\n", i+1);
        printf( "\nNota N1: %.1f", alunos[i].N1);
        printf( "\nNota N2: %.1f", alunos[i].N2);
        printf( "\nMedia..: %.1f", alunos[i].media);
       
    }  
    for (i=0;i<x;i++) {
       
    a = (alunos[i].N1 + alunos[i].N2)/2;
    b = (b + a);
    sm = b/x;
   
   
    }
    printf("\n\n\nA media dos alunos é: %.1f", sm);
       return (0);

}

