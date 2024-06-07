![](https://img.shields.io/badge/UMC-blue)

# proweb_gabrielle
Proyecto de pagina web para la materia programacion Web

Para la creacion de las ramas o branches y del repositorio en general se realizaron los siguientes pasos:

1. Crear un nuevo repositorio:

    Se hace clic en el icono + en la esquina superior derecha de la página y selecciona "New repository".

    Configurar el repositorio:
        En el campo "Repository name", ingresa el nombre del repositorio que se desee, asegurandose de que comience con proweb_. Por ejemplo: proweb_gabrielle.
        Opcionalmente, se agrega una descripción en el campo "Description".
        Selecciona "Public" o "Private" según tu preferencia.
        Se puede seleccionar "Add a README file", "Add .gitignore", o "Choose a license" si se desea.
        Se hace clic en "Create repository".

2. Agregar como colaborador (usuario: wilfredvasquez)

    Ir a la configuración del repositorio:
        En la página principal del repositorio recién creado, se hace clic en "Settings" (Configuración).

    Agregar colaborador:
        En el menú de la izquierda, se selecciona "Collaborators and teams" (Colaboradores y equipos).
        En la sección "Collaborators" (Colaboradores), se ingresa el nombre de usuario wilfredvasquez.
        Se hace clic en "Add collaborator" (Agregar colaborador).
        GitHub enviará una invitación al usuario wilfredvasquez, quien deberá aceptar para convertirse en colaborador del repositorio.

3. Crear las ramas main, staging y develop

   Para Clonar el repositorio se uso el siguiente comando en git bash:
   git clone https://github.com/GabrielleMrRobot/proweb_gabrielle.git

   Crear y empujar las ramas main, staging y develop:

   Por defecto, GitHub crea una rama llamada main al crear un repositorio pero aqui se deja un ejemplo de como crearla:
   git checkout -b main
   git push origin main

   Crear la rama staging a partir de main y empujarla:
   git checkout -b staging main
   git push origin staging

   Crear la rama develop a partir de main y empujarla:
   git checkout -b develop main
   git push origin develop

# Nombre del Proyecto

> Declaración de un párrafo sobre el proyecto.

![screenshot](./app_screenshot.png)

Descripción adicional sobre el proyecto y sus características.

## Construido con

- Lenguajes principales
- FrameWorks
- Tecnologías utilizadas

## Live Demo o deploy del proyecto en algun hosting de preferencia

[Live Demo Link](https://livedemo.com)


## Para ingresar al proyecto
Para poner en funcionamiento el proyecto, siga estos sencillos pasos de ejemplo:

### Requisitos previos

### Uso

### Ejecutar pruebas

### Implementación


## Autor

👤 **Gabrielle Jesus Brizuela Guacache**

- GitHub: [@GabrielleMrRobot](https://github.com/GabrielleMrRobot)


## Espero que le haya gustado

¡Dale un ⭐️ si te gusta este proyecto!
