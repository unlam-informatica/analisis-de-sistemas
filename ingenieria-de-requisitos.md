---
layout: page
title: Ingeniería de requisitos
sidebar_link: true
sidebar_sort_order: 3
---

## Definición
##### _Según Sommerville_
Los requerimientos para un sistema son descripciones de lo que el sistema debe hacer: el servicio que ofrece y las restricciones en su operación. Tales requerimientos reflejan las necesidades de los clientes por un sistema que atienda cierto propósito, como sería controlar un dispositivo, colocar un pedido o buscar información. Al proceso de descubrir, analizar, documentar y verificar estos servicios y restricciones se le llama ingeniería de requerimientos (IR).

La especificación del software o la ingeniería de requerimientos consisten en el proceso de comprender y definir qué servicios se requieren del sistema, así como la identificación de las restricciones sobre la operación y el desarrollo del sistema. La ingeniería de requerimientos es una etapa particularmente crítica del proceso de software, ya que los errores en esta etapa conducen de manera inevitable a problemas posteriores tanto en el diseño como en la implementación del sistema.

Existen cuatro actividades principales en el proceso de ingeniería de requerimientos:

1. **Estudio de factibilidad:** Se realiza una estimación sobre si las necesidades identificadas del usuario se cubren con las actuales tecnologías de software y hardware. El estudio considera si el sistema propuesto tendrá un costo-beneficio desde un punto de vista empresarial, y si éste puede desarrollarse dentro de las restricciones presupuestales existentes. Un estudio de factibilidad debe ser rápido y relativamente barato. El resultado debe informar la decisión respecto a si se continúa o no continúa con un análisis más detallado.

2. **Obtención y análisis de requerimientos:** Este es el proceso de derivar los requerimientos del sistema mediante observación de los sistemas existentes, discusiones con los usuarios y proveedores potenciales, análisis de tareas, etcétera. Esto puede incluir el desarrollo de uno o más modelos de sistemas y prototipos, lo que ayuda a entender el sistema que se va a especificar.

3. **Especificación de requerimientos:** Consiste en la actividad de transcribir la información recopilada durante la actividad de análisis, en un documento que define un conjunto de requerimientos. En este documento se incluyen dos clases de requerimientos. Los requerimientos del usuario son informes abstractos de requerimientos del sistema para el cliente y el usuario final del sistema; y los requerimientos de sistema son una descripción detallada de la funcionalidad a ofrecer.

4. **Validación de requerimientos:** Esta actividad verifica que los requerimientos sean realistas, coherentes y completos. Durante este proceso es inevitable descubrir errores en el documento de requerimientos. En consecuencia, deberían modificarse con la finalidad de corregir dichos problemas.

![proceso-ingenieria-requerimientos](/assets/ingenieria-de-requisitos/proceso-ingenieria-requerimientos.jpg)

Los requerimientos para un sistema son descripciones de lo que el sistema debe hacer: el servicio que ofrece y las restricciones en su operación. Tales requerimientos reflejan las necesidades de los clientes por un sistema que atienda cierto propósito. Al proceso de descubrir, analizar, documentar y verificar estos servicios y restricciones se le llama ingeniería de requerimientos (IR).

##### _Según Pressman_
La ingeniería de requerimientos proporciona el mecanismo apropiado para entender lo que desea el cliente, analizar las necesidades, evaluar la factibilidad, negociar una solución razonable, especificar la solución sin ambigüedades, validar la especificación y administrar los requerimientos a medida de que se transforman en un sistema funcional. Incluye siete tareas diferentes:

1. Concepción  

2. Indagación  

3. Elaboración  

4. Negociación  

5. Especificación  

6. Validación  

7. Administración  

Es importante notar que algunas de estas tareas ocurren en paralelo y que todas se adaptan a las necesidades del proyecto.

#### Proceso de Adquisición de Conocimientos:

1. Primeras reuniones y evaluación de viabilidad (de expertos, directivos y usuarios).

2. Extracción de conocimientos (de la documentación).

3. Educción de conocimientos (del experto).
	
	1. Interrogatorio inicial.

	2. Investigación profunda.

## Proceso Genérico de la Ingeniería de Requisitos

![proceso-generico-requisitos](/assets/ingenieria-de-requisitos/proceso-generico-requisitos.jpg)

### 1. Elicitación

#### Elicitar vs Relevar
**Relevar** un sistema tiene que ver con un **concepto estático**, fuera de uso, que implica aceptar lo que el cliente solicita. Va asociado a un concepto erróneo que suele tenerse durante el proceso de obtención de los requisitos, se piensa que los analistas deben determinar el sistema que el cliente quiere. Por el contrario el objetivo es determinar qué software es el que el cliente necesita. Muchos clientes no saben lo que necesitan, o incluso sabiendo lo que necesitan no pueden transmitirlo correctamente. Aquí es dónde la elicitación juega un papel importante.  
La **elicitación** es la habilidad de trabajar en colaboración con los clientes y/o representantes de ellos para **descubrir las necesidades** actuales del producto y acordar la visión y las metas del proyecto propuesto. Ya que las personas que van a interactuar con el sistema, no demandan exactamente las mismas funciones, parte del proceso de elicitación es la identificación temprana de las diferentes clases de usuarios y sus características

