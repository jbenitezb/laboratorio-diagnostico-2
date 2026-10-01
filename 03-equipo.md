# 3. Trabajo en equipo con GitHub y buenas prácticas

Autor: Jose Luis Sosa

## 3.1 Git y GitHub no son lo mismo

Git es el software local que registra los cambios de tu código en tu computadora. GitHub es la plataforma web donde subes esos registros para respaldarlos y colaborar en equipo.

## 3.2 Repositorio local y remoto

• Clone: Descarga un proyecto remoto completo a tu computadora por primera vez.
• Pull: Trae y fusiona los últimos cambios de la nube a tu copia local.
• Push: Sube tus cambios locales guardados al servidor en la nube.

## 3.3 Conflictos

Ocurren cuando dos personas modifican la misma línea de un archivo y Git no sabe cuál versión conservar.
Resolución paso a paso:
1. Detectar: Git bloquea la fusión y señala los archivos con problemas.
2. Abrir: Abres el archivo para ver tu código frente al de la otra persona.
3. Decidir: Borras las marcas de Git (<<<<<<<, =======) y dejas el código final correcto.
4. Finalizar: Guardas el archivo, haces un commit de resolución y subes (push) el resultado.

## 3.4 Buenas prácticas de commits

• Redactar mensajes claros y en modo imperativo ("Añadir", "Corregir").
• Hacer commits pequeños y frecuentes (uno por cada tarea terminada).
• Separar el título corto de una descripción detallada si el cambio es complejo.
• Excluir archivos temporales o datos sensibles usando un .gitignore.
Ejemplos:
• Malo: cambios finales arreglado todo
• Bueno: Corregir validación del formulario de registro