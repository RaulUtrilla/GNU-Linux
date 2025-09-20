# GNU-Linux
Apuntes de GNU/Linux

COMANDOS

ls:
Sirve para mostrar los archivos del repositorio 
se puede escribir con la flag -lrt para obtener informacion adicional

drwxr-xr-x 2 jdg jdg 4096 oct 1 20:44 Vídeos

d rwx r-x r-x
  |   |   |
  |   |   +--> Otros usuarios
  |   +------ Grupo
  +---------- Propietario

-Letras:
d → indica que es un directorio (si fuera -, sería un archivo normal).

rwx → permisos del propietario (lectura r, escritura w, ejecución x). Aquí rwx significa que el dueño puede leer, escribir y entrar en la carpeta.

r-x → permisos del grupo al que pertenece el archivo: r → leer, - → no escribir, x → ejecutar/entrar en la carpeta.

r-x → permisos de otros usuarios (igual que grupo).

-Número: 2 Es el número de enlaces físicos.
Para carpetas, indica cuántos directorios apuntan a esta carpeta (incluye ella misma y subdirectorios “.” y “..”).

-Propietario y grupo: jdg jdg
El primer jdg → nombre del usuario dueño del archivo.
El segundo jdg → nombre del grupo al que pertenece.

-Tamaño: 4096
Tamaño en bytes.
Para carpetas, Linux suele mostrar 4096 por defecto, que es el tamaño del bloque que ocupa la carpeta en el sistema de archivos, no el tamaño de los archivos dentro.

-Fecha y hora: oct 1 20:44
Fecha y hora de última modificación del archivo o carpeta.

-Nombre: Vídeos
Es el nombre del archivo o carpeta.

-Resumen rápido de la línea:
Es un directorio llamado Vídeos, propiedad del usuario jdg y del grupo jdg, con permisos de lectura/escritura/ejecución para el dueño y lectura/ejecución para grupo y otros. Tiene 2 enlaces, ocupa 4096 bytes y fue modificado por última vez el 1 de octubre a las 20:44.