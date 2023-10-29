<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 


<!-- Su documentación aquí -->

# Actividad: Ejercicios de Lógica de Programación

**1.Basándose en el algoritmo 1 de la sesión 11, aplicar la siguiente variante: Dado un conjunto de números enteros, se debe determinar si existe algún número que aparezca más de una vez. Si es así, se deben imprimir todos los números que aparezcan más de una vez.**

**2.Desarrollar un algoritmo que realice la conversión de binario a decimal.**

# Solución:

**1:**

public class Actividad8 {

    public static void main(String[] args) {
        
    


        int[] numeros = {1, 2, 3, 4, 2, 5, 6, 4, 7, 8, 9};

        HashMap<Integer, Integer> conteo = new HashMap<>();
        List<Integer> numerosRepetidos = new ArrayList<>();

        for (int numero : numeros) {
            if (conteo.containsKey(numero)) {
                int contador = conteo.get(numero);
                conteo.put(numero, contador + 1);
            } else {
                conteo.put(numero, 1);
            }
        }

        for (int numero : conteo.keySet()) {
            int contador = conteo.get(numero);
            if (contador > 1) {
                numerosRepetidos.add(numero);
            }
        }

        if (numerosRepetidos.isEmpty()) {
            System.out.println("No hay números repetidos.");
        } else {
            System.out.println("Números repetidos: " + numerosRepetidos);
        }
    }
}

**2:**

public class Actividad8 {

    public static void main(String[] args) {
        
   
   
        String numeroBinario = "101010"; 

        int decimal = convertirBinarioADecimal(numeroBinario);

        System.out.println("El número binario " + numeroBinario + " en decimal es: " + decimal);
    }

    public static int convertirBinarioADecimal(String numeroBinario) {
        int decimal = 0;
        int potencia = 0;

       
        for (int i = numeroBinario.length() - 1; i >= 0; i--) {
            char digito = numeroBinario.charAt(i);

            if (digito == '1') {
                decimal += Math.pow(2, potencia);
            }

            potencia++;
        }

        return decimal;
    }
}




