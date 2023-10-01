<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 7 


<!-- Su documentación aquí -->

# Crear un ejemplo de Array y otro de ArrayList para visualizar sus diferencias.

# EJEMPLO ARRAY

    // Un array que contenga los numeros del 1 al 100 y que calcule la suma y la media de los valores.
        int[] numeros = new int[100];

        int suma = 0;
        double media = 0;

        for (int i = 0; i < numeros.length; i++) {
            numeros[i] = i + 1;
            suma += numeros[i];

        }

        System.out.println("la suma es" + suma);

        media = (double) suma / numeros.length;

        System.out.println("la media es" + media);

# EJEMPLO ARRAYLIST

        java.util.ArrayList <String> ListaNombres = new java.util.ArrayList();
        // .add Añade elementos a nuestro ArrayList
        ListaNombres.add("Nicolas"); // 0
        ListaNombres.add("Yojan"); // 1
        ListaNombres.add("Sara"); // 2
        ListaNombres.add("Juan"); // 3
        ListaNombres.add("Samuel"); // 4
        
        //.size indica el tamaño de nuestro ArrayList
        for (int i = 0; i<ListaNombres.size(); i++) {
            
            //.get sirve para  devolvernos un elemento especifico
            System.out.println(ListaNombres.get(i));
            
        }
        System.out.println("");
        
        //.remove sirvw para eliminar el elemento especifico
        ListaNombres.remove(3);
        for (int i = 0; i <ListaNombres.size(); i++){
            
            System.out.println(ListaNombres.get(i));
        }
        
    }
    
}




