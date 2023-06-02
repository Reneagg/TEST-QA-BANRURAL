##Numero aleatorio entero en linea 44
Para generar un número entero aleatorio entre 1-100 se debe utilizar el metodo Math.floor el cual quedaría let randomNumber = Math.floor((Math.random() * 100) + 1); agregando una suma de +1 ya que este comienza a contar desde el 0.
##Cantidad de intentos en la linea 46
El programa pide que se realicen un maximo de 10 intentos pero solo cuenta con 5 por lo cual la forma correcta como debería de quedar es: const ATTEMPS = 10;
##Error en la linea 49
No se estaba llamando de forma correcta al div, la forma correcta sería const lowOrHi = document.querySelector('.lowOrHi'); colocando el punto al principio del nombre
##Numero entero para funcionar
El juego solicita que solo funcione con numeros enteros por lo cual hay que realizar una validación de que el numero ingresado por el usuario sea entero d elo contrario debe mostrar una alerta indicando que el numero no es valido.
##Error en la función para reiniciar el juego
En las líneas 87 y 95 estaba escrito: guessSubmit.addeventListener('click', checkGuess); cuando la forma correcta sería guessSubmit.addEventListener('click', checkGuess); colocando la "E" de Event con mayuscula
##Error en los colores de numero mayor y menor
Mostraba el mensaje de "El numero es mayor y menor" en color verde cuando el juego solicita que sea de color negro
##Error en el color al acertar el numero
Al adivinar el numero mostraba el mensaje en color rojo, dicho mensaje se tiene que mostrar en color verde
##Error en el color de mensaje "Perdiste"
Al perder el juego el mensaje de "Perdiste" se muestra de color negro, dicho mensaje tiene que ser mostrado de color verde
##Error al mostrar los mensajes
Estaban intercambiados los mensajes del juego, al adivinar el numero mostraba el mensaje de "Perdiste" y al perder el juego mostraba el mensaje de Felicitaciones! adivinaste el número!
##Corrección en la linea 114
randomNumber = randomNumber = Math.floor((Math.random() * 100) + 1);
##Corrección mensaje Numero menor
Al ingresar un numero menor mostraba "el numero es mayor" 
##Corrección mensaje Numero Mayor
Al ingresar un numero menor mostraba "el numero es menor"
##Validación de signo correcto
En la linea 64 solamente se debe usar 2 signos "="
