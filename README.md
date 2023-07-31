## Tutorial para agregar o editar la _wiki_ de un proyecto

 Este tutorial se base en el siguiente link:

 https://docs.github.com/en/communities/documenting-your-project-with-wikis/adding-or-editing-wiki-pages

 Se puede agregar y editar _wiki pages_ directamente en GitHub.

 1. En GitHub.com, navegue a la página principal del repositorio. Si no tiene un repositorio creado para su proyecto, debe crearlo antes de continuar este tutorial.
 2. En el repositorio, haga click en Wiki

    ![Alt text](figs/step1.png?raw=true "Title")
 
 3. Cree la primera página de la Wiki

    ![Alt text](figs/step2.png?raw=true "Title")

 4. Este paso nos llevará a una página con nombre por defecto ``home``. En esta página describiremos brevemente el proyecto. Después debemos dar click en el botón __save page__

    ![Alt text](figs/step3.png?raw=true "Title")

 5. Llegaremos a la página de visualización de la Wiki, donde por defecto tendremos acceso a la página __home__ pero además tendremos una barra de navegación a la derecha, una opción para editar la página en la que estemos ubicados y una opción para crear nuevas páginas. Lo ideal es que creemos una página para cada homework, workshop y deliverable.

    ![Alt text](figs/step4.png?raw=true "Title")

  Para escribir en la _wiki_ se utilizará _markdown_ que es una forma de texto enriquecido. Si quieren aprender más sobre esto les recomiendo el siguiente tutorial:

  https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

6. Para agregar imágenes a nuestra wiki, vamos a seguir los pasos descritos en el siguiente tutorial:

   https://gist.github.com/TT--/14260aef6c0e31fca5b37e7cb3c53020

Primero, debemos clonar el repositorio de forma local. Para esto, vamos a dirigirnos en nuesto PC al sitio (carpeta) en el que vamos a almacenar nuestra wiki.    Preferiblemente, este directorio debe ser el mismo directorio raíz donde está ubicado el repositorio del proyecto. __Nota:__ A pesar de que es posible manejar este directorio dentro de la carpeta local de nuestro proyecto, para evitar conflictos es preferible manejarlos como repositorios independientes. 

![Alt text](figs/step5.png?raw=true "Title")

Después, en la parte inferior derecha de la página de visualización de la _wiki_ (punto 5), aparece la url para clonar el repositorio. Abrimos una terminal en nuestro PC en la carpeta donde va a estar la _wiki_, para esto podemos hacer click derecho en la carpeta y después en _Abrir en terminal_, como se muestra en la figura anterior. Cuando la terminal se abra, escribimos el siguiente comando:

   ``git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY``

En mi caso, el comando para clonar la wiki del proyecto es:

   ``git clone https://github.com/jdmartinev/ProyectoPI_wiki.wiki.git``

![Alt text](figs/step6.png?raw=true "Title")

Como resultados podremos ver una nueva carpeta con una extensión .wiki

![Alt text](figs/step7.png?raw=true "Title")

Dentro de esta carpeta podemos crear una nueva carpeta con las imágenes que queremos incluir en nuestra _wiki_.

![Alt text](figs/step8.png?raw=true "Title")

Yo voy a agregar una figura de un cerebro

![Alt text](figs/step9.png?raw=true "Title")

__Nota:__ La rama principal de este repositorio es `master`. Esto debemos tenerlo en cuenta a la hora de sincronizar los archivos.

Para sincronizar esta figura, que hasta el momento se encuentra en la carpeta local de nuestro proyecto, con la versión en nube (GitHub), debemos utilizar los comandos ``add``, ``commit`` y ``push``. Para esto, desde la terminal escribiremos lo siguiente:

``git add .`` \
``git commit -m "brain fig"`` \
``git push -u origin master`` 

Ahora, 








   

    

