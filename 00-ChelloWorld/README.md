Chequeamos la versión del compilador por consola:
```
gcc --version
```
Salida:

``
gcc.exe (Rev3, Built by MSYS2 project) 13.2.0
Copyright (C) 2023 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
``

Ejecutamos ``hello.c`` en consola:
```
./hello.exe
```
Obtendremos:

``
Hola Juan Manuel Morillo!
``

Rediccionamos la salida a un archivo de texto:
```
./hello.exe > output.txt
```
Encontraremos en el repositorio ```output.txt```. Al abrirlo podremos ver que su contenido es: ``Hola Juan Manuel Morillo!``
