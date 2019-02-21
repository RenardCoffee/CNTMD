# Unidad 2

 2. Normas y estandares.
     - Modelo Osi (Referencia)
     - TCP/IP (Protocolo)
     - Comite 802 de la IEEE
     - Pilas de protocolos y flujo de datos.
     ---
     
# Modelo OSI
Inicialmente, el modelo OSI fue diseñado por la Organización Internacional para la Estandarización (ISO, International Organization for Standardization) para proporcionar un marco sobre el cual crear una suite de protocolos de sistemas abiertos. La visión era que este conjunto de protocolos se utilizara para desarrollar una red internacional que no dependiera de sistemas propietarios. 

Tenga en cuenta que, mientras las capas del modelo TCP/IP se mencionan sólo por el nombre, las siete capas del modelo OSI se mencionan con frecuencia por número y no por nombre.

Aplicación 
: La capa de aplicacion proporciona los medios para la conectividad de extremo a extremo entre individuos de la red humana que usan redes de datos.

Presentacion
: Proporciona una representacion comun de los datos transferidos entre los servicion de la capa de Aplicacion.

Sesion
: Proporciona servicios a la capa de Precentacion para organizar su dialogo y administrar el intercambio de datos

Transporte
: Define los servicios para segmentar, transferir y reensamblar los datos para las comunicaciones individuales entre diapostivos individuales entre diapositivos finales.

Red 
: Servicios para intercambiar los datos individuales en la red de diapositivos finales indentificados.

Enlace de datos
: Describen los metodos para interacambiar tramas de datos entre diapositivos en un medio comun.

Fisica
: Describen los medios mecanicos, electricos, funcionales y de procediminto para activar, mantener y desactivar conexiones fisicas para la transmision de bits hacia y desde un dispositivo de red.

# Capas superiores del modelo OSI

Existen dos tipos básicos de modelos de networking: modelos de protocolo y modelos de referencia. 

Modelo de Protocolo
: Proporciona un modelo que coincide fielmente con la estructura de una suite de protocolo en particular. El conjunto jerárquico de protocolos relacionados en una suite representa típicamente toda la funcionalidad requerida para interconectar la red humana con la red de datos. El modelo TCP/IP es un modelo de protocolo porque describe las funciones que se producen en cada capa de los protocolos dentro del conjunto TCP/IP.

Modelo de Referencia
: Proporciona una referencia común para mantener consistencia en todos los tipos de protocolos y servicios de red. Un modelo de referencia no está pensado para ser una especificación de implementación ni para proporcionar un nivel de detalle suficiente para definir de forma precisa los servicios de la arquitectura de red. El propósito principal de un modelo de referencia es asistir en la comprensión más clara de las funciones y los procesos involucrados.


El modelo de interconexión de sistema abierto (OSI) es el modelo de referencia de internetwork más ampliamente conocido. Se utiliza para el diseño de redes de datos, especificaciones de funcionamiento y resolución de problemas.

Aunque los modelos TCP/IP y OSI son los modelos principales que se utilizan cuando se analiza la funcionalidad de red, los diseñadores de protocolos de red, servicios o dispositivos pueden crear sus propios modelos para representar sus productos. Por último, se solicita a los diseñadores que se comuniquen con la industria asociando sus productos o servicios con el modelo OSI, el modelo TCP/IP o ambos.

![Capas Osi](https://sites.google.com/site/investigacionesitlm/_/rsrc/1479166460697/unidad-2/2-1-capas-superiores-del-modelo-osi/protocolos.PNG)



# 2.2 TCP/IP
El modelo TCP/IP describe  la funcionalida de los protocolos que formen parte de el. Estos se implementan tanto en el host emisor como receptor, interactuan para proporcionar la entrega de aplicaciones de extremo a extremo a travez de una red.
Su proceso de comunicacion incluye las sing pasos:
1. Creación de datos a nivel de la capa de aplicación del dispositivo final origen.

2. Segmentación y encapsulación de datos cuando pasan por la stack de protocolos en el dispositivo final de origen. 

3. Generación de los datos sobre el medio en la capa de acceso a la red de la stack.

4. Transporte de los datos a través de la internetwork, que consiste de los medios y de cualquier dispositivo intermediario. 

5. Recepción de los datos en la capa de acceso a la red del dispositivo final de destino. 

6. Desencapsulación y rearmado de los datos cuando pasan por la stack en el dispositivo final. 

7. Traspaso de estos datos a la aplicación de destino en la capa de aplicación del dispositivo final de destino.

![Capas Osi](https://sites.google.com/site/investigacionesitlm/_/rsrc/1479166460697/unidad-2/2-1-capas-superiores-del-modelo-osi/protocolos.PNG)

# 2.3 Comite 802 de la IEEE
def
: Tiene la funcion de desarrollar y mantener estandares y practicas recomendadas para redes LAN, MAN y de otros tipos. Los estandares estan disponibles en *ieee802.org* Los principales son :
  - 802.1 Arquitectura general de LANs.
  - 802.2 LLC (Logical Link Control).
  - 802.3 Ethernet. **
  - 802.4 Token Bus (descontinuada).
  - 802.5 Token Ring (LAN IBM).
  - 802.9 LANs de tiempo real.
  - 802.10 LANs virtuales
  - 802.11 Redes locales inalambricas **
  - 802.12 AnyLAN de H.P.
  - 802.15 Redes de area personal, Bluethooth. **
  - 802.16 Redes metropolitanas inalambricas(W.Max). **
  - 802.17 Redes Packet ring
  - 802.18 TAG(Tecnical Advisory Group) de reglamentacion de radio.
  - 802.19 Grupo de trabajo de coexistencia inalambrica.
  - 802.21 " " " " servicios independientes del medio.
  - 802.22 Redes de area regional inalambricas.
  - 802.24 TAG de aplicaciones veticales.