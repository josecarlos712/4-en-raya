# 4-en-raya. Practica 1 de IA

## CHANGELOG

- El metodo setup crea el tablero
- Activando el metodo mouse-manager en bucle comienza la detección del mouse sobre el tablero
- Si se clicka en una casilla se van poniendo las fichas de un color distinto alternativamente dependiendo del turno
- Agregada función. Cuando se agrega una tortuga tiene que ser siempre en "abajo", es decir, formando una pila de tortugas hacia arriba, no se puede poner en cualquier sitio del tablero.
- Se va guardando el estado del tablero en una matriz bidimensional para poder realizar comprobaciones del estado mas facilmente
- Se puede añadir una ficha haciendo click en el tablero o por comando escongiendo la x (ya que la y es automatica). Servira para cuando la IA tenga que poner una ficha.
- Añadida la comprobación de ganador por filas y columnas
- Cuando algún jugador gana, ya no se pueden poner mas fichas en el tablero
- Adaptado el juego para n*n (no es necesario creo, se puede quitar en un futuro aunque wikipedia dice un tamaño y la página 
  de las reglas que están en la página de Fernando dicen otro).
- Añadido límite de tortugas para una columna.
- Arreglado pequeño error con la comprobación del ganador anterior.
## TO-DO

