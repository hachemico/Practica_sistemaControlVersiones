
<h1> PRÁCTICA SISTEMAS CONTROL VERSIONES </h1>

<h3> ¿Que es GIT y GITHUB ?</h3>

![alt text](https://i.blogs.es/bd50eb/github_logo/1366_2000.png)

```
Git es un sistema de control de versiones distribuido. Esto significa que un clon local del proyecto es un repositorio
de control de versiones completo. Estos repositorios locales plenamente funcionales permiten trabajar sin conexión o de forma remota fácilmente. 
Los desarrolladores confirman su trabajo localmente y, a continuación, sincronizan su copia del repositorio con la copia en el servidor.
Este paradigma es distinto del control de versiones centralizado, donde los clientes deben sincronizar el código con 
un servidor antes de crear nuevas versiones.

La flexibilidad y popularidad de Git lo convierten en una excelente opción para cualquier equipo. 
Muchos desarrolladores y egresados de la universidad ya saben cómo usar Git. 
La comunidad de usuarios de Git ha creado muchos recursos para entrenar a los desarrolladores y la popularidad de Git 
facilita la ayuda cuando es necesario. Casi todos los entornos de desarrollo tienen compatibilidad con Git y las herramientas de 
línea de comandos de Git se ejecutan en todos los sistemas operativos principales.

GITHUB

Github una de las principales plataformas para crear proyectos abiertos de herramientas y aplicaciones, 
y se caracteriza sobre todo por sus funciones colaborativas que ayudan a que todos puedan aportar su 
granito de arena para mejorar el código.

Utiliza el sistema de control de versiones Git diseñado por Linus Torvalds. Un sistema de gestión de versiones 
es ese con el que los desarrolladores pueden administrar su proyecto, ordenando el código de cada una de las 
nuevas versiones que sacan de sus aplicaciones para evitar confusiones. 
Así, al tener copias de cada una de las versiones de su aplicación, no se perderán los estados anteriores cuando 
se va a actualizar.


```

<h3>DESAROLLO INICIAL DEL PROYECTO</h3>
<hr>

```
Creamos un repositorio en Github y el usuario1 se clona el repositorio.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-09-28%2016-05-12.png)

```
Creamos la rama devUsuario1, aunque realmente la desarrollamos desde main.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-09-28%2016-13-42.png)

```
Creamos las ramas sobre las que trabajaran el resto de compañeros: devUsuario2, devUsuario3
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2018-56-45.png)

```
Se crea la plantilla del proyecto siguendo la estructura marcada. Se agregan los archivos resultantes.
$git add. como la cantidad de archivos es grande, se utiliza la opcion $git add .
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2019-00-32.png)

```
Realizamos un comit colocando la correspondiente etiqueta.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2019-02-13.png)

```
Realizamos un push para subir los archivos generados al repositorio remoto. $git push "nombre-remoto" " nombre-rama"
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2019-06-08.png)

```
Como vemos a continuación vemos que el remoto de Github queda configurado con las ramas.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario2/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2019-58-57.png)

<hr>
<h3>DESARROLLO DEL FEATURE "CONTENIDO HTML" y "ATRIBUTOS HTML"  USUARIO 2</h3>
<hr>

```
Usuario 2 clona el repositorio de la rama principal del proyecto. Cambia a la rama devUsuario2, desde la cual trabajará.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario2/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2020-04-22.png)

```
Con los features desarrollados, se añaden los archivos al stage, previo al commit.
$git add "nombre-archivo"
$git commit -m "comentario-commit"
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario2/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2022-00-06.png)

```
Con esto hacemos un push al remoto, teniendo en cuenta, la rama a la que queremos subir los cambios, en este caso estamos
trabajando con la rama devUsuario2, y queremos actualizar la rama en /remote/origin/devUsuario2, por lo que:

$sudo git push "nombre-remoto" "nombre-rama"
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario2/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2022-12-29.png)

```
Como podemos observar, se ha hecho un commit en la rama correspondiente devUsuario2.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario2/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-03%2022-13-02.png)

<hr>
<h3>DESARROLLO DEL FEATURE " ESTILOS CSS " USUARIO 3</h3>
<hr>

```
El usuario3 clona el repositorio sobre el que va a trabajar.
```
```
Se esperaría que en el repositorio solo aparecieran los archivos generados por el Usuario1 en la configuración inicial, pero tras el commit del Usuario2,
el usuario1 ha realizado un Pull request, para adaptar ambos proyectos por lo que, si que apareceran los cambios sobre el repositorio que va a clonar el usuario2.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2009-26-41.png)


![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2009-32-15.png)

