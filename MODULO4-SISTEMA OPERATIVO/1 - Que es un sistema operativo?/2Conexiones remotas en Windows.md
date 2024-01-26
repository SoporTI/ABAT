> [!TIP]  
> [Ver video](https://youtu.be/bjYB1Kbm_Sk)

Poder establecer conexiones remotas es igual de útil en computadoras con Windows.
PuTTY es un software gratis de código abierto que puedes usar para crear conexiones remotas a través de varios protocolos de redes, incluido SSH. Visita el sitio web de PuTTY para descargar el paquete de software con el instalador de Microsoft. Esos son los archivos MSI que mencionamos antes. O puedes elegir un ejecutable específico que brinde las funciones que necesitas como PuTTY.exe. La página de descargas de PuTTY está vinculada en la siguiente lectura por si quieres visitarla.

Cuando hayas descargado e instalado PuTTY, puedes lanzar la GUI para usarlo. Aparecerá una ventana con las opciones básicas para tu conexión. Anota el nombre del host, el puerto y las opciones de tipo de conexión. El puerto está establecido en 22 porque es el predeterminado que usa el protocolo SSH y el tipo de conexión está establecido en SSH. Solo debes escribir el nombre del host o la dirección IP de la computadora a la que te quieres conectar y hacer clic en "Abrir" para comenzar una nueva sesión de SSH.

Establecí una conexión SSH con una computadora remota. Ejecutar PuTTY desde la GUI no es tu única opción. También puedes usarlo en la línea de comandos. Abre el símbolo del sistema de PowerShell y escribe el nombre de la aplicación, así. Luego, agrega la opción -ssh para indicar que quieres conectarte a través de SSH. O puedes proporcionar el usuario y la dirección con el formato usuario arroba dirección IP, y especificar el puerto al final. El comando completo se vería así.

PuTTY también tiene una herramienta llamada plink o vínculo PuTTY y se integra en la línea de comando después de instalar PuTTY. También puedes usar plink para establecer conexiones remotas de SSH. SSH puede ser muy útil, sobre todo si quieres conectarte de una computadora con Windows a un sistema operativo Linux que se ejecuta remotamente.

Microsoft brinda otra forma de conectarse a computadoras con Windows y se llama protocolo de escritorio remoto o RDP. También hay clientes de RDP para Linux en el SO 10 como RealVNC y Microsoft RDP en Mac. Agregaremos vínculos a esos clientes en la lectura complementaria.

RDP les brinda a los usuarios una interfaz gráfica en computadoras remotas siempre que la computadora remota haya habilitado las conexiones RDP entrantes. Un programa para clientes llamado Terminal Services de Microsoft o mstsc.exe se usa para crear conexiones RDP a computadoras remotas.

Para habilitar las conexiones remotas en tu computadora, abre el menú Inicio haz clic con el botón derecho en Este equipo y selecciona propiedades. Luego, selecciona Configuración remota. Elige una opción en Escritorio remoto, en el panel. Hay implicaciones de seguridad si permites que las personas se conecten remotamente a tu computadora. Solo debes permitir que los usuarios confiables lo hagan. En general, en un entorno industrial, esos tipos de parámetros los configura el administrador del sistema de las computadoras de la empresa que se conectan a la red.

Cuando permitas las conexiones en la computadora remota y, si estás en la lista de usuarios con permiso de acceso podrás usar el cliente de protocolo de escritorio remoto mstsc.exe para conectarte desde cualquier lugar en la red.

Puedes lanzar el cliente RDP de varias formas. Puedes escribir mstsc en el cuadro de ejecución o buscar conexiones de escritorio remoto en el menú Inicio. Cuando lances el cliente, te solicitará el nombre o la dirección IP de la computadora a la que te quieres conectar. El cliente RDP de Windows también se puede iniciar en la línea de comandos en la que puedes especificar más parámetros como /admin si quieres conectarte a la máquina remota con credenciales administrativas.






