#lagash-documentation

- CAPÍTULO 1
  - EL PROBLEMA
    - 1.1  Antecedentes
    - 1.2 Problema
      - 1.2.1 Situación problemática
      - 1.2.2 Formulación del problema
    - 1.3 Objetivos
      - 1.3.1 Objetivo general
      - 1.3.2 Objetivos específicos
    - 1.4 Justificación
      - 1.4.1 Justificación técnica
      - 1.4.2 Justificación social
    - 1.5  Límites y Alcances
      - 1.5.1 Límites
      - 1.5.2 Alcances
    - 1.6 Estudio de factibilidad
      - 1.6.1	Factibilidad técnica
      - 1.6.2	Factibilidad operacional

# CAPÍTULO 1
## EL PROBLEMA
### 1.1  Antecedentes
La biblioteca Sighart Klauss, es un departamento de la Universidad Adventista de Bolivia (UAB), cuenta con un aproximado de 36.000 materiales bibliográficos. Sin contar los libros que cuenta la biblioteca del Colegio Adventista de Bolivia.

La biblioteca es actualizada periódicamente con nuevos materiales bibliográficos como ser libros, tesis, proyectos de grado, monografías, revistas y periódicos. Los pedidos son realizados por los administradores de la biblioteca.

Los materiales bibliográficos para su registro correspondiente pasan por un criterio de selección, A esta etapa se lo conoce como la clasificación. La clasificación se realiza con los libros y tesis, los materiales bibliográficos restantes son guardados sin llevar ningún registro digital.

La clasificación consiste en dotar al libro o tesis un código (signatura topográfica) que son generados en la clasificación DEWEY que se construye en base a su contenido. Una vez finalizada la clasificación de cada material bibliográfico es asignado un número de inventario.

Por último se registra el libro o tesis al sistema y es trasladado a su pabellón (Sala asignada) correspondiente para que el encargado ya pueda realizar un préstamo. Las revistas no pasan el proceso clasificación de un libro, estas son registradas al sistema directamente.

Para los periódicos existe una suscripción de “Los Tiempo y Opinión” desde hace 5 años. Estos son almacenados directamente y no existe ningún registro digital. La biblioteca actualmente cuenta con sistema que fue desarrollado por el practicante Moisés Fernández Q. el año 2006, cuenta con funcionalidad para gestionar libros, revistas, tesis y un buscador.

Para el correcto registro al sistema el encargado realiza tres copias de los datos de un recurso bibliográfico.

Primero, copia en un papel toda esta información: signatura topográfica, número de inventario, editorial, año de edición, tamaño, precio, autor, media, tipo de libro y su índice.

Segundo, se transcribe a máquina de escribir su ficha topográfica con todos los datos generados y extraídos del libro y es trasladado al muestrario de fichas topográficas.

Por último, se transcribe al sistema.

Con el sistema actual el lector puede realizar un búsqueda por Titulo, Autor, Tema, y Año, La búsqueda en el sistema no diferencia entre mayúsculas y minúsculas o acentos de las palabras que componen el titulo o sus descriptores. Como alternativa el lector tiene habilitado un libro de búsqueda en cada pabellón con información del título y autor.

Una vez que el lector decidió que libró va a llevar prestado, copia la referencia del libro en una ficha de búsqueda. Esta ficha de búsqueda es llenada manualmente con información del libro como ser el título, autor y signatura topográfica. También, es llenado con información del lector, estatus (Estudiante, Docente, Administrador o Visitante), facultad a la que pertenece y la fecha, esta información sirve para realizar los reportes que periódicamente la administración de la biblioteca pública para conocimiento general.

El horario de atención se refleja en la siguiente tabla:

| HORARIO | NORMAL | PABELLÓN |
|---------|--------|----------|
| lunes-jueves | 08:00-12:30 / 14:00-21:00 | A, B, C |
| Viernes | 08:00-13:00 |	A, B, C |
| Domingo | 08:00-13:00 |	A, B, C |

Como regla general para un préstamo el lector debe portar su identificación, para los estudiantes el carnet estudiantil de la universidad, y para el caso de los lectores externos y los docentes la Cédula de identidad.

Los préstamos a domicilio son solo efectivos a partir de las 18:00 horas, los estudiantes están obligados a devolver los libros al día siguiente antes de las 9:30 a.m. caso contrario se aplicará una multa, con la excepción de los docentes que pueden extender el tiempo a una semana, los lectores externos no pueden llevar ninguna clase de material bibliográfico fuera de la biblioteca.

### 1.2 Problema
#### 1.2.1 Situación problemática
La gestión de los pedidos de materiales bibliográficos es demorosa provocando el retraso de la publicación del mismo.

El proceso de creación de la ficha topográfica es completamente independiente del sistema y esto conlleva una triple transcripción de la información requerida para el registro de los libros y tesis.

Las búsquedas no son flexibles al tipo de escritura (mayúscula, minúscula y acentos) provocando desconfianza en el sistema de búsqueda.

El sistema actual tiene muchas limitaciones a la hora de hacer búsquedas con los nuevos materiales bibliográficos provocando desconfianza con los resultados.

La generación manual de reportes a partir de las fichas de búsqueda es un proceso muy moroso provocando pérdida de tiempo a la administración de la biblioteca.

#### 1.2.2 Formulación del problema
Los ineficientes procesos de gestión de materiales bibliográficos y funcionalidad limitada en el sistema actual de búsqueda provoca, repetición de procesos, error en las búsquedas y desinformación de los lectores de la biblioteca Sighart Klauss.

