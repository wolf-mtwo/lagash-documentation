# LAGASH DOCUMENTACION

- CAPÍTULO 1
  - EL PROBLEMA
  - 1.1 Antecedentes
  - 1.2 Problema
    - 1.2.1 Situación problemática
    - 1.2.2 Formulación del problema
  - 1.3 Objetivos
    - 1.3.1 Objetivo general
    - 1.3.2 Objetivos específicos
  - 1.4 Justificación
    - 1.4.1 Justificación técnica
    - 1.4.2 Justificación social
  - 1.5 Límites y Alcances
    - 1.5.1 Límites
    - 1.5.2 Alcances
  - 1.6 Estudio de factibilidad
    - 1.6.1	Factibilidad técnica
    - 1.6.2	Factibilidad operacional

- CAPÍTULO 2
  - MARCO TEÓRICO
  - 2.1 Modelo de negocio
    - 2.1.1 Modelo de negocio actual
    - 2.1.2 Modelo de negocio alternativo
    - 2.1.3 Diseño del modelo de negocio
  - 2.2 Ingeniería de Software
    - 2.2.1 Metodologías de desarrollo de software
    - 2.2.2 Metodologías de desarrollo ágil
      - a) Programación Extrema (XP)
      - b) SCRUM
    - 2.2.3 Selección de la metodología de desarrollo
  - 2.3 Arquitectura de software
    - 2.3.1 Comparaciones
      - 2.3.2.1 Front-end y back-end
      - 2.3.2.2 Aplicación de una sola página (SPA)
      - 2.3.2.3 Back-end para Front-end (BFF)
    - 2.3.2 Arquitectura orientada a Servicios (SOA)
    - 2.3.3 Arquitectura multi/N capas (MLA)
    - 2.3.4 Arquitectura de Microservicios (MSA)
    - 2.3.5 Justificación de la arquitectura
  - 2.4 Aplicaciones web
    - 2.4.1 Arquitectura Cliente/Servidor
    - 2.4.2 Servicios web
      - 2.4.2.1 Justificación del servicio web e intercambio de datos
      - 2.4.2.2 SOAP (Simple Objet Access Protocol)
      - 2.4.2.3 REST (Representational State Transfer)
    - 2.4.3 Intercambio de datos
      - 2.4.3.1 Lenguaje de marcado extensible (XML)
      - 2.4.3.2 Notación de objetos de JavaScript (JSON)
  - 2.5 Tipos de aplicaciones móviles
    - 2.5.1 Aplicaciones nativas
    - 2.5.2 Aplicaciones web móviles
    - 2.5.3 Aplicaciones híbridas
    - 2.5.4 Elección de la aplicación móvil
  - 2.6 Indexación unica
    - 2.6.1 Identificador único universal UUID
    - 2.6.2 Códigos de respuesta rápida QR
  - 2.7 Lenguajes de programación
    - 2.7.1 C Sharp (C#)
    - 2.7.2 Java
    - 2.7.3 JavaScript
    - 2.7.4 Conclusión
    - 2.7.5 Elección del lenguaje de programación
  - 2.8 Calidad del software
    - 2.8.1 Pruebas unitarias
    - 2.8.2 Usabilidad
    - 2.8.3 Seguridad del sistema

- CAPÍTULO 3
  - MARCO PRÁCTICO
  - 3.1 Diseño de la arquitectura
    - 3.1.1 diagrama de componentes
  - 3.1 Diseño del modelo actual
  - 3.2 Diseño del modelo alternativo
    - 3.2.1 Adopción de la metodológica
    - 3.2.2 Planificación de iteraciones
    - 3.2.3 Cronograma de iteraciones
  - 3.3 Desarrollo de los micro-servicios
    - 3.3.1 Desarrollo de micro-servicios para administrar usuarios y la autenticación del sistema
      - 3.3.1.1 Iteración 1: Gestión de registro de usuarios
        - 3.3.1.1.1 Planificación y diseño
        - 3.3.1.1.2 Codificación
        - 3.3.1.1.3 Pruebas de integración
      - 3.3.1.2 Iteración 2: Autenticación
        - 3.3.1.2.1 Planificación y diseño
        - 3.3.1.2.2 Codificación
        - 3.3.1.2.3 Pruebas de integración
    - 3.3.2 Desarrollo de micro-servicios para administrar materiales bibliográficos
      - 3.3.2.1 Iteración 3: Gestión de registro de libros
        - 3.3.1.1.1 Planificación y diseño
        - 3.3.1.1.2 Codificación
        - 3.3.1.1.3 Pruebas de integración
      - 3.3.2.2 Iteración 4: Gestión de registro de tesis
        - 3.3.1.2.1 Planificación y diseño
        - 3.3.1.2.2 Codificación
        - 3.3.1.2.3 Pruebas de integración
      - 3.3.2.3 Iteración 5: Gestión de registro de revistas
        - 3.3.1.3.1 Planificación y diseño
        - 3.3.1.3.2 Codificación
        - 3.3.1.3.3 Pruebas de integración
  - 3.4 Iteración 6: Desarrollo de subsistema para administrar materiales bibliográficos
    - 3.4.1 Planificación y diseño
    - 3.4.2 Codificación
    - 3.4.3 Pruebas de integración
  - 3.5 Iteración 7: Desarrollo de subsistema de búsqueda
    - 3.5.1 Planificación y diseño
    - 3.5.2 Codificación
    - 3.5.3 Pruebas de integración

 - CONCLUSIONES
 - RECOMENDACIONES
 - REFERENCIAS BIBLIOGRÁFICAS
 - ANEXOS

# Requisitos basicos basicos

## Caracteristicas del servidor principal

| Nombre                   | Requerimiento                                        | Hardware o Software |
|--------------------------|------------------------------------------------------|---------------------|
| Sistema operativo        | Windows Server 2012                                  | Software            |
| Lenguaje de programación | C# .NET Framework 4.6.2                              | Software            |
| Base de datos            | SQL server 2016 Express edition                      |	Software            |
| Procesador               | Intel® Core™ i3-6300 Processor (4M Cache, 3.80 GHz)  | Hardware            |
| Memoria RAM	             | 8 Gb. RAM                                            |	Hardware            |

## Asignacion o actualizacion de los equipo de apoyo

| Componentes        | Posible ubicacion o proposito                                                            | Cantidad |
|--------------------|------------------------------------------------------------------------------------------|----------|
| PC - Buscador (i3) | replasar los buscadores existentes                                                       | 3        |
| MONITOR - Buscador | replasar los buscadores existentes (22 pulgadas para una mejor experiencia del usuario)  | 3        |
| PC                 | asignar un equipo para los encargados(as) de los pabellones                              | 3        |
| MONITOR            | asignar un equipo para los encargados(as) de los pabellones                              | 3        |
