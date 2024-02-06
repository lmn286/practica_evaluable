Comandos utilizados en la practica evaluable.
git init→ Crear nuestro repositorio.
git status→Te muestra lo que tienes en el área de trabajo y preparación.
git add → Añadir y lo visualizamos en el área de working.
git commit→Subir al repositorio local todo lo que esté en el área del working.
git log → Para ver cuántos commit llevamos hechos, más detallado.
git log -- oneline. Te muestra el código de cada commit. Para ver cuántos commit llevamos hechos.
git commit -m → “Añadir mensaje “cuándo hacemos el commit
git config -- global  Para configurar el nombre de usuario en git en todos los proyectos, configura el email también.
git show → te muestra lo que has hecho con commit
diff -- git→ te muestra los cambios hechos.
git checkout → Para deshacer los cambios en el área de trabajo.
git checkout fich* → Elimina todos los ficheros que empiecen por fich y que estén en el área de trabajo.
Git checkout -b +nombre de la rama Creas una nueva rama y te posicionas en ella a la vez.
git reset → Quitamos los cambios del área de preparación. Nos vemos entre commit con su número
git reset -- hard → Vacío o quito lo de los 2 estados, trabajo y preparación y me lo deja como en (“HEAD). 
git reset -- hard 06d3b84 cuidado con ello porque pierdes esa información y te vuelve a una version de ese codigo.
git revert HEAD → para revertir
rm nombre del fichero  se borra el fichero creado sin estar subido.
Echo +mensaje+ >> nombre del fichero con la extensión añadimos texto al fichero.
Echo +mensaje+ > nombre del fichero con la extensión añadimos texto por primera vez al fichero, pero si ya tenemos texto y añadimos solo con un sigo >, se borra lo anterior y se queda solo ese.
Cat+ nombre de fichero con la extensión , nos muestra el contenido de un archivo en la consola.
Git push -u origin main  Añades todos los commit con -u. Nos llevamos todo lo del repositorio local al repositorio remoto.
Git pull origin main  Te traes lo que tienes en el repositorio remoto al local. Del original al main.
Git branch Puedes ver en que rama te encuentras actualmente. Sale marcada con un *.
Git branch -M main Renombra la rama master del repositorio local a main por el repositorio master. También se puede poner -m. 
Vim + nombre documento  Editar fichero. Para modificarlo pulsar I y salir :q o una vez modificado :wq para guardar.

