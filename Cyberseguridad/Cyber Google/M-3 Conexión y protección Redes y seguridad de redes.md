
¡Hola! Te damos la bienvenida a **Conexión y protección: Redes y seguridad de redes**, el tercer curso del Certificado de Carrera de Google en Ciberseguridad. ¡Estás viviendo una experiencia emocionante!

Al finalizar este curso, comprenderás mejor la arquitectura de redes, las operaciones, las tácticas de intrusiones, los tipos comunes de vulnerabilidades y ataques de redes, así como también de qué modo asegurar las redes. Además, conocerás los protocolos de red comunes, los cortafuegos (firewalls), las redes privadas virtuales (VPN) y las prácticas de reforzamiento del sistema.

**Semana 1: Arquitectura de red**
Te presentaremos la seguridad de redes y te explicaremos cómo se vincula con las amenazas y vulnerabilidades de seguridad actuales. Aprenderás sobre la arquitectura de redes y los mecanismos para proteger una red.

**Semana 2: Operaciones de red**
Explorarás los protocolos de comunicación en red y cómo su uso puede introducir vulnerabilidades. Además, aprenderás sobre las medidas de seguridad más comunes, como los cortafuegos (firewalls), que ayudan a mantener seguras y confiables las operaciones de red.

**Semana 3: Protección contra intrusiones en redes**
Comprenderás los tipos de ataques a la red y las técnicas utilizadas para proteger los sistemas y dispositivos de red comprometidos. Explorarás las diversas formas en que los agentes de amenaza aprovechan las vulnerabilidades en la infraestructura de red y cómo las y los profesionales de la ciberseguridad detectan y solucionan posibles vulnerabilidades.

**Semana 4: Reforzamiento de la seguridad**
Te familiarizarás con las prácticas de reforzamiento de redes que refuerzan los sistemas. Aprenderás cómo esto ayuda a defenderse contra agentes de amenaza y métodos de intrusión. También aprenderás a utilizar el reforzamiento de la seguridad para abordar los desafíos específicos que plantean las infraestructuras en la nube.

## Network

Una red es un grupo de dispositivos conectados.Los dispositivos en una red pueden comunicarse entre sí mediante cables de red o conexiones inalámbricas. Las redes de tu casa y oficina pueden comunicarse con redes en otros lugares y sus dispositivos. Los dispositivos deben encontrarse entre sí en una red para comunicarse. Para ello, usan direcciones únicas, o identificadores. Estas garantizan que se comunican con el dispositivo correcto.

## Local Area Network (LAN)
Una red de área local, o LAN, cubre áreas pequeñas, como un edificio de oficinas, escuela u hogar.

## Wide Area Network (WAN)
WAN, cubre zonas geográficas grandes, como una ciudad, estado o país. Internet es como una gran WAN. Una persona en San Francisco puede comunicarse y compartir recursos con otra en Dublín mediante la WAN.

## Hub
Un hub es un dispositivo de red que transmite información a todos los dispositivos de la red. Un hub es como una torre de radio que difunde una señal a una radio sintonizada en la frecuencia correcta.

## Switch
Un switch establece conexiones entre ciertos dispositivos en una red enviando y recibiendo datos entre ellos. Un switch tiene capacidades superiores a un hub. Solo transfiere datos al destino previsto. Así, el switch es más seguro que el hub, controla el flujo de tráfico y mejora el rendimiento de la red.

## Router
Un router es un dispositivo de red que conecta varias redes. Por ejemplo, si una computadora en una red envía información a una tableta en otra red, se transfiere de la siguiente forma. Primero, la información va de la computadora al router. El router lee la dirección de destino y reenvía los datos al router deseado. Finalmente el router receptor envía la información a la tableta.

## Modem
Un módem es un dispositivo que conecta el router a Internet y da acceso a Internet a la LAN. Por ejemplo, si la computadora de una red envía información a un dispositivo en una red en otra área geográfica, se transfiere de la siguiente forma. La computadora envía información al router y este transfiere la información por el módem a Internet. El módem del destinatario recibe la información y la transfiere al router. Finalmente el router del destinatario la envía al dispositivo de destino.

## Virtualization tools
Las herramientas de virtualización son software que realizan operaciones de red. Llevan a cabo operaciones que normalmente realiza un hub, switch, router o módem. Las ofrecen proveedores de servicios en la nube. Estas herramientas permiten ahorrar costos y obtener escalabilidad.

**Cortafuegos (firewalls)**

Un **cortafuegos (firewall)** es un dispositivo de seguridad de red que monitorea el tráfico hacia o desde tu red. Además, los cortafuegos pueden restringir el tráfico de red específico, tanto de entrada como de salida, según la configuración de reglas de seguridad que realiza la organización. Los firewalls suelen ubicarse entre la red interna segura y controlada y los recursos de red no confiables fuera de la organización, como Internet.

**Servidores** 

Los servidores proporcionan un servicio para otros dispositivos en la red. Los dispositivos que se conectan a un servidor se denominan clientes. El siguiente gráfico ilustra este modelo, conocido como modelo cliente-servidor. Aquí, los clientes envían solicitudes al servidor para obtener información y servicios, y el servidor se encarga de cumplir estas solicitudes. Algunos ejemplos comunes incluyen servidores DNS, que realizan búsquedas de nombres de dominio para sitios web, servidores de archivos, que almacenan y recuperan archivos de una base de datos, y servidores de correos corporativos, que organizan el correo de una empresa.
![[Pasted image 20231016181258.png]]

**Punto de acceso inalámbrico**

Un punto de acceso inalámbrico envía y recibe señales digitales a través de ondas de radio, creando una red inalámbrica. Los dispositivos con adaptadores inalámbricos se conectan al punto de acceso utilizando Wi-Fi. El Wi-Fi se refiere a un conjunto de estándares utilizados por los dispositivos de red para comunicarse de forma inalámbrica. Los puntos de acceso inalámbrico y los dispositivos conectados a ellos utilizan protocolos Wi-Fi para mandar datos a través de ondas de radio a routers y switches, y dirigirlos a lo largo del camino hacia su destino final.
![[Pasted image 20231016181337.png]]

## Uso de diagramas de red como analista de seguridad

Los diagramas de red permiten a los/las administradores/as de red y al personal de seguridad imaginar la arquitectura y el diseño de la red privada de su organización.

Son mapas topográficos que muestran los dispositivos en la red y cómo se conectan. Utilizan pequeños gráficos representativos para reproducir cada dispositivo de red y líneas de puntos para mostrar cómo estos se conectan entre sí. Las/los analistas de seguridad utilizan diagramas de red para aprender sobre la arquitectura de red y cómo diseñar redes.

![[Pasted image 20231016181402.png]]

## Cloud computing
La computación en la nube consiste en usar servidores, aplicaciones y servicios de red remotos alojados en Internet y no en dispositivos físicos locales.

Las redes en la nube usan servidores remotos, que permiten utilizar servicios en línea y aplicaciones web desde cualquier ubicación geográfica. La seguridad en la nube será más relevante para nuestro campo, ya que cada vez más empresas migran a servicios a la nube. Los proveedores ofrecen computación en la nube para mantener aplicaciones. Por ejemplo, proporcionan almacenamiento y potencia de procesamiento a pedido que sus clientes pagan solo cuando lo necesitan. También ofrecen análisis comercial y web que se pueden usar para monitorear el tráfico web y las ventas.

## Cloud Network

^0cf0ee


Una red en la nube es un grupo de servidores o computadoras que almacenan recursos e información en un centro de datos remoto accesible a través de Internet. Los servidores están “en la nube” porque las empresas no los albergan de forma física. ^b813f9

Los servicios ofrecidos por los proveedores de servicios en la nube (CSP) se clasifican en tres categorías principales:

- **Software como servicio (SaaS)**: se refiere a suites de software operadas por el CSP que una empresa puede usar de forma remota sin alojar el software. 
    
- **Infraestructura como servicio** **(Iaas)**: se refiere al uso de componentes informáticos virtuales ofrecidos por el CSP. Estos incluyen almacenamiento y contenedores virtuales que se configuran de forma remota a través de la API o la consola web del CSP. Los servicios de almacenamiento y computación en la nube se pueden utilizar para operar aplicaciones existentes y otras cargas de trabajo tecnológicas sin hacer grandes modificaciones. Las aplicaciones existentes se pueden modificar para aprovechar las funcionalidades de disponibilidad, rendimiento y seguridad que son exclusivas de los servicios de proveedores en la nube.
![[Pasted image 20231016181940.png]]

## Entornos de nube híbrida

Un entorno de nube híbrida implica que las organizaciones utilizan los servicios de un CSP, junto con sus propios equipos, redes y almacenamiento locales. Además, cuando las organizaciones utilizan más de un CSP, se denomina entorno multinube o de nube múltiple. La gran mayoría de las empresas optan por entornos de nube híbrida para reducir costos y, a la vez, tener un mayor control sobre los recursos de su red.

## Redes definidas por software

