# 2. Los comandos esenciales de Git

Autor: Alejandro Medrano Ruiz

## 2.1 Las tres zonas

Git trabaja con tres zonas principales durante el control de los cambios. El directorio de trabajo es donde se encuentran los archivos que estamos editando normalmente. Cuando modificamos un archivo, el cambio todavía no forma parte de un commit. El área de preparación, también llamada staging area, contiene los cambios que seleccionamos con `git add` para incluirlos en el siguiente commit. Finalmente, el repositorio guarda los cambios que ya fueron confirmados con `git commit`. Estas tres zonas permiten revisar y decidir qué cambios queremos guardar antes de incorporarlos al historial del proyecto.

## 2.2 Configuración inicial

Antes de comenzar a trabajar con Git es importante configurar la identidad de la persona que realizará los commits. Git utiliza un nombre y un correo electrónico para registrar quién hizo cada cambio dentro del historial del proyecto. Para configurar estos datos se utilizan los comandos `git config --global user.name` y `git config --global user.email`. Es recomendable utilizar el mismo correo asociado a la cuenta de GitHub para que los commits puedan relacionarse correctamente con el perfil. También se puede definir `main` como la rama principal mediante `git config --global init.defaultBranch main`. Finalmente, el comando `git config --global --list` permite revisar la configuración guardada.