# Lista de comprobación para investigación

----

## 1. Al llegar a la escena

1. Comprobar la autorización y los límites de la investigación. Tener claro qué equipos y datos se pueden examinar y respetar la privacidad. (RFC 3227 §2.3 y §2.4).

2. Preguntar qué ha ocurrido y qué se sabe del incidente. Averiguar cuándo se detectó, qué sistemas están afectados y qué acciones se han realizado hasta el momento. (RFC 3227 §3.2 y NIST SP 800-86 §3.1).

3. Fotografiar y anotar el estado inicial de la escena. Registrar dónde están los equipos, sus conexiones y si están encendidos, sin manipularlos todavía. (ENFSI §8.2).

4. Identificar a las personas presentes. Anotar quién ha utilizado o manipulado los equipos y qué información puede aportar sobre lo ocurrido. (RFC 3227 §3.2).

5. Preparar las herramientas necesarias. Comprobar que se dispone de herramientas fiables y medios adecuados para recoger los datos sin modificarlos innecesariamente. (RFC 3227 §2.2 y §5, y ENFSI §9.1).

-----

## 2. Antes de tocar nada

6. Hacer un inventario de los dispositivos. Incluir ordenadores, móviles, servidores, discos externos y cualquier otro dispositivo que pueda estar relacionado con el incidente. (NIST SP 800-86 §3.1.1).

7. Revisar las conexiones y los equipos conectados. Identificar routers, switches, puntos de acceso y otros sistemas que puedan contener información relevante. (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1).

8. Identificar fuentes de evidencia fuera del equipo principal. Comprobar si hay registros en servidores, servicios en la nube, aplicaciones, cortafuegos o copias de seguridad. (NIST SP 800-86 §3.1.1).

9. Comprobar qué sistemas están activos. Identificar el orden de volatilidad, es decir, prestar atención a las sesiones abiertas, los procesos, las conexiones de red y los posibles datos que desaparecerían al apagar el equipo. (RFC 3227 §2.1 y §2.2).

10. Valorar qué acciones podrían destruir o alterar pruebas. Antes de apagar, desconectar o aislar un equipo, considerar las consecuencias y si podría perderse información importante. (RFC 3227 §2.2 y ENFSI §9.2).

11. Identificar datos que puedan desaparecer por el paso del tiempo. Comprobar si existen registros que se sobrescriben, sistemas temporales o servicios externos con periodos limitados de conservación. (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1).

12. Anotar las condiciones relevantes de los sistemas. Registrar las horas que muestran los equipos, las diferencias horarias conocidas y cualquier circunstancia que pueda afectar a la interpretación de los datos. (RFC 3227 §2).

----

## 3. Al decidir qué se adquiere y en qué orden

13. Relacionar cada fuente con la información que puede aportar. Determinar qué datos se esperan encontrar y cómo pueden ayudar a explicar el incidente. (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).

14. Priorizar las pruebas según su volatilidad. Recoger primero la información que pueda desaparecer antes, como la memoria RAM, los procesos activos y las conexiones de red. (RFC 3227 §2.1).

15. Valorar la importancia de cada fuente y el esfuerzo necesario para obtenerla. No decidir el orden únicamente por la volatilidad, hay que tener en cuenta también la utilidad de los datos y las dificultades para adquirirlos. (NIST SP 800-86 §3.1.2).

16. Decidir cómo preservar los equipos activos. Valorar si es necesario capturar primero los datos volátiles y determinar cómo actuar sin perder información ni modificarla innecesariamente. (RFC 3227 §2.1 y §2.2, y ENFSI §9.2).

17. Planificar la adquisición de discos y registros persistentes. Una vez atendidos los datos más urgentes, decidir qué unidades, archivos, registros y copias de seguridad deben adquirirse. (RFC 3227 §2.1 y §3.2, y NIST SP 800-86 §3.1.2).

18. Decidir cómo evitar cambios externos en los sistemas. Valorar las medidas de contención necesarias y sus posibles efectos antes de ejecutarlas. (RFC 3227 §2 y §2.2).

19. Comprobar si falta alguna fuente de evidencia. Revisar el inventario y preguntarse si hay otros dispositivos, registros remotos o sistemas externos que puedan aportar información. (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).

20. Documentar la recogida y proteger la integridad de las pruebas. Anotar qué se ha recogido, cuándo, quién lo ha hecho y cómo se ha conservado. Utilizar comprobaciones de integridad y mantener la cadena de custodia. (RFC 3227 §3.2 y §4.1).