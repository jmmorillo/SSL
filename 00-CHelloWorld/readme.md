# TP 0

## Contenido del TP

En este directorio tenemos un programita en C que se llama ``hola``. También anunciamos la versión del compilador y la version de C que compila.

Vamos a escribir en MINGW:

```
gcc --version
```
Con esto obtenemos la versión del compilador.

``
gcc.exe (Rev10, Built by MSYS2 project) 12.2.0
Copyright (C) 2022 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
``

 Ahora vamos a ejecutar nuestro archivo ``hola.c`` en la consola ingresando lo siguiente:
```
./hola.exe
```
Y obtendremos:

``
Hola mundo!
``

Para que la salida no se vea por pantalla si no que se exporte en un archivo de texto, ponemos en la consola:
```
./hola.exe > salida.txt
```
Automáticamente encontraremos en el repo nuestro archivo de texto. Al abrirlo podremos ver que su contenido es: ``Hola mundo!``
