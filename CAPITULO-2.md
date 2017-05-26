# CAPÍTULO 2

## MARCO TEÓRICO
En este capítulo se analizará las diferente arquitecturas de desarrollo de software que se utilizan actualmente, velando de los principios del desarrollo en calidad, escalabilidad seguridad y mantenimiento, del software y la curva de aprendizaje del entorno de desarrollo para los programadores, así también los patrones, antipatrones de diseño, que surgieron a largo de los últimos años.

## 2.1 Modelo de negocio
El “Modelo de Negocio” se define como un proceso de representación de uno o más aspectos o elementos de una empresa u organización. Se busca modelar las actividades que se hacen dentro de una empresa la cual va a tener un fin; los aspectos que se desean modelar son su propósito, estructura, funcionalidad, dinámica, logística de negocios y sus componentes como fines, procesos de negocio, regla de negocio, objeto de negocio, actores y unidades organizativas [1].

En el desarrollo de software, los requisitos tienen lugar en el espacio de la solución; el Modelado de Negocios aporta información esencial para la ingeniería de requisitos [2]. Siendo así la caracterización de los aspectos más significativos de la empresa o una parte de ella, para ello se debe tener claro cuál es el fin que se busca con ese modelo, para así tener claro los elementos del negocio que se desean representar y puede ser orientado al negocio propiamente u orientadas a la tecnología y su aplicación en el negocio.

### 2.1.1 Modelo de negocio actual
El modelo de negocio actual es una parte primordial de cualquier proceso de desarrollo de software, permite lograr comprender el ámbito de la información e identificar las responsabilidades, actividades y procesos que se realizan dentro de la organización. Éste resultado es de gran ayuda para identificar las posibles formas de hacer el negocio más eficiente.

### 2.1.2 Modelo de negocio alternativo
El modelo de negocio alternativo es la representación de la situación mejorada, lo cual requiere el análisis de los procesos del modelo de negocio actual y la búsqueda del modelo para nuevas formas de hacer las cosas. Esto significa que modelo de negocio actual y sus procesos son cambiados significativamente para crear diferentes y mejorados procesos.

### 2.1.3 Diseño del modelo de negocio
Los diagramas de flujo permiten modelar y representar gráficamente todo tipo de sistemas, una de las características principales es que proporcionan información sobre los procesos de forma clara, ordenada y concisa.

*Cuadro 2.1*

*Elementos principales de un diagrama de flujo*

![Alt text](/anexos/cuatro-1.png?raw=true "")

_**Fuente:** [Elaboración propia]_

A continuación se muestra un modelo de básico de un diagrama de flujo:

*Figura 2.1*

*Diagrama de flujo*

![Alt text](/anexos/figura-1.png?raw=true "")

_**Fuente:** [Elaboración propia]_

## 2.3 Ingeniería de Software
La ingeniería de software es “una disciplina que comprende todos los aspectos de la producción de software desde las etapas iniciales de la especificación del sistema, hasta el mantenimiento de este después de que se utiliza” [3].
El IEEE16 (Instituto de Ingeniería Eléctrica y Electrónica) define que: “la ingeniería de software es la aplicación de un enfoque sistemático, disciplinado y cuantificable al desarrollo, operación y mantenimiento de software [4]. Según Pressman la ingeniería de software es una tecnología con varias capas.

*Figura 2.2*

*Capas de la ingeniería de software*

![Alt text](/anexos/figura-2.png?raw=true "")

_**Fuente:** [11, Fig. 1.3]_

Cualquier enfoque de ingeniería (incluso la de software) debe basarse en un compromiso organizacional con la calidad [4].

La ingeniería de software es de mucha importancia ya que sugiere que se utilicen ciertas estrategias como metodologías, métodos, técnicas y tecnologías de softwares, dando una esencia del verdadero proceso de desarrollo de software las cuales serán aplicadas para la resolución de problemas del proyecto describiendo algunos modelos de desarrollo y sus procesos.

