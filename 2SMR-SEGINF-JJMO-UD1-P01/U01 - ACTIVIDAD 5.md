# Actividad 5 - Ordenar las fases de un test de intrusión
*OBJETIVO* 

Ordenar correctamente las fases de un test de intrusión (PenTest) a partir de un conjunto de acciones descritas de forma desordenada, y relacionar cada fase con sus herramientas típicas

*CONTEXTO DE LA SITUACIÓN* 

Una empresa de ciberseguridad ha sido contratada para realizar un test de intrusión autorizado sobre los servidores de un cliente. En su cuaderno de trabajo aparecen las siguientes anotaciones, mezcladas sin orden:

Anotación A: "Se ha utilizado Nmap para determinar qué puertos están abiertos y qué sistema operativo ejecuta el servidor."

Anotación B: "Se ha comprobado, mediante WHOIS y consultas DNS, el rango de direcciones públicas del cliente y la ubicación de sus servidores."

Anotación C: "Tras localizar un fallo documentado con identificador CVE en la versión del servicio web detectada, se ha configurado un exploit en Metasploit para confirmar si el fallo es explotable realmente."

Anotación D: "Se ha consultado una base de datos de vulnerabilidades para comprobar si la versión del servicio identificado tiene fallos conocidos."

Anotación E: "Se ha recomendado al cliente instalar la actualización del fabricante que corrige el fallo confirmado."
---
## TAREAS

1. Ordena las anotaciones A–E según la secuencia de fases de un test de intrusión vista en clase (de la primera a la última).

> **EL ORDEN ES**: B => A => D => C => E.

2. Indica el nombre de cada fase (footprinting, fingerprinting, búsqueda de vulnerabilidades, explotación, parcheo) junto a la anotación que le corresponde.

- Indico las fases de la siguiente forma:

   1. Anotación B: Footprinting.
   2. Anotación A: Fingerprinting.
   3. Anotación D: Busqueda de vulnerabilidades.
   4. Anotación C: Exploit.
   5. Anotación E: Parcheo y verificación.

1. Explica qué diferencia a este test de intrusión de un ataque malicioso real, a partir de un dato que debería figurar en el caso aunque no se mencione explícitamente.