>La elicitación es el proceso de adquirir (“eliciting”), sonsacar todo el conocimiento relevante necesario para producir un modelo de los requerimientos de un problema.

![elicitacion](/assets/ingenieria-de-requisitos/elicitacion.jpg)

En la elicitación no se acepta lo que el cliente dice, sino que buscan sus verdaderas necesidades, involucrando a las personas en un proceso activo, que siguiendo métodos, usa herramientas para descubrir, explicitar y documentar la colección de sucesos que se obtienen a partir de identificar las fuentes de información las cuales se utilizarán dentro del proceso de comunicación para obtener los requerimientos del sistema. No se debe ignorar que dependiendo del punto de vista los deseos y necesidades pueden variar.  

#### 1.1 Identificación de Fuentes de Información
Llamamos fuente de información a todo aquello que pueda ayudarnos a comprender tanto el dominio, como el problema en sí mismo. La información necesaria para construir un sistema puede encontrarse en múltiples y variadas fuentes, prácticamente pueden presentarse en infinitas formas distintas.

##### Extracción vs Educción
Cuando la fuente de conocimientos se presenta en forma escrita o cualquier tipo de soporte mecánico o digital, películas, audios, imágenes, etc., la adquisición se llamará Extracción de Conocimientos. Si, por el contrario, los conocimientos se obtienen de seres humanos, el proceso se denominará Educción de Conocimientos.

#### 1.2 Recolección de hechos
Esta actividad implica conseguir todos los requerimientos del sistema. Los analistas trabajan con los clientes, expertos, usuarios finales y demás stakeholders para determinar el dominio del sistema, definir sus funciones y encontrar sus restricciones.  
Esta tarea no es sencilla, muchas veces los stakeholders no saben lo que desean, o no saben expresar lo que desean, o no tienen conciencia de todo lo que implica implementar un deseo. Por otra parte si los analistas no conocen bien el dominio, pueden no comprender totalmente lo expresado por los stakeholders.  
En organizaciones grandes diferentes sectores pueden solicitar funcionalidades que se contraponen, o solicitar lo mismo de formas totalmente diversas y aparentar funcionalidades diferentes.  
Por lo tanto existen diferentes técnicas para recolectar información, cada una tiene características particulares para facilitar la tarea en diferentes ocasiones.  
#### 1.3 Comunicación
La comunicación es la característica más relevante de la elicitación. La misma se establece:
* dentro de la organización (cliente – cliente): para decidir que desean, definir / redefinir funcionalidades o resolver conflictos internos.
* entre la organización y el equipo de desarrollo: para comunicar sus deseos.
* dentro del equipo de desarrollo, para evaluar si estos deseos se corresponden
con las necesidades del sistema.

### 2. Modelización
Durante la modelización se representan, organizan y registran los hechos recolectados durante la elicitación. Organizamos toda la información obtenida, a través de un proceso de abstracción, generamos los modelos que irán representando el sistema. Estos modelos varían en función del nivel de detalle que se necesite mostrar, la técnica de representación, a quién están dirigidos, etc.
#### 2.1 Representación
En la representación seleccionamos la técnica que utilizaremos para realizar cada modelo en particular.
Ver “Anexo 3: Técnicas de Representación”.
#### 2.2 Organización
Aquí es dónde, a partir de un proceso de abstracción y con la técnica seleccionada confeccionamos el modelo que representa la información recolectada.
#### 2.3 Almacenamiento
Para poder hacer un seguimiento del proyecto durante el proceso de construcción, debemos guardar todos los documentos que le van dando forma. La documentación debe llevarse a cabo en una forma organizada, comprensible y significativa.
Los documentos se deben almacenar y poder recuperar tal cual como fueron presentados y / o aprobados. La selección se puede hacer por diferentes criterios, por ejemplo:
* autor
* destinatario
* Fecha de entrega
* Lugar de recolección de la información
* número de versión si es que el mismo va evolucionando.

### 3. Análisis
Con esta actividad vemos si realmente comprendimos la información que modelizamos. Debe existir coherencia entre los distintos modelos que fuimos generando del sistema, nunca debe dejar de representar el sistema que el cliente desea y necesita. Se debe acordar con el cliente en todo momento los requerimientos y requisitos del sistema.
#### 3.1 Verificación
La verificación responde a la pregunta: ¿Estamos construyendo correctamente el producto? [Boehm 1984]. Esto implica controlar que el modelo se corresponda con la información obtenida y con los modelos ya creados.  
Es una actividad interna, mediante el cual se comparan modelos entre sí, para verificar que los mismos sean coherentes, no tengan contradicciones y no existan ambigüedades.  
#### 3.2 Validación
La validación responde a la pregunta: ¿Estamos construyendo el producto correcto? [Boehm 1984]. Se ocupa de controlar si el modelo satisface los requerimientos del cliente.  
Es una actividad externa, donde el cliente aprueba el modelo, aceptando que este representa sus deseos y satisface sus expectativas.  
#### Tabla comparativa entre Verificación y Validación

