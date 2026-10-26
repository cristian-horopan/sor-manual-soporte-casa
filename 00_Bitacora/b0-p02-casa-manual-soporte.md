- **Alumno:** Cristian Raul Horopan
- **Bloque:** B0 — P02 · Casa · Manual de soporte con Git y GitHub
- **Fase / ejercicio:** Fase 0.8
- **Fecha de inicio:** 26/09/2026
- **Fecha de entrega:** 26/09/2026
---
## Qué se pedía
Crear desde cero una bóveda de Obsidian y un repositorio Git para elaborar un manual de soporte informático. 
## ⌨Comandos y pasos importantes
 git --version — comprobar que Git está instalado.
    
- git config --global user.name — configurar el nombre del usuario.
    
- git config --global user.email — configurar el correo del usuario.
    
- git init — iniciar un repositorio Git.
    
- git status — ver el estado de los archivos.
    
- git add archivo — preparar un archivo para guardarlo en un commit.
    
- git diff -- archivo — revisar los cambios realizados en un archivo.
    
- git diff --cached — revisar los cambios preparados antes del commit.
    
- git commit -m "mensaje" — guardar una versión del proyecto.
    
- git remote -v — comprobar la conexión con el repositorio remoto.
    
- git push -u origin main — subir los cambios a GitHub.
    
- git log --oneline — consultar el historial de commits.
    
- git switch --detach CODIGO_PRIMER_COMMIT — consultar una versión anterior.
    
- git switch main — volver a la rama principal.
    
- git check-ignore -v manual/videos/revision-01.mp4 manual/videos/revision-02.mp4 — comprobar qué regla ignora los vídeos.
## Qué he hecho
Primero, preparé la bóveda de Obsidian y organicé el proyecto dentro de la carpeta 01_Proyecto. Después, inicialicé Git y configuré los datos necesarios para identificar los commits.

A continuación, creé los archivos del manual y fui haciendo cambios en varias versiones. Revisé las diferencias antes de guardar cada versión, preparé los archivos con git add y registré los cambios con git commit.

También preparé la conexión con GitHub para subir el proyecto. Por último, consulté el historial, revisé un commit anterior y volví a la rama principal. Los vídeos quedaron excluidos del seguimiento mediante el archivo .gitignore.


## Qué me ha fallado y cómo lo he resuelto
Tuve un error que fue:

Se me duplico la carpeta de manual en obsidian, tuve que borrarla y mover la carpeta imagenes ya que estaba en la carpeta duplicada, y por eso git no me reconocia el comando de git add ya que buscaba en la carpeta que no era

## Respuestas a las preguntas
1. **¿Por qué se inicializa Git dentro de 01_Proyecto?**  
    Porque es la carpeta que contiene el proyecto que queremos controlar con Git. Así evitamos incluir archivos que no forman parte del manual.
    
2. **¿Para qué sirven git status y git diff?**  
    Git status muestra el estado de los archivos y git diff permite ver qué cambios se han realizado.
    
3. **¿Por qué un archivo nuevo puede aparecer en git status y no en git diff?**  
    Porque todavía no está siendo seguido por Git. Primero hay que añadirlo con git add para prepararlo.
    
4. **¿Qué diferencia hay entre git add y git commit?**  
    Git add prepara los archivos que queremos guardar y git commit registra esos cambios como una nueva versión.
    
5. **¿Para qué sirve .gitignore?**  
    Sirve para indicar qué archivos no queremos que Git incluya en el seguimiento, como los vídeos pesados de la práctica.
    
6. **¿Cómo se puede revisar una versión anterior y volver a la actual?**  
    Se puede consultar un commit anterior con git switch --detach y después volver a la rama principal con git switch main.
    
7. **¿Para qué sirve el historial de Git?**  
    Permite ver las versiones guardadas, consultar los mensajes de los commits y comprobar cómo ha evolucionado el proyecto.
    
8. **¿Qué diferencia hay entre hacer un commit y subir los cambios a GitHub?**  
    El commit guarda los cambios en el repositorio local, mientras que git push los envía al repositorio remoto de GitHub.
    
9. **¿Qué pasos hay que repetir al actualizar el manual?**  
    Modificar los archivos, revisar los cambios, preparar los archivos con git add, comprobarlos, crear un commit y subirlo a GitHub. La configuración inicial del repositorio no suele ser necesaria cada vez.
## Enlaces
- **Vídeo de esta fase:** https://www.youtube.com/watch?v=kURQorUDu_M
- **Playlist:** https://www.youtube.com/playlist?list=PLFpo3Sta_bkk
## Dudas / a repasar

- La diferencia entre el directorio de trabajo, los cambios preparados y los commits.
    
- La diferencia entre guardar un commit y subirlo a GitHub.
    
- Cómo funciona el archivo .gitignore.
    
- Cómo consultar versiones anteriores sin perder el trabajo actual.
    
- Cómo comprobar que el repositorio remoto está bien configurado.