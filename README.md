![GitHub](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/branches.png) 

# Tarea 4 [GitHub](https://github.com)

## 1. Colaborar en un repositorio existente

  * El primer paso es descargar el repositorio, para esto hay que clonarlo (en mi caso el repositorio de un compañero):

        $ git clone https://github.com/RicardoRamirezBerrocal/hello-world.git


  ![Imagen1](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/1.png)

  * Entramos en el repositorio:
      
        $ cd hello-world 

  * Creamos una nueva rama para guardar cualquier cambio:
     
              $ git branch my-branch

  * Cambiamos a esta rama:

         $ git checkout my-branch


![i2](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/2.png)

* Realizamos algunos cambios en el archivo README.md con VIM (en mi caso) y lo añadimos a la stage area:

       $ git add README.md

* Hacemos un commit con nuestro comentario breve:

       $ git commit -m "Mis cambios"


* Lanzamos los cambios a [GitHub](https://github.com):

       $ git push --set-upstream origin my-branch

![i3](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/3.png)


* En [GitHub](https://github.com) los cambios se verían así:

![i6](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/6.png)


## 2. Iniciar un nuevo repositorio en [GitHub](https://github.com)

* Inicializar el repositorio sin el archivo README.md
* Crear un nuevo directorio/carpeta e inicializarlo con ***git*** (repo5 en micaso):

       $ git init repo5

* Creamos nuestro primer archivo en el proyecto:

       $ touch README.md   

* Preparamos el archivo:
 
       $ git add README.md

![i12](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/12.png)

* Hacemos un commit:

       $ git commit -m "Subida de readme"

* Pegamos la ruta para el repositorio que creamos en [GitHub](https://github.com):

       $ git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY-NAME.git

* Por último lanzamos los cambios a [GitHub](https://github.com):

        $ git push --set-upstream origin main

![i13](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/13.png)


* Con esto hemos terminado el segundo ejercicio

![i11](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/11.png)

## 3. Colaborar en un branch ya existente en [GitHub](https://github.com)


* Lo primero es ubicarnos en el repositorio en el que queremos modificar una de sus branch:

      $ cd hello-world

* Actualizar todas las ramas en seguimiento, incluida la actual:

       $ git pull

* Cambiar a la rama existente llamada en mi caso:

       $ git checkout adalid-edit

***Así se vería por consola:***

 ![i15](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/15.png)
* Ahora hacemos cambios, por ejemplo en el archivo con extensión .md:

       $ vim README.md

* Preparar el archivo modificado:

       $ git add README.md

* Hacer el commit:

       $ git commit -m "edición del .md"

* Ahora el push de los cambios para [GitHub](https://github.com) para finalizar:

       $ git push

* Así quedaría en [GitHub](https://github.com):

![i8](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/8.png)

* Y para comparar los cambios:

![i10](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/10.png)

![i16](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/16.png)

***Con esto concluimos el ejercicio número 4***
![GitHub](https://github.com/AdalidTacubeno/HelloWorld_ej2/blob/master/images/branches.png) 