![verificacion-vs-validacion](/assets/ingenieria-de-requisitos/verificacion-vs-validacion.jpg)

#### 3.3 Negociación
El objetivo de la negociación es lograr el consenso entre todos los involucrados y los requisitos del sistema.  
Siempre ocurren contradicciones entre las necesidades de los usuarios, o demandas que entran en conflicto con los objetivos de la organización, o puede haber requisitos muy ambiciosos y no todos pueden satisfacerse de acuerdo al presupuesto de un proyecto, tanto en tiempo como costos.  
La negociación abarca dos aspectos de naturaleza bien distinguible:  
* Estudiar y resolver diferencias de intereses entre los involucrados, las cuales promueven requisitos contradictorios o no factibles.
* Evaluar y decidir sobre las propuestas que elaboran los ingenieros de requisitos sobre alternativas o soluciones candidatas al problema en cuestión.

### 4. Gestión
La gestión es una actividad cruzada que se realiza durante todo el desarrollo del sistema. Se ocupa de mantener actualizados todos los modelos que corresponda, cada vez que se decide tener en cuenta un cambio. Además debe documentar todas las propuestas de cambio, se incorporen o no al sistema.  
Un cambio o incorporación de un único requisito puede alterar un conjunto de requisitos en cascada, y dependiendo de la etapa en que se encuentre el proyecto es necesario la actualización de la documentación y otros artefactos del software, lo cual debe identificarse y evaluarse previo a su efectiva realización.  
#### 4.1 Identificación de cambios
Esta actividad consiste en identificar algún problema en los requisitos o un pedido de modificación o de nuevas necesidades proveniente de los clientes y usuarios, y proponer los cambios en los requisitos. Se debe registrar el pedido de cambio, identificando la fuente solicitante y la descripción del cambio mismo.
#### 4.2 Análisis de cambios
Consiste en analizar la validez de los cambios propuestos, identificar los requisitos afectados por los cambios y, si corresponde, los cambios en los componentes de software, estimar, evaluar y negociar el impacto del cambio en el alcance, el cronograma y el costo, y determinar la aceptación o rechazo del cambio.
#### 4.3 Realización de cambios
Consiste en implementar los cambios en los documentos de requisitos y en los modelos, así como verificar y validar estos cambios.

![gestion-de-requisitos](/assets/ingenieria-de-requisitos/gestion-de-requisitos.jpg)

#### Anexo 1: Fuentes de Información
* Libros y manuales: Los libros son útiles para obtener conocimientos básicos del dominio y las clasificaciones existentes en él. Es decir, los libros contienen conocimientos específicos y públicos del dominio y del problema. Su desventaja es que si la información ya está publicada en un libro puede estar desactualizada.
* Documentación formal: Además de los libros de texto, existe otra fuente de información en forma escrita. Se trata de aquellos documentos que contienen las políticas y procedimientos, los estándares, las normas y regulaciones, las leyes, etc., de un dominio. De esta fuente puede obtenerse unos conocimientos muy específicos, generalmente de nivel básico: procedimientos estándares de resolución, normas a cumplir al resolver un caso, etc. Los conocimientos proporcionados por esta fuente también son de carácter público. Representan lo que “DEBE SER” de la organización.
* Documentación informal: También como fuente de información en forma escrita, aparecen las notas manuscritas, «memos» internos, ayudas de trabajo, etc., que circulan dentro de las organizaciones. Esta documentación proporciona, a menudo, conocimientos heurísticos para resolución de problemas. De hecho, este tipo de notas suelen reflejar la experiencia de profesionales de la organización a la hora de enfrentarse a ciertos problemas. Además de su carácter, las más de las veces confidencial, esta fuente proporciona conocimientos semipúblicos. Representa “LO QUE ES” de la organización, que desgraciadamente, suele no coincidir con “LO QUE DEBE SER”.
* Registros internos: Un alto número de empresas suelen registrar los casos que se les presentan. En concreto, en forma de órdenes de reparación, fichas de clientes o pacientes, estudios o almacenamiento de casos, etc. Este tipo de fuente de conocimientos puede presentarse en forma escrita o en forma magnética (bases de datos, ficheros, etc.). Los conocimientos de estos registros son muy adecuados para ser utilizados en la validación y evaluación del sistema.
* Presentaciones: Todo el material utilizado para formación, ya sea impartida o recibida, suele contener conocimientos expuestos de un modo especialmente claro. El nivel de los conocimientos que se encuentran en esta fuente dependerá de a quién esté dirigida la formación.
* Publicaciones especializadas: Las versiones más actualizadas de los conocimientos de un dominio se encuentran expresadas, también de forma escrita, en las publicaciones especializadas tanto periódicas como esporádicas. En este caso, en forma de revistas especializadas, actas de congresos, etc.
* Investigaciones: Esta fuente también tiene información actualizada, son los resultados de las investigaciones que se estén llevando a cabo. En concreto, en forma de: datos empíricos, estudios, informes, resultados estadísticos, etc.
* Visitas: Una fuente de conocimientos que suele ser muy útil para clarificar las ideas al analista, son las visitas a los centros de trabajo del experto. Los conocimientos que se obtienen de observar la situación «in situ» suele ser de tipo estático (el «qué» del proceso de resolución de problemas).
* Humanos: Los expertos, los directivos y usuarios finales son también fuentes de conocimientos imprescindibles. De los expertos, se obtiene la mayor parte de los conocimientos a introducir en un sistema. De los directivos, se suelen extraer los objetivos del proyecto, el alcance del sistema, el contexto donde será instalado, etc.

