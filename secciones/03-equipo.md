# 3. Trabajo en equipo con GitHub y buenas prácticas

Autor: Daniel García Monge

## 3.1 Git y GitHub no son lo mismo
- Git funciona en la computadora con o sin internet.
- Git es quien registra los cambios y el historial de los archivos.
- GitHub hace más fácil compartir el trabajo y colaborar con el equipo.
- GitHub da la posibilidad de guardar los repositorios en el internet.
- Los 2 se complementan al guardar los cambios tanto en el dispositivo como al compartirlo

## 3.2 Repositorio local y remoto
- El repositorio local está en la computadora.
- El repositorio remoto se guarda en un servidor.
- clone descarga una copia del repositorio.  
- pull trae e integra los cambios que subieron los compañeros.  
- push sube los commits al repositorio remoto.

## 3.3 Conflictos
- Un conflicto puede ocurrir cuando dos personas cambian las mismas líneas y Git no puede combinar los cambios automáticamente.
- Al ejecutar git pull, Git puede detectar el conflicto y señalar el archivo afectado.  
- Se abre el archivo y se revisan las dos versiones.
- Se combina el contenido conservando los cambios necesarios de ambos.
- Se guarda el archivo y usamos git add para marcarlo como resuelto.  
- Se ejecuta git commit para completar la unión.  
- Se usa git push para compartir el resultado.