Los proveedores de servicios en la nube (CSP) ofrecen herramientas de redes similares a los dispositivos físicos que aprendiste en esta sección. A continuación, repasarás las redes definidas por software en la nube. Las redes definidas por software (SDN) están compuestas por dispositivos y servicios de red virtuales. Al igual que los CSP proporcionan computadoras virtuales, muchas SDN ofrecen switches, enrutadores, cortafuegos (firewalls) y otros componentes virtuales. La mayoría de los dispositivos de hardware de red modernos también admiten la virtualización de redes y las redes definidas por software. Esto significa que los enrutadores y los switches físicos utilizan software para el enrutamiento de paquetes. En el caso de las redes en la nube, las herramientas SDN se alojan en servidores ubicados en el centro de datos del CSP.

**Confiabilidad**

La confiabilidad en la computación en la nube se basa en la disponibilidad de los servicios y recursos, la seguridad de las conexiones y la frecuencia con la que los servicios operan de manera efectiva. Además, permite a los/las empleados/as y clientes acceder a los recursos que necesitan de forma consistente y con interrupciones mínimas.

**Costos**

Tradicionalmente, las empresas han tenido que proporcionar su propia infraestructura de red, al menos para las conexiones a Internet, lo cual implicaba que podían existir costos iniciales potencialmente significativos. Sin embargo, debido a que los CSP tienen centros de datos tan grandes, pueden ofrecer dispositivos y servicios virtuales a un costo inferior para que las empresas instalen, actualicen y gestionen los componentes y el software por sí mismas.

**Escalabilidad**

Otro desafío que enfrentan las empresas con la computación tradicional es la escalabilidad. Cuando las organizaciones experimentan un aumento en sus necesidades comerciales, pueden verse obligadas a adquirir más equipos y software para poder satisfacer esa demanda.

### **Data Packet**
Un paquete de datos es una unidad básica de información que va de un dispositivo a otro en una red. Al transferir datos por red de un dispositivo a otro, se envían como un paquete con información sobre su destino, su origen y el contenido del mensaje.


![[Pasted image 20231016192051.png]]

### **Bandwith**
Este se refiere a la cantidad de datos que un dispositivo recibe cada segundo. Se calcula dividiendo la cantidad de datos por el tiempo en segundos.  
### **Speed**
La velocidad es la rapidez con que los datos se reciben o descargan.

Al personal de seguridad le interesa el ancho de banda y velocidad de red porque si alguno fuera irregular, podría ser un indicio de un ataque.

### **Packet Sniffing**
El rastreo de paquetes es capturar e inspeccionar paquetes en la red.

### **Transmision Control Protocol**
es un protocolo de comunicación en Internet que permite a dos dispositivos establecer una conexión y transmitir datos. El protocolo incluye instrucciones para organizar datos y enviarlos por la red. También conecta dos dispositivos y garantiza que los paquetes lleguen a su destino.

### **IP**
IP en TCP/IP significa protocolo de Internet. El IP son estándares para enrutar y direccionar paquetes entre dispositivos en una red. La parte IP incluye la dirección IP, que es la dirección de cada red privada.

### **Port**
un puerto es una ubicación de software que organiza el envío y recepción de datos entre dispositivos. Los puertos dividen el tráfico de red en segmentos según el servicio que darán. Las computadoras que envían y reciben estos segmentos los priorizan y procesan según su número de puerto.

### *Port Numbers*
- 25 - Email
- 443 Secure internet communication
- 20 Large file transfers

### TCP/IP
Es un marco usado para ver cómo se organizan y transmiten los datos por la red. 

El modelo TCP/IP tiene cuatro capas. 

1. acceso a la red, 
2. capa de Internet
3. capa de transporte 
4. capa de aplicación.

### Capa de acceso a la red.
Esta se ocupa de crear paquetes de datos y transmitirlos por una red. Incluye dispositivos de hardware conectados a cables físicos y switches que envían datos a su destino.

El protocolo de resolución de direcciones (ARP, por sus siglas en inglés) forma parte de la capa de acceso a la red. El ARP ayuda a la IP a dirigir paquetes de datos al mapear direcciones IP a direcciones MAC en la misma red física.

###  Capa de Internet.
Ahí las direcciones IP se adjuntan a paquetes para indicar la ubicación del emisor y receptor. Esta capa también se enfoca en cómo las redes se conectan entre sí. Por ejemplo, los paquetes con información que determina si quedarse en la LAN o enviarse a una red remota, como Internet.

- **Protocolo de Internet (IP)**. Envía los paquetes de datos al destino correcto y se basa en el protocolo de control de transmisión/protocolo de datagramas de usuario (TCP/UDP) para entregarlos al servicio correspondiente. Los paquetes de IP posibilitan la comunicación entre dos redes, ya que se enrutan desde la red de origen hasta la de destino. El IP retransmite cualquier dato que se haya perdido o dañado.
    
- **Protocolo de mensajes de control de Internet (ICMP)**. Comparte información de errores y actualizaciones de estado de los paquetes de datos. Resulta útil para detectar y solucionar errores de red y, además, informa sobre paquetes que fueron descartados o desaparecieron durante el tránsito, problemas de conectividad de red y paquetes redirigidos a otros enrutadores.

### Capa de transporte
Incluye protocolos para controlar el flujo de tráfico en una red. Estos permiten o niegan la comunicación con otros dispositivos e incluyen información del estado de la conexión. 
En esta capa se controlan errores, que garantiza que los datos fluyan sin problemas a través de la red.

El protocolo de control de transmisión (TCP) y el de datagramas de usuario (UDP) son los dos protocolos de transporte que se producen en esta capa. 

**Protocolo de control de transmisión (TCP)**

El **TCP** garantiza que los datos se transmitan de forma segura al servicio de destino. Contiene el número de puerto del servicio de destino previsto, que reside en el encabezado TCP de un paquete TCP/IP.

**Protocolo de datagramas de usuario (UDP)**

Las aplicaciones que no están afectadas por la confiabilidad de la transmisión usan el protocolo **UDP**. Los datos enviados a través de UDP no son objeto de un seguimiento tan exhaustivo como los enviados mediante TCP. Debido a que el UDP no establece conexiones de red, se utiliza principalmente para aplicaciones sensibles al rendimiento que operan en tiempo real, como la transmisión de video.

### Capa de aplicación
Los protocolos determinan cómo interactúan los paquetes de datos con los dispositivos receptores. Las funciones organizadas aquí son las transferencias de archivos y servicios de correo.
esta capa define a qué servicios y aplicaciones de Internet puede acceder cualquier usuario. Algunos de los protocolos comunes utilizados en esta capa son: 

- Protocolo de transferencia de hipertexto (HTTP)
    
- Protocolo simple de transferencia de correo (SMTP)
    
- Secure Shell o shell seguro (SSH)
    
- Protocolo de transferencia de archivos (FTP)
    
- Sistema de nombres de dominio (DNS)
     ^28f4ee

Los protocolos de capa de aplicación se basan en capas subyacentes para transferir los datos a través de la red.

![[Pasted image 20231016193417.png]]

![[Pasted image 20231016193604.png]]
El modelo **OSI** organiza visualmente los protocolos de red en diferentes capas. Las y los profesionales de redes suelen usar este modelo para comunicarse entre sí sobre posibles fuentes de problemas o amenazas de seguridad.

El modelo TCP/IP combina múltiples capas del modelo OSI. Ambos modelos comparten muchas similitudes, ya que definen estándares para las redes y dividen el proceso de comunicación de red en diferentes capas. Sin embargo, el modelo TCP/IP es una versión simplificada del modelo OSI.

## Comparación entre el modelo TCP/IP y el modelo OSI

El **modelo TCP/IP** es un marco utilizado para visualizar cómo se organizan y transmiten los datos a través de una red. Este modelo ayuda a los/las ingenieros/as y analistas de seguridad de redes a diseñar la red de datos, conceptualizar procesos y comunicar dónde se producen las interrupciones o amenazas de seguridad.

El modelo TCP/IP tiene cuatro capas: de acceso a la red, de Internet, de transporte y de aplicación. Al analizar los eventos de la red, las y los profesionales de seguridad pueden determinar en qué capa o capas se produjo el ataque, basándose en los procesos involucrados en el incidente.

En cambio, el **modelo OSI** es un concepto estandarizado que describe las siete capas que las computadoras utilizan para comunicarse y enviar datos a través de la red. Las y los profesionales de seguridad y de redes suelen utilizarlo para comunicarse entre sí sobre posibles fuentes de problemas o amenazas de seguridad.

## *Capa 7: Capa de aplicación*

La capa de aplicación incluye procesos que involucran directamente al/a la usuario/a cotidiano/a. Esta capa incluye todos los protocolos de red que las aplicaciones de software utilizan para conectarlo/a a Internet. Esta característica es la que identifica a la capa de aplicación: conexión de usuarios/as a la red a través de aplicaciones y solicitudes.

Un ejemplo de un tipo de comunicación que ocurre en la capa de aplicación es el uso de un navegador web. El navegador de Internet utiliza HTTP o HTTPS para enviar y recibir información del servidor del sitio web. La aplicación de correo electrónico utiliza el protocolo simple de transferencia de correo (SMTP) para transmitir información de correo electrónico. Además, los navegadores web utilizan el protocolo del sistema de nombres de dominio (DNS) para traducir los nombres de dominio del sitio web en direcciones IP, que identifican el servidor web que aloja la información del sitio.