### 2.3.1 Metodologías de desarrollo de software
La metodología de software es un conjunto de procedimientos, técnicas, herramientas y un soporte documental que ayuda a los desarrolladores a realizar nuevo software.
La elección de metodología o procesos de desarrollo de software es de trascendental importancia, porque es la que nos guiara para alcanzar el objetivo de culminar el proyecto. Para eso se planteara una comparación entre las diversas metodologías.
Para el presente proyecto desde inicio se consideró aplicar algún proceso de desarrollo ágil principalmente debido a un alto grado de incertidumbre en cuanto a los requerimientos funcionales se refiere. Sin embargo, es necesario realizar un breve análisis de modelos de desarrollo ágil existentes y tomar la decisión correcta respecto al proceso que mas se adecua a las condiciones del proyecto. Por lo tanto, a continuación se describen tres modelos candidatos a ser aplicados en el proyecto y posteriormente se comparan sus características principales.

### 2.3.2 Metodologías de desarrollo ágil
El desarrollo ágil de software es un grupo de metodologías de desarrollo de software que se basan en principios similares. Las metodologías ágiles promueven generalmente un proceso de gestión de proyectos que fomenta el trabajo en equipo, la organización y responsabilidad propia, un conjunto de mejores prácticas de ingeniería que permiten la entrega rápida de software de alta calidad, y un enfoque de negocio que alinea el desarrollo con las necesidades del cliente.
Potencialmente, casi todos los métodos ágiles son adecuados para la adaptación. La conveniencia de situación puede considerarse como una característica de distinción entre los métodos ágiles y los métodos tradicionales, que son mucho más rígidos y preceptivos.
Asimismo, las metodologías convencionales tienden a acumular los riesgos y dificultades que surgen en el desarrollo del producto al final del proyecto, como puede apreciarse en la figura 2.3, repercutiendo en retrasos en la entrega de productos o influyendo en la incorrecta ejecución de las últimas fases del ciclo de vida.

*Figura 2.3*

*Distribución del riesgo*

![Alt text](/anexos/figura-3.png?raw=true "")

_**Fuente:** [5]_

Se puede decir que las metodologías tradicionales ponen por encima de lo demás los objetivos de la definición y del control del trabajo, mientras que las metodologías ágiles priman la libertad del equipo, la comunicación entre el cliente y el equipo, realizar sólo las tareas que aportan valor al cliente, y finalmente definir el trabajo tal y como éste se va realizando para el conocimiento adquirido durante su desarrollo evite realizar tareas innecesarias.
A continuación se presentaran diferentes modelos agiles de proceso. Entre ellas existen mucha similitud sin embargo cada una posee características únicas que las diferencian de las demás.

**a) Programación Extrema (XP)**
La programación extrema, es una metodología de desarrollo ágil, una de las más exitosas en tiempo reciente.
La programación extrema (XP) es un enfoque de la ingeniería del software formulado por Kent Beck. Es el más destacado de los procesos ágiles de desarrollo de software. Se diferencia de las metodologías tradicionales principalmente en que pone más énfasis en la adaptabilidad que en la previsibilidad.

El objetivo principal de XP es la satisfacción del cliente. Se le trata de dar al cliente lo que quiere y cuando quiere. Por tanto, se debe responder rápidamente a las necesidades del cliente. Como metodología Ágil que es, se pueden producir modificaciones de los requisitos del proyecto a lo largo de su desarrollo, sin que esto produzca dificultades.
Pressman dice que “La programación extrema usa un enfoque orientado a objeto como paradigma preferido de desarrollo, y engloba un conjunto de reglas y prácticas que ocurren en el contexto de cuatro actividades estructurales: planeación, diseño, codificación y pruebas” [6, pp. 61].

XP es una metodología centrada en potenciar las relaciones interpersonales como clave para el éxito en el desarrollo de software, promoviendo el trabajo en equipo y basándose en la realimentación continua entre el cliente y el desarrollador. XP es adecuado para proyectos con requisitos imprecisos y cambiantes.

