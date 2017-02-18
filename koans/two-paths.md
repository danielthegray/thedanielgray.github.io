---
layout: koan
---
## El Maestro Foo Diserta sobre los Dos Caminos
_(tomado de <http://catb.org/esr/writings/unix-koans/two_paths.html> y traducido el día 2017-02-17)_

El maestro Foo instruía a sus estudiantes:

"Hay una línea en la enseñanza de los Dharma's, ejemplificada por el mantra 'Haz una cosa bien' del Patriarca McIlroy, que enfatiza que el software participa del camino Unix cuando tiene un comportamiento simple y consistente, con propiedades que pueden ser fácilmente modeladas por la mente del usuario y usadas por otros programas."

"Sin embargo, hay otra línea de pensamiento dharmático (ejemplificada por el gran mantra del Patriarca Thompson 'En caso de duda, usa la fuerza bruta', y varios sutras acerca del valor de abarcar el 90% de los casos ahora, que el 100% después) que enfatiza la robustez y la simplicidad de la implementación."

"Ahora díganme: ¿qué programas tienen la naturaleza de Unix?"

Después de un periodo de silencio, Nubi comentó:

"Maestro, estas enseñanzas pueden entrar en conflicto."

"Una implementación simple muy probablemente carecerá de lógica para casos extremos/excepcionales, como agotamiento de recursos, o no cerrar una _race window_, o un _timeout_ durante una transacción no terminada."

"Cuando esos casos se presenten, el comportamiento del software se tornará irregular y difícil. ¿Ese ciertamente no es el Camino de Unix, no?"

El maestro Foo asintió con la cabeza.

"Por otro lado, es algo conocido que los algoritmos complejos son frágiles. Además, cada intento de cubrir un caso excepcional tiende a interactuar tanto con los algoritmos centrales del programa como con el código que cubre otros casos de ese tipo."

"Así, intentar cubrir todos los casos extremos por adelantado, garantizando 'simplicidad de descripción' puede en realidad producir código que por demás complicado y frágil, o que, plagado de _bugs_, nunca sea liberado al público. ¿Ese ciertamente no es el Camino de Unix, no?"

El maestro Foo asintió con la cabeza.

"¿Cuál es, entonces, el camino dharmático apropiado?", preguntó Nubi.

El maestró habló:

"Cuando el águila vuela, ¿olvida que sus pies han tocado el suelo? Cuando el tigre cae sobre su presa, ¿olvida su momento en el aire? ¡Tres libras de VAX!"

Al oír esto, Nubi fue iluminado.
