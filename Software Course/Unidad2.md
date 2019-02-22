- 7 Feb Jueves Examen
- 8 Feb Viernes Lab "D"
### 01/02/19
# Unidad 2 Diseño

## Métodos de Diseño
 El uso de metodos estructurados, normalmente incluye la produccion de modelos graficos del sistema y conduce a una gran cantidad de documentos de diseno. Las herramientas CASE se han desarrollado para ayudar a estos metodos en particular. Los metodos se han aplicado exitosamente en muchos proyectos grandes, comprenden gran reduccion de los costos debido al uso de nombraciones estandar y aseguran la produccion de documentacion estandar de diseño. 
 
  Modelo Espiral
  :  Metodo estructurado incluye un modelo de proceso de diseño, notaciones para representar el diseño, formato de informes, reglas y lineamientos de diseño. Los metodos estrucutados ayudan a todos o alguno  de los sig. modelos de un sistema.
  - Modelo de flujo de datos en el que el sistema se modela utilizando la transformacion de datos que tienen lugar cuando se procesan.
  - Modelo entidad-relación el cual se utiliza para describir las entidades fundamentales en el diseño y las relaciones entre ellas. Los modelos entida-relación son la tecnica normal que se utiliza para describir las estructuras de las bases de datos. *base de datos*
  - Modelo estructural en el cual se documenta los compinentes del sistema y sus interacciones.
  - Metodos orientados a objetos incluyen un modelo de herencia del sistema. Modelo de relaciones estaticas y dinamicas entre los objetos y un modelo de interaccion de los objetos cuando el sistma se ejecute.
  ![Modelo Espiral](https://proyectosinformaticoscht2009.files.wordpress.com/2009/11/screenshot-22.png)
  
  ### 05/02/19
  ## Progrmamacion y depuración
  def.
  : El desarrollo de un programa para implementar el sistema se sigue de forma natural del proceso de diseño. Las herraminetas *CASE* se pueden utilizar para generar un programa esqueleto apartir de un diseño, este incluye codigo para definir e implementar las interfaces y en muchos casos el desarrollador solo necesita agregar detalles de la operación de cada componente. La programación es una actividad personal y no existe un proceso general que se siga comunmente. 
  
- Algunos progrmadores inician con los componentes que comprenden mas, los desarrollan y despues continuan con los que comprenden menos. Otros toman el enfonque opuesto dejando los componentes que son mas familiares hasta el final, debido a que saben como desarrollorlos.
- Algunos desarrolladores prefieren definir los datos al inicio del proceso y los unilizan para conducir el desarrollo del programa, otros dejan los datos sin especificar tanto como sea posible.

### 06/02/19
## Case(Ingineria de Software Asistida por Computadora)
def
: Es el nombre que se le da al *SW* que se utuliza para ayudar a las actividades del proceso del *SW* como la inginieria de requerimientos, el diseño, el desarrollo de programas y las pruebas, por lo tanto las herraminetas *CASE* incluyer editores de diseño diccionario de datos, compiladores, depuradores, herraminetas de contrucción de sistemas etc. La tecnologia *CASE* porpociana ayuda el proceso de *SW* automatizando alguna de sus actividades asi como proporcionando informacion acerca del *SW* en desarrollo. 
  
La tecnologia CASE esta disponible para muchas actividades rutinarias en el proceso de SW, esto conduce algunas mejoras en la calidad y productividad del SW. Las mejoras por la utilizacion CASE estan limitadas por 2 fac.
   - Esencialmente la Ing. de Software es una actividad de diseño, que se basa en la creatividad. Los sistemas CASE automatizan las actividades de rutina pero los intentos de utilizar la IA para pro porcionar ayuda al diseño no han tenido exito.
   - En muchas org. la Ing. de SW es una actividad de equipo y los Ing. invierten mucho tiempo interactuando con los otros miembros del equipo. La tecnologia case no propociona mucha ayuda para esto. [**]
  
  ### Clasificación de CASE
  def.
  : Ayuda a comprender los diferentes tipos de heramientas *CASE* y su importancia en la ayuda a las actividades de proceso de sw. Existen varias formas diferentes de clasificar a las herraminetas *CASE* cada una de las cuales proporciona una perspectiva diferente de esas herramietas.
  
  ### Perspectivas:
   1. *Una perspectiva funcional* en las que las herraminetas *CASE* se clasifican de acuerdo con su función especifica.
   2. *Una perspectiva de proseso* en la que las herraminetas se clasifican de acuerdo con su ayuda a las actividades del proseso.
   3. *Una perspectiva de la integración* en las que herramineta case se clasifican de acuerdo con la forma en que estan organizadas en unidades integradas, las cuales proporcionan ayuda a una ó más actividades del proseso.

La sig. figura es una clasificacion de las herraminetas *CASE* acorde a su función. Esta tabla lista diferentes tipos de herraminetas case y da ejemplos especificos de cada una.

Tipo de Herramienta | Ejemplos
----------------------|-----------
Herramienta de Planeación | Herraminetas *PERT*, Herraminetas de estimación, hojas de cálculo.
Herramienta de Edición | Editores de texto, Editores de diagramas, Prosesadores de texto.
Herramienta de administracion de cambio | Herraminetas de rastreo de requerimientos, Sistema de control de cambios.
Herramienta de contruccion de prototipos | Lenguajes de muy alto nivel, generadores de interfaz de ususario.
Herramienta de administracion de la configuracion | Sistema de administracion de las versiones, Herraminetas de construccion de sistemas.
Herramienta de ayuda a los metodos | Editores de diseño, diccionario de datos, generadores de codigo.
Herramienta de procesamineto de lenguajes | Compiladores, Interpretes.
Herramienta de analizis de programas | Generadores de referencia cruzadas, analizadores estaticos - dinamicos.
Herramienta para pruebas | Generador de pruebas de datos, compresores de archivos.
Herramienta de depuración | Sistemas de depuración interactiva.
Herramienta de documentación | Programa de esquema de paginas, Editores de Imagenes
Herramientas de Re-Ingieneria | Sistema de referencia cruzado de restructuración de programas.

La sig figura mustra algunos ejemplos de estas clases diferentes de ayuda *CASE*. Las herraminetas de proposito general se utilizan a discrecion del ingeniero quien toma deciciones acerca de cuando aplicarlas para ayudar al proceso, los entornos se clasifican en integrados y centrados en el proceso. las heramientas se venden como productos individuales pero proporcionan ayuda a direntes actividades. Los bancos de trabajo *CASE* Para el diseño ayudan cada vez mas a la programación y a las pruebas de tal forma que se relacionan mas al entorno que a los bancos de trabajo especializado.

### Banco de trabajo
def.
: Ayuda a las fases o actividades del proceso como la espicificación, el diseño, etc. Normalmente consisten en un conjunto de herramientas con algun grado mayor o menor de integración.

## Especificacion de SW
def.
: Sirve para establecer que servicios requiere el sistema y las restricciones de operacion y desarrollo del mismo. Esta actividad se llama *Ing. de Requerimientos*. Esta etapa es particularmente critica en el proceso de *SW* ya que los errores en esta etapa conducen inevitablemente a problemas porsterires en el diseño y en el sistema.

Get las class notes ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
## 02/18/19 Class

### Validacion de requerimientos
def 
: Esta actividad comprueba la veracidad, consistencia, y complexion de los requerimientos. Durante este proceso se descubren los errores en el doc. de requerimienros, por lo tanto se modifica para corregir estos problemas.

# Diseño e Implementación del SW
def
: La etapa de implementacion del desarrollo de SW es el proceso de convertir una especificacion del sistema en un sistema ejecutable, simpre incluyen los procesos de diseño y programacion de SW, pero si se utiliza un enfoque evolutivo de desarrollo tambien incluye un refinamiento de la especificacion del SW. Un *Diseño de SW* es una descripcion de la estructura del SW que se va a implementar, Los datos que son parte del sistema, las interfaces entre los componentes del sistema y algunas veces los algoritmos utilizados. Los *diseñadores no tienen un diseño detallado, sino que lo desarrollan de manera iperativa atravez de diversas verciones diferentes*, el proceso de diseño incluye agregar formalidad y detalle durante el desarrollo del diseño y regresar a los diseños anteriores para corregirlos. El *proceso de diseño* incluye el desarrollo de varios modelos del sistema con diferentes niveles de abstracción. en cuanto se descompone el sistema se descubren los errores y omiciones de las etapas previas, esta retro'alimentacion permite mejorar los modelos de diseños previos.

La sig fig. *Es un modelo de este proceso que muestra las descripciones de diseño producidas en diferentes etapas de diseño Este diagrama sugiere que las etapas son sequenciales, de hecho las activiadades de proseso de diseno se etrelazan. La retroalimentacion entre etapas y la consecuente repeticion del trabajo es inevitable en todos los prosesos de diseño:*

Actividadees de diseño
![Procesos](/img/2.2.png)
Productos de diseño

Una especificación para la siguiente etapa es la salida de cada actividad de diseño. Esta clasificación puede ser abstracta y formal para clarificar los requerimientos o puede ser una especificación para determinar que parte del sistema se va a construir, durante todo el proceso de diseño se detalla cada vez mas la especificación. El resultado final del proceso son espicificaciones presisas de los algoritmos y estructuras de datos a implementarse.

Las actividades del proceso de diseño

Diseño arquitectonico
: Conforman el sistema y su relacion se identifica y documenta.

Especificacion abstracta
: Para cada sub-sistema se produce una especificación abstracta de servivios y las restricciones bajo las cuales opera.

Diseño de la interfaz
: Para cada sub-sistema se diseña y documenta su interacción con otros subsistemas.

Diseño de componentes
: Se asignan servicios a los diferentes componentes y se disenan sus interfaces.

Diseño de la estructura de datos
: Se disena a detalle y especifica la estructura de datos a utilizarse en la implementacion del sistema.

Diseno de Algoritmos
: Se disenan a detalle y especifican los algoritmos utilizados para proveer los servicios.

# Modelo de cascada
def
: El primer modelo de desarrollo de SW que se publico, se derivo de otros proceso de ingenieria. Debido a la casacada de una fase a otra este modelo se le conose como modelo de cascada ó  *Ciclo de vida del SW*

![Cascada](/img/Second.png)

# Desarrollo Orientado a la Reutilización
def
:  En la mayoria de los proyectos de SW existe algo de reutilizacion de SW por lo general esto pasa cuando las personas que trabajan en el proyecto conocen diseños o codigos similares al requerido. Este enfoque basado en la reutilización se compone de un gran numero  de componentes de SW reutilizable asi como de marcos de trabajos para estos, algunas veces esos componentes son sistemas por si mismos que se utilizan para proveer funcionalidad especifica.
![Procesos](/img/ModReuti.png)

# Validacion del SW
def
:  Se utiliza para mostrar que el sistema esta acorde a su especificacion y que cumple con las espectativas del usuario. Incluye procesos de comprobacion, como: LAs inspecciones y las reviciones de cada etapa del proceso del SW desde la definicion de requerimineto hasta el desarrollo del programa. en la sig figura se muentra un proceso de pruebas de 5 etapas en el cual se prueban los componentes del sistema.

![Procesos](/img/ValSW.png)

# Evolución del SW
def
: La flexibilidad de los sistemas de SW en una de las principales razones por las que más y más SW se incorpora a los sistemas grandes y complejos. El desarrollo de SW se considera una actividad creativa en el cual un sistema se desarrolla desde un concepto inicial hasta que se pone en funcionamiento. El mantenimiento de SW es el proceso de cambio del sistema una vez que se ha puesto en funcionamiento aunque los costos de mantenimiento son a menudo varias veces mas que los costos de desarrollo, el proceso de mantenimiento se considera menos problematico que el de desarrollo del SW original. Hoy en dia pocos sistemas de SW con completamente nuevo lo que implica que tienen más sentido ver el desarrollo y el mantenimiento como actividades continuas. Más qeu 2 procesos separados es más realista considerar a la ing de se como un proseso evolutivo en el cual cambia continuamente duracte su periodo de vida.

![2.6](https://lh3.googleusercontent.com/JtOWqXAEpTt0675uIS801OJJCjc0FaCPsjdH_A0ax7DvPuvlepRb610FsvIifAI1RFr--g) 

# Diseño arquitectonico
def
: Es el proceso de diseño inicial para identificar subsitemas y establecer un marco de trabajo para el control y comunicacion de los subsistemas, el modelo arquitectonico es a menudo el punto inicial para la especificacion de diversas partes del sistema. El proceso de diseño arquitectonico comprende el establecimiento de un marco de trabajo estructural basico para un sistema esto implica identificar los componentes principales del sistema y comunicacion entre ellos. El proceso utilizado depende del conocimineto de la aplicacion y de la capacidad e intuicion de los arquitectos del sistema.

## Subsistema
def
: Es un proceso por si mismo cuya operación no depende de los servicios suministrados por otros subsistemas. Los subsistemas se componen de módulos y tienen interfaces definidas que se utilizan para la comunicacion con otros subsistemas.                   ___AutoSificiente___

## Módulo
def
: Es por lo regular un componente del sistema que suministra uno ó más servicios a otros módulos por lo general *no se considera un sistema dependiente* ___Dependiente___

Las arquitecturas de muchos sistemas grandes comprenden más de un modelo, las diversas partes del sistema se diseñan utilizando diferentes modelos aquitectonicos más aún en algunos casos la arquitectura del sistema es una arquitectura compueta. La arquitectura del sistema afecta el desempeño, la robustez, la distributibilidad y la manteniabilidad de un sistema por lo tanto el estilo particular y la estructura elegida para una aplicacion puede depender de los requerimientos no funcionales del sistema.

1. Desempeño.
2. Seguridad.
3. Proteción.
4. Disponibilidad.
5. Mantenibilidad

1 def
: Aqui se sugiere que la arquitectura se debe diseñar para localizar las operaciones criticas dentro de un numero reducido de subsistemas con poca comunicación, hasta donde sea posible entre estos subsistemas.

2 def
: Si la proteción es un requerimiento critico esto sugiere que la arquitectura se debe diseñar de tal forma que las operaciones relacionadas con la protección se localicen en un solo subsistema o en numero reducido de subsistemas.

3 def
: Este sugiere que la arq se debe diseñar de tal forma que las operaciones relacionadas con la proteción se localizen en un solo subsitema o en un numero reducido de subsistemas.

4 def
 : Esto sugiere que la arquitectura debe diseñarse para incluir componentes redundantes de tal forma que sea posible remplazar y actualizar los componentes sin detener el sistema.
 
 5 def
 : Esto sugiere que la arquitectura se debe diseñar utilizando componentes auto-contenidos de grano fino que puedan cambiarse con facilidad.
 
 La primer faze de la actividad de diseño arquitectonico se refiere por lo general a la descomposición del sistema en un conjunto de subsistemas que interactuan.
 
 ## Modelo de depósito
 def
  : Los subsistemas que componen un sistema deben intercambiar información con el fin de que puedan trabajar de manera conjunta y efectiva, existen 2 formas para lograr esto:
  - Todos los datos compartidos se ubican en una base de datos central que puede ser accedida por todos los subsistemas. Un modelo del sistema basado en una *DB* compartida se denomina algunas veces *Modelo de deposito*.
  - Cada subsitema tiene su propia *DB* los datos intercambian con otros subsistems pasando mensaje entre ellos. La mayoria de los sistemas que utilizan grandes cantidades de datos se organizan alrededor de una *DB* compartida ó depostiso por lo tanto este modelo es adecuado para aplicaciones donde los datos sean generados por 1 subsistema y utilizados por otro.

## Modelo C-S
def
: Es un modelo de sistema distribuido que muestra como los datos y el procesamiento se distribuyen a lo largo de varios procesadores, los componentes de este modelo son:
  1. Un conjunto de servidores independientes que ofrecen servicios a otros subsistemas.
  2. Un conjunto de clientes que llaman a los serviciós ofrecidos por los servidores por lo general estos son subsistemas.
  3. Una red que permite a los clientes acceder a estos servicios.

## Modelo de maquina abstracta(Modelo de capas)
def
: Modela la interacción entre los subsistemas organiza un sistema en una serie de capas cada una de las cuales suministran un conjunto de servicios cada capa define una maquina abs. cuyo lenguaje de maquina se utilizan para implementar el sig. nivel de las maquinas abs. Cuando una capa se desarrolla algunos de los servicios suministrados por esa capa estan disponibles para los usuarios. esta arquitectura tambien es cambiable y portable, si su interfaz se preserva una capa puede remplazarze por otra. una desventaja es que estructurar los sistemas de esta forma es dificil.
