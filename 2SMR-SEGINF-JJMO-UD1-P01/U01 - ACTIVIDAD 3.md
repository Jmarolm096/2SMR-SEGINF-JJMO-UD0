# Actividad 3 - Análisis de un incidente de seguridad

*OBJETIVO* 

Aplicar correctamente la cadena causal activo → amenaza → vulnerabilidad → riesgo → ataque → impacto al análisis de un incidente de seguridad descrito mediante un caso.

*CONTEXTO DE LA SITUACIÓN* 

Una academia de formación online almacena en un servidor los datos personales y las calificaciones de su alumnado. El servidor ejecuta un sistema de gestión de contenidos (CMS) que lleva ocho meses sin actualizar, aunque __el fabricante publicó hace seis meses un parche que corrige un fallo de seguridad__ conocido y documentado con su correspondiente identificador CVE. __Un atacante externo localiza el servidor, comprueba que la versión del CMS es vulnerable__, __utiliza un exploit público para acceder sin autorización__ y descarga una copia completa de la base de datos de alumnado. Como consecuencia, la academia debe notificar la filtración a las familias afectadas y suspende temporalmente el acceso a la plataforma mientras investiga lo ocurrido.

---
## TAREAS
1. Identifica el activo o activos.

- El activo y del que no se aplica es el parche de dicho fabricante del sistema CMS. 

2. implicados en el incidente.

- Los implicados de los daños son la entidad, los familiares de os alumn@s y los propi@s alumn@s.

3. Identifica la amenaza.

- La amenaza es el ataque externo a la entidad.

4. Identifica la vulnerabilidad explotada.

- La vulnerabilidad de la situación está en el fallo de seguridad del sistema CMS.

5. Explica en qué consistía el riesgo antes de que el incidente se produjera.

- El riesgo está en la vulnerabilidad hábil sobre el atacante que puede aprovecharse de ello.

6. Describe en qué consistió el ataque.

- El atacante realizón una investigación sobre el centro pudiendo localizar el servidor, su versión, los ultimos relases del sistema y localizó la vulnerabilidad del sistema aprovechando un exploit público accediendo sin autorización.

7. Describe el impacto del incidente, distinguiendo si es de tipo cuantitativo, cualitativo o ambos.

- Cuantitativamente, el impacto es mayor sobre tantas credecniales registradas en el centro. Contando a todo el personal, alumnados y sus familiares.

- Caulitativamente, el impacto mayor es el cierre completo de la plataforma relacionada con el centro. Así a su vez, siendo responsable del centro, es el cierre físico del centro hasta que se investigue el ataque, su indulto y arrestén a dicho atacante. Como resultado a toda la espera necesaria, a que no llegue a producirse peores situaciones.

8. Indica qué tipo de vulnerabilidad era, según la clasificación por grado de conocimiento vista en clase (conocida sobre software instalado, conocida sobre software no instalado, o día cero), y justifica tu respuesta.

- **Conocida en software instalado**: Tenemos el conocimiento que el parche existe para dar con su solución.