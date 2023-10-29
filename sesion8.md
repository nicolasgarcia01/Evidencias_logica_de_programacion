<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->

# Actividad: Ejecicios de métodos en Java

**Implementar los siguientes métodos:**

**1. Escribe un método que reciba dos números como parámetros y devuelva el mayor de los dos.**

**2. Escribe un método que reciba una cadena de texto como parámetro y devuelva el número de vocales que contiene.**

**3. Escribe un método que reciba una cadena de texto como parámetro y devuelva una nueva cadena con todas las letras mayúsculas en minúsculas y viceversa.**

**4. Escribe un método que reciba una cadena de texto como parámetro y devuelva el número de palabras que contiene.**

**5. Escribe un método que reciba una cadena de texto como parámetro y devuelva una nueva cadena con todas las palabras en orden alfabético.**

# Solución.

**1:**

public class Actividad8 {

    public static void main(String[] args) {
        
        int numero1 = 8;
        int numero2 = 20;

        int mayor = encontrarMayor(numero1, numero2);

        System.out.println("El número mayor es: " + mayor);
    }

    public static int encontrarMayor(int num1, int num2) {
        if (num1 > num2) {
            return num1;
        } else {
            return num2;
        }
    }
}

**2:**

public class Actividad8 {

    public static void main(String[] args) {
        

    String texto = "Hola,soy nicolas garcia ossa";
        int cantidadVocales = contarVocales(texto);

        System.out.println("El número de vocales en el texto es: " + cantidadVocales);
    }

    public static int contarVocales(String texto) {
        int contador = 0;
        texto = texto.toLowerCase(); 

        for (int i = 0; i < texto.length(); i++) {
            char c = texto.charAt(i);
            if (c == 'a' || c == 'e' || c == 'i' || c == 'o' || c == 'u') {
                contador++;
            }
        }

        return contador;
    }
}

**3:**

public class Actividad8 {

    public static void main(String[] args) {
        
        String texto = "EStoy EstuDiando IngenieriA eN SOFtware";
        String resultado = intercambiarMayusculasMinusculas(texto);

        System.out.println("Texto con mayúsculas y minúsculas intercambiadas: ");
        System.out.println(resultado);
    }

    public static String intercambiarMayusculasMinusculas(String texto) {
        StringBuilder resultado = new StringBuilder();

        for (int i = 0; i < texto.length(); i++) {
            char c = texto.charAt(i);
            if (Character.isUpperCase(c)) {
                resultado.append(Character.toLowerCase(c));
            } else if (Character.isLowerCase(c)) {
                resultado.append(Character.toUpperCase(c));
            } else {
                resultado.append(c); 
            }
        }

        return resultado.toString();
    }
}

**4:**

public class Actividad8 {

    public static void main(String[] args) {
        
        String texto = "Mi profesor se llama jhon valencia y nos da las clases de los martes y jueves";
        int cantidadPalabras = contarPalabras(texto);

        System.out.println("El número de palabras en el texto es: " + cantidadPalabras);
    }

    public static int contarPalabras(String texto) {
        // Dividir el texto en palabras utilizando espacios como separadores
        String[] palabras = texto.split("\\s+");
        return palabras.length;
    }
}

**5:**

public class Actividad8 {

    public static void main(String[] args) {
        
        String texto = "a c b d f e";
        String resultado = ordenarPalabrasAlfabeticamente(texto);

        System.out.println("Texto con palabras en orden alfabético:");
        System.out.println(resultado);
    }

    public static String ordenarPalabrasAlfabeticamente(String texto) {
        String[] palabras = texto.split("\\s+"); 
        Arrays.sort(palabras); 

        
        StringBuilder resultado = new StringBuilder();
        for (int i = 0; i < palabras.length; i++) {
            resultado.append(palabras[i]);
            if (i < palabras.length - 1) {
                resultado.append(" "); 
            }
        }

        return resultado.toString();
    }
}






