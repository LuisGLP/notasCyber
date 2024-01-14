
Aprenderás acerca de la relación entre los sistemas operativos, el hardware y el software, y te familiarizarás con las funciones principales de un sistema operativo. Además, reconocerás los sistemas operativos comunes más comunes utilizados en la actualidad y comprenderás cómo tanto la interfaz gráfica de usuario (GUI) como la interfaz de línea de comandos (CLI) permiten a los/as usuarios/as interactuar con el sistema operativo.
![[Pasted image 20231027235718.png]]
Cinco íconos muestran el curso seguido de las cuatro semanas secuencialmente de izquierda a derecha con la semana 2 resaltada.

Se te presentará el sistema operativo Linux y aprenderás cómo se usa habitualmente en ciberseguridad. También adquirirás conocimientos sobre la arquitectura de Linux y las distribuciones más utilizadas. Además, te familiarizarás con el shell de Linux y aprenderás cómo te permite comunicarte con el sistema operativo.
Cinco íconos muestran el curso seguido de las cuatro semanas secuencialmente de izquierda a derecha con la semana 2 resaltada.

Se te presentará el sistema operativo Linux y aprenderás cómo se usa habitualmente en ciberseguridad. También adquirirás conocimientos sobre la arquitectura de Linux y las distribuciones más utilizadas. Además, te familiarizarás con el shell de Linux y aprenderás cómo te permite comunicarte con el sistema operativo.
Cinco íconos muestran el curso seguido de las cuatro semanas secuencialmente de izquierda a derecha con la semana 4 resaltada.

Tendrás la oportunidad de practicar el uso de SQL para interactuar con bases de datos. Aprenderás cómo realizar consultas y filtrar los resultados. Además, adquirirás conocimientos sobre cómo SQL puede combinar varias tablas en una sola consulta.

## Sistemas operativos
Es la interfaz entre el hardware y el usuario.

### Hardware
Se refiere a los componentes físicos de una computadora.

**Windows y macOS**

Windows y macOS son sistemas operativos comunes. El sistema operativo Windows se introdujo en 1985, y macOS en 1984. Ambos sistemas se utilizan en computadoras de uso hogareño, tanto de escritorio como portátiles, así como en equipos corporativos 

Windows es un sistema operativo de código cerrado, lo que significa que el código fuente no se comparte libremente con el público; macOS, en cambio, es parcialmente de código abierto. Algunos elementos son de código abierto, como el kernel de macOS, y otros son de código cerrado.

**Linux**

La primera versión de Linux se presentó en 1991 y posteriormente se realizaron otros lanzamientos importantes, a principios de aquella década. Linux es un sistema operativo completamente de código abierto, lo que significa que cualquier persona puede acceder al sistema y a su código fuente. Por su naturaleza de código abierto, permite la colaboración entre los/as desarrolladores/as de su comunidad.

Linux es particularmente importante para la industria de la seguridad. Existen algunas distribuciones que están diseñadas específicamente para la seguridad. Más adelante en este curso, aprenderás sobre Linux y su importancia para la industria de la seguridad.

**Sistemas operativos heredados**

Un **sistema operativo heredado** es un sistema operativo obsoleto, pero que todavía se sigue utilizando. Algunas organizaciones continúan utilizando sistemas operativos heredados debido a que el software del que dependen no es compatible con sistemas operativos más nuevos. Esto puede ser más común en industrias que utilizan una gran cantidad de equipos que requieren software integrado, es decir, software que se coloca dentro de los componentes del equipo.

Los sistemas operativos heredados pueden ser vulnerables a problemas de seguridad porque ya no reciben soporte ni actualizaciones. Esto significa que los sistemas operativos heredados pueden ser vulnerables a nuevas amenazas. 

**Otras vulnerabilidades**

Incluso cuando los sistemas operativos se mantienen actualizados, pueden volverse vulnerables a los ataques. A continuación se presentan varios recursos que incluyen información sobre los sistemas operativos y sus vulnerabilidades.

