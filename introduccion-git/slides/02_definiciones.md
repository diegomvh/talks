Terminología
============

Estructurales
-------------

* Repository, Working copy, Working version, Workspace

Conceptuales
------------

* Trunk, Branch, Tag
* Tip, Head
* Revision, Change, Changelist
* Stage

.notes: Dependiendo del SCV pueden encontrarse en distintas partes

Acciones
--------

* Commit, Checkout, Export, Import
* Conflict, Resolve, Merge, Rebase
* Cherry Pick, Revert, Stash, Patch
* Fork, Clone, Push, Pull

.notes: Muchos se traducen en comandos de los distintos SCV

# Presenter Notes

Tip es equivalente a tag pero se utiliza para los branches
Stage es donde se agregan los archivos en git antes de hacer el commit
Aclarar que Fork viene de la mano de GitHub
Rebase similar a merge solo que intenta preservar la historia de la rama de manera lineal, mientras que merge genera ramificaciones
Cada commit al repositorio debe estar bien documentado, es una recomendación de buenas prácticas de desarrollo.
Las ramas son bifurcaciones que permiten desarrollar diferentes partes de un software en paralelo, facilitan el aislar los cambios