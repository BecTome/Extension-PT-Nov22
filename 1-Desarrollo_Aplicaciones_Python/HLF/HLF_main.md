# Hundir la Flota: Main App File

En este taller vamos a desarrollar el fichero que llama a las clases.

Los pasos que seguirá nuestro programa serán:

1. Crear un tablero para el jugador
2. Crear un tablero para la máquina
3. Crear un tablero púbico para la máquina
4. Crear un player que represente al jugador
5. Crear un player que represente a la máquina
6. Comienzan los turnos:
   1. El jugador dispara a la máquina a partir de inputs solicitados
   2. El tablero privado de la máquina se actualiza
   3. El tablero público de la máquina se actualiza a partir del privado
        mostrando los impactos y las aguas
   4. Se comprueba que el disparo ha sido en un lugar en el que no se disparó antes
   5. Se muestran los tableros
   6. Si el disparo ha sido en un barco, vuelve a tirar y a mostrar hasta que haga agua
   7. La máquina dispara al jugador de forma aleatoria
   8. Se repiten los pasos 2, 4, 5 y 6
   9. Se comprueba que aún le quedan barcos a los dos
   10. Turno siguiente