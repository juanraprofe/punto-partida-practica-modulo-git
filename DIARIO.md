# DIARIO — Actividad : Laboratorio Git

Diario del desarrollo de la actividad Laboratorio Git

<!-- plantilla inserción imagen -->
<!-- ![Descripción de la imagen](capturas/nombre-imagen.png) -->
##  TASK 1 --> Fork y configuración inicial
### Fork
Un fork es una copia completa de un repositorio que se crea bajo tu propia cuenta en una plataforma como GitHub.

### Upstream
`upstream` es simplemente un alias de un repositorio remoto, normalmente usado para referirse al repositorio original del que hiciste fork.

![Terminal con git remote -v mostrando origin y upstream](capturas/task1.png)

![GitHub con la rama dev visible en el desplegable de ramas](capturas/task1-2.png)


##  TASK 2 --> Feature branch A: añadir la Opción 5
### Origen de la rama
La rama `feature/opcion-5` parte de la rama `dev` porque esa es la rama en la que nos encontrábamos al ejecutar el comando con el que la creamos:
`git switch -c feature/opcion-5`


![La app en el navegador con la Opción 5 recién añadida](capturas/task2.png)
##  TASK 3 --> Feature branch B: añadir la Opción 6 (generamos el conflicto)
### demo
La rama `feature/opcion-5` parte de la rama `dev` porque esa es la rama en la que nos encontrábamos al ejecutar el comando con el que la creamos:
`git switch -c feature/opcion-5`


![La app en el navegador con la Opción 5 recién añadida](capturas/task2.png)


4	El PR de Feature A en GitHub con la pestaña Files changed abierta
5	El PR de Feature B en GitHub mostrando el banner rojo de conflicto
6	Los marcadores de conflicto (<<<<<<<, =======, >>>>>>>) en VS Code
7	La app en el navegador con todas las opciones visibles tras resolver el conflicto
8	Terminal con git log --oneline en main mostrando todos los commits