## *Capa 6: Capa de presentación*

Las funciones en la capa de presentación incluyen la traducción de datos y el cifrado para la red. Esta capa agrega y reemplaza datos con formatos que pueden ser entendidos por las aplicaciones (capa 7), en los sistemas de envío y recepción. Los formatos que están más cerca del usuario final, es decir, donde se encuentra la aplicación o dispositivo que utiliza el/la usuario/a para interactuar con la red o recibir información, pueden ser diferentes de los del sistema receptor. Los procesos en la capa de presentación requieren el uso de un formato estandarizado. 

Algunas funciones de formateo que se producen en la capa 6 incluyen cifrado, compresión y confirmación de que el conjunto de caracteres puede ser interpretado en el sistema receptor. Un ejemplo de cifrado que se da en esta capa es SSL, que cifra los datos entre los servidores web y los navegadores como parte de sitios web con HTTPS.

## *Capa 5: Capa de sesión*

Una sesión indica cuando se establece una conexión entre dos dispositivos. Una sesión abierta permite que los dispositivos se comuniquen entre sí. El objetivo de los protocolos de la capa de sesión es mantener la sesión abierta mientras se transfieren datos y cerrarla una vez que se completa la transmisión. 

La capa de sesión también es responsable de actividades como la autenticación, reconexión y establecimiento de puntos de control durante una transferencia de datos. Si la sesión se interrumpe, los puntos de control aseguran que, cuando se restablece la conexión, la transmisión se retome desde el último punto de control de la sesión. Las sesiones incluyen una solicitud y respuesta entre aplicaciones. Las funciones en la capa de sesión responden a solicitudes de servicio de procesos en la capa de presentación (capa 6) y envían solicitudes de servicios a la capa de transporte (capa 4).

## *Capa 4: Capa de transporte*

La capa de transporte es la responsable de enviar datos entre dispositivos. Además, esta capa maneja la velocidad y el flujo de transferencia, y divide los datos en segmentos más pequeños para facilitar el envío. La segmentación es el proceso de dividir una gran transmisión de datos en piezas más pequeñas que puedan ser procesadas por el sistema receptor. Para que se puedan procesar en la capa de sesión (capa 5), estos segmentos tienen que volverse a ensamblar en su destino. La velocidad y la tasa de transmisión también tienen que coincidir con la velocidad de conexión del sistema de destino. TCP y UDP son protocolos de capa de transporte.

## *Capa 3: Capa de red*

La capa de red supervisa la recepción de los paquetes desde la capa de enlace de datos (capa 2) y las entrega al destino previsto. El destino previsto puede encontrarse en función de la dirección que reside en el marco de los paquetes de datos. Estos paquetes incluyen direcciones IP, que indican a los routers dónde enviarlos y se enrutan desde la red de envío hacia la red de recepción.

## *Capa 2: Capa de enlace de datos*

La capa de enlace de datos organiza el envío y la recepción de paquetes de datos dentro de una sola red. Esta capa incluye los switches en la red local y las tarjetas de interfaz de red en los dispositivos locales.

En la capa de enlace de datos se utilizan protocolos como el protocolo de control de red (NCP), el control de enlace de datos de alto nivel (HDLC) y el protocolo de control de enlace de datos sincrónico (SDLC).

## *Capa 1: Capa física* 

Como su nombre lo indica, la capa física corresponde al hardware físico utilizado en la transmisión de la red. Los hubs, los módems y el cableado que los conecta se consideran parte de esta capa. Para viajar a través de un cable Ethernet o coaxial, un paquete de datos debe ser traducido en una secuencia de ceros y unos, que se envía a través de los cables y conexiones físicas, se recibe y, luego, pasa a los niveles superiores del modelo OSI.

![[Pasted image 20231016194446.png]]
![[Pasted image 20231016194458.png]]
![[Pasted image 20231016194519.png]]

### Internet Protocol (IP) Address
Un protocolo de Internet, o dirección IP, es una cadena única de caracteres que identifica la ubicación de un dispositivo en Internet. Hay dos tipos de direcciones IP: IP versión 4, o IPv4, e IP versión 6, o IPv6. Veamos ejemplos de una dirección IPv4. Las direcciones IPv4 se escriben con 4 números de 1, 2 o 3 dígitos separados por un punto. Se desarrolló IPv6. Las direcciones IPv6 tienen hasta 32 caracteres. De esta forma, puede haber más dispositivos conectados a Internet 
sin agotar las direcciones como ocurrió con IPv4. Las direcciones IP pueden ser públicas o privadas. Tu proveedor de Internet asigna una dirección IP pública que se conecta a tu ubicación geográfica. Las comunicaciones de tu dispositivo en Internet por la red tienen la misma dirección pública.
![[Pasted image 20231016200657.png]]

![[Pasted image 20231016200722.png]]
Hay 13 campos dentro del encabezado de un paquete IPv4:

- **Versión:** el primer encabezado de 4 bits indica a los dispositivos receptores qué protocolo está utilizando el paquete. El paquete utilizado en la ilustración anterior es un paquete IPv4.
    
- **Longitud del encabezado IP (HLEN):** HLEN es la longitud del encabezado del paquete. Este valor indica dónde termina el encabezado del paquete y comienza el segmento de datos. 
    
- **Tipo de servicio (ToS):** los routers priorizan los paquetes a entregar con el fin de mantener la calidad del servicio en la red. El campo ToS proporciona esta información al router.
    
- **Longitud total:** este campo comunica la longitud total de todo el paquete IP, incluidos el encabezado y los datos. El tamaño máximo de un paquete IPv4 es de 65.535 bytes.
    
- **Identificación:** si el paquete IPv4 es superior a 65 535 bytes, se divide o fragmenta en paquetes IP más pequeños. El campo de identificación proporciona un identificador único para todos los fragmentos del paquete IP original para que puedan volver a ensamblarse cuando lleguen a su destino. 
    
- **Indicadores:** este campo proporciona al dispositivo de enrutamiento más información sobre si el paquete original se fragmentó y si hay más fragmentos en tránsito.
    
- **Desplazamiento de fragmentación:** el campo de desplazamiento de fragmento indica a los dispositivos de enrutamiento a qué parte del paquete original pertenece el fragmento.
    
- **Período de vida (TTL):** evita que los routers reenvíen los paquetes de datos de manera indefinida. Contiene un contador que determina la fuente. El contador disminuye de a uno, a medida que pasa por cada router. Cuando el contador TTL llega a cero, el router descartará el paquete y enviará al emisor un mensaje de tiempo superado ICMP. 
    
- **Protocolo:** este campo indica al dispositivo receptor qué protocolo se utilizará para el área de datos del paquete.
    
- **Suma de comprobación del encabezado:** este campo contiene una suma de comprobación que se puede usar para detectar si la cabecera IP en tránsito está dañada. Los paquetes dañados se descartan.
    
- **Dirección IP de origen:** es la dirección IPv4 del dispositivo emisor.
    
- **Dirección IP de destino:** es la dirección IPv4 del dispositivo receptor.
    
- **Opciones:** este campo permite aplicar opciones de seguridad al paquete si el valor HLEN es mayor que cinco. Además, comunica estas alternativas a los dispositivos de enrutamiento.
Una de las principales diferencias entre IPv4 e IPv6 es la longitud de las direcciones. Las direcciones IPv4 son numéricas, están compuestas por 4 bytes y admiten hasta 4300 millones de direcciones posibles. Un ejemplo sería: 198.51.100.0. En cambio, las direcciones IPv6 son hexadecimales, están compuestas por 16 bytes y permiten hasta 340 undecillones de direcciones (la cifra 340 seguida de 36 ceros). Un ejemplo de una dirección IPv6 sería: 2002:0db8:0000:0000:0000:ff21:0023:1234.

También hay algunas diferencias en el diseño del encabezado de un paquete IPv6. El formato del IPv6 es mucho más simple que el del IPv4. Por ejemplo, el encabezado de IPv4 incluye los campos HLEN, identificación e indicadores, mientras que el IPv6 no lo hace. El encabezado de IPv6 tiene otros campos que no están incluidos en IPv4, como etiqueta de flujo y clase de tráfico.
![[Pasted image 20231016200817.png]]


### MAC Address
Es un identificador alfanumérico único que se asigna a cada dispositivo físico en la red. Al recibir un paquete, el switch lee la dirección MAC del dispositivo destinatario y le asigna un puerto. Anota esta información en una tabla de direcciones MAC. La tabla de direcciones MAC es como una agenda que el switch usa para enviar paquetes a dispositivos.

![[Pasted image 20231016232915.png]]
## **Protocolos de Red**

Son un conjunto de reglas usadas por dos o más dispositivos en una red para descubrir el orden de entrega y la estructura de los datos. Los protocolos de red funcionan como instrucciones que vienen junto con la información en el paquete de datos. Estas instrucciones indican al dispositivo receptor qué hacer con los datos

### **Transmision Control Protocol TCP**
Es un protocolo de comunicación por internet permite conectar dos dispositivos y enviar datos entre ellos. Verifica la comunicación de  los dos dispositivos con el protocolo de enlace o handshake.

