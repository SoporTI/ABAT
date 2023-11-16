Anteriormente en este curso
hemos hablado acerca de cómo los programas son instrucciones que se dan a la CPU. Podemos enviar código binario o bits a nuestras CPUs, que luego usarán un conjunto de
instrucciones para ejecutar esos comandos. Pero estas CPUs pueden proceder de diferentes
fabricantes y pueden tener diferentes instrucciones. Incluso puede haber todo tipo de componentes hardware diferentes, como tarjetas de vídeo y discos duros, que también tienen sus propias interfaces especiales. Así que, ¿cómo escribimos un
programa que pueda entender el hardware? Bien, una forma podría ser escribir
un programa para cada combinación posible de CPU y hardware usando el lenguaje
nativo y las interfaces de estos componentes, pero hay potencialmente millones
de posibles configuraciones de hardware. Entonces, ¿cómo conseguimos que algo
funciones con todo este complejo y diverso hardware? Bueno, gracias a los esfuerzos de los investigadores
en computación y el principio de la abstracción, ahora podemos utilizar lenguajes de programación para escribir instrucciones que puedan ejecutarse en cualquier hardware.