**b) SCRUM**
SCRUM es una metodología que nace ajena al desarrollo del software, de hecho sus principios fundamentales fueron desarrollados en procesos de reingeniería por Goldratt, Takeuchi y Nonaka en la década de 1980.
Scrum es un proceso ágil que se puede usar para gestionar controlar desarrollos complejos de software y productos usando prácticas iterativas e incrementales. Es un proceso incremental iterativo para desarrollar cualquier producto o gestionar cualquier trabajo.
Los actores contemplados en esta metodología son los siguientes:

- Product Owner, conoce y marca las prioridades del proyecto o producto.
- Scrum Master, es la persona que asegura el seguimiento de la metodología guiando las reuniones y ayudando al equipo ante cualquier problema que pueda aparecer. Su responsabilidad es entre otras, la de hacer de paraguas ante las presiones externas.
- Scrum Team, son las personas responsables de implementar la funcionalidad o funcionalidades elegidas por el Product Owner.
- Usuarios o Cliente, son los beneficiarios finales del producto, y son quienes viendo los progresos, pueden aportar ideas, sugerencias o necesidades. que incluye a los desarrolladores.

### 2.3.3 Selección de la metodología de desarrollo
Entre las 2 metodologías ágiles descritas anteriormente la más utilizada es la metodología XP, ya que esta metodología propone una estrecha relación entre el equipo de desarrollo y los clientes, estableciendo como base la comunicación.

### 2.1 Arquitectura de software
Arquitectura de software es el proceso de definir una solución estructural, que conoce todas las técnicas y requerimientos operacionales, optimizando atributos comunes de cualidad como performance, seguridad y manejabilidad. esto envuelve una serie de decisiones basadas en un amplio rango de factores y cada uno de estas decisiones puede tener considerable impacto, sobre todo en el éxito de la aplicación.
"Arquitectura de software abarca el conjunto de decisiones importantes acerca de la organización de un sistema de software que incluye la selección de los elementos estructurales y sus interfaces mediante el cual el sistema se compone; comportamiento como se especifica en la colaboración entre dichos elementos; composición de estos elementos estructurales y de comportamiento en subsistemas más grandes; y un estilo arquitectónico que guía a esta organización. arquitectura de software también incluye la funcionalidad, facilidad de uso, la resistencia, el rendimiento, la reutilización, la comprensibilidad, las limitaciones económicas y tecnológicas, ventajas y desventajas y las preocupaciones estéticas ".[13]
Fowlwer, uno de los ingenieros más reconocidos en el área de desarrollo de software, dice que la arquitectura es “el desglose de más alto nivel de un sistema en sus partes; las decisiones que son difíciles de cambiar; hay múltiples arquitecturas en un sistema; lo que es de gran importancia arquitectónica puede cambiar durante la vida de un sistema; y, al final, la arquitectura se reduce a lo que más importante del sistema sea”[15].

### 2.2 Comparaciones.
La creación de un sitio web o una página de internet en general implica dos factores, el front-end y el back-end. /* para palabras en ingles, usar itálicas */
Front-end y back-end son términos utilizados para caracterizar las interfaces del programa y los servicios relativos al usuario inicial de estas interfaces y servicios. (El "usuario" puede ser un ser humano o un programa.) Una aplicación "front-end" es aquella con la que los usuarios de la aplicación interactúan directamente.

### 2.2.1 Front-end y back-end
El front-end es todo lo relacionado con lo que el usuario ve, incluyendo el diseño y algunos lenguajes como HTML y CSS.
Cuando discutimos el "frontend" de la web, lo que realmente estamos hablando es la parte de la web con la que puedes ver e interactuar. El frontend generalmente consta de dos partes: el diseño web y el desarrollo web front-end.
En el pasado, cuando alguien hablaba de desarrollo por lo general se refiere al backend, pero en los últimos años ha habido una necesidad real de diferenciar entre los diseñadores que trabajaban estrictamente en Photoshop y los que podían codificar HTML y CSS. Fue aún más lejos cuando los diseñadores cruzaron las líneas para trabajar con JavaScript y jQuery.