#### Anexo 2: Técnicas de Recolección de Hechos
* Técnicas de Extracción de Información: técnicas para obtener información a partir de fuentes NO humanas.

  - Lectura: leer libros, revistas, informes, etc. sigue siendo la técnica de extracción mas utilizada.

  - Ver videos

  - Escuchar audios

* Técnicas de Educción de Información: técnicas utilizadas para obtener información a partir de los humanos.  
El analista debe controlar constantemente el proceso de adquisición para educir conocimientos del experto. El proceso de educción consiste repetirse para cada sesión el ciclo de educción, el cual es independiente de la técnica utilizada.  
Hay dos clases de métodos para educir lo que saben los expertos.  
Los primeros, denominados directos, le preguntan directamente al experto lo que sabe; es decir, en ellos el experto reporta los conocimientos que él puede articular directamente. En estos métodos el experto es la única fuente de información, se confía totalmente en lo que el experto dice. Las técnicas de Entrevistas abiertas o estructuradas, y los Cuestionarios pertenecen a este grupo.  
El segundo tipo de métodos son los llamados indirectos. Estos métodos se usan porque no siempre los expertos pueden acceder a los detalles de sus conocimientos o procesos mentales, y para confirmar lo adquirido mediante técnicas directas. La Observación de Tareas Habituales, la Clasificación de Conceptos, el Análisis de Protocolos, son los métodos más conocidos de este segundo grupo.  

A continuación describiremos el ciclo de educción y las siguientes técnicas:

1. Entrevistas (Abiertas y Cerradas)

2. Cuestionario / Encuesta (Abiertos y Cerrados)

3. Joint Aplication Development JAD

4. Brain Storming

5. Concept Mapping

6. Storyboard

7. Card sorting

8. Análisis de protocolos

9. Observación









































###Requerimiento versus Requisito
En la bibliografía ambos términos se suelen utilizar en forma indistinta como traducción de la palabra inglesa “requirement”. En el siguiente texto vamos a utilizar:

* **Requerimiento** para referirnos a los pedidos que recibimos de los clientes. Entendiendo como cliente a aquel que solicita y define el sistema de software. _(Requerimientos del cliente según Sommerville)_  
Ej.: Registrar los clientes del negocio.  

* **Requisito** para identificar las especificaciones precisas, no ambiguas, consistentes y completas del comportamiento del sistema, incluyendo funciones, interfaces, rendimiento y limitaciones. Esto es lo que el equipo de desarrollo se compromete a cumplir para construir el sistema de software que necesita el cliente para satisfacer sus requerimientos. _(Requerimientos del sistema según Sommerville)_  
Ej.: El sistema debe registrar los clientes con los siguientes datos obligatorios: DNI (que servirá como clave de identificación única), nombres, apellidos, correo electrónico, teléfono, dirección. Si el DNI ya existe, el sistema debe mostrar los datos actualmente registrados con ese número.

###Definicion de Requisito
_Según Sommerville_:  
Los requisitos para un sistema son la descripción de los servicios proporcionados por el sistema y sus restricciones operativas. El término requisito no se utiliza de forma contante en la industria de software. En algunos casos, un requisito es simplemente una declaración abstracta de alto nivel de un servicio que debe proporcionar el sistema o una restricción de éste. En el otro extremo, es una definición detallada y formal de una función del sistema.

### Requerimientos funcionales y no funcionales
Algunos de los problemas que surgen durante el proceso de ingeniería de requerimientos son resultado del fracaso de hacer una separación clara entre esos diferentes niveles de descripción. En este texto se distinguen con el uso del término “requerimientos del usuario” para representar los requerimientos abstractos de alto nivel; y “requerimientos del sistema” para caracterizar la descripción detallada de lo que el sistema debe hacer. Los requerimientos del usuario y los requerimientos del sistema se definen del siguiente modo:

1. Los requerimientos del usuario son enunciados, en un lenguaje natural junto con diagramas, acerca de qué servicios esperan los usuarios del sistema, y de las restricciones con las cuales éste debe operar.

2. Los requerimientos del sistema son descripciones más detalladas de las funciones, los servicios y las restricciones operacionales del sistema de software. El documento de requerimientos del sistema (llamado en ocasiones especificación funcional) tiene que definir con exactitud lo que se implementará. Puede formar parte del contrato entre el comprador del sistema y los desarrolladores del software.

