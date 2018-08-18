![nahual-img](assets/proyecto-nahual.png)

Buenas! Somos Nahual, un proyecto social que se dedica, entre otras cosas, a enseñar testing manual con el objetivo
de generar una salida laboral.

[Acá](https://github.com/nahual) guardamos gran parte del material que usamos para dar las clases. 
Si querés darnos una mano, estás más que invitada. Hacenos PRs o ponete en contacto con cualquier miembro.

Este es el repositorio de la [página web](https://nahual.github.io). Es decir, donde vive todo el contenido 
a partir del cual se genera.
Si querés participar de su edición, abajo hay algunas pautas. 
Si lo lees y no queda claro, avisanos así nos ayudás a que quien quiera contribuir pueda hacerlo con las menores barreras.

### Cómo funciona?
A grandes rasgos es maaasomenos así:
- tenemos todo nuestro material en repositorios de Github. 
  Por ejemplo, el de "El Provinciano" está [acá](https://github.com/nahual/qc-provinciano)
- un repositorio especial es [este](https://github.com/nahual/nahual.github.com), 
  porque lo habilitamos para que funcione como ["Gihub Page"](https://pages.github.com/)
- cada vez que se hace un cambio en el repositorio (cambiar texto, subir un archivo, etc), Github agarra todo el material,
  lo pasa por "Jekyll", y lo publica (todo esto funciona de manera automágica).
  - [Jekyll](https://jekyllrb.com/) es básicamente un programa que transforma texto. 
    Vos le pasás un archivo escrito en formato HTML o Markdown y Jekyll lo transforma a HTML agregándole 
    un montón de cosas que lo hacen ver como un sitio web.

### Querés editarla?
#### Editando un archivo existente
- abrilo desde el navegador de archivos de Github y hacé click en el botón de "editar":
  ![edit-img](https://help.github.com/assets/images/help/repository/edit-file-edit-button.png)
- escribi lo que quieras en el formato del archivo. Por ahora son Markdown, porque es muy fácil de escribir.
  (abajo hay info de Markdown)
- acá hay una ayuda de Github: [editando archivos](https://help.github.com/articles/editing-files-in-your-repository/)
  
#### Nuevo archivo
Si creas un nuevo archivo, desde la página generada se va a generar un link automáticamente (de eso se encarga Jekyll).
- usando el navegador de Github, andá hasta donde quieras que esté el nuevo archivo (en general debería ser en la raíz
  del repositorio)
- hacé click en "crear nuevo archivo":
![create-img](https://help.github.com/assets/images/help/repository/create_new_file.png)
- como en la sección anterior, ponele el texto que quieras (preferiblemente en markdown), pero **obligatoriamente** ponele
  lo que se conoce como "front matter" para Jekyll. Eso va a hacer que el archivo "participe" del proceso que 
  hace Jekyll.

```
---
layout: page
title: Nahual FAQ
permalink: /faq/
---
```
- si no queda claro, fijate cómo están hechos los demás archivos del sitio. Por ejemplo, 
  la página de ["acerca de"](https://github.com/nahual/nahual.github.com/raw/master/faq.md).
- acá también hay una ayuda de Github: [creando-nuevos-archivos](https://help.github.com/articles/creating-new-files/)

### Markdown?

Markdown es una forma de escribir texto. Sirve para indicar de manera sencilla qué partes de tu texto
son títulos, listas, énfasis, citas, etc. Ese formato está muy aprovechado en otras herramientas que 
toman texto en formato Markdown y lo convierten a HTML, PDF, etc.
[Referencia](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) - [Probalo](https://stackedit.io/app)
