# Unidad I
# 1.1	Orígenes y Evolución :exclamation:
___
__Internet:__ inicio como *ARPANET* en 1969, mediante un contrato entre la *“Advanced Research Agency”* del Dept. de Defensa (DoD) de EEUU con la empresa BBN y las Uni. UCLA, Stanford Research Institute, UCSB (Santa Barbara) y U. de Utha, activándose en dic. 1969.

En Jun. 1970 se agregaron MIT, Harvard, BBN y SDC (System Development Corp.). En Ene. 1971 se agregan 4 Uni. Mas.
El protocolo inicial era NPC (Network Control Protocol) y fue remplazado en 1983 por TCP/IP.

Personas Involucradas:
-	Bob Kahn
-	Vint Cert

En 1972 Ray Tomlison desarrollo el e-mail.

El siguiente avance fue en 1989 con el desarrollo del HTTP en el Laboratorio CERN, que evoluciono al WWW en 1991. La primera página está en info.cern.ch
En 1993 con el navegador grafico Mosaic por el NCSA empieza la fase de crecimiento exponencial del Internet.
___
## 24/01/19
# 1.2	Conceptos básicos de redes. :tada:
Los 4 elementos de una red son:
- Reglas de Protocolos.
- Medios de transmisión.
- Mensajes a datos.
- Dispositivos.

Para representar a las redes en los diagramas y programas como *Packet Tracer (PT)* se utiliza una simbología estandarizada. Algunos de sus elementos son los siguientes:

1 | 2
------------ | -------------
PC o computadora de escritorio. | Nube (conjunto de ruteadores y switches).
Servidor.	 | Cable LAN normal o directo.
Hub o concentrador.| Cable LAN cruzado
Switch. | Cable serial a medio WAN.
Ruteador.	 | Conexión LAN inalámbrica.
Ruteador inalámbrico.	 | 

- **PC y Comp Portatil:** Se clasifican como “End devices” y van al final a extremos de la red. Tienen programas cliente como navegador, terminal y línea de comandos.

- **Servidor:** También es un “End device” pero proporciona diferentes servicios a la red, como HTTP, FTP, DNS, DHCP, TFTP, SMPT, etc.


- **Hubs, concentradores y repetidores:** Son dispositivos electrónicos que reciben una señal débil o de bajo nivel y la retransmiten para sus puertos a un nivel mas alto para que pueda cubrir distancias más largas sin degradación de la señal. Trabajando de la capa 1 (Física).

- **Switch a conmutador:** Dispositivo digital de lógica de interconexión que opera en la capa 2 (enlace de datos) e interconecta 2 a más segmentos de red, así como PCs, laptops y servidores. Envía los tramos en base a la dirección MAC.

- **Ruteador:** Dispositivo de la capa 3 (Red) que envía los paquetes de red en base a su dirección IP por la ruta óptima en base a una serie de parámetros llamados métricas. Cada puerto de un ruteador (sea LAN o WAN) debe estar conectado a una red diferente.

## 25/01/19
- Modelo OSI: Modelo de interconexión de sistemas abiertos (ISO/IEC, 7498-1) es un modelo de referencia para los protocolos de red de arquitectura en capas, creado en 1980 por la Organización Internacional de Normalización (ISO), publicado desde 1983 por la Unión Internacional de Telecomunicaciones (ITU) su desarrollo inicio en 1977 como un protocolo de red real, pero termino adoptándose como un modelo de arquitectura de red.

- Dirección MAC: Es el identificador único asignado por el fabricante a una pieza de hardware de red, como una tarjeta inalámbrica o una tarjeta Ethernet. MAC significa Media Access Control y cada código tiene la intención de ser único para dispositivo en partículas. Una dirección MAC consiste en seis grupos de dos caracteres, cada uno de ellos separados por dos puntos y un guion, aunque en Cisco PT se usa un formato diferente separando por puntos, por ejemplo:

	    1A:25:6E:40:12:BF
        1A-25-6E-40-12-BF (ARP)
        1A25.6E40.12BF

- Modelo TCP/IP: Es una descripción de protocolos de red desarrollado por Viton Cerf (Vint) y Robert E. (Bob) Khan en la década de 1970. Fue implementado en la red ARPA NET al remplazar NCP, la primera red de área amplia (WAN) desarrollada por encardo de DARPA, una agencia del Departamento de Defensa de los Estados Unidos. Es usado para comunicaciones en redes y, como todo protocolo, describe un conjunto de guías generales de operación para permitir que un equipo pueda comunicarse en una red. TCP/IP provee conectividad de extremo a extremo especificando como los datos deberían ser formateados, direccionados, transmitidos, enrutados y recibidos por el destinatario. Están disponibles en reff.org como una serie de documentos llamados “Reques For Comments” a RFC’s.

- Protocolo: El protocolo es la parte software de la red. Se encarga básicamente de establecer las reglas de comunicación entre equipos de la red, definir el formato de las informaciones que circulan por la red y también debe habilitar mecanismos para permitir la identificación de los equipos en la red.


