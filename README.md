# Uso de GitHub en TrueStudio

##Conceptos de Git
1. *Repositorio* - Carpeta donde se guarda el proyecto.
2. *Branch* - Rama, o versión del proyecto. Se usa para hacer pruebas, partiendo de un nodo común. En nuestro caso, cada uno tendrá una rama asignada, creando sus modificaciones en ella, para posteriormente subirla.

## TrueSTUDIO y GitHub
Para añadir un repositorio remoto dentro de TrueSTUDIO, sigue los pasos:

#### 1. Muestra el panel *Git Repositories* 
     Para ello ve a: `View>Other>Git>Git Repositories` 
     
     ![Alt text](/Images/GitPanel.PNG?raw=true "Git Repositories Panel") 

#### 2. Clona el repositorio remoto 
    Mediante: `Clone a Git Repository`
    Deberás introducir la URI del repositorio (Los dos campos siguientes se rellenan autmáticamente), y tus credenciales de GitHub.
    La URI la obtienes pinchando sobre **Clone or Download** dentro de la página del repositorio (en la web de github**, no obstante para nusetro caso será la siguiente: `https://github.com/domitilo/Template.git`

   ![Alt text](/Images/CloneRepository.PNG?raw=true "Clone Repository") 
   
   En la siguiente ventana debes elegir qué rama quieres trabajar. Cada uno bajará **la que tenga su nombre** y trabajará con ella.
   Aceptamos, y finalizamos el asistente.
   
   Una vez hecho esto, debemos tener una ventana como la siguiente, pero sólo con la rama con nuestro nombre. Si os fijáis en el icono ✔ que tiene la rama Domenech en la imagen, nos indica sobre qué rama se está trabajando actualemente.
   **Debe estar siempre maracada la rama local con vuestro nombre**
   
   ![Alt text](/Images/RepositoriesView.PNG?raw=true "Git Repositories Panel") 

#### 3. Descargar el contenido online.
    Útil si alguien modifica tu rama, y tienes que descargarla para empezar a trabajar sobre esta modificación. Si no, habitualmente sólo tendrás que subir tus modificaciones como se muestra después.
   Para ello, pulsamos con el botón derecho en el nombre del repositorio, y le damos a *Pull*.

#### 4. Cargar el contenido creado/modificado

   Cuando hayas modificado el contenido y quieras cargarlo a la web, sigue estos pasos.
   
     4.1. En la vista de proyecto, seleccionalo con el boton derecho y ve a:
     
       `Team>Commit...`
       
       ![Alt text](/Images/Commit.PNG?raw=true "Commit Option") 
       
       Nos pedirá añadir un comentario. **Trata de explicar qué cambios has realizado, para que sea más fácil despues retroceder en el tiempo, y/o fusionar código. En la parte de abajo de la ventana, debes seleccionar qué ficheros quieres subir, puedes seleccionarlos todos con el botón que tienes en la parte superior derecha.
       
       Cuando hayas terminado de rellenar los campos, selecciona **Commit and Push**
       
       **Asegúrate de que NO aparece el siguiente icono** ya que indica que ha habido un problema.
       
       ![Alt text](/Images/ErrorCommit.PNG?raw=true "Error Commiting") 
       
       
