GIT
===

.fx: centerquote

> Sistema de control de versiones distribuido, diseñado y desarrollado por Linus Torvalds para el kernel Linux.

"I'm an egotistical bastard, and I name all my projects after myself. First 'Linux', now 'git'."
<p class="cite">— <a href="http://wikipedia.org/">Linus Torvalds</a></p>

# Presenter Notes

2005, BitKeeper
Enfocado en la velocidad
High performance

---

Ventajas
========

* Distribuido
* Rápido
* Eficiente (branches)
* Seguro (reflog)
* Flexible
* Local
* Pequeño
* Limpio (.svn)
* GitHub

---

Desventajas
=========== 

* Curva de aprendizaje
* Número comandos
* Significado comandos (usuarios subversion)

---

Comandos
========

Local Commands
--------------

* git config
* git init
* **git add**
* **git commit**
* **git status**
* git tag
* git log

Branchy Commands
----------------

* **git checkout**
* **git branch**
* **git merge**
* git rebase

Remotey Commands
----------------

* git remote
* **git fetch**
* **git pull**
* **git clone**
* **git push**

Patchy Commands
---------------

* git diff
* git apply
* git format-patch
* git am

---

Estructura y flujos
===================

.fx: fullimage

![](images/220px-Git_data_flow_simplified.png)

---

Branching
=========

> En Git es común trabajar con múltiples ramas.

---

Cheat Sheet
===========

<iframe src="http://byte.kde.org/~zrusin/git/git-cheat-sheet-medium.png" name="CheatSheet" width="100%" height="560" scrolling="auto" frameborder="0">
<p>http://byte.kde.org/~zrusin/git/git-cheat-sheet-medium.png</p></iframe>
