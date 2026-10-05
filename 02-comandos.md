Repositorio: Es un historial donde se guardan las versiones de un proyecto en una computadora.
Staging: Es el espacio donde dejamos solo los cambios que se quieren guardar.
Directorio de trabajo: Es donde creamos y editamos los archivos que se van a nesecitar, esto en la computadora.

2.2 Configuración inicial

A la hora de trabajar en Github por primera vez se deben realizar y ejecutar ciertos comandos en la terminal de la computadora para configurarlo con información de nuestra identidad, tales como:
git config --global user.name "Nombre Completo".
git config --global user.email "tucorreo@ejemplo.com".
git config --global --list

2.3 El ciclo status, add, commit y push
Este es un ciclo que se da a la hora de querer guardar y compartir cambio en el proyecto, estos son lo siguientes:
git status: Nos permite observar el estado actual de los archivos.
git add . : Selecciona y prepara los archivos que queremos adjuntar al proyecto
git commit "nombre acerca de lo que se sube": Este guarda de manera oficial la version nueva a nuestra computadora, en este se adjunta un pequeño texto donde se menciona lo que se hizo.
git push: Sube los archivos nuevos de nuestro trabajo para compartirlos con los compañeros del proyecto.

2.4 Consultar el historial
Esto permite observar la lista de todos los cambios que se han guardado recientemente, estos son los siguientes:
git log: Muestra el historial completo de todos los commits que se han hecho, indicando la fecha, el autor y el mensaje que pusimos para cada cambio.
git log --oneline: Muestra un resumen donde cada cambio se ve se ve en una sola linea para leerlo de manera fácil.
