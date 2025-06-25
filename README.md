# Lista-de-Exerc-cios-Linguagem-C
Lista de Exercício de linguagem C
## Liguagem-C-codes


## Questão 34


    #include <stdio.h>

    int main(void){  

    int nome, idade, endereco, numero;
    printf("Digite seu nome, idade, endereco e numero: ");
    scanf("%d" , &nome);
    scanf("%d" , &idade);
    scanf("%d" , &endereco);
    scanf("%d", &numero);
    printf("Seu nome é %d você tem %d anos mora na rua %d e seu telefone é %d", nome, idade, endereco, numero);
    return 0;
    }

## Questão 25

    #include <stdio.h>

    int main() {
   
    float fahrenheit, celsius;

    printf("digite a temperatura em fahrenheit: ");
    scanf("%f", &fahrenheit);

    celsius = (fahrenheit - 32) * 5.0 / 9.0;

    printf("é igual a %.2f celsius\n", celsius);

    return 0;
    }

## Questão 27
     #include <stdio.h>

     int main() {
  
     float valor, valor_inflacionado;

     printf("digite o preço do produto: ");
     scanf("%f", &valor);

    if (valor < 100) {
    valor_inflacionado = valor * 1.10;
    } 
    else {
    valor_inflacionado = valor * 1.20;
    }

    printf("O valor inflacionado é: %.2f\n", valor_inflacionado);

    return 0;
    }
