# Términos y Condiciones del sistema "lagash" y sub-sistemas

esta licencia es una extensión de la licencia [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.html)

Podemos cambiar los Términos y Condiciones de vez en cuando, en cualquier momento sin ninguna notificación. AL USAR EL SISTEMA, USTED ACEPTA Y ESTÉ ACUERDO CON ESTOS TÉRMINOS Y CONDICIONES EN LO QUE SE REFIERE A SU USO DEL SISTEMA "LAGASH"

**Lagash:** Nombre del proyecto en etapa de desarrollo

**Sighart Klauss:** Cliente a medida del proyecto Lagash

## Desarrollo
### 1 Código fuente
- El código fuente se aloja en github en las siguientes direcciones:

    https://github.com/wolf-mtwo/lagash-client-admin
    
    https://github.com/wolf-mtwo/lagash-server
    
    https://github.com/wolf-mtwo/lagash-documentacion
  
de forma pública y permanente. todos los proyectos y clientes web o móviles.

### 2 Mantenimiento
Para no correr riesgo con sorpresas de funcionalidad desconocida y estar consciente de nuevos cambios
- El soporte y mantenimiento solo se dará al código fuente que esta alojado en los links que se expone en la primera clausula de este documento (1 Código fuente).

# Términos y Condiciones con la biblioteca "Sighart Klauss" - FASE 1

### 3 Soporte
- Se dara soporte hasta que el pabellón de tesis funcione.
- La funcionalidad estará limitada a lo que se defina en los mock-ups (Revisar los mock-ups del proyecto lagash-documentacion).

### 4 Migración
La migración de datos no garantizara el correcto funcionamiento de sistema resultante.
  - Se hará la migración solo de los datos más relevantes y que tengan sentido. de otra manera sus valores serán nulos o cero.

### 5 Funcionalidad
- Se garantizara la implementación de las funcionalidades que actualmente tiene el sistema, si solo si están en uso (revisar 3 soporte).
- El siguiente mapa muestra la relación funcionalidad/estado al concluir la primera fase:

| FUNCIONALIDAD           | ESTADO |
|-------------------------|--------|
| gestión de libros       | si |
| gestión de tesis        | si |
| gestión de revistas     | si |
| gestión de periódicos   | si |
| catalogo de libros      | si |
| catalogo de tesis       | si |
| catalogo de revistas    | si |
| catalogo de periódicos  | si |
| préstamo de libros      | si |
| préstamo de tesis       | si |
| préstamo de revistas    | si |
| préstamo de periódicos  | si |
| búsqueda de libros      | si |
| búsqueda de tesis       | si |
| búsqueda de revistas    | si |
| búsqueda de periódicos  | si |

### 5 Puesta en producción (producción: el lugar final donde se alojara el sistema)
- No se añadirá ninguna regla de generación de backups.
- No se añadirá ninguna regla de backups para los medias (imágenes, etc)
- No nos hacemos responsables de la perdida de la base de datos.
- No nos hacemos responsables de la perdida de las medias.
- El cliente deberá otorgar un servidor en condiciones para tener el sistema activo
- No se desarrollada ningún trabajo de CI/CD (Integración continua / Entrega contenía)
- Nos limitaremos solo a la puesta en marcha el sistema.

### 5 Conclusiones
- Se dará alta prioridad de tener un nuevo sistema funcionando en las áreas de administración y búsqueda
- La tesis del proyecto no es una guía, ni una extensión de este documento
- El soporte termina una vez que la fase 1 se dé por concluido
