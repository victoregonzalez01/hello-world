#include<stdio.h> 
int main() { 
    int num1, num2, result;

    printf("Bienvenido al programa de victor\n vamos a sumar \n introduce el primer numero: ");
    scanf("%d",&num1);
    printf("introduce el segundo numero: ");
    scanf("%d",&num2);
    result= num1+num2;
    printf("El resultado de la suma es %d", result, "\n");
    system("pause");
    return 0;
}
