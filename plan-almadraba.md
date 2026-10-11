# Plan Almadraba

## Urgencias del caso

El caso tiene dos urgencias claras: el registro del cortafuegos podría sobrescribirse en aproximadamente una semana y los equipos activos pueden contener datos volátiles. También hay que pedir cuanto antes la conservación de información a terceros, como Bahía Sistemas y la administración del edificio.

## 1. Las fuentes de evidencia
-----
### En el puesto de Marta

- El portátil de la empresa puede contener el render, archivos recientes, historial de actividad, documentos y rastros de posibles copias o transferencias. Puntos 6 (NIST SP 800-86 §3.1.1) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- Memoria RAM y registros del portátil: como está encendido y bloqueado, puede haber información volátil que se pierda si se apaga o reinicia. Puntos 9 (RFC 3227 §2.1 y §2.2) y 14 (RFC 3227 §2.1).
- Hay que comprobar qué dispositivos están conectados y si alguno puede almacenar datos. Puntos 6 (NIST SP 800-86 §3.1.1) y 7 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1)
- El disco externo puede contener copias de proyectos o archivos transferidos. Puntos 6 (NIST SP 800-86 §3.1.1), 8 (NIST SP 800-86 §3.1.1) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- El iPhone de empresa puede contener conversaciones de WhatsApp con clientes, archivos y otros datos relacionados con el proyecto. Puntos 6 (NIST SP 800-86 §3.1.1), 8 (NIST SP 800-86 §3.1.1) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).

### En otros puestos

- El pendrive de Javier que dice que le prestó a Marta podría contener archivos relacionados con la actividad del día 14. Puntos 8 (NIST SP 800-86 §3.1.1) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- Sobremesa compartido de la entrada: la sesión de Outlook web abierta pertenece a otra compañera. Podría aportar información, pero hay que proteger su privacidad y evitar alterar la sesión. Puntos 1, 7 y 13
- Impresora multifunción: conserva un historial de trabajos de impresión y escaneo que podría relacionarse con documentos del proyecto. Puntos 8 y 13

### En la empresa y servicios externos

- Servidor de ficheros: almacena los documentos de los proyectos. Puntos 8 (NIST SP 800-86 §3.1.1) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- OneDrive: puede contener archivos sincronizados, versiones y actividad relacionada con los documentos. Puntos 8 (NIST SP 800-86 §3.1.1) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- Cortafuegos: sus registros de conexiones pueden ayudar a reconstruir lo ocurrido, pero se sobrescriben aproximadamente cada semana. Puntos 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1), 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1) y 15 (NIST SP 800-86 §3.1.2).
- NAS de copias de seguridad: conserva las últimas catorce copias nocturnas, que podrían permitir comparar versiones de los archivos. Puntos 8 (NIST SP 800-86 §3.1.1), 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1) y 15 (NIST SP 800-86 §3.1.2).
- Portal de Microsoft: puede ser necesario solicitar las claves de recuperación de BitLocker para acceder al contenido del portátil si está cifrado. Puntos 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1) y 19 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- VPN y sistemas gestionados por Bahía Sistemas: podrían existir registros de conexiones remotas, accesos y actividad de mantenimiento. Puntos 8 (NIST SP 800-86 §3.1.1), 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- Correo electrónico y servicios de comunicación: además de WhatsApp, podrían existir mensajes o archivos enviados por correo relacionados con el render. Puntos 8 (NIST SP 800-86 §3.1.1) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).

### Fuera de la oficina

- Cámara del pasillo y grabador de conserjería: la administración del edificio podría conservar imágenes de las entradas y salidas, especialmente del día 14. Hay que pedir que se preserven cuanto antes porque podrían borrarse automáticamente. Puntos 8 (NIST SP 800-86 §3.1.1), 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1), 15 (NIST SP 800-86 §3.1.2) y 19 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).

## 2. La prioridad
-----

