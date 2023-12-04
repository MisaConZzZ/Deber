#include <stdio.h>

int main() {
    float total_compra, descuento, total_pagar;

    printf("Ingrese el total de la compra: ");
    scanf("%f", &total_compra);

    descuento = total_compra * 0.15;

    total_pagar = total_compra - descuento;

    printf("El total a pagar despues del descuento es: %.2f\n", total_pagar);

    return 0;
}
