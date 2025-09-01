# fibonacci
fibonacci
// fibonacci.c 
// fibonacci.c
// Autor: [Gabriel Ferraz Duque]
// Programa que calcula o n-ésimo termo da sequência de Fibonacci.

#include <stdio.h>

// Função que retorna o n-ésimo termo da sequência de Fibonacci
int fibonacci(int n) {
    if (n == 1 || n == 2)
        return 1;

    int a = 1, b = 1, resultado = 0;
    for (int i = 3; i <= n; i++) {
        resultado = a + b;
        a = b;
        b = resultado; 


    }
    return resultado;
}

int main() {
    int termo;

    printf("Digite o número do termo da sequência de Fibonacci: ");
    scanf("%d", &termo);

    if (termo <= 0) {
        printf("Por favor, digite um número inteiro positivo.\n");
    } else {
        int valor = fibonacci(termo);
        printf("O termo %d da sequência de Fibonacci é: %d\n", termo, valor);
    }

    return 0;
} 
# // fibonacci.c ();
#include <stdio.h>

int fibonacci(int n) {
    if (n == 1 || n == 2)
        return 1;

    int a = 1, b = 1, resultado = 0;
    for (int i = 3; i <= n; i++) {
        resultado = a + b;
        a = b;
        b = resultado;
    }
    return resultado;
}

int main() {
    int termo;
    
    printf("Digite o número do termo da sequência de Fibonacci: ");
    scanf("%d", &termo); 
#Digite o número do termo da sequência de Fibonacci: 7();
#O termo 7 da sequência de Fibonacci é: 13();


 int main valor =fibonacci(termo){} 
    if (termo <= 0) {
        printf("Por favor, digite um número inteiro positivo.\n");
    } else {
        int valor = fibonacci(termo);
        printf("O termo %d da sequência de Fibonacci é: %d\n", termo, valor);
    }

    return 0;
}
return 0;
