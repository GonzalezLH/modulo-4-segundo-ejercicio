# modulo-4-segundo-ejercicio




package com.educacionit;
import java.util.Scanner;

public class programa {
    public static void main(String[] args) {

Scanner cuenta = new Scanner (System.in);
int numero;
int suma = 0;
int numeroMenor = Integer.MAX_VALUE;
int numeroMayor = Integer.MIN_VALUE;

do{
	System.out.println( "ingrese numero o (0 para canelar ) : ");
	numero = cuenta.nextInt();
	
	if(numero!=0) {
		suma+=numero;
	
	if(numero > numeroMayor) {
		numeroMayor=numero;
	}
	if(numero < numeroMenor) {
		numeroMenor= numero;	
}
}
}while (numero!=0);
    System.out.println("la suma de los numero ingresados : " + suma);
    System.out.println("el numero menor es : "+ numeroMenor);
    System.out.println("el numero mayor es : " + numeroMayor);
}



(SE CREA UN PROGRAMA UTILIZANDO EL MOTODO DO WHILE CREAMOS LA VARIANTES Y LE ASIGANAMOS DICHO VALOR QUE  NOS INFORME EL MAXIMO O EL MINIMO DE LOS MISMO,
EL USUARIO A LA HORA DE INTERACTUAR INGRESARA LOS NUMEROS QUE Y LA SUMA QUE DESEA , ARROJARA ASI EL NUMERO MAYOR , MENOR Y LA SUMA DE LAS MISMA UNA VEZA QUE CANCELE LA OPERACION
INGRESANDO EL NUMERO 0 )
