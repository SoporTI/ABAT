Una de las tareas más importantes que realiza nuestro kernel es la Gestión de Procesos. Un proceso es un programa que se está ejecutando, como nuestro navegador o editor de texto. Un programa es una aplicación que podemos ejecutar, como Chrome. Tome nota de la diferencia.

Podemos tener muchos procesos del mismo programa funcionando al mismo tiempo. Piensa en cuántas ventanas de Chrome puedes abrir. Todas son diferentes procesos para el mismo programa.

Cuando queremos ejecutar nuestros programas, tenemos que dedicarles recursos informáticos, como RAM y CPU. Solo tenemos una cantidad finita de recursos y queremos ser capaces de ejecutar varios programas. Un núcleo tiene que gestionar nuestros recursos de forma eficiente, de forma que se puedan ejecutar todos los programas que queremos usar.

Nuestro kernel no solo dedica todos los recursos de nuestras computadoras a un proceso. Nuestro sistema está realmente ejecutando constantemente múltiples procesos que son necesarios para su funcionamiento, así que nuestro kernel tiene que preocuparse de todos estos procesos a la vez.

Lo que un programa quiere ejecutar, necesita un proceso que sea creado para él. Este proceso necesita tener más recursos como memoria RAM y CPU. El kernel tiene que programar el tiempo de la CPU para ejecutar las instrucciones del proceso.

Pero hay sólo una CPU y varios procesos. ¿Cómo hace a la CPU capaz de ejecutar varios procesos a la vez? Realmente lo hace, ejecuta uno por uno los procesos a través de algo conocido como un segmento de tiempo. Un segmento de tiempo es un muy breve intervalo de tiempo que es asignado a un proceso para su ejecución por la CPU. Es tan corto que incluso no te darías cuenta. Quiero decir, es súper corto.

La CPU ejecuta un proceso en milisegundos, luego ejecuta otro proceso, luego otro. Para el ojo humano todo parece ejecutarse al mismo tiempo, así es cómo de rápido trabaja la CPU.

Si tu equipo se ejecuta lentamente y los recursos de tu CPU están al máximo, podría haber muchos factores en juego. Es posible que un proceso esté ocupando más segmentos de tiempo de lo debido. Esto significa que el siguiente proceso no puede ser ejecutado. Otra posibilidad es que haya demasiados procesos que quieran tiempo de CPU y la CPU no pueda mantenerlos a todos.

En cualquier caso, a pesar de que el núcleo hace todo lo posible para gestionar procesos para nosotros, podríamos tener que intervenir manualmente de vez en cuando. Hablaremos acerca de cómo gestionar los procesos en un curso posterior.

El kernel crea procesos, los programa eficientemente y gestiona cómo se cancelan los procesos. Esto es importante ya que necesitamos una manera de recoger todos los recursos previamente usados que procesos activos fueron ocupando y reasignarlos a otro proceso.
