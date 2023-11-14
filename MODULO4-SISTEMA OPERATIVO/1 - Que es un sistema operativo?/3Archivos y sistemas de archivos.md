Imagina si tuvieras que guardar un solo archivo dentro de un armario. ¿Eso no tan malo, verdad? ¿Qué pasa si, en lugar de un archivo, tienes que almacenar 100.000? Puedes ver el problema? Pues bien, en nuestros ordenadores, nosotros fácilmente podemos almacenar cientos de miles de archivos, si no es que más. ¿Problema solucionado? No del todo, tenemos que ser capaces de hacer un seguimiento de todos estos archivos.

El kernel del SO se encarga del almacenamiento de los archivos y del Sistema de archivos en nuestras máquinas. Y en esta lección vamos a profundizar un poco en cómo lo hace. Hay tres componentes principales para el manejo archivos en un sistema operativo: los datos de archivo, metadatos y el sistema de archivos.

Vamos a empezar con el sistema de archivos. Cuando tenemos un disco duro nuevo que queremos para almacenar datos, tenemos que borrar y configurar el disco. De esta manera, nuestro sistema operativo puede leer y escribir datos en él. Esto es importante, ya que así es como nuestro sistema operativo mantiene un registro de archivos. Por lo que se debe saber qué tipo de sistema de archivos es utilizado.

Hay muchos sistemas de archivos, y ellos se utilizan para diferentes propósitos. Algunos sistemas de archivos ofrecen el soporte el almacenamiento de grandes cantidades de datos, otros sólo admiten pequeñas cantidades. Los sistemas de archivos pueden operar a diferentes velocidades y tener diversa resiliencia hacia la corrupción de archivos y así sucesivamente. Nosotros no entraremos en determinar cuál sistema es mejor. Eso es para que usted decida. Pero los principales fabricantes de sistema operativo tienen sus propios sistemas de archivo único que ellos recomiendan.

Para Windows, el sistema de archivos principal que se utiliza es NTFS. Fue introducido en la versión anterior del sistema operativo Windows, Windows NT. E incluye muchas características, como la encriptación, velocidades más rápidas de acceso, seguridad y mucho más. Microsoft está desarrollando otro sistema de archivos llamado ReFS, pero todavía no está totalmente listo para el usuario. Si tú estás interesado en aprender más, puedes leer más sobre él en la siguiente lectura complementaria.

Para Mac OS, el sistema de archivos predeterminado es HFS+. Es transaccional, lo que significa que hace un mejor trabajo recuperando el estado del disco en caso de falla. Esta es una característica en otros tipos de sistemas de archivos, como NTFS.

Para Linux, distribuciones diferentes utilizarán diferentes tipos de sistema de archivo. Un estándar para sistemas de archivos para Linux es ext4, que es compatible con los más viejos sistemas de archivo ext. En general, tipos de sistema de archivos diferente no interactúan muy bien con los demás. Tal vez no seas capaz de mover fácilmente archivos entre sistemas de archivos diferentes, lo anterior está dependiendo del tipo de sistema de archivo. Una buena pauta a seguir es solo utilizar el sistema de archivos que recomiende tu sistema operativo. Puedes leer más sobre los diferentes tipos de sistemas de archivos en la lectura complementaria.

Otra parte importante de la gestión de archivos es el almacenamiento de datos del archivo. Escribimos los datos en nuestro disco duro en forma de bloques de datos. Cuando salvamos algo en nuestros discos duros, no siempre se aloja en una sola pieza. Puede ser dividida en muchas piezas y escrita a diferentes partes del disco. El almacenamiento en bloque mejora el manejo rápido de datos porque los datos no son almacenados en una larga pieza y puede ser encontrado más rápido. También es mejor para la utilización de espacio de almacenamiento.

Por último, tenemos que mantener los metadatos que contiene la información de nuestro archivo. Hay mucha información acerca de nuestro archivo que nosotros queremos saber, como quién lo ha creado, cuándo fue la última modificación, quién tiene acceso a él y así sucesivamente. Los metadatos de archivo nos dicen todo lo que necesitamos saber sobre nuestro archivo. También nos dice qué tipo de archivo es. Una extensión de archivo es la parte anexa de un nombre de archivo que nos dice qué tipo de archivo es, en ciertos sistemas operativos. Por ejemplo, cool_image.jpeg. JPEG es una extensión de archivo asociada con los archivos de imagen. Tu verás diferentes tipos de extensiones de archivo como este cuando tú estás trabajando con el sistema operativo.

Conocimientos de sistemas de archivos y las diferencias entre ellos es una gran habilidad que se debe tener en la caja de herramientas del especialista en soporte IT. Puede ser muy útil cuando necesitas hacer cosas como recuperar datos de discos dañados. O explorar formas para que el arranque desde dos tipos de sistemas operativos diferentes, como Windows y Linux, en el mismo equipo.