### **Address Resolution Protocol ARP** 
Sirve para definir la dirección MAC del siguiente router o dispositivo. Esto garantiza que los datos lleguen a su destino. Cada dispositivo en la red ejecuta el ARP y realiza un seguimiento de las direcciones IP y MAC coincidentes en un caché ARP. El ARP no tiene un número de puerto específico.

### **HyperText Transfer Protocol Secure HTTPS**
Es un protocolo de red que brinda un método seguro de comunicación entre servidores de clientes y de sitios.

### **Domain Name System DNS**
Un protocolo de red que traduce nombres de dominio de Internet a direcciones IP.

- El **protocolo de control de transmisión (TCP)** es un protocolo de comunicación de Internet que permite a dos dispositivos establecer una conexión y transmitir datos. El TCP utiliza un proceso de tres pasos. Primero, el dispositivo envía una solicitud de sincronización (SYN) a un servidor. Luego, el servidor responde con un paquete SYN/ACK para confirmar la recepción de la solicitud del dispositivo. Una vez que el servidor recibe el paquete ACK final desde el dispositivo, se establece una conexión TCP. En el modelo TCP/IP, el TCP se encuentra en la capa de transporte.
    
- El **protocolo de datagramas de usuario (UDP)** es un protocolo sin conexión que no establece un enlace entre dispositivos antes de la transmisión. Esto lo hace menos confiable que el TCP, pero también lo hace adecuado para transmisiones que requieren llegar rápidamente a su destino. Un ejemplo de uso de UDP se da en las transmisiones de juegos en línea. En el modelo TCP/IP, el UDP se encuentra en la capa de transporte.
    
- El **protocolo de transferencia de hipertexto (HTTP)** es un protocolo de capa de aplicación que proporciona un método de comunicación entre clientes y servidores de sitios web. El HTTP usa el puerto 80 y se considera inseguro. Aunque aún algunos sitios web lo utilizan, en muchos otros está siendo reemplazado por una versión segura, llamada HTTPS. En el modelo TCP/IP, el HTTP se encuentra en la capa de aplicación.
    
- El **sistema de nombres de dominio (DNS)** es un protocolo que traduce los nombres de dominio de Internet como direcciones IP. Cuando un equipo del cliente desea acceder a un dominio de sitio web utilizando su navegador de Internet, se envía una consulta a un servidor DNS dedicado. El servidor DNS luego busca la dirección IP que corresponde al dominio del sitio web. El DNS suele usar un protocolo de datagramas de usuario (UDP) en el puerto 53. Sin embargo, si la respuesta del DNS a una solicitud es grande, se pasará al protocolo TCP. En el modelo TCP/IP, el DNS se encuentra en la capa de aplicación.

### **Security Protocols**
El HTTPS cifra los datos utilizando la capa de conexión segura y seguridad de la capa de transporte, 

denominadas SSL/TLS.
- HTTPS
- SSL/TLS

## Las tres categorías de protocolos de red

Los protocolos de red se pueden dividir en tres categorías principales: protocolos de comunicación, de gestión y de seguridad. Existen decenas de protocolos de red diferentes, pero no es necesario que los memorices todos para desempeñar un puesto de analista de seguridad de nivel inicial.

### **Protocolos de gestión**

La siguiente categoría es la de los protocolos de gestión. Estos se utilizan para monitorear y administrar la actividad en una red. Incluyen protocolos para notificar errores y optimizar el rendimiento en la red.

- El **protocolo simple de administración de red (SNMP)** es un protocolo de red utilizado para monitorear y gestionar los dispositivos en una red. El SNMP puede restablecer una contraseña en un dispositivo de red o cambiar su configuración básica. También puede enviar solicitudes a los dispositivos de red para obtener un informe sobre cuánto ancho de banda de la red está siendo utilizado. En el modelo TCP/IP, el SNMP se encuentra en la capa de aplicación.
    
- El **protocolo de mensajes de control de Internet (ICMP)** es un protocolo de Internet utilizado por los dispositivos para informarse mutuamente sobre errores de transmisión de datos en la red. El ICMP es utilizado por un dispositivo receptor para enviar un informe al dispositivo emisor sobre la transmisión de datos. Suele usarse como una forma rápida de solucionar problemas de conectividad y el tiempo de respuesta (o latencia) de la red mediante la emisión del comando “ping” en un sistema operativo Linux. En el modelo TCP/IP, el ICMP se encuentra en la capa de Internet.
 ^5cf012
- El **protocolo seguro de transferencia de archivos (SFTP)** es un protocolo seguro utilizado para transferir archivos de un dispositivo a otro a través de una red. El SFTP utiliza el protocolo Secure Shell (SSH), en general, a través del puerto TCP 22. El SSH utiliza un estándar de cifrado avanzado (Advanced Encryption Standard, AES) y otros tipos de encriptación para asegurar que destinatarios no deseados no puedan interceptar las transmisiones. En el modelo TCP/IP, el SFTP se encuentra en la capa de aplicación. El SFTP suele utilizarse con almacenamiento en la nube. Cada vez que un/a usuario/a carga o descarga un archivo desde el almacenamiento en la nube, el documento se transfiere utilizando el protocolo SFTP.
## Telnet 

Telnet es un protocolo de capa de aplicación que permite que un dispositivo se comunique con otro equipo o servidor. Telnet envía toda la información en texto claro. Si bien utiliza indicadores de línea de comando para controlar otro dispositivo similar al protocolo Secure Shell  (SSH), no es tan seguro como el SSH. Telnet se puede usar para conectarse a dispositivos locales o remotos y utiliza el puerto TCP 23.

## Protocolo Secure Shell (SSH)

El protocolo Secure Shell (SSH) se utiliza para crear una conexión segura con un sistema remoto. Este protocolo de capa de aplicación proporciona una alternativa para la autenticación segura y la comunicación cifrada. El SSH opera sobre el puerto TCP 22 y es un reemplazo para protocolos menos seguros, como Telnet.

## Protocolo de oficina postal

El protocolo de oficina postal (POP, por Post Office Protocol) es un protocolo de capa de aplicación (capa 4 en el modelo TCP/IP) que se utiliza para gestionar y recuperar correos electrónicos de un servidor de correo. Muchas organizaciones tienen un servidor de correo dedicado que maneja el correo entrante y saliente para los/as usuarios/as en la red. Los dispositivos de usuario envían solicitudes al servidor y descargan mensajes de correo electrónico de forma local. Si alguna vez has actualizado tu aplicación de correo electrónico y has visto nuevos correos electrónicos aparecer en tu bandeja de entrada, estás experimentando el POP y el protocolo de acceso a mensajes de Internet (IMAP). La autenticación de texto no encriptada utiliza el puerto TCP/UDP 110, mientras que los correos electrónicos cifrados utilizan capa de conexión segura/seguridad en la capa de transporte (SSL/TLS) sobre el puerto TCP/UDP 995. Al usar el POP, el correo debe terminar de descargarse en un dispositivo local antes de poder leerse. Además, no permite que un/a usuario/a sincronice los correos electrónicos.

## Protocolo de acceso a mensajes de Internet (IMAP)

El protocolo de acceso a mensajes de Internet (IMAP) se utiliza para correos electrónicos entrantes. Descarga sus encabezados, pero no el contenido, que permanece en el servidor, posibilitando a los/as usuarios/as acceder a su correo electrónico desde diferentes dispositivos. El IMAP utiliza el puerto TCP 143 para correos electrónicos no encriptados y el puerto TCP 993 con el protocolo TLS. El uso del IMAP permite a las personas leer parcialmente los correos electrónicos antes de que se terminen de descargar y sincronizarlos. Sin embargo, el IMAP es más lento que el POP3.

## Protocolo para transferencia simple de correo (SMTP)

El protocolo para transferencia simple de correo (SMTP) se utiliza para transmitir y enrutar correos electrónicos desde el remitente hasta la dirección del/de la destinatario/a. El SMTP funciona con el software Message Transfer Agent (MTA), que consulta los servidores de sistema de nombres de dominio (DNS) para obtener las direcciones IP correspondientes a las direcciones de correo electrónico, asegurando que estos lleguen al destino previsto. El SMTP usa el puerto TCP/UDP 25 para correos electrónicos no cifrados y el puerto TCP/UDP 587 utiliza TLS para los cifrados. Con cierta frecuencia, el puerto TCP 25 se usa para el spam de alto volumen. El SMTP ayuda a filtrar el spam regulando la cantidad de correos electrónicos que una fuente puede enviar al mismo tiempo.

## Protocolos y números de puerto

Recuerda que los números de puerto son utilizados por los dispositivos de red para determinar qué se debe hacer con la información contenida en cada paquete de datos una vez que lleguen a su destino. Los cortafuegos (firewalls) pueden filtrar el tráfico no deseado, basándose en los números de puerto. Por ejemplo, una empresa puede configurar un cortafuegos para permitir solo el acceso al puerto TCP 995 (POP3) a través de direcciones IP que pertenecen a la organización.