El back-end, o el "lado del servidor", es básicamente cómo funciona el sitio, las actualizaciones. Esto se refiere a todo lo que el usuario no puede ver en el navegador, como bases de datos y servidores. En el lado de  back-end los desarrolladores se preocupan más por cuestiones como la seguridad, la estructura y la gestión de contenidos.
Una aplicación o programa "back-end" sirve indirectamente en apoyo de los servicios front-end, normalmente por estar más cerca del recurso requerido o tener la capacidad de comunicarse con el recurso requerido. La aplicación de del lado del servidor puede interactuar directamente con el front-end.
El backend normalmente consta de tres partes: un servidor, una aplicación y una base de datos. Si reserva un vuelo o compra entradas de conciertos, normalmente abre un sitio web e interactúa con el frontend. Una vez que haya ingresado esa información, la aplicación la almacena en una base de datos que se creó en un servidor.

Toda esa información permanece en el servidor, así que cuando vuelva a iniciar sesión en la aplicación para imprimir sus tickets, toda la información aún está en su cuenta.

### 2.2.1.1 Single-page application (SPA)

Las aplicaciones de una página (SPAs) son aplicaciones Web que cargan una sola página HTML y actualizan dinámicamente esa página a medida que el usuario interactúa con la aplicación.
Las SPA utilizan AJAX y HTML5 para crear aplicaciones Web fluidas y sensibles, sin recargas constantes de la página. Sin embargo, esto significa que gran parte del trabajo ocurre en el lado del cliente, Afortunadamente, hay muchos frameworks en JavaScript de código libre que facilitan la creación de SPAs. Entre los más conocidos están Angular, Angular 2 y Ember.

###  2.2.1.2 Backend For Frontend (BFF)
Los valiosos servicios soportan muchas variaciones en los clientes, como el móvil frente a la web y diferentes formas de interfaz web. Es tentador diseñar una única API de back-end para apoyar a todos los clientes con una API reutilizable. /* el tono de escritura debe ser científico. 3ra persona impersonal */ Pero las necesidades del cliente varían, al igual que las restricciones, como el ancho de banda para los dispositivos móviles frente al deseo de un montón de datos sobre las conexiones web rápidas. Por lo tanto, a menudo es mejor definir diferentes servicios de back-end para cada tipo de cliente front-end. Estos extremos posteriores deben ser desarrollados por equipos alineados con cada extremo frontal para asegurarse de que cada extremo posterior cumple adecuadamente las necesidades de su cliente.

###  2.2.1.3 Mobile Application Architecture
El desarrollo de aplicaciones móviles plantea muchos desafíos, como usabilidad, seguridad, integración, conectividad y velocidad. El rápido desarrollo de estas aplicaciones complejas, si no se ejecuta cuidadosamente, puede conducir rápidamente a importantes problemas de soporte. La demanda de aplicaciones móviles ha crecido rápidamente debido a la rápida adopción de la movilidad en los últimos años. A finales de 2017, la demanda de negocios para aplicaciones móviles empresariales crecerá al menos cinco veces más rápido que la capacidad interna de la organización de TI para entregarlas, según Gartner. Ellos recomendaron varias buenas prácticas para superar estos desafíos.
Normalmente, una aplicación móvil se estructurará como una aplicación de múltiples capas que consistirá en capas de experiencia de usuario, de negocio y de datos. Al desarrollar una aplicación móvil, puede optar por desarrollar un cliente basado en Web delgado o un cliente enriquecido. Si está creando un cliente enriquecido, es probable que las capas de servicios empresariales y de datos se encuentren en el propio dispositivo. Si está creando un cliente ligero, las capas empresariales y de datos se ubicarán en el servidor. Entre las más conocidas  arquitecturas existe:
Native Application Architecture – Platform Specific
Native Application Architecture – Code Shared
Hybrid Application Architecture

### 2.2.2 Web, mobile and integration
### 2.3 Transporte de Datos
### 2.3.1 XML, JSON y AJAX

