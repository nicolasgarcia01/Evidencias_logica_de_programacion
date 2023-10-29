<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 


<!-- Su documentación aquí -->

# Actividad: Prueba, ejecución y explicación de ejercicios de lógica de programación.

**Selecciona dos ejercicios de la sesión 10, impleméntalos, ejecútalos y proporciona una explicación detallada de cada uno**

# Solución:

**Explicación detallada de cada una:**

**1:**

-Se importa la clase Scanner desde el paquete java.util para permitir la entrada de datos desde el teclado.

-Se declara la clase IMC.

-En el método main, se crea una instancia de la clase Scanner llamada input, que se utilizará para capturar las entradas del usuario.

-Se declaran tres variables de tipo double: weight (peso), height (altura) e imc (Índice de Masa Corporal).

-El programa imprime el mensaje "Ingrese su peso en kilogramos: " y espera que el usuario ingrese su peso en kilogramos. La entrada del usuario se almacena en la variable weight utilizando el método nextDouble() de la instancia input.

-Luego, el programa imprime el mensaje "Ingrese su altura en metros: " y espera que el usuario ingrese su altura en metros. La entrada del usuario se almacena en la variable height utilizando el método nextDouble() de la instancia input.

-El programa calcula el IMC dividiendo el peso (en kilogramos) por el cuadrado de la altura (en metros). El resultado se almacena en la variable imc.

-Finalmente, el programa imprime el IMC calculado utilizando System.out.printf(), formateando el número para mostrarlo con dos decimales. La línea "Su IMC es %.2f" indica que se debe mostrar el valor de imc con dos decimales.

**En resumen, este programa solicita al usuario que ingrese su peso y altura, calcula su IMC y muestra el resultado en la consola. El IMC es una medida comúnmente utilizada para evaluar si una persona tiene un peso saludable en relación con su altura.**

**2:**

-Se importa la clase Scanner desde el paquete java.util para permitir la entrada de datos desde el teclado.

-Se declara la clase CantidadLadrillos.

-En el método main, se crea una instancia de la clase Scanner llamada input, que se utilizará para capturar las entradas del usuario.

-Se declaran varias variables de tipo double para almacenar los datos necesarios: largo, alto, ancho para las dimensiones de la pared, largoLadrillo, altoLadrillo, anchoLadrillo para las dimensiones de un ladrillo, areaPared para el área de la pared y cantidadLadrillos para la cantidad de ladrillos necesarios.

-El programa solicita al usuario ingresar las dimensiones de la pared, es decir, el largo, alto y ancho de la misma. Estos valores se almacenan en las variables correspondientes.

-Luego, el programa solicita al usuario ingresar las dimensiones de un ladrillo, es decir, el largo, alto y ancho del ladrillo. Estos valores se almacenan en las variables largoLadrillo, altoLadrillo y anchoLadrillo.

-El programa calcula el área de la pared multiplicando su largo por su alto y almacena este valor en la variable areaPared.

-Luego, calcula el área de un ladrillo multiplicando su largo por su alto y almacena este valor en la variable areaLadrillo.

-Para determinar la cantidad de ladrillos necesarios, el programa realiza la división del área de la pared (areaPared) por el área de un ladrillo (areaLadrillo), y luego multiplica el resultado por el cociente del ancho de la pared (ancho) dividido por el ancho del ladrillo (anchoLadrillo). La función Math.ceil() se utiliza para redondear el resultado al número entero superior más cercano, ya que no se pueden utilizar fracciones de ladrillos.

-Finalmente, el programa imprime el resultado en la consola utilizando System.out.printf(). El mensaje muestra la cantidad de ladrillos necesarios para construir la pared, y se utiliza %.0f para formatear el número como un entero.

**En resumen, este programa calcula la cantidad de ladrillos necesarios para construir una pared dadas las dimensiones de la pared y los ladrillos, así como el ancho de la pared. Este cálculo se basa en el área de la pared y el área de un ladrillo, y redondea el resultado al número entero superior más cercano.**





