<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->

# Actividad 5: Ejercicios de bucles

-Resolver los siguientes ejercicios:

# Ejercicios - while

-Pedir al usuario que ingrese un número y mostrar su tabla de multiplicar hasta el número 10.

-Pedir al usuario que ingrese una cadena de caracteres y contar la cantidad de caracteres que son números.

# Ejercicios - do while

-Escribe un programa en Java que imprima los números del 1 al 100, pero que se detenga si el usuario introduce un número negativo.

-Escribe un programa en Java que pida al usuario un número entero e imprima la tabla de multiplicar de ese número, pero que se detenga si el usuario introduce el número 0.

# Ejercicios - for

-Imprimir los números impares del 1 al 50.

-Imprimir los números primos del 1 al 100.
Previous

# SOLUCION 

# Ejercicio 1 while

   Scanner sc = new Scanner(System.in);
        
        System.out.println("Ingrese un numero");
        int  numero = sc.nextInt();
        
        int contador = 1;
        
        while (contador <=10){
        
        int producto = numero * contador;
        
        System.out.println(numero + "x" + contador + "=" + producto);
        
        contador++;
    }
        
     sc.close();   
    }
    
}


# Ejercicio 2 while

System.out.println("Ingrese una cadena de caracteres:");
        String cadena = scanner.nextLine();
        
        int contador = 0;
        
        for (int i = 0; i < cadena.length(); i++){
            
            char caracter = cadena.charAt(i);
            
           if (Character.isDigit(caracter)){
               contador++;
           }
        }
        System.out.println("La cantidad  de caracteres que son numero es:" + contador);

# Ejercicio 1 do-while

    Scanner scanner = new Scanner(System.in);
        
        System.out.println("introduce un numero: (ingrese un numero negativo para detener):");
        
        int numero = scanner.nextInt();
        
        int i = 1;
        
        do {
            System.out.println(i);
            i++;
            
        } while (i <= 100 && numero >= 0);
        

  



# Ejercicio 2 do-while

Scanner scanner = new Scanner(System.in);
        
        System.out.println("Introduce un numero entero:");
        
        int numero = scanner.nextInt();
        
        int i = 1;
        
        do{
            System.out.println(numero + "x" + i + "=" + (numero + i));
            i++;
            
        }while (i <=10 && numero !=0);

# Ejercicio 1 for

  int i = 1;
        
        for(;i<=50;i++){
            if (i % 2 != 0) 
            System.out.println(i);
        }
        
        }

  
# Ejercicio 2 for 

for (int  numero = 2; numero <= 100; numero++){
           boolean esPrimo = true;
           
           for (int divisor = 2; divisor < numero; divisor++){
               if (numero % divisor == 0){
                   esPrimo = false;
                   break;
                   
               }   
           }
           
           if (esPrimo){
               System.out.println(numero);