- [Microsoft Security Response Center (MSRC)](https://msrc.microsoft.com/update-guide/vulnerability): un listado de vulnerabilidades conocidas que afectan a los productos y servicios de Microsoft.
    
- [Actualizaciones de seguridad de Apple](https://support.apple.com/en-us/HT201222): un listado de actualizaciones de seguridad e información para los sistemas operativos de Apple®, incluidos macOS e iOS, y otros productos.
    
- [Informe de vulnerabilidades y exposiciones comunes (CVE) para Ubuntu](https://ubuntu.com/security/cves): un listado de vulnerabilidades conocidas que afectan a Ubuntu, que es una distribución específica de Linux.
    
- [Boletín de seguridad de Google Cloud](https://cloud.google.com/support/bulletins): una lista de vulnerabilidades conocidas que afectan a los productos y servicios de Google Cloud.
    

Mantener un sistema operativo actualizado es una de las principales formas de ayudar a que el sistema permanezca seguro. Dado que puede ser difícil mantener todos los sistemas actualizados en todo momento, es importante que los/as analistas de seguridad tengan conocimiento sobre los sistemas operativos heredados y cuáles son los riesgos que pueden generar.

Al presionar el botón de encendido,  están interactuando con el hardware. Esto arranca la computadora y el sistema operativo. Arrancar la computadora implica activar un microchip especial llamado BIOS. En muchas computadoras fabricadas después de 2007, el chip cambió a UEFI. Tanto el BIOS como UEFI contienen instrucciones de arranque que activan un programa especial llamado cargador de arranque. Este inicia el sistema operativo. Y así se enciende la computadora.

### Aplicación
Es un programa que realiza una tarea en específica.

Al ingresar el número que quieres calcular, la aplicación se comunica con el SO. El SO envía el cálculo a un componente del hardware, la unidad central de procesamiento, o CPU. Cuando el hardware determina el número final, envía la respuesta al SO.

Los microchips BIOS o UEFI contienen una variedad de instrucciones de carga para la computadora. Por ejemplo, una de estas consiste en verificar el estado del hardware de la computadora.

La última instrucción del BIOS o UEFI activa el cargador de arranque. El **cargador de arranque** es un programa de software que inicia el sistema operativo. Una vez que el sistema operativo termina de arrancar, la computadora está lista para su uso

### User interface
Es un programa que permite al usuario controlarlas funciones del sistema operativo.

### *Graphical user interface*
Utiliza íconos en la pantalla para gestionar varias tareas en la computadora.

### Basic GUI components
- Start Menu
- Task Bar
- Desktop with icons and shortcuts

### *Command Line interface* CLI
Se basa en el texto y usa comandos para interactuar con la computadora.
CLI es más flexible y más potente que la GUI

![[Pasted image 20231105201110.png]]**Función**

Estas dos interfaces también difieren en su funcionamiento. Una GUI es una interfaz que solo te permite realizar una solicitud a la vez. Sin embargo, una CLI te permite realizar múltiples solicitudes al mismo tiempo. 

## **Ventajas de una CLI en ciberseguridad**

La elección entre utilizar una GUI o una CLI se basa en parte en las preferencias personales, pero las/los analistas de seguridad deberían poder usar ambas interfaces. El uso de una CLI puede ofrecer ciertas ventajas.

**Eficiencia**

Algunas personas prefieren la CLI porque se puede utilizar más rápidamente, cuando se sabe cómo administrarla. Para un/a usuario/a nuevo/a, una GUI puede ser más eficiente, ya que es más fácil de navegar para principiantes.

Dado que una CLI puede aceptar múltiples solicitudes al mismo tiempo, es más potente cuando necesitas realizar múltiples tareas de manera eficiente. Por ejemplo, si tuvieras que crear varios archivos nuevos en tu sistema, podrías realizar rápidamente esta tarea en una CLI. Si estuvieras utilizando una GUI, esto podría llevar mucho más tiempo, ya que tendrías que repetir los mismos pasos para cada archivo nuevo.

**Archivo de historial**

Para las/los analistas de seguridad, el uso de la CLI de Linux es útil porque registra un archivo de historial de todos los comandos y acciones. Si estuvieras utilizando una GUI, tus acciones no se guardarían necesariamente en un archivo de historial.

Por ejemplo, podrías encontrarte en una situación en la que estás respondiendo a un incidente utilizando un manual de estrategias. Sus instrucciones requieren que ejecutes una serie de comandos diferentes. Si utilizas una CLI, podrías consultar el historial y asegurarte de que todos los comandos se utilizaron correctamente. Esto podría ser útil si hubiera habido problemas con el manual y tuvieras que revisar los pasos que realizaste en la línea de comandos.

Además, si sospechas que un atacante ha comprometido tu sistema, podrías rastrear sus acciones utilizando el archivo de historial.

**Cargador de arranque:** Programa que carga el sistema operativo en una computadora.

**Hardware:** Componentes físicos de una computadora.

**Interfaz de firmware extensible unificada (UEFI):** Microchip que contiene instrucciones de carga para la computadora y reemplaza el BIOS en los sistemas más modernos.
**Sistema básico de entrada/salida (BIOS):** Un microchip que contiene instrucciones de carga para la computadora y que predomina en los sistemas más antiguos.

**Sistema Operativo (SO)**: La interfaz entre el hardware de la computadora y el usuario.

**Sistema operativo heredado:** Sistema operativo obsoleto, pero que se sigue utilizando.

## Linux
Es un SO de código abierto.

### Arquitectura de Linux

*Components of Linux*
- User es multiusuario más de un usuario puede utilizar los recursos
- Applications
	- ## **Aplicaciones**

Una **aplicación** es un programa diseñado para realizar una tarea específica. En tu computadora, puedes encontrar diversas aplicaciones. Algunas de ellas vienen preinstaladas, como calculadoras o calendarios, mientras que otras necesitan ser instaladas, como ciertos navegadores web o clientes de correo electrónico. En el caso de Linux, se utiliza comúnmente un gestor de paquetes para instalar aplicaciones. Un **gestor de paquetes** es una herramienta que ayuda a los/las usuarios/as a instalar, gestionar y desinstalar paquetes o aplicaciones. Vale aclarar que un **paquete** es un componente de software que puede combinarse con otros paquetes para formar una aplicación.

- Shell
- Filesystem Hierarchy Standard
- Kernel es un componente de Linux que gestiona procesos y memoria
- Hardware
## **Hardware interno**

**El hardware interno** involucra los componentes necesarios para que funcione la computadora, como una placa de circuito principal, también denominada placa base, y todos los elementos conectados a ella. El hardware interno incluye: 

- La **unidad central de procesamiento (CPU),** que es el procesador principal de una computadora y que se utiliza para realizar tareas informáticas generales. La CPU ejecuta las instrucciones proporcionadas por los programas, permitiendo que estos se ejecuten. 
    
- La **memoria de acceso aleatorio (RAM)**, que es un componente de hardware utilizado para la memoria a corto plazo. Es donde se almacenan temporalmente los datos mientras se realizan tareas en la computadora. Por ejemplo, si estás escribiendo un informe, los datos necesarios para que esto ocurra se almacenan en la memoria RAM. Cuando terminas de escribir el informe y cierras el programa, estos datos se eliminan de la memoria RAM. No se puede acceder a la información de la memoria RAM una vez que se ha apagado la computadora. La CPU toma los datos de la memoria RAM para ejecutar los programas.
## *Distributions*
Las versiones de Linux se llaman distribuciones o sabores.

## *Parent distributions*
- Red Hat (Cent OS)
- Slackware (SUSE)}
- Debian (Ubuntu and KALI LINUX)

### Penetration Test
Es una prueba de penetración, un ataque simulado, para identificar vulnerabilidades en sistemas , red, sitios, apps y procesos.

## **Penetration testing tools in KALI LINUX**
- *Metasploit* sirve para buscar y explotar vulnerabilidades en equipos
- *Burn suite* se buscan debilidades en apps web.
- *John the Ripper* sirve para adivinar contraseñas.

### Digital forensics
El análisis forense digital consiste en recopilar y analizar datos para determinar que ocurrió tras un ataque.

## **Digital forensics tools in KALI LINUX**
- *TCPDump* analiza paquetes de línea de comandos se utiliza para capturar el tráfico de red.
- *Wireshark* para analizar tráfico de red en vivo y capturado.
- *Autopsy* es una herramienta forense para analizar discos duros y smartphones.
(Kali Linux ™ es una marca comercial de OffSec.). Además de esta, hay otras distribuciones de Linux con las que los/las analistas de seguridad deberían estar familiarizados/as. En esta lectura, conocerás otras distribuciones de Linux.

## **Kali Linux ™**

**Kali Linux ™** es una distribución de Linux de código abierto que se utiliza ampliamente en la industria de la seguridad. Se basa en Debian y se caracteriza por incluir de forma preinstalada muchas herramientas útiles para pruebas de penetración y análisis forense digital. Las **pruebas de penetración** consisten en ataques simulados que ayudan a identificar vulnerabilidades en sistemas, redes, sitios web, aplicaciones y procesos. Por otro lado, el **análisis forense digital** es una práctica que implica recopilar y analizar datos para determinar qué sucedió después de un ataque. Estas actividades son claves en el ámbito de la seguridad. 

Sin embargo, Kali Linux ™ no es la única distribución de Linux utilizada  en ciberseguridad. 

## **Ubuntu**

**Ubuntu** es una distribución de código abierto y fácil de usar que goza de amplia popularidad en el ámbito de la seguridad y en otros sectores. Ofrece tanto una interfaz de línea de comandos (CLI) como una interfaz gráfica de usuario (GUI). Al ser un derivado de Debian, Ubuntu incluye de forma predeterminada aplicaciones comunes. Además, los/las usuarios/as pueden descargar un gran cantidad de aplicaciones adicionales a través de un gestor de paquetes, incluyendo herramientas especializadas en seguridad. Debido a su extenso uso, Ubuntu cuenta con una gran cantidad de recursos comunitarios para brindar apoyo a los/las usuarios/as.

Ubuntu también se utiliza ampliamente en el ámbito de la computación en la nube. Por lo tanto, a medida que las organizaciones migran hacia servidores en la nube, el trabajo en ciberseguridad puede involucrar con mayor frecuencia derivados de Ubuntu.

## **Parrot**

**Parrot** es una distribución de código abierto ampliamente utilizada en el ámbito de la seguridad. Al igual que Kali Linux ™, Parrot viene con herramientas preinstaladas relacionadas con pruebas de penetración y análisis forense digital. Asimismo, como Kali Linux ™ y Ubuntu, está basada en Debian.

Una característica destacada de Parrot es su enfoque en brindar una experiencia de uso amigable. Esto se logra mediante una interfaz gráfica de usuario (GUI) intuitiva que facilita la navegación. Además, también ofrece una interfaz de línea de comandos (CLI).

## **Red Hat®**

**Red Hat®** es una distribución de Linux basada en suscripción y diseñada para su uso en empresas. A diferencia de las distribuciones mencionadas anteriormente, Red Hat no es gratuita. Debido a que está diseñada y respalda para uso corporativo, también cuenta con un equipo de soporte dedicado, al que las empresas clientes pueden consultar ante incidentes.

## **CentOS**

**CentOS** es una distribución de código abierto que está estrechamente relacionada con Red Hat. Utiliza el código fuente publicado por Red Hat para proporcionar una plataforma similar. Sin embargo, no ofrece el mismo soporte corporativo y se basa en el respaldo y la colaboración de la comunidad de usuarios/as para obtener apoyo.

# Práctica de APT Suricata y tcpdump
![[Pasted image 20231105232927.png]]![[Pasted image 20231105233221.png]]
![[Pasted image 20231105233327.png]]![[Pasted image 20231105233341.png]]![[Pasted image 20231105233420.png]]

## Shell
El shell interpreta líneas de comandos. Es decir, te comunica con el SO mediante la línea de comandos.

### **Command**
Le indica a la computadora que haga algo. El shell se comunica con el kernel para ejecutar estos comandos.

### *Standard Input*
Información que recibe el SO por la línea de comandos. La información se ingresa mediante el teclado.

### **echo**
Que emite un cadena de texto especificada.
### *String Data*
Los datos de cadena son una secuencia ordenada de caracteres.

### *Standard output*
Es la información que devuelve el SO por el shell.

### *Standard error*
Mensajes de error que devuelve el SO por el shell.

# Práctica de Echo y Expr
![[Pasted image 20231105235012.png]]![[Pasted image 20231105235122.png]]
![[Pasted image 20231105235134.png]]
![[Pasted image 20231105235233.png]]
![[Pasted image 20231105235248.png]]

## Security Analysts
- Work with server logs
- Navigate, manage, and analyze files remotely
- Verify and configure users and group access
- Give authorization and set file permissions

### **Bash**
Es el shell incluido en casi todas las distribuciones Linux.

### *Command*
Es una instrucción que le dice a la computadora que haga algo.

### *Argument (Linux)*
Es una información específica que un comando necesita.

# FHS
## Root directory
Es la directorio de nivel más alto. `/`

### **pwd**
Imprime el directorio de trabajo en la pantalla

### *ls*
muestra los nombres de los archivos y directorios.

### *cd*
Navega entre directorios.

### *cat*
Muestra el contenido de un archivo.

### *head*
Muestra solo el comienzo de un archivo, 10, líneas por defecto]

El **directorio raíz** es el directorio de mayor nivel en Linux, y siempre se representa con una barra (/). Todos los subdirectorios se ramifican desde el directorio raíz y pueden continuar ramificándose a tantos niveles como sea necesario.

**Directorios estándar del FHS**

Justo debajo del directorio raíz, encontrarás los directorios estándar del FHS. En el diagrama, home, bin y etc son eso mismo. Estos son algunos ejemplos del contenido de los directorios estándar:

- /home: Cada usuario del sistema obtiene su propio directorio de inicio.
    
- /bin: Este directorio significa “binario” y contiene archivos binarios y otros archivos ejecutables. Los archivos ejecutables contienen una serie de comandos que una computadora debe seguir para ejecutar programas y llevar a cabo otras funciones.
    
- /etc: Este directorio almacena los archivos de configuración del sistema.
    
- /tmp: Este directorio almacena varios archivos temporales. Las/los atacantes suelen usar el directorio /tmp porque cualquier persona en el sistema puede modificar datos en estos archivos.
    
- /mnt: Este directorio significa “montaje” y almacena medios, como unidades USB y discos duros.
    

**Consejo profesional**: Puedes usar el comando man hier para obtener más información acerca del FHS y sus directorios estándar.

**Subdirectorios específicos del usuario**

En home hay subdirectorios para usuarios específicos. En el diagrama, estos usuarios son analyst y analyst2. Cada usuario tiene sus propios subdirectorios personales, como projects, logs o reports.

**Nota:** Cuando la ruta conduce a un subdirectorio debajo del directorio de inicio del usuario, este puede representarse con una virgulilla (~). Por ejemplo, /home/analyst/logs también puede representarse como ~/logs.

Puedes navegar a subdirectorios específicos utilizando sus rutas de archivo absolutas o relativas. La **ruta de archivo absoluta** es la ruta completa del archivo, que comienza desde la raíz. Por ejemplo, /home/analyst/projects es una ruta de archivo absoluta. La **ruta de archivo relativa** comienza en el directorio actual del usuario.

**Nota:** Las rutas de archivo relativas pueden usar un punto (.) para representar el directorio actual, o dos puntos (..) para representar el directorio superior del directorio actual. Un ejemplo de una ruta de archivo relativa podría ser ../projects.

## **Comandos clave para navegar por el sistema de archivos**

Los siguientes comandos de Linux pueden utilizarse para navegar por el sistema de archivos: pwd, ls y cd.

**pwd**

El comando pwd imprime el directorio de trabajo en la pantalla. O, en otras palabras, devuelve el directorio en el que te encuentras actualmente. 

La salida te da la ruta absoluta a este directorio. Por ejemplo, si estás en tu directorio home y tu nombre de usuario es analyst, al ingresar pwd, obtienes como resultado /home/analyst. 

**Consejo profesional**: Para saber cuál es tu nombre de usuario, usa el comando whoami. El comando whoami devuelve el nombre de usuario del usuario actual. Por ejemplo, si tu nombre de usuario es analyst, al ingresar whoami obtienes como resultado analyst.

**ls**

El comando ls muestra los nombres de los archivos y directorios en el directorio de trabajo actual. En el video, por ejemplo ls devolvió directorios como logs y un archivo llamado updates.txt. 

**Nota**: Si quieres acceder al contenido de un directorio que no sea tu directorio de trabajo actual, puedes agregar un argumento después de ls con la ruta de archivo absoluta o relativa al directorio deseado. Por ejemplo, si estás en el directorio /home/analyst pero quieres enumerar el contenido de tu subdirectorio projects, puedes ingresar ls /home/analyst/projects o simplemente ls projects.

**cd**

El comando cd se usa para navegar entre directorios. Cuando necesites cambiar de directorio, debes usar este comando.

Para navegar a un subdirectorio del directorio actual, puedes agregar un argumento después de cd con el nombre del subdirectorio. Por ejemplo, si estás en el directorio /home/analyst y quieres navegar a tu subdirectorio projects, puedes ingresar cd projects.

También puedes navegar a cualquier directorio específico ingresando la ruta de archivo absoluta. Por ejemplo, si estás en /home/analyst/projects, al ingresar cd /home/analyst/logs cambias de tu directorio actual a /home/analyst/logs.

**Consejo profesional**: Puedes usar la ruta de archivo relativa e ingresar cd .. para subir un nivel en la estructura de archivos. Por ejemplo, si el directorio actual es /home/analyst/projects, al ingresar cd .. cambiarías tu directorio de trabajo a /home/analyst. 

## **Comandos comunes para leer el contenido del archivo**
#comandosLinux
Los siguientes comandos de Linux son útiles para leer el contenido del archivo: cat, head, tail y less.

**cat**

El comando cat muestra el contenido de un archivo. Por ejemplo, al ingresar cat updates.txt, se devuelve todo el contenido del archivo updates.txt.

**head**

El comando head muestra solo el comienzo de un archivo; 10 líneas, por defecto. El comando head puede ser útil cuando quieres conocer el contenido básico de un archivo pero no necesitas todo el contenido. Al ingresar head updates.txt, obtienes solo las primeras 10 líneas del archivo updates.txt.

**Consejo profesional**: Si quieres cambiar el número de líneas que devuelve el comando head, puedes incluir -n para especificar el número de líneas. Por ejemplo, si solo quieres que se te muestren las primeras cinco líneas del archivo updates.txt, ingresa head -n 5 updates.txt.

**tail**

El comando tail hace lo opuesto a head. Este comando puede usarse para mostrar solo el final de un archivo; 10 líneas, por defecto. Al ingresar tail updates.txt, obtienes solo las últimas 10 líneas del archivo updates.txt.

**Consejo profesional**: Puedes usar tail para leer la información más reciente en un archivo de registro.

**less**

El comando less devuelve el contenido de un archivo, una página a la vez. Por ejemplo, al escribir less updates.txt, se cambia la ventana de la terminal para mostrar el contenido de updates.txt una página a la vez. Esto te permite avanzar y retroceder por el contenido, con facilidad. 

Una vez que hayas accedido a tu contenido con el comando less, puedes usar varios controles de teclado para moverte por el archivo:

- Barra espaciadora: desplazarse a la página siguiente
    
- b: desplazarse a la página anterior
    
- Flecha hacia abajo: avanzar una línea
    
- Flecha hacia arriba: retroceder una línea
    
- q: salir y volver a la ventana de terminal anterior

### *grep*
Busca un archivo en especifico y devuelve todas las líneas dentro de ese archivo que contiene una cadena especificada.
![[Pasted image 20231106103446.png]]
### *Pipping |*
El comando pipe envía una salida estándar de un comando como entrada estándar en otro comando para procesarlo luego.
![[Pasted image 20231106103802.png]]

**Nota:** El comando pipe es una forma general de redireccionamiento en Linux y puede utilizarse para múltiples tareas, además del filtrado. Puedes considerarlo como una herramienta general a utilizar, siempre que quieras que la salida de un comando se convierta en la entrada de otro comando.

## **find**

El comando find sirve para buscar directorios y archivos que cumplan con criterios especificados. Hay una amplia variedad de criterios que se pueden especificar con find. Por ejemplo, puedes buscar archivos y directorios que:

- Contengan una cadena específica en el nombre;
    
- Tengan un determinado tamaño de archivo; o
    
- Se hayan modificado por última vez dentro de un período de tiempo determinado.
    

Cuando usas find, el primer argumento después de find indica dónde comenzar a buscar. Por ejemplo, al ingresar find /home/analyst/projects se busca todo lo que comienza en el directorio projects.

Después de este primer argumento, debes indicar tus criterios para la búsqueda. Si no incluyes un criterio de búsqueda específico con tu segundo argumento, es probable que tu búsqueda devuelva una gran cantidad de directorios y archivos. 

La especificación de criterios implica opciones. Las **opciones** modifican el comportamiento de un comando y, por lo general, comienzan con un guión (-). 

## **-name e -iname**

Un criterio clave que las/los analistas podrían usar con find es buscar nombres de archivos o directorios que contengan una cadena específica. Debes ingresar la cadena específica que estés buscando entre comillas después de las opciones -name o -iname. La diferencia entre estas dos opciones es que -name distingue entre mayúsculas y minúsculas, mientras que -iname no lo hace. 

Supongamos que quieres buscar todos los archivos en el directorio projects que contienen la palabra “log” en el nombre. Para hacerlo, ingresarías find /home/analyst/projects -name "*log*". También podrías ingresar find /home/analyst/projects -iname "*log*".

En estos ejemplos, la salida estaría conformada por todos los archivos del directorio projects que contengan log rodeada de cero o más caracteres. La parte del comando que dice "*log*" es el criterio de búsqueda que indica que se debe buscar la cadena “log”. Cuando la opción es -name, no se devolverán los archivos con nombres que incluyan Log o LOG, por ejemplo, porque esta opción distingue entre mayúsculas y minúsculas. Sin embargo, sí se devolverán si la opción es -iname.

**Nota**: El asterisco (`*`) se usa como comodín para representar cero o más caracteres desconocidos.

## **-mtime**

Las/los analistas de seguridad también pueden usar find para buscar archivos o directorios modificados por última vez, en un período de tiempo determinado. Para esta búsqueda, se puede utilizar la opción -mtime. Por ejemplo, al ingresar find /home/analyst/projects -mtime -3, se devuelven todos los archivos y directorios del directorio projects que han sido modificados en los últimos tres días. 

La búsqueda de la opción -mtime se basa en días, por lo que la entrada -mtime +1 indica todos los archivos o directorios que se modificaron por última vez hace más de un día y la entrada -mtime -1 indica todos los archivos o directorios que se modificaron por última vez hace menos de un día. 

**Nota:** Si quieres basar la búsqueda en minutos en lugar de días, puedes usar la opción -mmin en lugar de -mtime.




- # Practica
![[Pasted image 20231106101938.png]]![[Pasted image 20231106102005.png]]![[Pasted image 20231106102124.png]]
![[Pasted image 20231106102850.png]]

![[Pasted image 20231106104606.png]]
![[Pasted image 20231106104737.png]]
![[Pasted image 20231106104810.png]]

### *mkdir*
Crea un un nuevo directorio
### *rmdir*
Removes, or deletes, a directory.
### *touch* 
Creates a new file.
### *rm*
Removes, or deletes, a file.
### *mv*
Moves a file or directory to a new location.
### *cp*
Copies a file or directory into a new location.
## **Redireccionamiento de salida estándar**

Hay otra forma de escribir en archivos. Anteriormente, aprendiste sobre la entrada estándar y la salida estándar. La **entrada estándar** es información recibida por el sistema operativo a través de la línea de comandos, mientras que la **salida estándar** es la información devuelta por el SO a través del shell.

También aprendiste acerca del comando pipe, o pleca. El comando _**pipe**_ envía la salida estándar de un comando como entrada estándar a otro comando, para su posterior procesamiento. Para usarlo, se ingresa el carácter pleca (|). 

Además de la pleca (|), también puedes usar los operadores del signo “mayor que” (>) y el “doble mayor que” (>>) para redirigir la salida estándar.

Al usarlos con echo, los operadores > y > > pueden servir para enviar la salida de echo a un archivo específico en lugar de a la pantalla. La diferencia entre ambos es que > sobrescribe tu archivo existente, mientras que >> agrega tu contenido al final del archivo existente en lugar de sobrescribirlo. El operador > debe usarse con cuidado, ya que no es fácil recuperar archivos sobrescritos.

Cuando estés dentro del directorio que contiene el archivo permissions.txt, ingresa echo "last updated date" >> permissions.txt y agrega la cadena “last updated date” al contenido del archivo. Al ingresar echo "time" > permissions.txt después de este comando, se sobrescribe todo el contenido del archivo permissions.txt con la cadena “time”.

**Nota:** Los operadores > y >> crearán un archivo nuevo si todavía no existe uno con el nombre especificado.

# Practica
![[Pasted image 20231106193954.png]]
![[Pasted image 20231106194037.png]]
![[Pasted image 20231106194345.png]]
![[Pasted image 20231106194439.png]]
![[Pasted image 20231106194552.png]]
![[Pasted image 20231106194606.png]]
![[Pasted image 20231106194905.png]]

## *Permissions*
Es el tipo de acceso que se da a un archivo o directorio.
## *Authorization*
Es el concepto de dar acceso a recursos específicos de un sistema.
## *Permissions in Linux*
- Read
- Write
- Execute
## *Types of owner*
- User
- Group
- Other
Están representados los permisos en 10 caracteres 
drwxrwxrwx el primer carácter indica el tipo de archivo en este caso es d de directorio si tuviera un guion seria un archivo regular después de agrupan en 3 el permiso de usuario, permiso de grupo y permiso de otros.

world-writeable es un riesgo de seguridad.

### *Options*
Las opciones de un comando pueden ser una letra o una palabra.

### *ls -l*
Muestra permisos para archivos y directorios.

Los archivos ocultos y directorios contienen un `.` antes del nombre 
### *ls -a*
Se muestran los archivos ocultos.
### *ls -la*
Para mostrar on las dos opciones.

![[Pasted image 20231106200544.png]]
### *chmod*
Cambia los permisos en archivos y directorios.
**Cómo usar chmod**

El comando chmod requiere dos argumentos. El primer argumento indica cómo cambiar los permisos, y el segundo indica el archivo o directorio para el que quieres cambiar los permisos. Por ejemplo, el siguiente comando agregaría todos los permisos a login_sessions.txt:

chmod u+rwx,g+rwx,o+rwx login_sessions.txt

Si quisieras quitar todos los permisos, podrías usar

chmod u-rwx,g-rwx,o-rwx login_sessions.txt

Otra forma de asignar estos permisos es usar el signo igual (=) en este primer argumento. Al usar = con chmod, se establecen o asignan los permisos exactamente según se especificó. Por ejemplo, el siguiente comando establecería permisos de lectura para login_sessions.txt para usuario, grupo y otros usuarios:

chmod u=r,g=r,o=r login_sessions.txt

Este comando sobreescribe permisos existentes. Por ejemplo, si antes el usuario tenía permisos de escritura, estos permisos de escritura se eliminan después de especificar permisos de solo lectura con =.

La siguiente tabla revisa cómo se usa cada carácter dentro del primer argumento de chmod:

|**Carácter**|**Descripción**|
|---|---|
|u|indica que se realizarán cambios en los permisos de usuario|
|g|indica que se realizarán cambios en los permisos de grupo|
|o|indica que se realizarán cambios en los permisos de otros usuarios|
|+|agrega permisos al usuario, grupo u otros usuarios|
|-|elimina permisos del usuario, grupo u otros usuarios|
|=|asigna permisos para el usuario, grupo u otros usuarios|

**Nota:** Cuando hay cambios de permiso en más de un tipo de propietario, hay que usar comas para separar los cambios para cada tipo de propietario. No se debe agregar espacios después de esas comas.

**El principio de mínimo privilegio en acción**

Como analista de seguridad, es posible que te encuentres en una situación como esta: hay un archivo llamado bonuses.txt dentro de un directorio de remuneración. El propietario de este archivo es un miembro del departamento de Recursos Humanos cuyo nombre de usuario es hrrep1. Se decidió que hrrep1 necesita acceso a este archivo. Pero, dado que este archivo contiene información confidencial, nadie más en el grupo hr debería acceder a él.

Ejecutas ls -l para verificar los permisos de los archivos en el directorio de remuneración y descubres que los permisos para bonuses.txt son -rw-rw----. El tipo propietario del grupo tiene permisos de lectura y escritura que no se alinean con el principio de mínimo privilegio. 

Para remediar la situación, ingresas chmod g-rw bonuses.txt. Ahora, solo puede acceder a este archivo el/la usuario/a que lo necesita para llevar a cabo sus responsabilidades laborales.

![[Pasted image 20231106222627.png]]
si necesitas acceso a sudo, debes tener cuidado y usarlo solo con los comandos que necesitas. La ejecución de comandos con sudo permite a los/las usuarios/as eludir los controles de seguridad típicos que existen para evitar que un/a atacante obtenga acceso elevado.

**Nota**: Ten cuidado de no usar sudo si estás copiando comandos de una fuente en línea. Es importante que no uses sudo por accidente. 

## **Autenticación y autorización con sudo**

Puedes usar sudo para muchas tareas de gestión de autenticación y autorización. Como recordatorio, la **autenticación** es el proceso de verificar quién es una persona, mientras que la **autorización** es el concepto de otorgar acceso a recursos específicos en un sistema. Estos son algunos de los comandos clave que se utilizan para estas tareas:

**useradd**

El comando useradd agrega un usuario al sistema. Para agregar un usuario con el nombre de usuario fgarcia con sudo, ingresa sudo useradd fgarcia. Existen otras opciones que puedes usar con useradd:

- -g: Establece el grupo predeterminado del usuario, también conocido como su grupo principal.
    
- -G: Agrega al usuario a grupos adicionales, también llamados grupos complementarios o secundarios.
    

Para usar la opción -g, debe especificarse el grupo principal después de -g. Por ejemplo, al ingresar sudo useradd -g security fgarcia, se agrega a fgarcia como un nuevo usuario y se le asigna security como grupo principal.

Para usar la opción -G, debe incluirse el grupo complementario en el comando después de -G. Con la opción -G, puedes agregar más de un grupo complementario a la vez. Al ingresar sudo useradd -G finance,admin fgarcia, se agrega a fgarcia como usuario nuevo y se lo añade a los grupos existentes finance y admin.

**usermod**

El comando usermod modifica las cuentas de usuario existentes. Las mismas opciones _-_g y -G del comando useradd pueden utilizarse con usermod si el usuario ya existe. 

Para cambiar el grupo principal de un usuario existente, debes usar la opción -g. Por ejemplo, al ingresar sudo usermod -g executive fgarcia, se cambiaría el grupo principal de fgarcia a executive.

Para agregar un grupo complementario para un usuario existente, debes usar la opción -G. También necesitas una opción -a, que agrega al usuario a un grupo existente y solo se usa con la opción -G. Por ejemplo, al ingresar sudo usermod -a -G marketing fgarcia, se agregaría el usuario existente fgarcia al grupo complementario marketing.

**Nota:** Al cambiar el grupo complementario de un usuario existente, si no incluyes la opción -a, -G reemplazará a cualquier grupo complementario existente con aquellos  que se especifiquen después de usermod. El uso de -a con -G asegura que se agreguen los nuevos grupos, pero no se reemplaza a los grupos existentes.

Hay otras opciones que puedes usar con usermod para especificar cómo quieres modificar el usuario, entre ellas, las siguientes:

- -d: Cambia el directorio de inicio del usuario.
    
- -l: Cambia el nombre de inicio de sesión del usuario.
    
- -L: Bloquea la cuenta para que el usuario no pueda iniciar sesión.
    

La opción siempre va después del comando usermod. Por ejemplo, para cambiar el directorio de inicio de fgarcia a /home/garcia_f, ingresa sudo usermod -d /home/garcia_f fgarcia. La opción -d va justo después del comando usermod y antes de los otros dos argumentos necesarios.

**userdel**

El comando userdel elimina a un usuario del sistema. Por ejemplo, al ingresar sudo userdel fgarcia, se elimina a fgarcia como usuario. Ten cuidado antes de eliminar a un usuario con este comando.

El comando userdel no elimina los archivos en el directorio de inicio del usuario, a menos que se use la opción -r. Al ingresar sudo userdel -r fgarcia, se eliminaría a fgarcia como usuario y se eliminarían todos los archivos en su directorio de inicio. Antes de eliminar cualquier archivo de usuario, debes asegurarte de tener copias de seguridad en caso de que las necesites más adelante.

**Nota**: En lugar de eliminar al usuario, podrías considerar desactivar su cuenta con usermod -L. Esto le impide al usuario iniciar sesión y te otorga acceso a su cuenta y sus permisos asociados. Por ejemplo, si un usuario abandona una organización, esta opción te permitiría identificar los archivos sobre los que tiene propiedad, por lo que podrías transferir esta propiedad a otros usuarios.

**chown**

El comando chown cambia la propiedad de un archivo o un directorio. Puedes usar chown para cambiar la propiedad del usuario o del grupo. Para cambiar el usuario propietario del archivo access.txt a fgarcia, ingresa sudo chown fgarcia access.txt. Para cambiar el grupo propietario del archivo _access.txt_ a _security_, ingresa sudo chown :security access.txt. Tienes que ingresar dos puntos (:) antes de security para designarlo como un nombre de grupo.

Al igual que con useradd, usermod y userdel, existen otras opciones que puedes usar con chown.


# Practica
![[Pasted image 20231107210425.png]]![[Pasted image 20231107210800.png]]![[Pasted image 20231107213924.png]]
![[Pasted image 20231107213939.png]]
![[Pasted image 20231107213954.png]]
![[Pasted image 20231107214727.png]]

## **man**
Muestra información sobre otros comandos y como funcionan.

![[Pasted image 20231107221932.png]]
## **whatis**
Muestra una descripción de un comando en una sola linea.

![[Pasted image 20231107222058.png]]

## **apropos**
Busca una determinada cadena en las descripciones del manual.

![[Pasted image 20231107222211.png]]
El -a devolvera solo los comandos con ambas cadenas.

![[Pasted image 20231107222446.png]]

![[Pasted image 20231107222515.png]]![[Pasted image 20231107222648.png]]
![[Pasted image 20231107222914.png]]
![[Pasted image 20231107223038.png]]

# SQL
Una recopilación organizada de datos.

## Spreadsheets
- Diseñadas para un solo usuario o un equipo pequeño y almacenan menos datos.
- Almacenan menos datos.

## Databases
- Varias personas pueden acceder a las bases de datos a la vez.
- Almacenan grandes cantidades de datos.
- Pueden realizar tareas complejas al acceder a los datos.

## Relational database
Una base de datos estructurada que contiene tablas y esta relacionada entre si.

### Primary key
Es una columna que en la que cada fila tiene una entrada unica.

### Foreign key
Es una a columna que en una tabla que es una clave primaria en otra tabla.

### SQL Structured Query Language
Es una lenguaje de programación usado para crear bases de datos, interactuar con ellas y solicitarles datos.

### Query
A request for data from database table or a combination of tables.
### Log
A record of events that occur within an organization´s systems.

