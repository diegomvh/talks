GIT
===

.fx: centerquote

> Sistema de control de versiones distribuido, diseñado y desarrollado por Linus Torvalds para el kernel Linux.

"I'm an egotistical bastard, and I name all my projects after myself. First 'Linux', now 'git'."
<p class="cite">— <a href="https://git.wiki.kernel.org/index.php/GitFaq#Why_the_.27git.27_name.3F">Linus Torvalds</a></p>

# Presenter Notes

2005, BitKeeper
Enfocado en la velocidad
High performance

---

Ventajas
========

.fx: bigbullet

* Distribuido
* Rápido
* Eficiente (branches)
* Seguro (reflog)
* Flexible
* Local
* Pequeño
* Limpio (solo .git)
* GitHub

# Presenter Notes

Cada programador tiene una copia local del historial del desarrollo
Renombrado trabajado por similitudes

---

Desventajas
=========== 

.fx: bigbullet

* Curva de aprendizaje
* Número comandos
* Significado comandos (usuarios subversion)

---

Comandos
========

<div style="float: left; width:50%">
<h2>Local Commands</h2>
<ul>
<li>git config</li>
<li>git init</li>
<li><strong>git add</strong></li>
<li><strong>git commit</strong></li>
<li><strong>git status</strong></li>
<li>git tag</li>
<li>git log</li>
</ul>
<h2>Branchy Commands</h2>
<ul>
<li><strong>git checkout</strong></li>
<li><strong>git branch</strong></li>
<li><strong>git merge</strong></li>
<li>git rebase</li>
</ul>
</div>

<div style="float: right; width:50%">
<h2>Remotey Commands</h2>
<ul>
<li>git remote</li>
<li><strong>git fetch</strong></li>
<li><strong>git pull</strong></li>
<li><strong>git clone</strong></li>
<li><strong>git push</strong></li>
</ul>
<h2>Patchy Commands</h2>
<ul>
<li>git diff</li>
<li>git apply</li>
<li>git format-patch</li>
<li>git am</li>
</ul>
</div>

---

Estructura y flujos
===================

.fx: fullimage adjustheight

![](images/220px-Git_data_flow_simplified.png)

---

Branching
=========

> En Git es común trabajar con múltiples ramas.

Convención
----------

![](images/convention.png)

# Presenter Notes

Fuerte apoyo al desarrollo no lineal, es rápido y eficiente en el manejo de ramas
Cuando iniciamos un repositiorio estamos en la rama master, es fasil saltar de rama en rama como un mono,
->hay una convención básica como para trabajar

---

Doit
====

.fx: centerquote

> Me lo contaron y lo olvidé; lo vi y lo entendí; lo hice y lo aprendí.

<p class="cite">— <a href="http://es.wikiquote.org/wiki/Confucio">Confucio</a></p>


# Presenter Notes

Por lo menos vamos a intentar hasta verlo :)
Hacer un init, agregar archivos

---

Cheat Sheet
===========

.fx: fullimage adjustheight

![](http://byte.kde.org/~zrusin/git/git-cheat-sheet-medium.png)
