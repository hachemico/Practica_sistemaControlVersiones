
INCLUIR IMAGENES

![alt text](http://url/to/img.png)
![alt text]()


<hr>
<h3>DESAROLLO INICIAL DEL PROYECTO</h3>
<hr>

Creamos un repositorio en Github y el usuario1 se clona el repositorio.
![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-09-28%2016-05-12.png)

Creamos la rama devUsuario1, aunque realmente la desarrollamos desde main.

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-09-28%2016-13-42.png)

Creamos las ramas sobre las que trabajaran el resto de compañeros: devUsuario2, devUsuario3
![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2018-56-45.png)

Se crea la plantilla del proyecto siguendo la estructura marcada. Se agregan los archivos resultantes.
$git add. como la cantidad de archivos es grande, se utiliza la opcion $git add .

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2019-00-32.png)

Realizamos un comit colocando la correspondiente etiqueta.

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2019-02-13.png)

Realizamos un push para subir los archivos generados al repositorio remoto. $git push "nombre-remoto" " nombre-rama"

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2019-06-08.png)

Como vemos a continuación vemos que el remoto de Github queda configurado con las ramas.

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario2/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2019-58-57.png)
<hr>
<h3>DESARROLLO DEL FEATURE "CONTENIDO HTML" y "ATRIBUTOS HTML"  USUARIO 2</h3>
<hr>

Usuario 2 clona el repositorio de la rama principal del proyecto. Cambia a la rama devUsuario2, desde la cual trabajará.

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario2/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2020-04-22.png)

Con los features desarrollados, se añaden los archivos al stage, previo al commit.
$git add "nombre-archivo"
$git commit -m "comentario-commit"

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario2/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2022-00-06.png)

Con esto hacemos un push al remoto, teniendo en cuenta, la rama a la que queremos subir los cambios, en este caso estamos
trabajando con la rama devUsuario2, y queremos actualizar la rama en /remote/origin/devUsuario2, por lo que:

$sudo git push "nombre-remoto" "nombre-rama"

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario2/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2022-12-29.png)

Como podemos observar, se ha hecho un commit en la rama correspondiente devUsuario2.

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario2/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2022-13-02.png)

<hr>
<h3>DESARROLLO DEL FEATURE " ESTILOS CSS " USUARIO 3</h3>
<hr>

El usuario3 clona el repositorio sobre el que va a trabajar.

Se esperaría que en el repositorio solo aparecieran los archivos generados por el Usuario1 en la configuración inicial, pero tras el commit del Usuario2,
el usuario1 ha realizado un Pull request, para adaptar ambos proyectos por lo que, si que apareceran los cambios sobre el repositorio que va a clonar el usuario2.

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2009-26-41.png)


![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2009-32-15.png)

Usuario 3 crea su rama para desarrollar el feature, situandose en la rama devUsuario3.

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2009-32-47.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2009-33-12.png)

Se desarrolla el feature siguiendo las especificaciones del cliente. Una vez completado el proceso, añadimos los archivos al stage, commit y push para actualizar la rama en el remoto.

$git add "nombre-archivo"
$git commit -m "nombre comentario"
$git push "nombre-remoto" "nombre-rama"

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2010-00-18.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2010-00-49.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2010-01-09.png)

<hr>
<h3>USUARIO 1 FUSIONA PROYECTO</h3>
<hr>


![alt text]()
![alt text]()

![alt text]()
![alt text]()
![alt text]()
![alt text]()



## Welcome to GitHub Pages

You can use the [editor on GitHub](https://github.com/hachemico/Practica_sistemaControlVersiones/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/hachemico/Practica_sistemaControlVersiones/settings/pages). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
