Recuerda que cuando un proceso corre, éste necesita tiempo de CPU, pero también necesita memoria. Cuando los procesos corren, tienen que tomar más espacio en la memoria, de tal forma que la computadora los pueda leer y cargar rápidamente.

Sin embargo, comparado con nuestros discos duros, la memoria llega en cantidades pequeñas. Así que, para obtener más memoria como la que hay físicamente, usamos algo llamado **memoria virtual**. La memoria virtual es una combinación de espacio de disco duro y RAM que actúan como memoria para que nuestros procesos la puedan usar.

Cuando ejecutamos un proceso, tomamos los datos del programa en pedazos llamados páginas. Almacenamos estas páginas en la memoria virtual. Si queremos leer y ejecutar estas páginas, éstas tienen que ser enviadas a la memoria física o a la RAM.

¿Por qué no almacenar todo el programa en RAM tal que pueda ejecutarse rápidamente? Pues, se podría si éste fuera bastante pequeño, pero para aplicaciones grandes, esto podría ser muy desperdiciado. ¿Alguna vez has trabajado en un procesador de textos, ir a un menú que normalmente no usas, y notar que la aplicación va un poco más despacio? Esto es porque tu computadora tuvo que cargar la página para ese menú desde la memoria virtual a la RAM. No usamos todas las características de nuestra aplicación de una vez. Así que ¿Por qué cargar todo de una vez?

Esto es parecido como cuando cocinamos una receta de un libro de cocina. No necesitas leer todo el libro sólo para preparar una receta. Sólo necesitas leer las páginas de la receta que estas preparando.

Cuando almacenamos la memoria virtual en el disco duro, llamamos al espacio asignado, **espacio de intercambio (swap space)**. Cuando nos metemos en aplicaciones prácticas de partición de disco, también asignaremos el espacio para intercambio.

El kernel toma cuidado de todo esto por nosotros, absolutamente. Éste maneja el proceso de toma de página de datos y los intercambia entre la RAM y la memoria virtual. Pero, el kernel no hace todo el trabajo acerca de esto.

Has hecho un gran trabajo a través de las lecciones hasta ahora. Buen trabajo. ¡Hasta la próxima! Ahora abordaremos la **administración de Entrada/Salida (I/O management)**. Nos vemos allí.
