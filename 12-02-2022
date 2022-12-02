/* Instrucciones

Este año los elfos han comprado una máquina que envuelve regalos. Pero... ¡no viene programada! Necesitamos crear un algoritmo que le ayude en la tarea.

A la máquina se le pasa un array con los regalos. Cada regalo es un string. Necesitamos que la máquina envuelva cada regalo en papel de regalo y lo coloque en un array de regalos envueltos.

El papel de regalo es el símbolo * y para envolver un regalo se coloca el símbolo * de forma que rodee totalmente al string por todos los lados. Por ejemplo:

const gifts = ['book', 'game', 'socks']
const wrapped = wrapping(gifts)
console.log(wrapped)

/* [
     "******\n*book*\n******",
     "******\n*game*\n******",
     "*******\n*socks*\n*******"
   ] */

/*   
Como ves, el papel de regalo envuelve el string. Por arriba y por abajo, para no dejar ningún hueco, las esquinas también están cubiertas por el papel de regalo.

Nota:El carácter \n representa un salto de línea.

¡Ojo!Asegúrate que pones el número correcto de * para envolver completamente el string.

Y no modifiques (mutes) el array o

*/

const gifts = ['book', 'game', 'socks']
const wrapped = wrapping(gifts)
console.log(wrapped)

function wrapping (gifts) {
  const wrapped = []
  for (let i = 0; i < gifts.length; i++) {
    const numbersymbols = gifts[i].length + 2
    const symbols = '*'.repeat(numbersymbols)
    wrapped.push(symbols +'\n*' + gifts[i] + '*\n'+ symbols)
  }
  return wrapped
}