**Requerimientos funcionales:** Son enunciados acerca de servicios que el sistema debe proveer, de cómo debería reaccionar el sistema a entradas particulares y de cómo debería comportarse el sistema en situaciones específicas. En algunos casos, los reque- rimientos funcionales también explican lo que no debe hacer el sistema.  
**Requerimientos no funcionales:** Son limitaciones sobre servicios o funciones que ofrece el sistema. Incluyen restricciones tanto de temporización y del proceso de desarrollo, como impuestas por los estándares. Los requerimientos no funcionales se suelen aplicar al sistema como un todo, más que a características o a servicios individuales del sistema.

#### Requerimientos funcionales
Los requerimientos funcionales para un sistema refieren lo que el sistema debe hacer. Tales requerimientos dependen del tipo de software que se esté desarrollando, de los usuarios esperados del software y del enfoque general que adopta la organización cuando se escriben los requerimientos. Al expresarse como requerimientos del usuario, los requerimientos funcionales se describen por lo general de forma abstracta que entiendan los usuarios del sistema. Sin embargo, requerimientos funcionales más específicos del sistema detallan las funciones del sistema, sus entradas y salidas, sus excepciones, etcétera.  
En principio, la especificación de los requerimientos funcionales de un sistema debe ser completa y consistente. Totalidad significa que deben definirse todos los servicios requeridos por el usuario. Consistencia quiere decir que los requerimientos tienen que evitar definiciones contradictorias.
En la práctica, para sistemas complejos grandes, es casi imposible lograr la consistencia y la totalidad de los requerimientos. Una causa para ello es la facilidad con que se cometen errores y omisiones al escribir especificaciones para sistemas complejos. Otra es que hay muchos participantes en un sistema grande. Un participante es un individuo o una función que se ve afectado de alguna forma por el sistema. Los participantes tienen diferentes necesidades, pero con frecuencia son inconsis- tentes. Tales inconsistencias tal vez no sean evidentes cuando se especifican por primera vez los requerimientos, de modo que en la especificación se incluyen requerimientos inconsistentes. Los problemas suelen surgir sólo después de un análisis en profundidad o después de que se entregó el sistema al cliente.

#### Requerimientos no funcionales
Los requerimientos no funcionales, como indica su nombre, son requerimientos que no se relacionan directamente con los servicios específicos que el sistema entrega a sus usuarios. Pueden relacionarse con propiedades emergentes del sistema, como fiabilidad, tiempo de respuesta y uso de almacenamiento. De forma alternativa, pueden definir res- tricciones sobre la implementación del sistema, como las capacidades de los dispositivos I/O o las representaciones de datos usados en las interfaces con otros sistemas.  
Los requerimientos no funcionales, como el rendimiento, la seguridad o la disponi- bilidad, especifican o restringen por lo general características del sistema como un todo. Los requerimientos no funcionales a menudo son más significativos que los requerimientos funcionales individuales. Es común que los usuarios del sistema encuentren formas para trabajar en torno a una función del sistema que realmente no cubre sus necesidades. No obstante, el fracaso para cubrir los requerimientos no funcionales haría que todo el sis- tema fuera inútil. Por ejemplo, si un sistema de aeronave no cubre sus requerimientos de fiabilidad, no será certificado para su operación como dispositivo seguro; si un sistema de control embebido fracasa para cubrir sus requerimientos de rendimiento, no operarán correctamente las funciones de control.  
La implementación de dichos requerimientos puede propagarse a lo largo del sistema. Para esto existen dos razones:

1. Los requerimientos no funcionales afectan más la arquitectura global de un sistema que los componentes individuales. Por ejemplo, para garantizar que se cumplan los requerimientos de rendimiento, quizá se deba organizar el sistema para minimizar las comunicaciones entre componentes.

2. Un requerimiento no funcional individual, como un requerimiento de seguridad, podría generar algunos requerimientos funcionales relacionados que definan nuevos servicios del sistema que se requieran. Además, también podría generar requerimientos que restrinjan los requerimientos ya existentes.

Los requerimientos no funcionales surgen a través de necesidades del usuario, debido a restricciones presupuestales, políticas de la organización, necesidad de interoperabilidad con otro software o sistemas de hardware, o factores externos como regulaciones de seguridad o legislación sobre privacidad.

![requerimientos-no-funcionales](/assets/ingenieria-de-requisitos/requerimientos-no-funcionales.jpg)

Los requerimientos no funcionales provienen de características requeridas del software (requerimientos del producto), la organización que desarrolla el software (requerimientos de la organización) o de fuentes externas:

1. **Requerimientos del producto:** Estos requerimientos especifican o restringen el comportamiento del software. Los ejemplos incluyen requerimientos de rendimiento sobre qué tan rápido se debe ejecutar el sistema y cuánta memoria requiere, requerimientos de fiabilidad que establecen la tasa aceptable de fallas, requerimientos de seguridad y requerimientos de usabilidad.