Algunos protocolos tienen números de puerto asignados por la Internet Assigned Numbers Authority  (IANA, por sus siglas en inglés). Estos números de puerto se incluyen en la descripción de cada protocolo, si están asignados.
Los protocolos abordados en esta lectura son los siguientes: NAT, DHCP, ARP, Telnet, SSH, POP3, IMAP y SMTP. Es igualmente importante comprender dónde se ubica cada protocolo en el modelo TCP/IP y qué puertos ocupa.

|**Protocolo**|**Puerto**|
|---|---|
|DHCP|Puerto UDP 67 (servidores)<br><br>Puerto UDP 68 (clientes)|
|ARP|Ninguno|
|Telnet|Puerto TCP 23|
|SSH|Puerto TCP 22|
|POP3|Puerto TCP/UDP 110 (sin cifrar)<br><br>Puerto TCP/UDP 995 (cifrado, SSL/TSL)|
|IMAP|Puerto TCP 143 (sin cifrar)<br><br>Puerto TCP 993 (cifrado, SSL/TSL)|
|SMTP|Puerto TCP/UDP 25 (admite cifrado TSL)<br><br>Puerto TCP/UDP 587 (cifrado, TSL)|

## Traducción de direcciones de red

Los dispositivos en tu red doméstica u oficina local tienen cada uno una dirección IP privada que utilizan para comunicarse entre sí. Para que los dispositivos con direcciones IP privadas puedan comunicarse con Internet pública, necesitan tener una dirección IP pública. De lo contrario, las respuestas no se enrutarán correctamente. En lugar de tener una dirección IP pública dedicada para cada uno de los dispositivos en la red local, el enrutador puede reemplazar la dirección IP de origen privado con su dirección IP pública y realizar la operación inversa para las respuestas. Este proceso se conoce como traducción de direcciones de red (NAT) y generalmente requiere que el enrutador o cortafuegos (firewall) se configuren específicamente para tal fin. La NAT es parte de la capa 2 (capa de Internet) y la capa 3 (capa de transporte) del modelo TCP/IP.

|**Direcciones IP privadas**|**Direcciones IP públicas**|
|---|---|
|- Las asignan los administradores de red<br>    <br>- Son únicas solo dentro de la red privada<br>    <br>- No tienen costo de uso<br>    <br>- Rangos de direcciones:<br>    <br>    - 10.0.0.0-10.255.255.255<br>        <br>    - 172.16.0.0-172.31.255.255<br>        <br>    - 192.168.0.0-192.168.255.255|- Las asignan el IANA y el ISP<br>    <br>- Las direcciones son únicas en Internet a nivel mundial<br>    <br>- Alquilar una dirección IP pública tiene costo<br>    <br>- Rangos de direcciones:<br>    <br>    - 1.0.0.0-9.255.255.255<br>        <br>    - 11.0.0.0-126.255.255.255<br>        <br>    - 128.0.0.0-172.15.255.255<br>        <br>    - 172.32.0.0-192.167.255.255<br>        <br>    - 192.169.0.0-233.255.255.255|

## Protocolo de configuración dinámica de host

El protocolo de configuración dinámica de host (DHCP) pertenece a la familia de los protocolos de gestión de redes. El DHCP es un protocolo de capa de aplicación utilizado en una red para configurar dispositivos. Asigna una dirección IP única y proporciona las direcciones del servidor DNS adecuado y la puerta de enlace predeterminada para cada dispositivo. Los servidores DHCP operan en el puerto UDP 67, mientras que los clientes DHCP operan en el puerto UDP 68.

## **Protocolos Inalámbricos**
### **IEEE 802.11 Wi-Fi**
Son estándares que definen las comunicaciones entre LAN inalámbricas.

### **WiFi protected Access WPA**
Es un protocolo de seguridad inalámbrica para conectar a Internet.

### **WPA2 y WPA3**

#### **WPA2**

La segunda versión del acceso Wi-Fi protegido (WPA), conocida como WPA2, se lanzó en 2004. El WPA2 es una mejora con respecto al WPA que se basa en el uso del Advanced Encryption Standard (AES). También, optimiza el uso del TKIP. El WPA2 usa Counter Mode Cipher Block Chain Message Authentication Code Protocol (CCMP), que proporciona encapsulación y garantiza la autenticación e integridad de los mensajes. Debido a la fortaleza del WPA2, se considera el estándar de seguridad para todas las transmisiones Wi-Fi en la actualidad. Sin embargo, al igual que su predecesor, el WPA2 es vulnerable a los ataques KRACK. Esto llevó al desarrollo de WPA3 en 2018.

#### **Personal**

El modo personal del WPA2 es el más adecuado para redes domésticas por diversas razones; es fácil de implementar y la configuración inicial lleva menos tiempo que para la versión empresarial. La frase de contraseña global para la versión personal del WPA2 debe aplicarse a cada computadora y punto de acceso individual en una red. Esto lo hace ideal para redes domésticas, pero poco práctico de gestionar en las organizaciones.

#### **Empresarial**

El modo empresarial del WPA2 es el más adecuado para aplicaciones corporativas. Proporciona la seguridad necesaria para las redes inalámbricas en entornos comerciales. Si bien la configuración inicial es más complicada que en el modo personal WPA2, el empresarial ofrece un control individualizado y centralizado sobre el acceso Wi-Fi a una red empresarial. Esto significa que quienes administren la red pueden otorgar o eliminar el acceso de los/las usuarios/as a una red en cualquier momento. Los/las usuarios/as nunca tienen acceso a las claves de cifrado, lo que evita que posibles atacantes recuperen las claves de red en computadoras individuales.

#### **WPA3**

El WPA3 es un protocolo de Wi-Fi seguro y su uso está creciendo a medida que se lanzan más dispositivos compatibles con este protocolo. Las principales diferencias entre el WPA2 y el WPA3 son:

- El WPA3 aborda la vulnerabilidad de intercambio de autenticación a los ataques KRACK, que está presente en el WPA2. 
    
- El WPA3 utiliza la Autenticación Simultánea de Iguales (SAE, por sus siglas en inglés), un acuerdo de autenticación de contraseña y cifrado de claves. Esto evita que los atacantes descarguen datos de las conexiones de redes inalámbricas para intentar descifrarlos.
    
- El WPA3 incrementó el cifrado para hacer que las contraseñas sean más seguras mediante el uso de encriptación de 128 bits, mientras que el modo WPA3 empresarial ofrece un cifrado opcional de 192 bits.
## **Firewall**
Un cortafuegos es un dispositivo de seguridad que monitorea el tráfico de red. Autoriza o bloquea el tráfico según un conjunto de reglas de seguridad. 
## **Port Filtering**
Filtra puertos para bloquear o permitir ciertos números de puerto y limitar la comunicación indeseada.  Por ejemplo, puede haber una regla que solo autoriza el puerto 443 para HTTPS o el puerto 25 para correo electrónico, y bloquea lo demás.

## **Cloud Firewall**
Los proveedores de servicios en la nube ofrecen cortafuegos como servicio, o FaaS. Estos son cortafuegos de software alojados en la nube por un proveedor. Las organizaciones configuran reglas en la interfaz del proveedor. El cortafuegos realizará operaciones de seguridad con el tráfico entrante antes de llegar a la red local de la organización. Los cortafuegos basados en la nube también protegen activos o procesos en la nube.

### **Stateful**
Stateful es un cortafuegos que hace un seguimiento de la información que pasa a través de él y filtra proactivamente las amenazas. Un cortafuegos stateful busca características y comportamientos sospechosos del tráfico y evita que entre a la red.

### **Stateless**
funciona según reglas predeterminadas y no hace un seguimiento de los paquetes. El cortafuegos stateless solo actúa según las reglas preconfiguradas por el administrador. Estas reglas indican al dispositivo qué aceptar y qué rechazar. Un cortafuegos stateless no almacena información analizada ni descubre tendencias sospechosas como el cortafuegos stateful.

### NGFWs
No solo realiza una inspección stateful del tráfico entrante y saliente, también realiza funciones más profundas como la inspección profunda de paquetes y protección contra intrusiones. Algunos NGFW se conectan a servicios de inteligencia de amenazas basados en la nube para protegerse contra amenazas cibernéticas.


### **Virtual Private Network**

Es un servicio de seguridad que cambia tu dirección IP Pública y oculta tu ubicación virtual para proteger tus datos al usar una red pública como Internet.

### **Encapsulación**
 El encapsulado de la VPN protege los datos, envolviéndose en otros paquetes de datos.

La VPN cifra tus paquetes de datos y los encapsula en otros paquetes de datos que leen los routers. Así tus solicitudes llegan a su destino, pero con tus datos personales cifrados para que no se lean en tránsito. La VPN también usa un túnel cifrado entre tu dispositivo y el servidor VPN. El cifrado no puede hackearse sin una clave criptográfica, por lo que nadie puede acceder a tus datos.

## **Security Zone**
Es un segmento de l una red que protege la red interna de Internet. Forma parte de una técnica de seguridad llamada segmentación de red.

## **Network Segmentation**
Técnica de seguridad llamada segmentación de red, que divide la red en segmentos. Cada uno tiene sus propios permisos y reglas de seguridad.
![[Pasted image 20231019191807.png]]

La red de una organización se clasifica en dos tipos de zonas de seguridad.

