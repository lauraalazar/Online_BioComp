## Scripts Ejecutables

Ahora que ya estamos un poco familiarizados con la línea de comando, vamos a utilizar algunas herramientas básicas de programación: al digitar un comando, este da una instrucción para recibir una inofrmación. Este proceso se puede **automatizar** (por ejemplo mover, renombrar y copiar archivos), escribiendo el comando en un **script**. 

Los scripts son la forma mas simple de escribir un programa. Vamos a escribir un **script bash** y a ejecutarlo.

Dentro del directorio ``biocomp_clase1`` vamos a crear un nuevo archivo llamado ``miscript.sh``. Puedes hacer esto utilizando un  editor de texto de terminal llamado ``nano``

```
nano miscript.sh
```

Este comando inicia el editor de texto. A continuación escriba ``echo Hello World!``. "Hello World!" es una frase icónica en programación y "echo" es una instrucción que reproduce el texto que sigue. Guarde el archivo usando ``[ctrl-o] [enter]``  y cierre el programa con ``[ctrl-x]``. En la terminal, ejecute el script con el siguiente comando:

```
bash miscript.sh
```

**Bash** es un "interpretador" que lee el archivo y entiende cómo ejecutar el comando.

