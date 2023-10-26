Antes de ensuciarnos las manos con aprender a construir una computadora, hablemos primero de teoría. En una lección anterior, se habló de binario y cómo las computadoras realizan los cálculos. Recuerda que nuestra computadora solo puede comunicarse en binario usando unos y ceros. Nuestras computadoras hablan en lenguaje de máquinas, pero nosotros, por supuesto, hablamos en lenguajes humanos, como Inglés, Español, Mandarín, Hindi. Ya captas la idea. Si queremos comunicarnos con otras máquinas, tenemos que usar algún diccionario de traducción. Si yo quiero decir algo en español, lo busco en un diccionario Inglés - Español.

Bien. Nuestras computadoras tienen incorporado su propio libro de traducciones. En esta lección, profundizaremos en cómo nuestra computadora traduce la información que le damos en instrucciones que entiende. Ahora mismo, quizá, estás utilizando un navegador web, un reproductor de música, un procesador de texto o algo más en la computadora. Interactuamos con estas aplicaciones a diario. Se les conoce como programas. Los programas son instrucciones básicas que le dicen a la computadora qué hacer.

Técnicamente almacenamos programas en medios duraderos como discos duros. Puedes pensar en programas como recetas de cocina. Todas estas recetas se guardan juntas en un libro de cocina, al igual que las aplicaciones se almacenan en un disco duro. Ahora queremos hacer una tonelada de comida. Así que contratamos a un chef para que siga nuestras recetas y prepare algo bueno. Cuanto más rápido trabaje nuestro chef, más comida preparará. El chef es nuestra CPU, procesa las recetas que le enviamos y prepara la comida. Nuestro chef trabaja súper rápido, tan rápido que puede cocinar más rápido de lo que puede leer. Así que, tomamos copia de las recetas y las ponemos en la memoria RAM.

Recuerda que la RAM es la memoria a corto plazo de nuestro ordenador. Almacena información en una ubicación en la que nuestro CPU puede acceder más rápido de lo que podría con nuestro disco duro. Ahora podemos darle a nuestro chef una o dos recetas a la vez, en vez de recitarle todo el libro de cocina.

Bien, ahora digamos que quiero hacer un sándwich de mantequilla de maní y jalea. Veo una receta bastante buena, y se la mando a nuestro chef para que la haga. Recuerda que nuestro chef necesita estas instrucciones rápidamente, por lo que no le envío la receta completa, le envío una línea a la vez.

1.  Consigue dos rebanadas de pan.
2.  Pon mantequilla de cacahuete en un portaobjetos.
3.  Pon la jalea en otra rebanada.
4.  Combina las dos rebanadas de pan.

Ahora, déjame decirte una cosa más. Nuestro chef solo puede comunicarse con nosotros en unos y ceros. Así que en vez de enviar algo legible, como la receta de una mantequilla de maní y sándwich de jalea, tenemos que enviarle algo como esto. En realidad, este proceso es un poco más complicado. Nuestra CPU está constantemente tomando instrucciones y ejecutándolas. Estas instrucciones están escritas en binario pero ¿cómo viajan por el ordenador?

En nuestro ordenador, tenemos algo llamado el Bus de Datos Externos o EDB. No se parece en nada a un autobús. Es una fila de cables que interconectan las partes de nuestra computadora, algo así como las venas de nuestro cuerpo. Cuando usted envía un voltage uno de los cables, decimos que el estado del cable está encendido, representado por un 1. Si no hay voltaje, entonces decimos que el estado está apagado, representado por un 0. Así es como enviamos nuestros unos y ceros. ¿Te suena? La última lección hablamos sobre cómo los transistores nos ayudan a enviar voltajes. Ahora sabemos cómo nuestros bits viajan físicamente alrededor de la computadora.

El EDB viene en diferentes tamaños, 8 bits, 16 bits, 32, incluso 64. ¿Te imaginas si tuvieras 64 cables en marcha? Puedes moverte por muchos más datos. En este momento, vamos a seguir usando un EDB con 8 bits en nuestros ejemplos. Enviando 1 byte a la vez. Bien, nuestra CPU está recibiendo un byte y necesita ponerse a trabajar. Dentro de la CPU hay componentes conocidos como Registros. Nos permiten almacenar los datos con los que trabaja nuestra CPU. Si, por ejemplo, nuestra CPU quisiera añadir dos números, un número se almacenaría en un registro "A". Otro número se almacenaría en el registro "B". El resultado de estos dos números se almacenaría en el registro "C". Imagina que el registro es una de las mesas de trabajo de nuestro chef. Como tiene un lugar para trabajar, puede empezar a cocinar. Para ello utiliza un libro de traducción para traducir su binario en tareas que puede realizar.

