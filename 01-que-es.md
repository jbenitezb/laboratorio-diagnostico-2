# 1. Qué es el control de versiones y por qué se usa

Autor: Karina Sanchez Rosales

## 1.1 Definición

Un control de versiones es un sistema que guarda el historial de cambios relacionado a un proyecto, archivo o documento,
sirve para saber qué se modificó, quién lo hizo y cuándo, Si cometés un error, podés recuperar una versión anterior
también facilita que varias personas trabajen en el mismo proyecto y unan sus cambios

## 1.2 El método de las copias con fecha

Este método consiste en copiar toda la carpeta de un proyecto cada vez que se quiere guardar una versión y agregarle la
fecha al nombre, por ejemplo: proyecto_2026-09-30. Así se conservan versiones anteriores para consultarlas o recuperarlas.
pero utilizar este metodo puede traer problemas como: 

1. Ocupa mucho espacio: se duplican todos los archivos, aunque solo se haya modificado uno.
2. Genera confusión: puede ser difícil identificar cuál es la versión más reciente o la correcta.
3. No muestra los cambios: no permite saber fácilmente qué se modificó entre una copia y otra.
4. Dificulta el trabajo en equipo: al compartir distintas copias, se pueden sobrescribir cambios o perder el trabajo de otra persona.

## 1.3 Qué resuelve un sistema de control de versiones

1. Guarda el historial de cambios: permite saber qué se modificó, quién lo hizo y cuándo.
2. Recupera versiones anteriores: ayuda a volver a una versión previa si se comete un error.
3. Facilita el trabajo en equipo: permite que varias personas trabajen en el proyecto y unan sus cambios.
4. Evita tener muchas copias de carpetas: mantiene las versiones organizadas sin crear carpetas distintas para cada fecha.
5. Permite comparar versiones: muestra las diferencias entre los cambios realizados.
 
## 1.4 Centralizado y distribuido

Un sistema centralizado guarda el historial de versiones en un servidor central, al que las personas se conectan para consultar el historial y registrar cambios.
Un sistema distribuido permite que cada persona tenga una copia del proyecto y de su historial en su computadora. Así puede guardar versiones sin internet y compartirlas después.
Git es un sistema de control de versiones distribuido.