## /01/30/2019
# Clasificación de redes.
Las redes de computadoras se clasifican de distinta forma conforme :
- Su forma de transmisión.
- Su forma de conmutación.
- Su alcance geográfico.

### Por su forma de transmisión
Redes de Broadcast
: Aquellas redes en las que la transmisión de datos se realiza por un sólo canal de comunicación, compartido entonces por todas las máquinas de la red. Cualquier paquete de datos enviado por cualquier máquina es recibido por todas las de la red.

 Redes Point-To-Point
: Aquellas en las que existen muchas conexiones entre parejas individuales de máquinas. Para poder transmitir los paquetes desde una máquina a otra a veces es necesario que éstos pasen por máquinas intermedias, siendo obligado en tales casos un trazado de rutas mediante dispositivos routers.

### Por su forma de conmutación
La conmutación consiste en el establecimiento de un sistema de comunicación entre dos puntos, un emisor  (Tx) y un receptor (Rx) a través de equipos o nodos de transmisión,  es decir,  que con el proceso de conmutación podemos hacer entrega de una señal desde un puerto origen hacia un puerto destino.
La conmutación es un proceso que funciona en la capa 2 del modelo OSI (Enlace de Datos).
Los tres servicios fundamentales que emplean técnicas de conmutación son el telefónico, el telegráfico y el de datos, pudiendo utilizar una de las tres técnicas de conmutación actuales:

  - De circuitos
  - De mensajes
  - De paquetes

## Conmutación de circuitos

La técnica de conmutación de circuitos, que puede ser espacial o temporal, consiste en el establecimiento de un circuito físico previo al envío de información, que se mantiene abierto durante todo el tiempo que dura la misma. El camino físico se elige entre los disponibles, empleando diversas técnicas de señalización -"por canal asociado" si viaja en el mismo canal o "por canal común" si lo hace por otro distinto-, encargadas de establecer, mantener y liberar dicho circuito, vistas anteriormente. Un ejemplo de red de este tipo, es la red telefónica conmutada.

Esta conmutación se divide en tres fases:
 - Establecimiento del circuito
 - Transferencia de datos
 - Desconexión del circuito

Desventajas
:   - Se consume tiempo al principio y al final de la transferencia de datos para establecer /  cerrar la conexión.
    - Los recursos permanecen reservados incluso en aquellos periodos de tiempo en que no se mandan datos (podrían ser usados para otras comunicaciones).
Ventajas
:  - La información se recibe ordenada.
   - Retardo de nodo es muy pequeño.
   - La transferencia de datos se realiza a una velocidad constante conocida.
   - Especialmente interesante para trafico síncrono (voz).

## Conmutación de paquetes

Un Paquete es un grupo de información que consta de dos partes: los datos propiamente dichos y la información de control, en la que está especificado la ruta a seguir a lo largo de la red hasta el destino del paquete. Mil octetos es el límite de longitud superior de los paquetes, y si la longitud es mayor el mensaje se fragmenta en otros paquetes.

Esta técnica es parecida a la anterior, sólo que emplea mensajes más cortos y de longitud fija (paquetes), lo que permite el envío de los mismos sin necesidad de recibir el mensaje completo que, previamente, se ha troceado. Cada uno de estos paquetes contiene información suficiente sobre la dirección, tanto de partida como de destino, así como para el control del mismo en caso de que suceda alguna anomalía en la red. El mejor ejemplo actual de red que hace uso de esta técnica es Internet, que hace uso del protocolo IP. Otros ejemplos son las redes X.25 y Frame Realy.

Los paquetes permanecen muy poco tiempo en memoria, por lo que resulta muy rápida, permitiendo aplicaciones de tipo conversacional, como son las de consulta.

## -Por tamaño:

WAN
: Wide Area Network, ARPANET fue la 1ra en 1969. Tienen un alcance de cientos a miles de km y estan formados en su mayoria por conexiones punto a punto entre nodos o ruteadores , que se encargan de dirigir el trafico usando un protocolo de encaminamiento como BGP.

MAN 
: Metropolitan Area Network, Tienen un alcanze de unos cuantos km y conectan los nodos en el centro de algunas ciudades. LA tecnologia mas comun es Ethernet sobre fibra optica monomodo, que tiene un rango de opacacion de 10Km y switches en el nucleo de la red. Pueden usar o no ruteador, en cuyo caso manejan protocolos de enrutaminto de gateway interior EIGP y USPF.

LAN
:  Local Area Network, Viene ser el tipo mas comun. tuvo sus inicios de los laboratorios Xerox PARC conectando estaciones de trabajo de Alto usando un persucor del Ethernet sobre cable coaxial grueso con una distancia maxima de 500 mts. Su alcanze es de 10 mts a 2 km sobre una combinacion de fibra optica multimodo a monomodo, cable par trenzado y medios inalambricos. Ruteadores con EIGRP u OSPF

