<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->

Actividad 3: Ejercicios de operaciones básicas en Java.

## 1.Suma y multiplicación: Escribe un programa que solicite al usuario dos números enteros y luego imprima la suma y multiplicación de esos números.

## 2.Resta y división: Escribe un programa que tome dos números enteros ingresados por el usuario y calcule la resta y división de esos números.

## 3.Operaciones combinadas: Escribe un programa que solicite al usuario tres números enteros y realice las siguientes operaciones: suma de los tres números, multiplicación del primer número por el segundo y división del resultado entre el tercer número.

## 4.Operaciones con decimales: Escribe un programa que solicite al usuario dos números decimales y realice las siguientes operaciones: suma, resta, multiplicación y división.

## 5.Incremento y decremento: Escribe un programa que declare una variable entera y la inicialice con un valor. Luego, incrementa su valor en 1 y muestra el resultado. Después, decrementa su valor en 1 y muestra el resultado nuevamente.

## 6.Operador de asignación compuesta: Escribe un programa que declare una variable entera y la inicialice con un valor. Utiliza el operador de asignación compuesta para sumar 5 a la variable y luego mostrar su valor.

## 7.Operadores lógicos: Escribe un programa que tome dos valores booleanos ingresados por el usuario y muestre el resultado de las operaciones lógicas AND, OR y NOT entre esos valores.

## 8.Operador ternario: Escribe un programa que tome un número entero ingresado por el usuario y utilice el operador ternario para determinar si el número es positivo o negativo. Luego, muestra el resultado en la salida.

# SOLUCION

# 1. 

import java.util. Scanner;
class Main {
public static void main(String[] args) {

Scanner scanner = new Scanner(System. in);

System.out. print( "Introduce el primer número entero: ");
int numl = scanner, netxtInt();
System. out. print( "Introduce el segundo número entero: ");
int num2 = scanner.nextInt();
int suma = numl + num2;
int multiplicacion = num1 * num2;
System.out. println("La suma de los números es: " + suma);
System.out. println("La multiplicación de los números es: "+ multiplicacion);
scanner. close();
}
}

# 2.

import java util. Scanner;

class Main 1
public static void main(Stringl] args) {
System. out print In( "Hello world!");

Scanner scanner = new Scanner(System. in);

System.out. print( "Introduce el primer número entero: ");
int num1 = scanner.nextInt();

System. out. print( "Introduce el segundo número entero: ");
int num2 = scanner. nextInt();

int resta = num1 - num2;

double division = (double) num / num;

System. out. println("La resta de los números es: "+ resta); System.out.println("El resultado de la
division es: " + division) ;
scanner. close();
}
}

# 3.

Import java. util. Scanner;
Class Main｛
public static void main(Stringl] args) {
Scanner scanner = new Scanner(System. in);
System. out println("Ingrese el primer número entero:");
int numi = scanner. nextInt();
System out-println( "Ingrese el segundo número entero:");
int num = scanner.nextInt();
System.out-println|"Ingrese el tercer número entero:");
int num3 = scanner nextInt();
int suna = num] + num2 + num3;
int multiplicacion = numl * num2;
double resultadoDlVEston - (double) nultipllcacion / nun3;
System.out.println("Suma de los tres números: " + suma);
System. out-printint "Multiplicación del primer número por el segundo: " + multiplicacion);
System.out.println("División del resultado entre el tercer número: " + resultadoDivision);
scanner.close();

# 4. 

import java.util. Scanner;
class Main {
public static void main(Stringl] args) {
Scanner scanner = new Scanner(System. in);
System.out.println( "Ingrese el primer número decimal:");
double num = scanner. nextDouble();
System.out.println("Ingrese el segundo número decimal:");
double num2 = scanner. nextDouble();
double suma = numl + num2;
double resta = num1 - nun2;
double multiplicacion = numl * num2;
double division = numl / num2;
System. out. println("Suma: " + suma);
System. out. println(*Resta: "+ resta); System. out. println( "Multiplicación: " + multiplicacion);
System.out.println("division:" + division);

# 5. 

import java. util. Scanner;
class Main {
public static void main(Stringl] args) {
Scanner scanner = new Scanner(System. in);
int numero = 10;
numero+ti
System.out-println( "Valor incrementado: "
+ numero);
numero--；
System.out. println( "Valor decrementado: " + numero);
scanner. close();

# 6. 

import java.util.Scanner;
class Main {
public static void main(String[] args) {
Scanner scanner = new Scanner(System. in);
int numero = 10;
numero+=5;
System. out. printIn( "Valor después de sumar 5: " + numero);
scanner. close();

# 7.

import java.util.Scanner;
class Main {
public static void main(Stringl] args) {
Scanner scanner = new Scanner(System. in);
System. out printIn("Ingrese el primer valor booleano (true o false):");
boolean valor1 = scanner. nextBoolean();
System. out.printls
Engrese el segundo valor booleano (true ofalse):");
boolean valor = scanner. nextBoolean();
boolean resultadoAND = valor1 65 valor2;
boolean resultadooR = valor1 || valor2;
boolean
resultadoNOT1 - 1valor];
booLean resultadoNOT2= Ivalorz:
System out, println( "Resultado de AND: " + resultadoAND); System.out. println( "Resultado de OR: " resultadoOR);
System out println( "Resultado de NOT para el primer valor: " + resultadoNOT1);
System.out printint "Resultado de NOT para el segundo valore * + resultadoNOT2);

# 8.

import java.util.Scanner;
class Main {
public static void main(String[] args) {
Scanner scatner = new Scanner(System. in);
System.out.println( "Ingrese un numero entero");
int numero = scanner. nextInt();
String resultado = (numero >= 0) ? "positivo" : "negativo";
System.out. println("El número ingresado es: " + resultado);