```
Usuario 3 crea su rama para desarrollar el feature, situandose en la rama devUsuario3.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2009-32-47.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2009-33-12.png)

```
Se desarrolla el feature siguiendo las especificaciones del cliente. Una vez completado el proceso, añadimos los archivos al stage, commit y push para actualizar la rama en el remoto.
```
```
$git add "nombre-archivo"
$git commit -m "nombre comentario"
$git push "nombre-remoto" "nombre-rama"
```
![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2010-00-18.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2010-00-49.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/devUsuario3/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2010-01-09.png)

<hr>
<h3>USUARIO 1 FUSIONA PROYECTO</h3>
<hr>

```
Para emperzar tenemos que saber que cambios se han realizado en todas las ramas del repositorio, para ello realizamos un fetch.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2010-27-32.png)

```
Actualizamos main, para obtener los cambios realizados sobre la rama main, que incluyen los features realizados por usuario2, como antes hemos explicado.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2010-27-49.png)

```
Ahora tenemos que obtener los datos de la rama devUsuario3. Cambiamos de rama y aplicamos un pull: $sudo git pull "repos-remoto" "rama-remota".
Nos aparece un conflicto que tenemos que arreglar manualmente. Añadimos los archivos a staged. Comit.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2011-08-49.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2011-24-08.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2011-24-19.png)

```
Ahora que ya tenemos todo lo necesario cambiamos a la rama Principal "main". Sobre la que vamos a aplicar un merge de la rama devUsuario3.
$sudo merge "rama-fusionar"
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2011-26-52.png)

```
Se modifica los archivos, para que todo funcione y se añaden los archivos al stage, seguido de commit.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2011-36-25.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2011-36-37.png)

```
Realizamos un push para actualizar el repositorio.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2011-39-32.png)


<hr>
<h3>ETIQUETAR PROYECTO Y CREAR RAMA TEST </h3>
<hr>

```
Se puede etiquetar un commit ya realizado, pero necesitamos conocer el Hash del comit para poder asociarlo.
$git log --graph --all
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2012-03-42.png)

```
Creamos el tag: v1.0, para ello:
git tag -a nombre_tag -m “Mensaje asociado al tag” hash_asociado_al_commit
```
![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2012-06-03.png)

```
Como se puede observar si ejecutamos de nuevo el log. Aparece el commit de la fusión del proyecto con la tag v1.0.
```
![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2012-06-24.png)

```
Para que las etiquetas aparezcan en el repositorio, relizaremos un:

$git push origin --tags

Para crear la rama test. Se crea de modo local con $git branch "nombre-rama". 
No colocamos sobre la misma y realizamos un merge de main para tener una copia del proyecto contenido por main.
Como no vamos a realizar cambios y solo queremos subirlo al repositorio remoto. 

$git push "nombre-remoto" "rama-remoto"
```


<hr>
<h3> AUTOMATIZACIÓN HOOKS </h3>
<hr>
<h5> Qué son los Git Hooks? </h5>

```
¿Qué son los Git Hooks?
Con Git podemos crear ramas de desarrollo, registrar cambios y tener un control absoluto sobre las versiones. Sin embargo, es posible automatizar este proceso. La automatización de Git funciona a nivel de programas y deployment. Y para eso existen los Hooks.

Los ganchos de Git son scripts de shell que se ejecutan automáticamente antes o después de que Git ejecute un comando importante como Commit o Push. Para que un Hook funcione, es necesario otorgarle al sistema Unix los permisos de ejecución. Mediante el uso de estos scripts, podemos automatizar ciertas cosas.
```
```
mas info : https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks
```
```
<h6> npm install al realizar un checkout o clone </h6>

Para realizar un hook, tenemos que declararlo dentro de la carpeta .git/.hooks.
Podemos crearlo o editar uno de los ya existentes, quitandole la extensión .example.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2013-33-54.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2013-34-15.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2013-44-54.png)

```
Observamos que efectivamente lanza la intrucción npm install.
Como detalle a tener en cuenta, el archivo tine que tener permisos de ejecucion, 
de lo contrario se produce un error y no se ejecuta.
$sudo chmod 776 nombre-hook
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2015-47-09.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2015-47-35.png)

<h6> Comprobar mensaje commit </h6>

```
Lo primero es implementar el hook, en este caso se ha seguido un ejemplo de StackOverflow. Definiendo un pattern y comparandolo. Si se cumple el patrón continua con el commit, sino cumple exit 1 mostrando el mensaje de error y parando el commit al recibir este un valor distinto de 0.
```
```
https://stackoverflow.com/questions/5393178/get-commit-message-in-git-hook
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2016-44-14.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2016-44-56.png)

```
Tenemos que aplicar derechos de ejecución para que funcione. $sudo chmod 777 nombre-hook
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2016-47-24.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2016-48-23.png)

```
Realizamos pruebas para confirmar que funciona.
```

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2016-48-59.png)

![alt text](https://github.com/hachemico/Practica_sistemaControlVersiones/blob/main/html5-boilerplate_v8.0.0/assets_GitPages/Captura%20de%20pantalla%20de%202021-10-04%2016-50-20.png)