### **Uncontrolled zone**
Cualquier red fuera del control de la organización (Internet).

### **Controlled Zone**
Una subred que protege a la red interna de la zona no controlada.


Areas in the controlled zone.

- Demilitarized zone (DMZ) que contiene servicios públicos que acceden a internet(Servidores Web, servidores proxy) actúa como un perímetro de red para la red interna.
- Internal Network tiene servidores privados y datos que las empresas necesitan proteger.
- Restricted zone está protege la información confidencial que solo puede ver los empleados autorizados.
![[Pasted image 20231019192816.png]]

# Subnetting y enrutamiento entre dominios sin clases (CIDR)

Anteriormente, en este curso aprendiste sobre la segmentación de redes, una técnica de seguridad que divide las redes en secciones. Una red privada puede segmentarse para proteger ciertas partes de la red de acceso a Internet, que es una red global no segura. 

Por ejemplo, aprendiste sobre la zona no controlada, la zona controlada, la zona desmilitarizada y la zona restringida. Si lo deseas, puedes revisar el video sobre [las zonas de seguridad](https://www.coursera.org/learn/conexion-y-proteccion-redes-y-seguridad-de-redes/lecture/GccYm/zonas-de-seguridad) para refrescar cómo la segmentación de redes para agregar una capa de seguridad a las operaciones de red de tu organización. La creación de zonas de seguridad es un ejemplo de una estrategia llamada subnetting.

## Descripción general del subnetting

**El subnetting** es la subdivisión de una red en grupos lógicos llamados subredes, lo que funciona como una red dentro de otra red. Este proceso divide el rango de direcciones de red en subredes más pequeñas dentro de la red principal. Estas subredes se forman según las direcciones IP y máscara de red de los dispositivos. Al utilizar el subnetting, se genera una red de dispositivos que funcionan como su propia red, lo cual mejora la eficiencia general de la red. También puede ser utilizado para crear zonas de seguridad. Cuando los dispositivos en la misma subred se comunican entre sí, el switch de la red cambia las transmisiones para que permanezcan en la misma subred, mejorando la velocidad y la eficiencia de las comunicaciones.

![[Pasted image 20231019193106.png]]

## Notación del enrutamiento entre dominios sin clase (CIDR) para el subnetting

El enrutamiento entre dominios sin clase (CIDR) es un método para asignar máscaras de subred a direcciones IP con el fin de crear  subredes, que reemplaza al antiguo direccionamiento con clase. Este último, que solía usarse en la década de 1980, agrupaba las direcciones IP en clases (de la Clase A a la Clase E), cada una con un número limitado de direcciones. Sin embargo, a medida que el número de dispositivos conectados a Internet aumentaba, en la década de 1990, estas direcciones con clase se agotaron. En cambio, el enfoque CIDR amplió la cantidad de direcciones IPv4 disponibles. 

El CIDR permite a las y los profesionales de la ciberseguridad segmentar redes clasificadas en clases en fragmentos más pequeños. Las direcciones IP en formato CIDR son similares a las direcciones IPv4, pero incluyen una barra diagonal ("/") seguida de un número al final de la dirección, conocido como el prefijo de red IP. Por ejemplo, una dirección IPv4 normal utiliza el formato 198.51.100.0, mientras que una dirección IP CIDR incluiría el prefijo de red IP al final de la dirección, 198.51.100.0/24. Esta dirección CIDR abarca todas las direcciones IP entre 198.51.100.0 y 198.51.100.255. El sistema de direccionamiento CIDR reduce el número de entradas en las tablas de enrutamiento y proporciona más direcciones IP disponibles dentro de las redes. Puedes probar la conversión de direcciones CIDR a direcciones IPv4 y viceversa a través de una herramienta de conversión en línea, como [IPAddressGuide](https://www.ipaddressguide.com/cidr), para practicar y comprender mejor este concepto.

## Beneficios de seguridad del subnetting

El subnetting permite a las y los profesionales y analistas crear una red dentro de su propia red sin solicitar otra dirección IP de red al proveedor de servicios de Internet. Este proceso utiliza el ancho de banda de la red de manera más eficiente y mejora el rendimiento. El subnetting es un componente para crear subredes aisladas a través del aislamiento físico, la configuración de enrutamiento y los cortafuegos (firewalls).

## **Proxy Server**
Es un servir que cumple con la solicitud de un cliente al transmitirla a otros servidores.

### **Foward proxy server**
El servidor proxy directo regula y restringe el acceso a Internet. Oculta la dirección IP del cliente y se aprueban todas las solicitudes salientes.

### **Reverse proxy server**
Un servidor proxy inverso regula y restringe el acceso a Internet a un servidor interno. Se recibe el tráfico de partes externas, se aprueban y se reenvía a los servidores internos.

### **Email proxy server**
Filtra el correo spam verificando si la dirección del remitente ha sido fasificada. Esto reduce el riesgo de ataques de pishing que se hacen pasar por personas conocidas.

Estos servidores utilizan la traducción de direcciones de red (NAT) para actuar como una barrera entre los clientes en la red y las amenazas externas. Los servidores proxy directos manejan consultas de clientes internos cuando acceden a recursos externos a la red. Por otro lado, los servidores proxy inversos funcionan de manera opuesta, manejando las solicitudes provenientes de sistemas externos hacia los servicios en la red interna. Además, algunos servidores proxy se pueden configurar con reglas similares a un cortafuegos. Por ejemplo, es posible crear filtros para bloquear sitios web identificados como portadores de malware.

**Archivo de libre escritura (World-writable file):** Archivo que puede ser alterado por cualquier persona.
![[Pasted image 20231019210925.png]]
![[Pasted image 20231019210941.png]]![[Pasted image 20231019211539.png]]

## Ataques de interceptación de red
se conoce como **rastreo de paquetes (packet sniffing)**. Además de ver información a la que no tienen derecho, los agentes de amenaza también pueden interceptar el tráfico de red y alterarlo. Estos ataques pueden causar daños a la red de una organización al insertar modificaciones de código malicioso, alterar el mensaje o bien, interrumpiendo las operaciones de la red. Por ejemplo, un/a atacante puede interceptar una transferencia bancaria y cambiar la cuenta que recibe los fondos por otra que esté bajo su control.

## Ataques de puerta trasera
Un **ataque de puerta trasera** es otro tipo de ataque que deberás conocer como analista de seguridad. Una organización puede contar con muchas medidas de seguridad, como cámaras, escáneres biométricos y códigos de acceso, para evitar que los/las empleados/as entren y salgan sin ser vistos. Sin embargo, un/a empleado/a podría burlar las medidas de seguridad si encuentra una puerta trasera al edificio que no esté tan vigilada, lo que le permitiría escabullirse por allí. 

En ciberseguridad, las puertas traseras son puntos débiles dejados intencionalmente por programadores/as o administradores/as de sistemas y redes, que eluden los mecanismos normales de control de acceso. Las puertas traseras están pensadas para ayudar a los/las programadores/as a solucionar problemas o realizar tareas administrativas. Sin embargo, las/los atacantes también pueden instalarlas tras haber puesto en riesgo a una organización, para asegurarse el acceso permanente.

[[Modulo 2 Ataques, conceptos y técnicas#**Denegación de Servicio DoS**]] 

[[Modulo 2 Ataques, conceptos y técnicas#*DoS Distribuido*]]

### SYN (synchronize) flood attack
A type of DoS attack that simulates a TCP connection and floods a server with a SYN packets

### ICMP FLOOD
[[#^5cf012]]
A type of DoS attack performed by an attacker repeatedly sending ICMP packets to a network server.

### Ping of dead
A type of Dos attack caused when a hacker pings a system by sending it an oversized ICMP packet that is bigger than 64KB.

Un **analizador de protocolo de red**, a veces llamado sniffer de paquetes (rastreador de paquetes) o analizador de paquetes, es una herramienta diseñada para capturar y analizar el tráfico de datos dentro de una red. Suele usarse como herramienta de investigación para monitorear redes e identificar actividades sospechosas. Existe una gran variedad de analizadores de protocolos de red. Algunos de los más comunes son:

- Analizador de tráfico NetFlow de SolarWinds
    
- ManageEngine OpManager
    
- Azure Network Watcher
    
- Wireshark
    
- tcpdump

**tcpdump** proporciona un breve análisis de paquetes, convierte información clave sobre el tráfico de red en formatos fácilmente legibles para las personas e imprime información sobre cada paquete directamente en el terminal. tcpdump también muestra la dirección IP de origen, las direcciones IP de destino y los números de puerto que se utilizan en las comunicaciones.

## Interpretación de la salida

tcpdump imprime la salida del comando como los paquetes detectados en la línea de comandos y, opcionalmente, en un archivo de registro, después de ejecutar un comando. La salida de una captura de paquetes contiene mucha información importante sobre el tráfico de red.

![[Pasted image 20231027095551.png]]**Nota:** De forma predeterminada, tcpdump intentará convertir direcciones de host a nombres de host. También reemplazará los números de puerto con los servicios comúnmente asociados que usan estos puertos.
## Usos comunes

tcpdump y otros analizadores de protocolos de red se utilizan habitualmente para capturar y visualizar comunicaciones de red y para recopilar estadísticas sobre la red, por ejemplo, para solucionar problemas de rendimiento. También se pueden usar para:

- Establecer una línea de base para los patrones de tráfico de red y las métricas de utilización de la red.
    
- Detectar e identificar tráfico malicioso.
    
- Crear alertas personalizadas para enviar las notificaciones adecuadas cuando surgen problemas de red o amenazas a la seguridad.
    
- Localizar mensajería instantánea (IM), tráfico o puntos de acceso inalámbricos no autorizados.
    

Sin embargo, las/los atacantes también pueden utilizar maliciosamente los analizadores de protocolos de red para obtener información sobre una red específica. Por ejemplo, podrían capturar paquetes de datos que contengan información sensible, como nombres de usuario y contraseñas de cuentas. Como analista de ciberseguridad, es importante comprender la finalidad y los usos de los analizadores de protocolos de red.

![[Pasted image 20231027100441.png]]

El día del ataque DDoS que estamos estudiando, muchas grandes empresas estaban utilizando un proveedor de servicios DNS. El proveedor de servicios alojaba el sistema DNS de estas empresas. O sea que, cuando las/los internautas escribían la URL del sitio web al que querían acceder, sus dispositivos eran dirigidos al lugar correcto. El 21 de octubre de 2016, el proveedor de servicios fue víctima de un ataque DDoS.

## Antes del ataque

Previo al ataque al proveedor de servicios, un grupo de estudiantes universitarios creó una botnet. Una **botnet** es un conjunto de computadoras infectadas por software malicioso que están bajo el control de un solo agente de amenaza, conocido como el “bot-herder” (pastor de bots). Cada computadora de la botnet se puede controlar de forma remota, para enviar un paquete de datos a un sistema de destino. En un ataque de botnet, las/los ciberdelincuentes instruyen a todos los bots de la botnet que envíen paquetes de datos al sistema de destino al mismo tiempo, lo que da lugar a un ataque DDoS.

El grupo de estudiantes universitarios publicó en línea el código de la botnet para que fuera accesible a miles de usuarios/as de Internet y las autoridades no pudieran rastrearla. Al publicar el código, permitieron que otros agentes de amenaza aprendieran el código de la botnet y la controlaran de forma remota, entre ellos, las/los ciberdelincuentes que atacaron al proveedor de servicios DNS.

## El día del ataque

A las 7:00 de la mañana del día del ataque, la botnet envió decenas de millones de solicitudes DNS al proveedor de servicios. Esto desbordó el sistema y el servicio DNS se desconectó, por lo cual no se podía acceder a ninguno de los sitios web que utilizaban el proveedor de servicios. Cuando los/las usuarios/as intentaron acceder a varios sitios web que utilizaban el proveedor de servicios, no fueron dirigidos al sitio que habían escrito en su navegador. Las interrupciones de cada servicio web se produjeron en toda Norteamérica y Europa. 

Los sistemas del proveedor de servicios se restauraron tras solo dos horas de inactividad. Aunque las/los ciberdelincuentes enviaron oleadas posteriores de ataques de botnet, la empresa de DNS estaba preparada y fue capaz de mitigar el impacto.

## Conclusiones clave

Como se demostró en el ejemplo anterior, los ataques DDoS pueden ser muy perjudiciales para una organización. Como analista de seguridad, es importante reconocer la gravedad de un ataque de este tipo para saber cómo proteger la red. Si tu red tiene operaciones importantes distribuidas a través de hosts que pueden adaptarse dinámicamente, entonces las operaciones pueden continuar si la infraestructura de host de línea de base se desconecta. Los ataques DDoS son dañinos, pero hay acciones concretas que las/los analistas de seguridad pueden tomar para proteger sus organizaciones. Continúa con este curso y aprenderás sobre las estrategias de mitigación más comunes, que se utilizan para protegerse contra los ataques DDoS.

### Passive packet sniffing 
A type of attack where data packets are read in transit.
### Active packet sniffing
A type of attack where data packets are manipulated in transit.

### IP spoofing - suplantación de IP
A network attack performed when an attacker changes the source IP of a data to impersonate an authorized system and gain access to a network.

### Common IP spoofing attacks 
- On-path attack
- Replay attack
- Smurf attacks

### ON-path attack
An attack where a malicious actor places themselves in the middle of an authorized connection and intercepts or alters the data in transit.

### Replay attack
A network attack performed when a malicious actor intercept a data packet in transit and delays it or repeats it at another time.

### Smurf attack
A network attack performed when an attacker sniffs an authorized user´s IP address and floods it with packets.

### Como proteger a estos ataques
- On-path attack
	- Con cifrado de conexiones
- Replay attack
	- Firewalls como protección, bloquear todo el trafico entrante que tenga la misma dirección IP de la red local.
- Smurf attacks

La **tarjeta de interfaz de red** **(NIC)** del dispositivo es un componente hardware que conecta el dispositivo a una red. La NIC lee la transmisión de datos y, si contiene la dirección MAC del dispositivo, acepta el paquete y lo envía al dispositivo para que procese la información según el protocolo. Esto ocurre en todas las operaciones de red estándar. Sin embargo, una NIC se puede configurar en modo promiscuo, lo que significa que acepta todo el tráfico de la red, incluso los paquetes que no están dirigidos al dispositivo de la NIC.

### **Ataque pitufo**

Un **ataque pitufo** sucede cuando un atacante detecta la dirección IP de un usuario autorizado y la abruma con paquetes. Una vez que el paquete falsificado llega a la dirección de difusión, se envía a todos los dispositivos y servidores de la red. 

En un ataque pitufo, la suplantación de IP se combina con otra técnica de denegación de servicio (DoS) para inundar la red con tráfico no deseado. Por ejemplo, el paquete falsificado podría incluir un ping del protocolo de mensajes de control de Internet (ICMP). Como aprendiste antes, ICMP se utiliza para solucionar problemas de una red. Pero si se transmiten demasiados mensajes ICMP, las respuestas de eco ICMP abruman a los servidores de la red y estos se apagan. Esto crea una denegación de servicio que puede detener las operaciones de una organización.

Una forma importante de protegerse contra un ataque pitufo es usar un cortafuegos avanzado que pueda monitorear cualquier tráfico inusual en la red. La mayoría de los cortafuegos de nueva generación (NGFW) incluyen funciones que detectan anomalías en la red para garantizar que se detecten transmisiones de gran tamaño antes de que tengan la oportunidad de derribar la red

![[Pasted image 20231027113901.png]]

## *Security Hardening*
The process of strengthening a system to reduce its vulnerability and attacks surface.

### *Security hardening is conducted on*
- Hardware
- Operating Systems
- Applications
- Computer networks
- Databases

### *Penetration test*
A simulated attack that helps identify vulnerabilities in systems, networks, websites, applications, and processes.

### *Operating system (os)*
The interface between computer hardware and the user.

### *Patch update*
A software and operating system update that address security vulnerabilities within a program or product.

### *Baseline configuration (baseline image)*
A documented set of specifications within a system that is used as a basis for future builds, releases, and updates.

### *Multi-factor authentication (MFA)*
A security measure which requires a user to verify their identity in two or more ways to access a system or network.

### **Categories of multi-factor identification**
- Something you know
- Something you have
- Something unique about you
## Evaluación de vulnerabilidades

Antes de que ocurra un ataque de fuerza bruta u otro incidente de ciberseguridad, las empresas pueden ejecutar una serie de pruebas en su red o aplicaciones web para evaluar vulnerabilidades. Las/los analistas pueden usar máquinas virtuales y entornos controlados (sandboxes) para probar archivos sospechosos, verificar vulnerabilidades antes de que ocurra un evento o simular un incidente de ciberseguridad.

### **Máquinas virtuales (VM)**

Las máquinas virtuales (VM) son versiones en software de computadoras físicas. Las máquinas virtuales proporcionan una capa adicional de seguridad porque se pueden usar para ejecutar código en un entorno aislado, evitando que el código malicioso afecte al resto de la computadora o sistema. Las máquinas virtuales también se pueden eliminar y reemplazar por una imagen prístina después de probar el software malicioso. 

Las máquinas virtuales son útiles cuando se investigan máquinas potencialmente infectadas o se ejecuta malware en un entorno restringido. El uso de una máquina virtual puede evitar daños en tu sistema en caso de que sus herramientas se utilicen incorrectamente. Las máquinas virtuales también te dan la capacidad de restablecer a un estado anterior. Sin embargo, aún existe un pequeño riesgo de que un programa malicioso pueda escapar de la virtualización y acceder a la máquina host. 

Con máquinas virtuales, puedes probar y explorar aplicaciones fácilmente, y es fácil cambiar entre diferentes máquinas virtuales desde tu computadora. Esto también puede ayudar a agilizar muchas tareas de seguridad.

### **Entornos controlados (Sandboxes)**

Un área de prueba o “sandbox” es un tipo de entorno que te permite ejecutar software o programas fuera de tu red. Se usan comúnmente para probar parches, identificar y abordar errores o detectar vulnerabilidades de ciberseguridad. Estas áreas de prueba también se pueden utilizar para evaluar software sospechoso o archivos que contienen código malicioso y simular escenarios de ataque. 

Las áreas de prueba pueden ser computadoras físicas independientes que no están conectadas a una red; sin embargo, como entornos para un área de prueba, suele ser más rentable usar software o máquinas virtuales basadas en la nube. Ten en cuenta que quienes crean malware, por lo general, saben cómo escribir código, para detectar si el código malicioso se ejecuta en una máquina virtual o en un entorno de área de prueba. Las/los atacantes pueden programar su código malicioso para que se comporte como un software inofensivo cuando se ejecuta dentro de este tipo de entornos de prueba.

## Medidas de prevención

Algunas medidas comunes que las organizaciones utilizan para prevenir ataques de fuerza bruta y similares son: 

- **Salting y hashing:** el hashing convierte la información en un valor único que luego se puede usar para determinar su integridad. Es una función unidireccional, lo que significa que es imposible descifrar y obtener el texto original. Salting agrega caracteres aleatorios a las contraseñas hash. Esto aumenta la longitud y la complejidad de los valores hash, haciéndolos más seguros.
    
- **Autenticación de múltiples factores (MFA) y autenticación de dos factores (2FA):** MFA es una medida de seguridad que requiere que un usuario verifique su identidad de dos o más maneras para acceder a un sistema o red. Esta verificación se realiza al utilizar una combinación de factores de autenticación: un nombre de usuario y contraseña, huellas dactilares, reconocimiento facial o una contraseña única (OTP) enviada a un número de teléfono o correo electrónico. 2FA es similar a MFA, pero utiliza solo dos formas de verificación.
    
- **CAPTCHA y reCAPTCHA:** CAPTCHA significa Prueba de Turing Pública y Automatizada para Diferenciar entre Máquinas y Humanos. Pide a los/las usuarios/as que completen una prueba simple que demuestre que son personas. Esto ayuda a evitar que el software intente forzar una contraseña. reCAPTCHA es un servicio gratuito de CAPTCHA de Google que ayuda a proteger los sitios web de bots y software malicioso.
    
- **Políticas de contraseña:** las organizaciones utilizan políticas de contraseña para estandarizar buenas prácticas. Estas pueden incluir pautas sobre el nivel de complejidad que debe tener una contraseña, la frecuencia con la que los/las usuarios/as deben actualizarlas y el límite de intentos de inicio de sesión por parte de un/a usuario/a antes de que se suspenda su cuenta.

 ![[Pasted image 20231027172237.png]]![[Pasted image 20231027172322.png]]![[Pasted image 20231027172350.png]]
## **Network security hardening**
- Port filtering
- Network access privilege
- Encryption

### *Task performed*
- firewalls
- Network log analysis
- Patch updates
- Server backups

### *Network log analysis*
The process of examining network logs to identify events of interest.

### *Security Infomration and Event Management tool (SIEM)*
AN application that collects and analyzes log data to monitor critical activities in an organization.

### *Port filtering*
A firewall function that blocks or allows certain port numbers to limit unwanted communication.

![[Pasted image 20231027225724.png]]
## Cortafuegos (firewall)

Hasta el momento en el curso, aprendiste sobre cortafuegos (firewalls) sin estado, con estado, de próxima generación (NGFW), y conociste las ventajas de seguridad de cada uno de ellos.

La mayoría de los firewalls son similares en sus funciones básicas. Todos permiten el tráfico o lo bloquean en función de un conjunto de reglas. A medida que los paquetes de datos entran en una red, se inspecciona el encabezado del paquete para permitir o denegar su acceso en función de su número de puerto. Los NGFW también pueden inspeccionar cargas útiles de paquetes. Cada sistema debe tener su propio firewall, independientemente del de la red.

## Sistema de detección de intrusiones

Un **sistema de detección de intrusiones** (IDS) es una aplicación que monitorea la actividad del sistema y alerta sobre posibles intrusiones. Un IDS alerta a los/las administradores/as en función de la firma del tráfico malicioso.

El IDS está configurado para detectar ataques conocidos. Los sistemas IDS suelen detectar paquetes de datos a medida que se mueven por la red, y los analizan en busca de las características de ataques conocidos. Algunos sistemas IDS revisan no solo las firmas de ataques conocidos, sino también las anomalías que podrían ser el signo de actividad maliciosa. Cuando el IDS descubre una anomalía, envía una alerta al/ a la administrador/a de la red que luego investigará más a fondo.

La limitación de los sistemas IDS reside en que solo pueden escanear en busca de ataques conocidos o anomalías obvias. Es posible que no se detecten ataques nuevos y sofisticados. La otra limitación es que el IDS en realidad no detiene el tráfico entrante si detecta algo mal. Depende del/de la administrador/a de la red detectar la actividad maliciosa antes de que haga algo perjudicial.
Cuando se combina con un firewall, un IDS agrega otra capa de defensa. El IDS se coloca detrás del firewall y antes de ingresar a la LAN, lo que permite que el IDS analice los flujos de datos después de que el tráfico de red desautorizado por el firewall se haya filtrado. Esto se hace para reducir el ruido en las alertas IDS, también conocidas como falsos positivos.
## Sistema de prevención de intrusiones

Un **sistema de prevención de intrusiones (IPS)** es una aplicación que monitorea la actividad del sistema en busca de actividad intrusiva y toma medidas para detenerla. Ofrece aún más protección que un IDS porque detiene activamente las anomalías cuando se detectan, a diferencia del IDS que simplemente las informa a un/a administrador/a de red.

Un IPS busca firmas de ataques conocidos y anomalías de datos a las/los analistas de seguridad y bloquea un remitente específico o deja caer paquetes de red que parecen sospechosos.

## Gestión de eventos e información de seguridad

Un **sistema de gestión de eventos e información de seguridad (SIEM)** es una herramienta que recopila y analiza datos de registro para monitorear actividades críticas en una organización. Las herramientas SIEM funcionan en tiempo real para informar las actividades sospechosas, a través de un panel de control centralizado. Las herramientas SIEM también analizan los datos de registro de red procedentes de IDS, IPS, cortafuegos, VPN, proxies y registros de DNS. Las herramientas SIEM son una forma de agregar datos de eventos de seguridad a fin de que todo aparezca en un solo lugar para que las/los analistas de seguridad lo analicen. Esto se conoce como panel único.

A continuación, puedes analizar un ejemplo de un panel de la herramienta SIEM de Google Cloud, Chronicle. **Chronicle** es una herramienta nativa de la nube diseñada para conservar, analizar y buscar datos.
![[Pasted image 20231027225911.png]]
**Splunk** es otra herramienta SIEM común que ofrece diferentes opciones de herramientas SIEM: Splunk Enterprise y Splunk Cloud. Ambas opciones incluyen paneles detallados que ayudan a los profesionales de seguridad a revisar y analizar los datos de una organización. También hay otras herramientas SIEM similares disponibles, y es importante que las y los profesionales de seguridad las investiguen para determinar cuál es la más beneficiosa para la organización.

Una herramienta SIEM no reemplaza la experiencia de los analistas de seguridad ni las actividades de reforzamiento de redes y sistemas cubiertas en este curso, sino que se utilizan en combinación con otros métodos de seguridad. Las/los analistas de seguridad suelen trabajar en un Centro de Operaciones de Seguridad (SOC) donde pueden monitorear la actividad en toda la red. Luego utilizan su experiencia y conocimientos para determinar cómo responder a la información en el panel y decidir cuándo los eventos cumplen con los criterios para ser notificados a supervisión.

## Conclusiones clave

|**Dispositivos/Herramientas**|**Ventajas**|**Desventajas**|
|---|---|---|
|Cortafuegos (Firewall)|Los firewalls permiten o bloquean el tráfico en función de un conjunto de reglas.|Un firewall solo puede filtrar paquetes basándose en la información proporcionada en su encabezado.|
|Sistema de detección de intrusiones (SDI)|Un IDS detecta y alerta a los/las administradores/as sobre posibles intrusiones, ataques y otro tráfico malicioso.|Un IDS solo puede escanear en busca de ataques conocidos o anomalías obvias; es posible que no se detecten ataques nuevos y sofisticados. Tampoco detiene el tráfico entrante.|
|Sistema de prevención de intrusiones (IPS)|Un IPS monitorea la actividad del sistema en busca de intrusiones y anomalías y toma medidas para detenerlas.|Un IPS es un dispositivo inline. Si falla, la conexión entre la red privada e Internet se interrumpe. Puede detectar falsos positivos y bloquear el tráfico legítimo.|
|Gestión de eventos e información de seguridad (SIEM)|Una herramienta SIEM recopila y analiza datos de registro de múltiples máquinas de red. Agrega eventos de seguridad para su monitoreo en un panel de control central.|Una herramienta SIEM solo informa sobre posibles problemas de seguridad. No toma ninguna acción para detener o prevenir eventos sospechosos.|
![[Pasted image 20231027230038.png]]![[Pasted image 20231027230052.png]]

### **Cloud Network**
![[M-3 Conexión y protección Redes y seguridad de redes#^b813f9]]

![[Pasted image 20231027233920.png]]![[Pasted image 20231027234326.png]]