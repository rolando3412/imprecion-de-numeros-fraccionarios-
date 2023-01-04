# imprecion-de-numeros-fraccionarios-

#include <iostream>
#include <cmath>
#include<cstdlib>
/**
# 26 ejercicio
 considere la siguiente lista de números: (1/1 , 1/2, 1/3,1/4,1/5, 1/6, 1/7, 1/8, 1/9, 1/10,
   2/1, 2/2, 2/3, 2/4, 2/5, 2/6, 2/7, 2/8, 2/9, 2/10,
   3;1 )
   escriba un algoritmo que resiba como entrada un numero entero y a continuancion imprima
    los primeros n elementos de la lista. anterior */

using namespace std;

    int imprimir(int numerador , int denominador); // declaracion de la funcion

// variables globales
int n = 0;
int numerador = 0;
int denominador = 0;
int z = 0;
int main()
{

    std::cout << "ingrese un numero entero: ";
    cin >> n;

    // llamado de funcion
    cout<<"la lista es" << imprimir( numerador ,  denominador)<< endl ;


    return 0;
}
// definicion de resultados
    int imprimir(int numerador , int denominador)
    {

        // proceso para hacer la operacion  la varible n,
for (int   i = 1; i <= n; i++)
     for (int  j = 1; j <= 10; j++)
     {
         /* imprimiendo los resultados como faccion
             de los parametros dados */
         numerador = i;
         denominador = j;
         std::cout << numerador << "/" << denominador << std::endl;
     }
      return z  ;
    }