- Memoria RAM y actividad del portátil de Marta. El portátil está encendido y bloqueado. Si se apaga o reinicia, pueden perderse datos volátiles, como procesos activos, conexiones de red y sesiones abiertas. Antes de actuar, hay que valorar cómo preservar esa información sin alterar innecesariamente el equipo. Puntos 9 (RFC 3227 §2.1 y §2.2), 14 (RFC 3227 §2.1), 16 (RFC 3227 §2.1 y §2.2, y ENFSI §9.2) y 17 (RFC 3227 §2.1 y §3.2, y NIST SP 800-86 §3.1.2).
- Grabaciones de la cámara del pasillo. Debemos contactar cuanto antes con la administración del edificio para que conserve las imágenes del día 14. No sabemos cuánto tiempo se guardan, por lo que podrían desaparecer antes de que podamos solicitarlas formalmente. Puntos 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1), 15 (NIST SP 800-86 §3.1.2) y 19 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- Registros del cortafuegos. Son muy urgentes porque el técnico de Bahía Sistemas ha indicado que se sobrescriben aproximadamente cada semana. Hay que solicitar que se conserven inmediatamente los registros disponibles, especialmente los del día 14 y los días cercanos al incidente. Puntos 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1), 14 (RFC 3227 §2.1) y 15 (NIST SP 800-86 §3.1.2).
- Registros de VPN y otros registros de Bahía Sistemas. Hay que preguntar qué registros existen, cuánto tiempo se conservan y solicitar su preservación antes de que caduquen o se sobrescriban. Puntos 8 (NIST SP 800-86 §3.1.1), 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1) y 15 (NIST SP 800-86 §3.1.2).
- Historial de la impresora multifunción. No sabemos cuánto tiempo conserva los trabajos de impresión y escaneo. Conviene pedir que no se borre el historial y comprobar si hay trabajos relacionados con el proyecto. Puntos 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1), 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1) y 15 (NIST SP 800-86 §3.1.2).
- Sesiones y datos de servicios en línea. Hay que preservar cuanto antes los registros pertinentes de Microsoft 365, OneDrive, correo y otros servicios que se identifiquen. Algunos datos pueden tener periodos de retención limitados. No debemos cerrar sesiones ni modificar cuentas sin valorar antes las consecuencias. Puntos 1 (RFC 3227 §2.3 y §2.4), 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1), 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1) y 16 (RFC 3227 §2.1 y §2.2, y ENFSI §9.2).
- Pendrive de Javier. Es importante obtenerlo y preservarlo pronto, porque pudo utilizarse durante el periodo relevante. Hay que pedir a Javier que no lo conecte ni modifique su contenido hasta que se pueda recoger adecuadamente. Puntos 8 (NIST SP 800-86 §3.1.1), 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1), 16 (RFC 3227 §2.1 y §2.2, y ENFSI §9.2) y 20 (RFC 3227 §3.2 y §4.1).
- Portátil de Marta, disco externo e iPhone de empresa. Hay que preservar estos dispositivos y planificar su adquisición. El disco externo puede contener copias del render y el móvil, conversaciones o archivos. En el portátil, además, hay que tener en cuenta BitLocker y conseguir las claves de recuperación por el procedimiento autorizado. Puntos 6 (NIST SP 800-86 §3.1.1), 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1), 16 (RFC 3227 §2.1 y §2.2, y ENFSI §9.2), 18 (RFC 3227 §2 y §2.2) y 20 (RFC 3227 §3.2 y §4.1).
- Servidor de ficheros y NAS de copias de seguridad. Conviene protegerlos antes de que nuevas modificaciones o ciclos de copia alteren el estado de los datos. Las copias nocturnas pueden ayudar a comparar versiones y determinar cuándo apareció o cambió un archivo. Puntos 8 (NIST SP 800-86 §3.1.1), 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1), 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1) y 15 (NIST SP 800-86 §3.1.2).
- Sobremesa compartido de la entrada. Debe documentarse la sesión de Outlook abierta y evitar que alguien la cierre o la utilice antes de valorar qué hacer. Como pertenece a otra compañera, hay que limitar cualquier actuación a lo autorizado. Puntos 1 (RFC 3227 §2.3 y §2.4), 7 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1), 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1) y 16 (RFC 3227 §2.1 y §2.2, y ENFSI §9.2).

## 3. Las medidas inmediatas
-----

- Registros del cortafuegos. Contactaría con Bahía Sistemas para solicitar que exporten y conserven los registros disponibles, especialmente los correspondientes al día 14 y a los días cercanos. También pediría que indiquen cuánto tiempo se conservan y cómo se pueden obtener sin modificarlos. Puntos 8 (NIST SP 800-86 §3.1.1), 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1) y 20 (RFC 3227 §3.2 y §4.1).

- Portátil de Marta y memoria RAM. Fotografiaría su estado y anotaría que está encendido y bloqueado, así como los dispositivos conectados. No lo apagaría, reiniciaría ni desconectaría del dock sin valorar antes cómo capturar los datos volátiles. La adquisición de la memoria debe realizarla personal preparado, utilizando herramientas adecuadas y documentando cualquier cambio que provoque. Puntos 3 (ENFSI §8.2), 9 (RFC 3227 §2.1 y §2.2), 10 (RFC 3227 §2.2 y ENFSI §9.2) y 16 (RFC 3227 §2.1 y §2.2, y ENFSI §9.2).

