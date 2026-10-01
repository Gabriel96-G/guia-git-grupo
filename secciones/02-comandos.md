# 2. Los comandos esenciales de Git

Autor: Alejandro Medrano Ruiz

## 2.1 Las tres zonas

Git trabaja con tres zonas principales durante el control de los cambios. El directorio de trabajo es donde se encuentran los archivos que estamos editando normalmente. Cuando modificamos un archivo, el cambio todavía no forma parte de un commit. El área de preparación, también llamada staging area, contiene los cambios que seleccionamos con `git add` para incluirlos en el siguiente commit. Finalmente, el repositorio guarda los cambios que ya fueron confirmados con `git commit`. Estas tres zonas permiten revisar y decidir qué cambios queremos guardar antes de incorporarlos al historial del proyecto.