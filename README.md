# practicas-primero-2023
Repositorio para las prácticas profesionales de Primer Año de CC y CD en el curso 2023

Los estudiantes, individualmente, deben crear un issue en este repositorio con información relativa a sus actividades en las prácticas.
Este issue debe contener la siguiente información:
-Nombre Completo del Estudiante
-Grupo
-URL del Repositorio de Github donde se encuentre su proyecto

Cualquier ausencia o error de la información requerida es responsabilidad del estudio con lo que ello implique.

En el proyecto, el contenido en el repositorio de Github, debe contener:
- El código de sus respectivos proyectos de programación
- Un subdirectorio, dentro del repositorio, con el nombre informe, que contiene el fichero .tex (y resto de ficheros necesarios) del informe del proyecto elaborado en latex
- Un subdirectorio, dentro del repositorio, con el nombre presentación, que contiene el fichero .tex (y resto de ficheros necesarios) de la presentación del proyecto elaborado en latex (como sugerencia puede usar beamer o cualquier otro paquete que prefiera)
- Un subdirectorio, dentro del repositorio, con el nombre script, que contiene el fichero proyecto.sh que es un script en bash, que, cómo mínimo, tiene las siguientes opciones (run, clean, report, slides, show_report, show_slides). Con estos parámetros se debe hacer lo siguiente:
    - *run*: ejectutar el proyecto
    - *report*: compilar y generar el pdf del proyecto latex relativo al informe
    - *slides*: compilar y generar el pdf del proyecto latex relativo a la presentación
    - *show_report*: ejecutar un programa que permita visualizar el informe, si el fichero en pdf no ha sido generado debe generarse. Esta opción puede recibir como parámetro el comando de la herramienta de visualización que se quiera utilizar, aunque debe tener una por defecto.
    - *show_slides*: ejecutar un programa que permita visualizar la presentación, si el fichero en pdf no ha sido generado debe generarse. Esta opción puede recibir puede recibir como parámetro  el comando de la herramienta de visualización que se quiera utilizar, aunque debe tener una por defecto. 
    - *clean*: eliminar todos los ficheros auxiliares que no forman parte del contenido del repositorio y se generan en la compilación o ejecución del proyecto, o en la generación de los pdfs del reporte o la presentación

***En caso de que finalmente la conferencia de bash no se imparta, se deberá estudia e investigar bash de manera individual de modo que se pueda completar esta parte de las prácticas. Con esto queda claro que, aún sin impartirse la conferencia de bash, se deben completar todos los requerimientos especificados.***