PAN
: Personal Area Network, Es la mas reciente y conecta 2 diapositivos en un rango aprox. 2 metros usando una combinacion de tecnologias inalambricas (WIFI, Bluethooth, NFC ) y opticas (IRDA). Va conectar telefonos, audiculares, impresoras y otros diapositivos inalambricos


# 1.4 Topologia de redes: fisica y logica.
Es la froma en que estas conectados los elementos de la red, ya sea por los medios de transmision o por la manera en la que viajan los datos por la red.

Bus
: Es la topologia original del *Ethernet*, con un tramo de cable coaxial al que se conectan todaslas computadoras, con 
Todos los equipos de una red están unidos a un cable contiguo. El paquete se transmite a todos los dispositivos de red en ese segmento.Las redes de ductos son consideradas como topologías pasivas. Las computadoras "escuchan" al ducto. Cuando éstas están listas para transmitir, ellas se aseguran que no haya nadie más transmitiendo en el ducto, y entonces ellas envían sus paquetes de información. Las redes de ducto basadas en contención (ya que cada computadora debe contender por un tiempo de transmisión) típicamente emplean la arquitectura de red ETHERNET.
![Topologia de Busl](https://sites.google.com/site/investigacionesitlm/_/rsrc/1478823403159/home/1-6-topologias-de-redes/bus%20red.jpg)

Estrella 
: Usa cable par trenzado para conectar cada diapositivoa un concentrador (hub) a conmutador (switch) centra. En caso del hub todos comparten el medio y su topologia logica es de bus. Al usar un switch este se aprende las direcciones MAC de cada aparato y su topologia logica es de estrella. Es la que requiere mas cables.

Los segmentos de cable de cada equipo en la red están conectados a un componente centralizado o concentrador (hub). Un concentrador es un dispositivo que conecta varios equipos juntos. En una topología en estrella, las señales se transmiten desde el equipo, a través del concentrador, a todos los equipos de la red.
![Topologia de Estrellal](https://sites.google.com/site/investigacionesitlm/_/rsrc/1478823449110/home/1-6-topologias-de-redes/estrella%20red.jpg)

Anillo
: Cada dispositivo va conectado al siguiente hasta que el ultimo se conecta al primero y se cierra un anillo. 

Los equipos están conectados con un cable de forma circular. No hay extremos con terminaciones. Las señales viajan alrededor del bucle en una dirección y pasan a través de cada equipo que actúa como repetidor para amplificar la señal y enviarla al siguiente equipo. 
![Topologia de Anillol](https://sites.google.com/site/investigacionesitlm/_/rsrc/1478823514995/home/1-6-topologias-de-redes/anillo%20red.jpg)

Malla
: Puede ser parcial a completa, con conexiones directas entre sus elementos. En una malla completael numero de cables es n(n-1)/2 veces el # de maquinas. En la practica se usan mallas parciales para WAN usando ruteadores, o puntos de acceso inalambricos ''mesh'' con un canal para la malla y otro para los clientes.

Cada equipo está conectado a cada uno del resto de los equipos por un cable distinto. Gracias a los múltiples caminos que ofrece a través de los distintos dispositivos, es posible orientar el tráfico por trayectorias alternativas en caso de que algún nodo esté averiado u ocupado.Este tipo de tecnología requiere mucho cable (cuando se utiliza el cable como medio, pero puede ser inalámbrico también). Pero debido a la redundancia, la red puede seguir operando si una conexión se rompe.
Una red con topología en malla ofrece una redundancia y fiabilidad superiores. Aunque la facilidad de solución de problemas y el aumento de la confiabilidad son ventajas muy interesantes, estas redes resultan caras de instalar, ya que utilizan mucho cableado.
![Topologia de Malla](https://sites.google.com/site/investigacionesitlm/_/rsrc/1478823566555/home/1-6-topologias-de-redes/malla%20red.jpg)

Arbol
: Parte de un switch central o ''Core'' y de ahi a otros switches y despues a las computadoras. Puede haber 3 niveles de switches. Las conexiones switch a switch suelen ser de fibra óptica y de mayor velocidad que las de las computadoras, que son par tenzado. Fisicamente viene a ser una estrella distribuida.

![Topologia de Malla](https://sites.google.com/site/investigacionesitlm/_/rsrc/1478823631535/home/1-6-topologias-de-redes/arbol%20red.jpg)

# Tipo de Red


Tipo de red  | Fisica    | Logica 
------------ | -------   | -----------
Coaxial grueso o delgado.              | Bus | Bus
Hub con UDP.	                       | Estrella | Bus
Switch con UDP.                        | Estrella | Estrella
Token ring con cable UDP.              | Estrella | Anillo
FDDI con doble fibra optica.           | Anillo | Anillo
Ruteadores en WAN.	               | Malla parcial | Malla parcial
AP inalambricas mesh.                  | Malla completa | Malla Completa
Red jerarquica con switches.           | Arbol | Arbol 
Fibra optica y UDP.                    | Arbol | Arbol 