### 1.3 Objetivos
#### 1.3.1 Objetivo general
Desarrollar un sistema Web para la gestión y búsqueda de materiales bibliográficos utilizando una arquitectura de micro-servicios para la Biblioteca Sighart Klauss de la Universidad Adventista de Bolivia.

#### 1.3.2 Objetivos específicos
-	Desarrollar el modelado actual y nuevo para gestión de materiales bibliográficos.
-	Diseñar e implementar micro-servicios para de gestión de materiales bibliográficos.
-	Diseñar e implementar micro-servicios que permitan agilizar e enriquecer las búsquedas de materiales bibliográficos.
-	Generar reportes de búsquedas de los materiales bibliográficos.

### 1.4 Justificación
#### 1.4.1 Justificación técnica
La arquitectura de micro-servicios permitirá una mejor distribución de carga de trabajo en los diferentes componentes que se implementara en la construcción de sistema, teniendo vistas y módulos especialistas para cada funcionalidad del sistema que tiene la biblioteca Sigart Klauss.

El hecho de desarrollo de una API (Application Programming Interface) para la administración y persistencia de datos, permitirá al sistema, la integración de subsistemas o en última instancia ser reemplazada por uno nuevo sin afectar la funcionalidad de gestión, búsqueda o sistemas integrados.

El desarrollo de los subsistemas de administración y de búsqueda de forma separada será posible, se podrá mejorar la experiencia de usuario en las búsquedas de forma independiente y de acuerdo al diseño propuesto por la UAB, o a las tendencias actual.
A la vez permitirá una mejor integración con los diferentes sistemas de la UAB sin importar el lenguaje de programación en las que se haya escrito o qué modelo de trabajo se utilizan.

Respecto a la escalabilidad para futuras implementaciones y mejoras, el sistema está abierto a una perspectiva más amplia.

### 1.4.2 Justificación social
El sistema actual ya no cuenta con soporte técnico desde varios años atrás y no se puede garantizar el correcto funcionamiento del sistema a largo plazo.

Con la ayuda de un nuevo sistema desarrollado de acuerda a las necesidades y exigencias actuales, Los administradores y lectores tendrán menos problemas que enfrentar a la hora de gestionar los materiales bibliográficos, ofreciendo eficiencia y garantizando la integridad de los datos.

Además, se incluirá mejoras en el buscador incrementando el alcance con búsquedas por palabras y caracteres. El estado de los libros se reflejará en el resultado de una búsqueda evitándonos realizar una reservación a un libro previamente prestado o con un estado neutral.

La migración de base de datos del sistema actual atreves de la API es una funcionalidad muy valioso como parte de la integración al nuevo sistema esta maniobra ayudará a los administradores a no tener que realizar la importación de los materiales bibliográficos nuevamente, a la vez esta implementación garantizara que los datos migrados funcionen correctamente en el nuevo sistema.

### 1.5  Límites y Alcances
#### 1.5.1 Límites
-	El sistema no ayudará en la clasificación y el conteo de número de inventario en los materiales bibliográficos.
-	El sistema no permitirá el almacenamiento de recursos multimedia a excepción de las imágenes de portada de los libros y periódicos.
-	El sistema no ayudará en el cálculo de multas por retrasos en devoluciones de los materiales bibliográficos.
-	La integración con el sistema académico está condicionada a la implementación del módulo de integración por parte de sus administradores.
-	El Módulo de autenticación contempla dos roles Súper administrador y Administrar

##### 1.5.2 Alcances
-	Desarrollar una API para la gestión, búsqueda y persistencia los materiales bibliográficos.
-	Definir una interfaz (API) para la integración con el sistema académico.
-	Desarrollar un subsistema WEB para la administración visual de los materiales bibliográficos.
-	Desarrollar un subsistema WEB para la gestión de búsquedas y reservas.
-	Desarrollar un subsistema ANDROID para facilitar la gestión de préstamos y el control de los inventarios.

### 1.6 Estudio de factibilidad
#### 1.6.1	Factibilidad técnica
Los requerimientos para la gestión, búsqueda y préstamos del sistema de la biblioteca Sighart Klauss son los siguientes:

|Nombre |	Requerimiento |	Hardware o Software |
|-------|---------------|---------------------|
| Sistema operativo |	Windows Server 2012 |	Software |
| Lenguaje de programación | C# .NET Framework 4.6.2 | Software |
| Base de datos |	SQL server 2016 Express edition |	Software |
| Procesador |	Intel® Core™ i3-6300 Processor (4M Cache, 3.80 GHz) | Hardware |
| Memoria RAM	 |8 Gb. RAM |	Hardware |
_**Fuente:** [Elaboración propia]_

El requerimiento cumple las expectativas para el buen funcionamiento del sistema, y las tecnologías fueron seleccionadas de acuerdo a un convenio con la universidad ya que cuenta con las licencias correspondientes para el correcto despliegue y publicación del sistema. Por lo tanto la propuesta se considera factible.

#### 1.6.2	Factibilidad operacional
Los sistemas web en la actualidad se volvieron populares y la gran parte del personal se encuentra capacitado para el manejo de una computadora personal (PC) y la navegación en internet. Al estar el proyecto basado en un entorno de trabajo moderno la experiencia de usuario serán mucho más efectivas.

Con la ayuda de los administradores se llegó a un acuerdo de trabajo mutuo, en la gestión de requerimientos para evitar malos entendidos a la hora de entrega el proyecto final.

También podemos destacar que el sistema actual cuenta con varios fallos a hora de gestionar los materiales bibliográficos, y este sistema es inviable a mediano y largo plazo por falta de soporte técnico.
