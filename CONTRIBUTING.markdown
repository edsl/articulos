Herramientas
============

## [git](http://git-scm.com) con [git-flow](https://github.com/nvie/gitflow).

Configuración:

* master   => master
* develop  => queue
* feature  => traduccion
* hotfix   => hotfix
* release  => edicion

Ver el archivo `.gitflow`.

### Propuesta de texto con `git-flow`

1.  Crear una nueva feature con el artículo a traducir

        git flow feature start nombre-del-articulo

2.  Agregar el texto (en formato markdown)

        git add nombre-del-articulo.mdwn

3.  Guardar el cambio

        git commit -m "Explicación de por qué publicar este artículo"

4.  Traducir un párrafo, agregar y guardar el cambio

        git commit -am "Tal vez un comentario sobre algunas elecciones de traducción..."

5.  Repetir 4 hasta terminar

    Traducir párrafo por párrafo es para facilitar la revisión, al contrastar
    directamente el párrafo original (eliminado) con el párrafo traducido
    (agregado) con un simple `git diff`, antes de realizar el commit, o con `git
    log -p` después.

6.  Si tenés un repositorio público (e.g. cuenta en
    [Github](http://github.com/)) de donde podamos incorporar tus cambios,
    pusheá la rama del artículo y avisanos.

        git push repositorio traduccion/nombre-del-articulo

7.  ¡Revisar! Mejor una persona diferente a la que tradujo

8.  Mergear en la rama *queue*

        git flow feature finish nombre-del-articulo

### Correcciones después de publicado

1.  Crear un hotfix

        git flow hotfix start nombre-del-articulo

2.  Corregir y cerrar el hotfix

        git flow hotfix finish nombre-del-articulo

### Sólo quiero/puedo revisar

Para ver los artículos traducidos pero que aún no se publicaron, podés usar

    git diff --name-only master queue

Cualquier revisión en cualquiera de esos artículos es bienvenida.

### Más información

* [Modelo de ramas](http://nvie.com/git-model)
* [Cheatsheet](http://danielkummer.github.io/git-flow-cheatsheet/)

## vim

En este repo hay un archivo `.vimrc` con configuraciones básicas para
mantener cierta coherencia en el diagramado de los textos. Si agregás
esto en tu `~/.vimrc`:

    set exrc

vim lee ese archivo del directorio actual, y no tenés que modificar
ninguna otra configuración.

Guía de estilo
==============

## ¡Quiero mi capital social!

Si tradujiste desde cero, o corregiste una traducción contrastando con
el artículo original, agregate a la lista de traductoras del artículo,
con nombre o nick y un mail si querés. Si corregiste a partir del texto
traducido (por ejemplo la ortografía o puntuación) agregate en la lista
de correctoras.

## Notas de traducción

Muchas veces las traducciones necesitan una explicación o una referencia
al original para no perder el contexto, y muchas otras veces es
interesante aclarar términos oscuros o de nicho para poder acercar los
textos a gente fuera del ambiente. En esos casos usamos notas de traducción así:

    Texto con término confuso[^ndt-nombre-de-la-nota] y bla bla,
    sigue el párrafo hasta el final.

    [^ndt-nombre-de-la-nota]: Explicación. _(Nota de traducción)_

Siempre empezá con `[^ndt-]` para diferenciar más fácilmente las notas
que son de traducción de las notas en el texto original.
