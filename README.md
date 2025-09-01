#src/fibonacci.c
#fibonacci
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

#Edite src/fibonacci.c para implementar fibonacci(int n) retornando o n-ésimo termo (1→1, 2→1, 3→2 ...).
Use APENAS um unified diff com as linhas alteradas.

Critérios:
- Iterativo, O(n), int64_t.
- Trate n <= 0 como erro (retorne -1).
- Para n >= 93, retorne -2 (overflow em int64_t).
- Mantenha cabeçalho e comentários existentes.

Verificação esperada:
- n=1→1, n=2→1, n=7→13, n=50→12586269025
- n=0→-1, n=93→-2


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