### 2.1.1 Service Oriented Architecture (SOA)
La arquitectura orientada a servicios (SOA) es un enfoque utilizado para crear una arquitectura basada en el uso de servicios. Los servicios (como los servicios Web RESTful) realizan alguna función pequeña, como la producción de datos, la validación de un cliente o la prestación de servicios analíticos simples.
Además de construir y exponer servicios, SOA tiene la capacidad de aprovechar estos servicios una y otra vez dentro de las aplicaciones (conocidas como aplicaciones compuestas). SOA abordando la mayoría de los principales sistemas como servicios, y la abstracción de los servicios en un único dominio donde se forman en soluciones.
Las arquitecturas orientadas al servicio no son algo nuevo. La primera arquitectura orientada a servicios para muchas personas en el pasado fue con el uso de DCOM u ORB (Object Request Brokers) basado en la especificación CORBA.

### 2.1.2 Multi-layered Architecture (MLA)
La arquitectura de una aplicación N-capas se caracteriza por la descomposición funcional de las aplicaciones, los componentes de servicio y su implementación distribuida, proporcionando escalabilidad, disponibilidad, capacidad de administración y utilización de recursos mejoradas. Cada nivel es completamente independiente de todos los demás niveles, excepto los inmediatamente superiores e inferiores. La comunicación entre niveles es típicamente asíncrona para soportar mejor escalabilidad.
Las arquitecturas de nivel N generalmente tienen al menos tres partes lógicas separadas, cada una ubicada en un servidor físico separado. Cada parte es responsable de la funcionalidad específica. Cuando se utiliza un enfoque de diseño en capas, se despliega una capa en un nivel si más de un servicio o aplicación depende de la funcionalidad expuesta por la capa.
Los principales beneficios de la arquitectura en N-capas / 3-capas son:
Mantenibilidad. Debido a que cada nivel es independiente de los otros niveles, las actualizaciones o cambios se pueden llevar a cabo sin afectar la aplicación en su conjunto.
Escalabilidad. Dado que los niveles se basan en el despliegue de capas, la ampliación de una aplicación es razonablemente sencilla.
Flexibilidad. Debido a que cada nivel puede ser administrado o escalado de forma independiente, la flexibilidad se incrementa.
Disponibilidad. Las aplicaciones pueden aprovechar la arquitectura modular de sistemas habilitadores que utilizan componentes fácilmente escalables, lo que aumenta la disponibilidad.

Como un ejemplo, la capa de presentación no debe almacenar datos confidenciales, mientras que esto puede almacenarse en las capas de datos y de negocio.
Considere la posibilidad de utilizar sólo tres niveles si está desarrollando una aplicación de intranet donde todos los servidores están ubicados dentro de la red privada; O una aplicación de Internet en la que los requisitos de seguridad no restringen el despliegue de la lógica de negocios en el servidor Web o en la Web que se enfrenta al público. Considere la posibilidad de utilizar más de tres capas si los requisitos de seguridad dictaminan que la lógica empresarial no se puede implementar en la red perimetral o que la aplicación utiliza mucho los recursos y desea descargarla a otro servidor.

### 2.1.3 Microservices Architecture (MSA)
La arquitectura de microservicio, es un método de desarrollo de software que ha crecido en popularidad en los últimos años. Para muchos desarrolladores se ha convertido en la forma preferida de crear aplicaciones empresariales. Gracias a su escalabilidad, este método arquitectónico se considera especialmente ideal cuando se tiene que habilitar el soporte para una amplia gama de plataformas y dispositivos, que abarcan la web, el móvil, Internet de las cosas y los portátiles, o simplemente cuando no está seguro de qué tipo de dispositivos Usted tendrá que apoyar en un futuro cada vez más nublado.
La idea detrás de los microservicios es que algunos tipos de aplicaciones se vuelven más fáciles de construir y mantener cuando se dividen en piezas más pequeñas y componibles que trabajan juntas. Cada componente se desarrolla por separado, y la aplicación es entonces simplemente la suma de sus componentes constituyentes. Esto es en contraste con una aplicación tradicional, "monolítica", que es todo desarrollado en una sola pieza.
Si bien no existe una definición estándar y formal de microservicios, existen ciertas características que nos ayudan a identificar el estilo. Esencialmente, la arquitectura de microservicios es un método de desarrollo de aplicaciones de software como un conjunto de servicios modulares, desplegables de forma independiente, en los que cada servicio ejecuta un proceso único y se comunica a través de un mecanismo ligero y bien definido para servir una meta de negocio.

