Software Design Document [SDD] Rocketbot

1- Introducción.
* Nombre del proyecto : Ejercicio 1 - Extracción de datos de un e-commerce.
* Autor: Jorge Ferreyra
* Fecha de versión: 2025.0
* Número de versión: v1

2- Objetivo.
Este documento describe la arquitectura y el diseño del proceso RPA desarrollado en Rocketbot,
incluyendo flujos, módulos y configuraciones utilizadas.

3- Descripción.
Este bot automatiza la busqueda, extracción y guardado de la descripcion de 5 productos de una pagina web.

4- Sistema
Windows 10.
Chrome.
Rocketbot versión v.2025.01.17

5- Diagrama de flujo:

![Diagram 2025-03-10 13-05-53](https://github.com/user-attachments/assets/84bd4552-2eb0-4852-ba72-0ec872a9cc73)

6 Descripción de paso a paso del proceso:
Inicio:
* Abrir la webpage de megatone.net en el navegador "Chrome" y
* Esperar 10 seg la carga de la webpage
Procesamiento:
* Implementamos un condicional if-else que evalua la carga de la webpage
* Si la carga fue True, se sigue con el flujo del bot, posicionando el cursor en el input de busqueda.
* Carga el texto ingresado por variable a buscar, dentro del input.
* Ejecuta el Enter para realizar la busqueda del texto ingresado por variable-

Salida:
* Implementamos un bucle while ( contador <= 5) para recorrer el elemento seleccionado de la pagina web.
*  Extraemos los elementos establecidos en el ciclo.
*  guardamos los elementos en un archivo txt. (texto.txt)

Final:
* Mensaje final (mensaje_final)
* Cerrar el navegador.

7- Variables:
* carga_ok = True
* texto=
* contador = 6
* mensaje_final = El bot se ejecutó satisfactoriamente, Fin.


  