2. **Requerimientos de la organización:** Son requerimientos de sistemas amplios, derivados de políticas y procedimientos en la organización del cliente y del desarrollador. Los ejemplos incluyen requerimientos del proceso operacional que definen cómo se usará el sistema, requerimientos del proceso de desarrollo que especifican el lenguaje de programación, estándares del entorno o el proceso de desarrollo a utilizar, y requerimientos ambientales que definen el entorno de operación del sistema.

3. **Requerimientos externos:** Este término cubre todos los requerimientos derivados de factores externos al sistema y su proceso de desarrollo. En ellos se incluyen requerimientos regulatorios que establecen lo que debe hacer el sistema para ser aprobado en su uso por un regulador, como sería un banco central; requerimientos legislativos que tienen que seguirse para garantizar que el sistema opere conforme a la ley, y requerimientos éticos que garanticen que el sistema será aceptable para sus usuarios y el público en general.

Siempre que sea posible, se deberán escribir de manera cuantitativa los requerimientos no funcionales, de manera que puedan ponerse objetivamente a prueba. La siguiente imagen muestra las métricas que se utilizan para especificar propiedades no funcionales del sistema:

![propiedades-no-funcionales](/assets/ingenieria-de-requisitos/propiedades-no-funcionales.jpg)

En la práctica, en el documento de requerimientos, resulta difícil separar los requerimientos funcionales de los no funcionales. Si los requerimientos no funcionales se expresan por separado de los requerimientos funcionales, las relaciones entre ambos serían difíciles de entender. No obstante, se deben destacar de manera explícita los requerimientos que están claramente relacionados con las propiedades emergentes del sistema, como el rendimiento o la fiabilidad. Esto se logra al ponerlos en una sección separada del documento de requerimientos o al distinguirlos, en alguna forma, de otros requerimientos del sistema.

###Propiedades y Atributos de los requisitos
Las principales propiedades o cualidades que deben presentar los requisitos son:

*  Correctos: los requisitos deben ser realmente necesarios y cumplir con el propósito del sistema.

*  Conciso: Un requisito es conciso si es fácil de leer y entender. Su redacción debe ser simple y clara para aquellos que vayan a consultarlo en un futuro.

*  Consistentes: los requisitos no deben estar en conflicto entre ellos.

*  Completos: los requisitos deben abarcar toda posible entrada al sistema y toda posible respuesta del sistema.

*  Entendibles: los requisitos deben poder ser comprendidos por cualquier involucrado con un mínimo de explicación.

*  No ambiguo: Un requerimiento no es ambiguo cuando tiene una sola interpretación. El lenguaje usado en su definición, no debe causar confusiones al lector

*  Realizables: los requisitos deben poder satisfacerse considerando los recursos disponibles y restricciones, es decir, los requisitos deben ser posibles de llevarse a cabo.

*  Rastreables: los requisitos deben poder relacionarse bidireccionalmente a las fuentes que les dieron origen, y también a los modelos, documentos y componentes del software.

*  Verificables: los requisitos deben poder comprobarse a través del software.

*  Abstractos: los requisitos deben ser independientes de la implementación.

*  Referenciables por importancia y/o estabilidad: los requisitos deben permitir que se les asignen prioridad y grado de estabilidad que presentan en el tiempo.

## Especificación de requerimientos (ERS) o Software Requirement Specification (SRS)
La especificación de requerimientos es el proceso de escribir, en un documento de requerimientos, los requerimientos del usuario y del sistema. De manera ideal, los requerimientos del usuario y del sistema deben ser claros, sin ambigüedades, fáciles de entender, completos y consistentes. Esto en la práctica es difícil de lograr, pues los participantes interpretan los requerimientos de formas diferentes y con frecuencia en los requerimientos hay conflictos e inconsistencias inherentes.  
Los requerimientos del usuario para un sistema deben describir los requerimientos funcionales y no funcionales, de forma que sean comprensibles para los usuarios del sistema que no cuentan con un conocimiento técnico detallado. De manera ideal, deberían especificar sólo el comportamiento externo del sistema. El documento de requerimientos no debe incluir detalles de la arquitectura o el diseño del sistema.  
Idealmente, los requerimientos del sistema deben describir de manera simple el comportamiento externo del sistema y sus restricciones operacionales. No tienen que ocuparse de cómo se diseña o implementa el sistema. Sin embargo, al nivel de detalle requerido para especificar por completo un sistema de software complejo, es prácticamente imposible excluir toda la información de diseño.  

