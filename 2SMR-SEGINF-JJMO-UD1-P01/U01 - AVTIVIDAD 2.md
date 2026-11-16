# Actividad 2 - Clasificación de medidas de seguridad física/lógica y activa/pasiva

*OBJETIVO* 

Clasificar correctamente un conjunto de medidas de seguridad según el elemento que protegen (física o lógica) y según el momento en que actúan (activa o pasiva), incluyendo medidas de disponibilidad como el SAI o la redundancia de discos.

*CONTEXTO DE LA SITUACIÓN* 

El departamento de sistemas de una empresa ha enumerado las siguientes medidas de seguridad implantadas en su sala de servidores y en los equipos de usuario. Debes clasificar cada una según los dos ejes trabajados en clase.

---
## TAREAS
Para cada medida, indica:

* Si es seguridad física o lógica.
* Si es de seguridad activa o pasiva.
* Una frase que justifique ambas clasificaciones.

Medidas que clasificar: 
1. Extintor automático en la sala de servidores.\
\
.
**Física**: Se debe por la acción de cumple ante la adversidad. (Apagar el fuego) \
.**Pasiva**: Se activa automáticamente cuando detecta la adversidad y minimice los daños causados.

2. Política de contraseñas con caducidad cada 60 días. \
**Lógica**: Es el descrito sobre como ha de generar una contraseña correcta sobre la entidad y es aplicado desde un apartado web de la entidad.

**Activa**: Se actualiza manualmente una vez pasado los 60 días.

3. Sistema de Alimentción interrumpida (SAI) en el ervidor principal.\
\
**Física**: Es un elemento físico que protege la vida útil de los equipos instalados ante caídas o subídas de alta tensión.

**Pasiva**: Minimiza los posibles daños por la caída.

4. Corafuegos (Firewall) instalado en el perímetro de la red.

**Lógica**: Se limita a establecer conexiones con otras redes. Esto se lleva acabo internamente en la red.

**Activa** : Previene posibles conflictos con otras redes.

5. Sistema de discos redudantes (RAID) en el servidor de archivos.\
\
**Físico**: Elemnto físico que permite el aumento de capacidad de almacenamiento de la entidad.

**Activo**: Evita que se produzcan indultos o modificaciones de toda la información al tenerlo alojados en una ubicación no conocida para el personal y sí conocida para los especialistas de estos servidores.

6. Control de acceso con tarjeta a la sala de servidores.\
\
**Físico**: Elemento físico unicamente preparado para aquellos agentes directamente relacionados con la entidad.

**Activo**: Evita por completo que no puedan acceder terceros (Quienes no tienen ninguna relación con al entidad)

7. Copia de seguridad semanal de los datos de clientes.\
\
**Lógica**: Se establece una programación para mantener a salvo la información semanalmente.

**Activa**: Se evita que la información no se pierda por completo en caso de secuestro o pérdidas.
   
1. Antivirus actualizado en todos los equipos.\
\
**Lógica**: Herramienta instalada en nuestro sistema para evitar ataques maliciosos.

**Activo**: Evita que podamos sufrir diferentes ataques de malware en el equipo.