Retrocedamos un segundo. Recuerda que nuestros programas se copian en la memoria RAM para que la CPU los lea. RAM es la memoria a la que se accede aleatoriamente, permitiendo a nuestra CPU leer desde cualquier parte de la RAM tan rápidamente como desde cualquier otra parte. En realidad no enviamos datos desde la RAM a través del EDB. Habría muchas cosas. La memoria RAM puede contener millones, incluso miles de millones, de filas de datos. A pesar de nuestro ejemplo de sándwich, la mayoría de nuestras recetas no son nada sencillas. Puede haber miles de líneas largas. Queremos procesarlas y en realidad no vamos en ningún orden en particular.

Ya que sólo podemos enviar una línea de datos a través del EDB a la vez, necesitamos la ayuda de otro componente, el Memory Controller Chip (Chip Controlador de Memoria) o MCC. El MCC es un puente entre la CPU y la RAM. Puedes pensar en, un nervio en tu cerebro conectándose con tus recuerdos. El PC habla con el MCC, y dice: "Oye, necesito las instrucciones para el paso número tres de esta receta. El MCC encuentra las instrucciones para el paso número tres en la RAM,

toma los datos, y lo envía a través del EDB.

Hay otro bus. No hay nada como un bus involucrado en el proceso llamado el bus de dirección. Conecta la CPU con el MCC, y envía la ubicación de los datos, pero no los datos en sí. Entonces el MCC toma la dirección y busca los datos. Y entonces los datos se envían a través del EDB.

Lo creas o no, la RAM no es la forma más rápida de obtener más datos a nuestra CPU para procesarla. La CPU también utiliza algo conocido como Caché. La caché es más pequeña que la RAM, pero nos permite almacenar los datos que usamos a menudo, y nos permite una referencia más rápida. Piensa en RAM como un refrigerador lleno de comida. Es fácil entrar, pero lleva tiempo sacar algo. Por otro lado, el caché es como las cosas que tenemos en nuestros bolsillos. Se utiliza para almacenar datos de acceso reciente o frecuente. Hay tres niveles de caché diferentes en una CPU: L1, L2 y L3.

L1 es el caché más pequeño y rápido. Si estás interesado en saber más sobre esto, pueden ver la lectura suplementaria que he incluido justo después de este vídeo. Así que ahora entendemos cómo interactúa nuestra RAM con nuestra CPU. Pero, ¿cómo sabe nuestra CPU cuándo termina el conjunto de instrucciones y comienza una nueva? Nuestra CPU tiene un reloj interno que mantiene su funcionamiento sincronizado. Se conecta a un cable especial llamado cable del reloj. Cuando usted envía o recibe datos, envía un voltaje a ese cable del reloj para permitir que la CPU sepa que puede empezar a hacer cálculos. Piensa en nuestros cables del reloj como el tic-tac de un reloj.

Por cada tictac, la CPU realiza un ciclo de operaciones. Cuando se envía un voltaje al cable del reloj, se le llama ciclo de reloj. Si tienes muchos datos, necesitas procesar en un comando. Necesita ejecutar muchos ciclos de relojes. ¿Has visto alguna vez una CPU en una tienda y tiene algo etiquetado como 3.4GHZ? Este número se refiere a la velocidad del reloj de la CPU. Es un número máximo de ciclos de reloj que puede manejar en un conjunto en determinado de período de tiempo. 3.40 gigahertz son 3.4 billones de ciclos por segundos. Eso es súper rápido.

Pero solo porque pueda correr a esta velocidad, no significa que lo haga. Solo significa que no puede exceder este número. Aún así, ese número no impide que algunas personas lo intenten. Hay una manera de que puedas exceder el número de ciclos de reloj en su CPU, y en casi cualquier dispositivo. Se le conoce como Overclocking y aumenta la velocidad de los ciclos del reloj de su CPU para realizar más tareas. Esto se utiliza comúnmente para aumentar el rendimiento en las CPUs de gama baja. Digamos que eres un jugador y quieres tener mejores gráficos y menos retraso en el juego. Puede que quieras overclockear tu CPU cuando juegues el juego, pero hay desventajas en hacer esto, como sobrecalentar potencialmente tu CPU. Puedes leer más sobre el overclocking en la próxima lectura suplementaria.