|Notación|Descripción|
|--------|-----------|
|Enunciados en lenguaje natural|Los requerimientos se escriben al usar enunciados numerados en lenguaje natural. Cada enunciado debe expresar un requerimiento.|
|Lenguaje natural estructurado|Los requerimientos se escriben en lenguaje natural en una forma o plantilla estándar. Cada campo ofrece información de un aspecto del requerimiento.|
|Lenguajes de descripción de diseño|Este enfoque usa un lenguaje como un lenguaje de programación, pero con características más abstractas para especificar los requerimientos al definir un modelo operacional del sistema. Aunque en la actualidad este enfoque se usa raras veces, aún tiene utilidad para especificaciones de interfaz.|
|Anotaciones gráficas|Los modelos gráficos, complementados con anotaciones de texto, sirven para definir los requerimientos funcionales del sistema; los casos de uso del UML y los diagramas de secuencia se emplean de forma común.|
|Especificaciones matemáticas|Dichas anotaciones se basan en conceptos matemáticos como máquinas o conjuntos de estado finito. Aunque tales especificaciones sin ambigüedades pueden reducir la imprecisión en un documento de requerimientos, la mayoría de los clientes no comprenden una especificación formal. No pueden comprobar que representa lo que quieren y por ello tienen reticencia para aceptarlo como un contrato de sistema.|


Los requerimientos del usuario se escriben casi siempre en lenguaje natural, complementado con diagramas y tablas adecuados en el documento de requerimientos. Los requerimientos del sistema se escriben también en lenguaje natural, pero de igual modo se utilizan otras notaciones basadas en formas, modelos gráficos del sistema o modelos matemáticos del sistema.

![especificación-de-requerimientos](/assets/ingenieria-de-requisitos/especificacion-de-requerimientos.jpg)

En una organización, la adquisición y el análisis de requerimientos pueden involucrar a diversas clases de personas. Un participante en el sistema es quien debe tener alguna influencia directa o indirecta sobre los requerimientos del mismo. Los participantes incluyen a usuarios finales que interactuarán con el sistema, y a cualquiera en una organización que resultará afectada por él. Otros participantes del sistema pueden ser los ingenieros que desarrollan o mantienen otros sistemas relacionados, administradores de negocios, expertos de dominio y representantes de asociaciones sindicales.

Las actividades del proceso son:

1. **Descubrimiento de requerimientos:** Éste es el proceso de interactuar con los participantes del sistema para descubrir sus requerimientos. También los requerimientos de dominio de los participantes y la documentación se descubren durante esta actividad. Existen numerosas técnicas complementarias que pueden usarse para el descubrimiento de requerimientos, las cuales se estudian más adelante en esta sección.

2. **Clasificación y organización de requerimientos:** Esta actividad toma la compilación no estructurada de requerimientos, agrupa requerimientos relacionados y los organiza en grupos coherentes. La forma más común de agrupar requerimientos es usar un modelo de la arquitectura del sistema, para identificar subsistemas y asociar los requerimientos con cada subsistema. En la práctica, la ingeniería de requeri- mientos y el diseño arquitectónico no son actividades separadas completamente.

3. **Priorización y negociación de requerimientos:** Inevitablemente, cuando intervienen diversos participantes, los requerimientos entrarán en conflicto. Esta actividad se preocupa por priorizar los requerimientos, así como por encontrar y resolver conflictos de requerimientos mediante la negociación. Por lo general, los participantes tienen que reunirse para resolver las diferencias y estar de acuerdo con el compromiso de los requerimientos.

4. **Especificación de requerimientos:** Los requerimientos se documentan e ingresan en la siguiente ronda de la espiral. Pueden producirse documentos de requerimientos formales o informales.

La adquisición y la comprensión de los requerimientos por parte de los participantes del sistema es un proceso difícil por diferentes razones:

1. Los participantes con frecuencia no saben lo que quieren de un sistema de cómputo, excepto en términos muy generales; pueden encontrar difícil articular qué quieren que haga el sistema; pueden hacer peticiones inalcanzables porque no saben qué es factible y qué no lo es.

2. Los participantes en un sistema expresan naturalmente los requerimientos con sus términos y conocimientos implícitos de su trabajo. Los ingenieros de requerimientos, sin experiencia en el dominio del cliente, podrían no entender dichos requerimientos.

3. Diferentes participantes tienen distintos requerimientos y pueden expresarlos en variadas formas. Los ingenieros de requerimientos deben descubrir todas las fuentes potenciales de requerimientos e identificar similitudes y conflictos.

4. Factores políticos llegan a influir en los requerimientos de un sistema. Los administradores pueden solicitar requerimientos específicos del sistema, porque éstos les permitirán aumentar su influencia en la organización.

5. El ambiente económico y empresarial donde ocurre el análisis es dinámico. Inevitablemente cambia durante el proceso de análisis. Puede cambiar la importancia de requerimientos particulares; o bien, tal vez surjan nuevos requerimientos de nuevos participantes a quienes no se consultó originalmente.

### Adquisición de conocimientos
Cuando la fuente de conocimientos se presenta en forma **escrita**, la adquisición se llamará **Extracción de Conocimientos**. Si, por el contrario, los conocimientos se obtienen de **seres humanos**, el proceso se denominará **Educción de Conocimientos**. Esta diferenciación pretende destacar que el proceso, los métodos o técnicas utilizados, los objetivos, los resultados, etc. son distintos dependiendo de si la fuente de conocimientos es escrita o humana.