El modo en que los servicios se comunican entre sí depende de los requisitos de su aplicación, pero muchos desarrolladores usan HTTP / REST con JSON o Protobuf. El REST (Representational State Transfer) es un método de integración útil debido a su comparativamente menor complejidad sobre otros protocolos.

Para empezar a entender la arquitectura microservicios, ayuda a considerar su opuesto: el estilo arquitectónico monolítico. A diferencia de los microservicios, la aplicación monolítica siempre se construye como una unidad única y autónoma. En un modelo cliente-servidor, la aplicación del lado del servidor es un monolito que maneja las solicitudes HTTP, ejecuta la lógica y recupera / actualiza los datos en la base de datos subyacente. El problema con una arquitectura monolítica, sin embargo, es que todos los ciclos de cambio suelen terminar ligados entre sí. Una modificación realizada en una pequeña sección de una aplicación puede requerir la creación e implementación de una versión totalmente nueva. Si necesita escalar funciones específicas de una aplicación, puede que tenga que escalar la aplicación completa en lugar de sólo los componentes deseados. Aquí es donde la creación de microservicios puede venir al rescate.

Hay muchas razones por las que este enfoque se considera una manera más fácil de desarrollar grandes aplicaciones, aplicaciones empresariales particulares y varios tipos de software como servicio entregado a través de Internet.
Si esta desarrollando una aplicación empresarial de servidor. Debe soportar una variedad de clientes diferentes, incluyendo navegadores de escritorio, navegadores móviles y aplicaciones móviles nativas. La aplicación también puede exponer una API para que terceras partes consuman. También podría integrarse con otras aplicaciones a través de servicios web o un intermediario de mensajes. La aplicación gestiona las solicitudes (solicitudes y mensajes HTTP) mediante la ejecución de la lógica empresarial; Acceder a una base de datos; Intercambiar mensajes con otros sistemas; Y devolver una respuesta HTML / JSON / XML.

### 2.3 Microservices architecture
### 2.3.1 Rest API
### 2.3.2 Los diez mandamientos de microservicios
### 2.3.3 Patterns
### 2.3.3.1 API Gateway pattern
### 2.3.3.2 Database per Service pattern
### 2.3.3.3 Microservice chassis pattern
### 2.3.4 12 factores

### 2.5 Identificación única
Existen varias maneras de identificación que se tornaron populares en la actualidad y podemos mencionar entre todos: UUID (Universally unique identifier)[10], y QR (Quick response codes)[11]. Cada una estas formas de identificación se utiliza de forma separada, podemos mencionar que un UUID es una cadena de caracteres y en cambio un QR es un contenedor de datos que se vuelve único en base a su contenido.

### 2.5.1 Identificador único universal UUID
Como el la introducción de su manifiesto dice[12]: “Un UUID es un identificador que es único a lo largo entre espacio y tiempo… para identificar de forma fiable objetos persistentes a través de una red.” entre sus características se puede mencionar que es un cadena de 32 caracteres alfanuméricos en minúscula con una forma de 8-4-4-4-12 y un total de 36 caracteres. un UUID tendría un parecido a este identificador, ejemplo: 00000000-0000-0000-0000-000000000000, entre las posibilidades de combinaciones de los caracteres alfanuméricos es imposible poder duplicar la generación de uno igual.

### 2.5.2 Códigos de respuesta rápida QR
Los códigos QR han ganado popularidad en los últimos años por su capacidad de almacenaje de datos y son mucho más efectivo que el código de barras, un código QR puede contener varios tipos de datos mensajes, texto, URL, geolocalización. La capacidad de un QR es muy variado, pero con la ayuda de los UUID los QR pasarían a convertirse en entidades únicas y perfectos a la hora de identificar un recurso bibliográfico, y sin tener que estar asociado a ningún sistema.

## REFERENCIAS BIBLIOGRÁFICAS

