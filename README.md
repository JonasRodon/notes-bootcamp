#Apuntes Skylab Bootcamp 2017

[![bootcamp.png](https://s23.postimg.org/uhm56bibf/bootcamp.png)](https://postimg.org/image/ew4tmd6d3/)

***

![cor.png](https://s29.postimg.org/a0d4ufwo7/cor.png)[Hosting de imagenes gratuito](https://postimg.org/)

![cor.png](https://s29.postimg.org/a0d4ufwo7/cor.png) [LogoMakr](https://logomakr.com/)

***

##Consola Terminal

***

###Copiar directorios

Para copiar directorios completos (con todos sus archivos y subcarpetas internas):
```
cp -r directorio/ ruta_de_destino/nombre_copia
```


####El comando cp en Linux crea una copia.

1. Al escribir cp -r indicamos recursividad, es decir, que haga lo mismo con todos los elementos internos (archivos y subcarpetas)
1. El nombre del directorio debe terminar con una barra (/), asi indicamos que se trata de una carpeta. Sin la barra, Linux considera que estamos manejando un archivo y nos dará error.
1. Luego de un espacio se escribe el nombre del directorio de destino y su ruta (puede ser relativa al directorio origen o a la raiz)
1. Las rutas del directorio de origen y el de destino pueden ser relativas a la raiz o al directorio de trabajo actual.

###Mover directorios

Para mover directorios la sintaxis es casi la misma, con la diferencia que no se necesita indicar recursividad.
```
mv directorio ruta_de_destino/nombre_directorio
```

>Ejemplo 1 (mover el directorio img a un nivel por encima sin cambiarle el nombre)

```
mv img ../img
```

>Ejemplo 2 (mover el directorio img a la carpeta interna files cambiandole el nombre a images)

```
mv img files/images
```

###Renombrar directorios

Para renombrar directorios usamos el mismo comando mv, pero no es necesario indicar una nueva ruta para el directorio, solo un nuevo nombre.

```
mv directorio directorio_renombrado
```


```
mv img images
```

***

[![cor.png](https://s29.postimg.org/a0d4ufwo7/cor.png)](https://postimg.org/image/qo4mwxrfn/) [**cheat sheet**-Linux Command Line Cheat Sheet_UNIX_](https://www.cheatography.com/davechild/cheat-sheets/linux-command-line/pdf/)

[![cor.png](https://s29.postimg.org/a0d4ufwo7/cor.png)](https://postimg.org/image/qo4mwxrfn/) [**cheat sheet**-comandos de terminal _UNIX_](https://files.fosswire.com/2007/08/fwunixref.pdf)

***

##MarkDown Tips

***

You can create tables by separating elements with |.
Separate first row using hyphen -.

| Do | Re | Mi | Fa | Sol |
|:-:|:-:|:-:|---|---|
| La | Si | Do | Re | Mi |
| Fa | Sol | La | Si | Do |
| Re | Mi | Fa | Sol | La |

***

Para generar tablas MarkDown [ **pulsa aqui** ](http://www.tablesgenerator.com/markdown_tables)

[![cor.png](https://s29.postimg.org/a0d4ufwo7/cor.png)](https://postimg.org/image/qo4mwxrfn/) [**cheat sheet**-comandos de terminal _UNIX_](https://files.fosswire.com/2007/08/fwunixref.pdf)

***

##Sublime Tips

***

[![cor.png](https://s29.postimg.org/a0d4ufwo7/cor.png)](https://postimg.org/image/qo4mwxrfn/) [**cheat sheet**-Sublime Text 3](https://www.cheatography.com/njovin/cheat-sheets/sublime-text-2-windows/pdf/)

[![cor.png](https://s29.postimg.org/a0d4ufwo7/cor.png)](https://postimg.org/image/qo4mwxrfn/) [**cheat sheet**-Sublime and Linux Cheatsheet Keyboard Shortcuts](https://www.cheatography.com/nezipt/cheat-sheets/sublime-and-linux-cheatsheet/pdf/)

***

##Git/GitHub Tips

***

##Workflow de git

[![git-schema-1.png](https://s28.postimg.org/kdn8bh4il/git_schema_1.png)](https://postimg.org/image/677hg8tnd/)

[![git-schema-2.png](https://s28.postimg.org/sprdtd7zx/git_schema_2.png)](https://postimg.org/image/uhkco9rcp/)

[![workflow-git.png](https://s30.postimg.org/6pkf33r01/workflow_git.png)](https://postimg.org/image/601mqqqgd/)

[![Flow2.png](https://s28.postimg.org/g9sgspqfh/Flow2.png)](https://postimg.org/image/5zq1th0jt/)

[![serversscreen.png](https://s23.postimg.org/5clzjfk3f/serversscreen.png)](https://postimg.org/image/98zbff52v/)

[![cor.png](https://s29.postimg.org/a0d4ufwo7/cor.png)](https://postimg.org/image/qo4mwxrfn/) [**cheat sheet**-Git](https://services.github.com/on-demand/downloads/es_ES/github-git-cheat-sheet.pdf)

***

##Expresiones Regulares Tips

[![cor.png](https://s29.postimg.org/a0d4ufwo7/cor.png)](https://postimg.org/image/qo4mwxrfn/) [**cheat sheet**-Expresiones Regulares](https://www.cheatography.com/davechild/cheat-sheets/regular-expressions/pdf/)