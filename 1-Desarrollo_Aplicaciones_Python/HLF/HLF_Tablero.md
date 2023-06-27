# Hundir la Flota: Clase Tablero

En este taller vamos a desarrollar la clase Tablero. Para ello, primero tendremos que definir lo que necesitamos:

1. **Constantes**: ¿Qué características editables tendrá nuestro tablero?
    * Tamaño (Por ejemplo, será 10x10)
    * El símbolo con el que representaremos nuestro barco
    * Los barcos que vamos a ubicar en él
    * El símbolo para el “Agua”
    * El símbolo para el “Impacto”
    * El símbolo para el “Vacío” (Antes de que haya un disparo en esa celda)

Esto serán nuestros atributos de clase.

2. **Acciones y métodos**: Definiremos un único objeto que será el propio tablero.
    * Se construirá en el *\_\_init\_\_* de la clase y será un array
    * Definiremos un **método para colocar los barcos** dando una posición inicial y una orientación
      * Ejemplo 1: (0,0) y Este con tamaño 3 irá del (0,0) al (0,2)
      * Ejemplo 2: (0,0) y Sur con tamaño 3 irá del (0,0) al (2,0)
      * Ejemplo 3: (4,0) y Norte con tamaño 3 irá del (4,0) al (2,0)
      * Ejemplo 4: (0,4) y Oeste con tamaño 3 irá del (0,4) al (0,2)
    * Crearemos un **método de validación** para comprobar:
      * Condición de frontera: La posición no se sale del tablero
      * Condición de solapamiento: No se solapa con otro barco
    * Crearemos un **método de inicialización random** de los barcos