- Historial de la impresora multifunción. Pediría que no se borre ni se reinicie el historial de trabajos. Solicitaría a la persona responsable que conserve los registros existentes y que informe sobre su periodo de retención. Puntos 8 (NIST SP 800-86 §3.1.1), 11 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1) y 20 (RFC 3227 §3.2 y §4.1).

- Microsoft 365, OneDrive y correo electrónico. Solicitaría a Bahía Sistemas o al administrador correspondiente que preserve los registros de actividad y las versiones de archivos relevantes. Antes de acceder a cuentas o cerrar sesiones, documentaría su estado y comprobaría qué actuaciones están autorizadas. Puntos 8 (NIST SP 800-86 §3.1.1), 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1) y 18 (RFC 3227 §2 y §2.2).

- Disco externo de 2 TB e iPhone de empresa. Documentaría su estado y sus conexiones. Evitaría desconectarlos o manipularlos sin planificar antes su adquisición, ya que podría perderse información o modificarse su contenido. Para el móvil, tendría en cuenta que las medidas de aislamiento pueden afectar a los datos o servicios y deben decidirse según el riesgo. Puntos 3 (ENFSI §8.2), 10 (RFC 3227 §2.2 y ENFSI §9.2), 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1) y 16 (RFC 3227 §2.1 y §2.2, y ENFSI §9.2).

- Servidor de ficheros y NAS de copias de seguridad. Pediría a Bahía Sistemas que evite las operaciones de limpieza o cambios innecesarios que puedan afectar a los datos relevantes. Identificaría las copias nocturnas disponibles y solicitaría que se preserven las versiones necesarias antes de que sean sustituidas por nuevas copias. Puntos 8 (NIST SP 800-86 §3.1.1), 17 (RFC 3227 §2.1 y §3.2, y NIST SP 800-86 §3.1.2) y 20 (RFC 3227 §3.2 y §4.1).

- Documentación de todas las actuaciones. Durante todo el proceso anotaría las horas, las personas que intervienen, las decisiones tomadas, los dispositivos recogidos y cualquier modificación producida. Cuando se adquieran los datos, utilizaría hashes u otras comprobaciones de integridad cuando corresponda y mantendría la cadena de custodia. Puntos 12 (RFC 3227 §2) y 20 (RFC 3227 §3.2 y §4.1).

## 4. Los límites
-----

- **Móvil personal de Marta**. No deberíamos revisar su contenido ni incautarlo automáticamente sin una autorización que permita examinarlo y aclare a qué partes del dispositivo podemos acceder. Puntos 1 (RFC 3227 §2.3 y §2.4) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- **Cuenta de Outlook abierta en el ordenador compartido**. La sesión pertenece a otro empleado, por lo que no debemos abrir correos, buscar mensajes ni utilizar la cuenta como si tuviéramos permiso para hacerlo. Podemos documentar que la sesión estaba abierta. Puntos 1 (RFC 3227 §2.3 y §2.4), 7 (RFC 3227 §2.1 y NIST SP 800-86 §3.1.1) y 16 (RFC 3227 §2.1 y §2.2, y ENFSI §9.2).
- **Sistemas de la empresa y servicios en la nube**. Hay que comprobar el alcance de la autorización que Elena ha firmado porque la información personal o ajena al incidente debe quedar fuera del examen. Puntos 1 (RFC 3227 §2.3 y §2.4) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- **USB de Javier**. El USB puede contener información relevante porque Marta lo utilizó durante la semana del incidente, pero al pertenecer a Javier y poder incluir archivos personales, debemos justificar su adquisición y limitar el análisis a los datos pertinentes. Le podemos pedir que no lo conecte, borre ni modifique. Documentarlo y acordar su entrega para realizar una adquisición forense. Puntos 1 (RFC 3227 §2.3 y §2.4), 8 (NIST SP 800-86 §3.1.1) y 13 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).
- **Cámara del edificio**. La cámara y su grabador están bajo el control de la comunidad del edificio, por lo tanto, no podemos acceder por nuestra cuenta al grabador ni dar por hecho que tenemos permiso para examinar todo su contenido. Puntos 1 (RFC 3227 §2.3 y §2.4), 8 (NIST SP 800-86 §3.1.1) y 19 (RFC 3227 §3.2 y NIST SP 800-86 §3.1.1).