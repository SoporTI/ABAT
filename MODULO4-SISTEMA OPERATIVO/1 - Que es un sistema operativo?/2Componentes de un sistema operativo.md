Hemos introducido el concepto de sistema operativo en lecciones anteriores pero, ¿qué es exactamente? Muchos de nosotros al escuchar el término sistema operativo pensamos en las interfaces de nuestros ordenadores y teléfonos, como los menús, botones y fondos. Técnicamente, estos son parte del sistema operativo, pero es un poco más complicado que eso. Un sistema operativo es el conjunto que gestiona los recursos de nuestro ordenador y nos permite interactuar con él. Hay dos partes principales en un sistema operativo, el kernel y el espacio de usuario. El kernel es el núcleo principal de un sistema operativo. Habla directamente a nuestro hardware y gestiona los recursos del sistema. Como usuarios, no interactuamos directamente con el kernel. En cambio, interactuamos con la segunda parte del sistema operativo, el espacio de usuario. El espacio de usuario está compuesto básicamente por todo aquello fuera del kernel. Las cosas del usuario con las que interactuamos directamente como programas del sistema, interfaces de usuario, etcétera. Cuando decimos sistema operativo, estamos hablando de los dos, kernel y espacio de usuario.

Hay cientos de sistemas operativos, pero nos centraremos en los más importantes usados en TI; Windows, Mac y Linux. El sistema operativo Windows está desarrollado por Microsoft y es usado ampliamente en el espacio de negocios y doméstico. La mayoría de los PCs que se compran vienen con Windows como sistema operativo por defecto. PC significa Personal Computer, que técnicamente significa un ordenador usado por una persona. Pero en el mundo actual, PC es más comúnmente empleado para referirse a un ordenador con Windows. Así que, nos referiremos a un PC como a un ordenador con Windows desde aquí. El sistema operativo Mac de Apple, se utiliza principalmente en el espacio del consumidor. Si compras un ordenador Apple, vendrá con Mac OS instalado. El último sistema operativo en el que vamos a sumergirnos es el sistema operativo Linux. Linux es un sistema operativo de código abierto, lo que significa que es un software libre para ser compartido, modificado y distribuido. Linux está muy extendido en la infraestructura de negocios y en el ámbito doméstico. Linux en sí mismo es realmente un kernel desarrollado por Linus Torvalds. Por cómo ha evolucionado, llamamos al kernel Linux el sistema operativo Linux. Hoy en día, Linux se ha convertido en un gran esfuerzo comunitario con desarrolladores de todo el mundo contribuyendo a su éxito. porque Linux es de código abierto, gran cantidad de organizaciones diferentes compilan su propia versión. Sistemas operativos como Windows o Macintosh por el contrario, son desarrollados exclusivamente por sus respectivas compañías. Llamamos estos diferentes sistemas operativos Linux distribuciones. Algunas distribuciones comunes de Linux son Ubuntu, Debian y Red Hat.

Otro sistema operativo que ha comenzado a ganar popularidad es Chrome OS, pero no entramos en detalle sobre eso. Puedes leer más sobre él en la lectura complementaria justo después de este vídeo. Tampoco vamos a tratar sobre ninguno de los sistemas operativos empleados en dispositivos móviles como Android OS, iOS y Windows 10 mobile. Pero deberías tener en cuenta que los sistemas operativos de los teléfonos móviles están superando rápidamente a sus homólogos de escritorio en términos de cantidad. El uso del teléfono móvil en el mundo es más frecuente que el de los ordenadores de escritorio. Puedes leer más sobre esto en las lecturas complementarias. Pero en este curso nos vamos a centrar solo en los sistemas Windows y Linux puesto que serán con los que seguramente trabajes en soporte TI.

Algo guay a resaltar es que Chrome OS y Android OS corren ambos el kernel de Linux debajo del capó. Así que existe la posibilidad de que ya hayas trabajado con Linux y no lo sepas. Hay un montón de sistemas operativos ahí fuera y todos ellos comparten características comunes. Si eres capaz de entender los pilares básicos de un sistema operativo, los puedes aplicar a cualquier sistema operativo y entender cómo funciona. En el soporte TI es muy común trabajar con muchos sistemas operativos distintos desde sistemas de escritorio a sistemas de teléfonos inteligentes y más.

A través del resto de este módulo, vamos a aprender qué es un sistema operativo. Más concretamente, vamos a aprender acerca de los dos componentes que conforman un sistema operativo, el espacio de kernel y el espacio de usuario. Antes de llegar allí, vamos a hacer un resumen de los fundamentos. El kernel efectúa el almacenamiento de archivos en la gestión de archivos. Puedes compararlo con el archivo de una oficina física donde almacenamos los datos en un formato de papel. Un archivo de ordenador es simplemente datos que almacenamos y un archivo pude ser cualquier cosa, un documento de word, una imagen, una canción, literalmente cualquier cosa. Un sistema de archivos es cómo gestionamos estos archivos, tal y como en una oficina utilizamos un sistema para almacenar nuestros archivos. No solo ponemos todos nuestros archivos en un armario, eso sería extremadamente desordenado. En su lugar, organizamos los archivos en carpetas o directorios para hacerlos más fácil de encontrar.

Hay un montón diferente de sistemas de archivos distintos, que cubriremos más en profundidad en futuros videos. Otra función importante del kernel es la gestión de procesos. Tenemos muchos programas que queremos ejecutar en nuestro sistema. Para ejecutarlos, gestionamos el orden en que se ejecutan, Cuántos recursos utilizan, Cuánto se ejecutan, etcétera. Nuestro kernel nos ayuda a hacer esto con sus capacidades de gestión de proceso. Por ejemplo, probablemente has usado tu ordenador para hacer varias tareas a la vez. Tal vez escribes en un documento de texto mientras escuchas música o reproduces un vídeo. El planificador de proceso es la parte del kernel que hace posible esta multitarea. Él cambia la ejecución de cada proceso diferente en la CPU más rápido de lo que puedes parpadear, y te da la ilusión de que las cosas están sucediendo simultáneamente.

La siguiente es la gestión de memoria. Nuestro núcleo optimiza el uso de la memoria y asegura que nuestras aplicaciones tengan memoria suficiente para ejecutarse. No entraremos en demasiados detalles por ahora, así que estad atentos para más información sobre esto en siguientes vídeos. La última función importante que realiza un kernel es la entrada/salida o administración de I/O. Se trata de cómo nuestro kernel habla con dispositivos externos como discos, teclados, redes, conexiones, dispositivos de audio y más. La administración de I/O es cualquier cosa que nos puede dar entrada o que podemos utilizar para salida de datos. Si alguna vez has guardado un archivo en un disco, haces clic en el botón del ratón, usas un micrófono haciendo un vídeo chat con un amigo, tienes que darle las gracias a la capacidad del kernel para la gestión I/O.

Y ese es el resumen de las funciones principales del kernel; gestión de archivos, gestión de procesos, gestión de memoria y administración de I/O. Por último, vamos a hablar sobre el otro componente de un sistema operativo, el espacio de usuario. El espacio de usuario es todo fuera del kernel. Estas son las cosas con las que nos relacionamos directamente, como los programas, como editores de texto, reproductores de música, configuración del sistema, interfaces de usuario, etcétera. Al final de este módulo, usted tendrá con suerte una sólida comprensión de todas estas funciones de un sistema operativo. Empecemos por tomar una inmersión más profunda en la administración de archivos del kernel.