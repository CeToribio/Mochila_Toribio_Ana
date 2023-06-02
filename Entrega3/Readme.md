# ACTIVIDAD INTRO CLASE 12


### ¿Que es un usuario root en Linux?

* Es una cuenta predeterminada que tiene privilegios de acceso a todos los ficheros y comandos del sistema. El usuario root Linux es el superusuario que más privilegios tiene en Linux.

### ¿Por qué ubuntu no me deja establecer la contraseña durante la instalación?

* No se pueden añadir contraseñas para la cuenta root. Hay algo llamado el mecanismo sudo para manejar eso. En su lugar, se añaden usuarios a la cuenta admin. Todos esos usuarios pueden entonces ejecutar comandos o programas como root ejecutando sudo command para los comandos de terminal o gksu command para que las aplicaciones GUI se ejecuten como root.

### ¿Cuáles son los procesos típicos de Linux?

* Podríamos definir a los procesos como programas que están corriendo en nuestro Sistema Operativo. Dependiendo de la forma en que corren estos programas en LINUX se los puede clasificar en tres grandes categorías:
    - Procesos Normales.
    - Procesos Daemon.
    - Procesos Zombie.

### ¿Cómo identificarlos?

Para identificar los procesos en Linux, puedes usar alguno de los siguientes comandos:

- ps: Este comando te muestra una lista de los procesos que están ejecutándose actualmente en el sistema. Por ejemplo, si usas el comando "ps aux", obtendrás una lista detallada de los procesos, incluyendo el usuario que los inició, su ID de proceso (PID) y su consumo de recursos.
- top: Este comando muestra un resumen de los procesos activos en tiempo real, con información sobre su uso de CPU, memoria y otros recursos.
- Htop: Es un comando similar a Top pero más visual y completo, permite además de ver los procesos en tiempo real, matar procesos, cambiar prioridades, entre otras opciones.
- pstree: Este comando muestra la jerarquía de los procesos en forma de árbol, lo que facilita la visualización de la relación entre los procesos y sus procesos hijos.
- lsof: Este comando te muestra los archivos que están siendo usados por diferentes procesos, lo que puede ser útil para depurar problemas de recursos y evitar conflictos.

### ¿Cómo establecer una contraseña para el usuario root.

1. Abre la Terminal (Control + Alt + T)
    Asegurarse  de estar autenticado como un usuario con privilegios de superusuario o utiliza el comando su para cambiar al usuario root.
2. Teclea (sin comillas) "sudo su"
3. Introduce tu clave actual
4. Teclea "passwd root" y escribe tu nueva clave
5. Pulsa enter y cierra la terminal