#### Proceso de adquisición de conocimientos
El problema de la adquisición de conocimientos consiste en extraer los conocimientos correctos, y obtener la cantidad y el tipo adecuados de conocimientos en el momento apropiado. Es por esto que se debe controlar el proceso de adquisición constantemente, determinando en cada instante qué información se necesita, en qué profundidad, sobre qué tema, que técnica se debe emplear para adquirirlo, etc. En general, es una tentación improvisar, en lugar de planificar un proceso con una estructura coherente. Pero la planificación y el control es la clave del éxito en el proceso.  
En otras palabras, la adquisición es un proceso que se lleva a cabo de arriba a abajo. En líneas generales, se debe focalizar en los conocimientos estáticos del dominio (el «qué»), para, posteriormente, pasar a las estrategias y procedimientos de resolución de problemas (el «cómo»).  
Los principios para controlar la adquisición de conocimientos son la subdivisión en perspectivas y profundización gradual, los cuales quedan reflejados en el Proceso de adquisición de Conocimientos.

**Proceso de adquisición de conocimientos:**

1. Primeras reuniones y evaluación de viabilidad (de expertos, directivos y usuarios).

2. Extracción de conocimientos (de la documentación).

3. Educción de conocimientos (del experto).

	1. Interrogatorio inicial. 

	2. Investigación profunda.


El proceso de adquisición de conocimientos comienza con una serie de reuniones con el experto, los usuarios y los directivos del proyecto. Estas reuniones deben servir para:

- Determinar los requisitos funcionales del sistema o, en su caso, las necesidades de los usuarios del futuro sistema, o lo que los usuarios esperan del mismo.

- Introducir al equipo de desarrollo en el dominio a un nivel tal que sea capaz de desarrollar un estudio de viabilidad del sistema donde se determine si la tarea es tratable, o no.

**En las primeras reuniones se buscan conocimientos generales**, no de detalle, así como familiarizarse con la terminología del dominio. Las perspectivas en las que el analista debe centrarse en estas reuniones son el entorno de la tarea y sus usuarios. La profundidad que debe alcanzarse en estas reuniones es mínima; se busca el grano grueso, la visión general.  
**El siguiente paso es el estudio de la documentación existente.** El analista debe aprender sobre el dominio tanto como sea posible antes de comenzar las sesiones con el experto. Este periodo de preparación tiene como objetivo evitar o, por lo menos, reducir el tiempo que, de otro modo, deberá malgastar el experto a fin de iniciar al analista en el tema. Como, normalmente, la educción formal de conocimientos no se inicia hasta que el proyecto ha sido parcialmente definido y aprobado, esto le proporciona al analista el tiempo suficiente para obtener buenas fuentes de información, estudiarlas y asimilar su contenido.  
Tanto en las primeras reuniones como en el estudio de la documentación, se debe resistir la tentación de bajar a los detalles en cuanto comienza a tener algo claro sobre la tarea. Recuérdese que, en estos dos primeros pasos del proceso de adquisición, se está buscando una visión general del dominio. No se pretende profundizar aún en el grano fino de los conocimientos.  
**El tercer paso es el Ciclo de Educción de Conocimientos.** Es durante este ciclo cuando se obtienen los conocimientos genuinamente privados del experto. La educción de conocimientos es un subproceso del proceso de adquisición de conocimientos. La educción es, específicamente, el proceso de interactuar con un experto humano con el propósito de construir un sistema. El proceso de educción puede dividirse en dos etapas fundamentales: el interrogatorio inicial y la investigación profunda. En el interrogatorio inicial se tratará una visión de alto nivel del dominio, donde el analista llegue a comprender el alcance del dominio (qué problemas y áreas tratará el sistema y cuáles quedan fuera); cuál es la tarea del experto; y el entorno de la tarea (conceptos, objetos, procedimientos, etc., que el experto usa en la resolución). Posteriormente, y de modo gradual, se bajará a los detalles concretos de las distintas áreas del dominio hasta configurar el cuadro completo, Nuevamente se debe controlar e impedir que el experto varíe el objetivo de las sesiones ya sea, por ejemplo, por bajar demasiado al detalle o por el problema contrario.

>En 1983 Yukio Mizuno [Mizuno 1983] propuso un modelo, conocido como “catarata de errores de Mizuno”, para representar la propagación de los errores durante el desarrollo de sistemas de software. El modelo muestra como a partir de una especificación de requisitos “normal”, que incluya algún tipo de incorrección, estos errores originados en una etapa se arrastran en las fases sucesivas, y en cada una se agregan nuevos errores. Esto puede ocasionar errores ocultos dentro del sistema que son difíciles de detectar. Además indica que el crecimiento de los costos de reparación es producto de la catarata de errores.

![errores-mizuno](/assets/ingenieria-de-requisitos/errores-mizuno.png)

>Boehm [Boehm 2001] establece como primera causa para reducir los defectos de software que “encontrar y corregir un problema de software después de la entrega suele ser 100 veces más caro que encontrar y corregir el error durante las fases de requisitos y diseño”.

![costo-errores](/assets/ingenieria-de-requisitos/costo-errores.jpg)