/* Falta del 7 al 9 */
[1] Y. Gascón, Revisión de conceptos básicos Modelado de Negocios, disponible en
http://es.slideshare.net/yamilagascon/revisin-de-conceptos-bsicos-modelado-de-negocios accedido el 24 de Mayo 2017.

[2] J. Montilva, Modelo de Negocio, disponible en
http://es.slideshare.net/RaulIram/tarea-16614847 accedido el 24 de Mayo 2017.

[3] Ian Sommerville (2005) Ingeniería del Software, 7th edición, Madrid, España, Pearson Educación.

[4] R. S. Pressman, Ingeniería del software: Un enfoque práctico, 7th. Edición, The McGraw-HillCompanies.

[5] Pilar Rodríguez Gonzales, Estudio de la aplicación de metodologías ágiles para la evolución de productos software, Master en tecnologías de la información. Universidad Politécnica De Madrid 2008

[6] Roger S. Pressman, Ingeniería de software, en Ingeniería del software un enfoque práctico.7ª edición, México: Mexicana, 2010, Cap.1, pp. 10

[10] UUID, Universally unique identifier, disponible en
https://en.wikipedia.org/wiki/Universally_unique_identifier, accedido el 3 de Octubre 2016

[14] Wikipedia, Martin Fowler
https://es.wikipedia.org/wiki/Martin_Fowler, accedido el 12 de Octubre 2016
[15]  Martin Fowler, Patterns of Enterprise Application Architecture,
ftp://ftp.heanet.ie/mirrors/sourceforge/w/we/webtune/Patterns%20of%20Enterprise%20Application%20Architecture.pdf, accedido el 12 de Octubre 2016

[11] QR, Quick response codes, disponible en
http://www.qrcode.com/en/about/, accedido el 3 de Octubre 2016
[12] UUID, Definition, disponible en
http://www.ietf.org/rfc/rfc4122.txt, accedido el 4 de Octubre 2016
[13] patterns & practices Developer Center, What is Software Architecture?, disponible en
https://msdn.microsoft.com/en-us/library/ff650706.aspx, accedido el 12 de Octubre 2016

backend and frontend
http://blog.digitaltutors.com/whats-difference-front-end-back-end/
13 de Diciembre 2016
http://blog.teamtreehouse.com/i-dont-speak-your-language-frontend-vs-backend
13 de Diciembre 2016
Marshall, Catherine & Rossman, Gretchen B. (1989). Designing qualitative research. Newbury Park, CA: Sage.

SPA
http://singlepageappbook.com/goal.html
13 de Diciembre 2016

BFF
https://www.thoughtworks.com/radar/techniques/bff-backend-for-frontends
13 de Diciembre 2016

Mobile Application Architecture Guide
libro
Mobile Application Architecture Guide
14 de Diciembre 2016

Observation
http://www.qualitative-research.net/index.php/fqs/article/view/466/996
29 de Diciembre 2016

Mobile Application Architecture
http://smartbridge.com/architecture-prevails-mobile-application-development/
14 de Diciembre 2016

http://microservices.io/patterns/microservices.html

https://es.wikipedia.org/wiki/Front-end_y_back-end

http://thenewstack.io/ten-commandments-microservices/

https://12factor.net/es/

https://es.wikipedia.org/wiki/Single-page_application

Mobile app services, web, mobile and integration
https://azure.microsoft.com/en-us/documentation/articles/app-service-mobile-value-prop/

FOO file
https://www.google.com.bo/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8#q=soa%20what%20is%20it

http://www.service-architecture.com/articles/web-services/service-oriented_architecture_soa_definition.html

FYI

https://opensource.com/resources/what-are-microservices
https://www.nginx.com/blog/microservices-at-netflix-architectural-best-practices/


/*
Sugerencias:
1. Complementar el texto con citas.  Hay pocas citas en el documento
2. Complementar el texto con elecciones y fundamentaciones.  Cuando el concepto lo requiera, provee argumentos que sustenten la elección tomada.  Ej. Arquitectura.
3. Faltan temas como ser: seguridad, calidad, usabilidad del software
*/
