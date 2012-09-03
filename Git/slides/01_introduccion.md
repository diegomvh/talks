Control de versiones
====================

.fx: centerquote

> Gestión de cambios sobre los elementos de algún producto o una configuración del mismo.

<p class="cite">— <a href="http://wikipedia.org/">Wikipedia</a></p>
  
# Presenter Notes

Aspecto relacionado con la gestión de configuración dentro de la ingeniería de software
Una versión o revisión de un producto, es el estado en el que se encuentra dicho producto 
en un momento dado de su desarrollo o modificación.
-> Aunque un sistema de control de versiones puede realizarse de forma manual,

---

Control de versiones manual
===========================

.fx: fullimage adjustwidth

![](images/humor_montt.jpg)

# Presenter Notes

Es muy aconsejable disponer de herramientas que faciliten esta gestión dando lugar a los llamados 
sistemas de control de versiones o SVC (del inglés System Version Control).

---

Qué es un SCV?
==============

.fx: centerquote

> Software para gestionar el historial de versiones de un proyecto.

# Presenter Notes

Estos sistemas facilitan la administración de las distintas versiones de cada producto desarrollado, 
así como las posibles especializaciones realizadas.

---

Ventajas de un SCV
==================

.fx: bigbullet

* Copias de seguridad
* Deshacer cambios
* Historial de cambios
* Diferentes versiones del proyecto

# Presenter Notes

3 Que, Como, Quien, Cuando hizo un cambio

---

Cuando usar un SCV
==================

.fx: bigbullet

* Trabajos, 
* Tesis, 
* Documentación, 
* Traducciones,
* Software
* ...
* Trabajando en equipo
* Trabajando solo

# Presenter Notes

Cuando se comienza a usar un SCV se tiene la sensación de "Como pude trabajar antes sin esto?" 

---

Algunos SCV
===========

.fx: fullimage adjustwidth

![](images/scvs.jpg)

---

Caracterización
===============

.fx: bigbullet

* Formas de colaborar
    * Exclusiva
    * Colaborativa
* Flujos de trabajo
    * Centralizado
    * Gestor de Integraciones
    * Dictador y Tenientes
* Arquitecturas de almacenamiento
    * Centralizados
    * Distribuidos

# Presenter Notes
Forma en que los usuarios aportan sus cambios luego de obtener el repositorio, exclusiva bloqueando, colaborativa cambiando y resolviendo conflictos
Desventaja del flujo centralizado es que solo el primer desarrollador podrá comprometer sus cambios el otro tendrá que hacer merge y quizá resolver conflictos
Realizar petición para subir cambios a los repositorios gestionados por otros desarroladores

---

Centralizados
=============

.fx: fullimage adjustheight

![](images/18333fig0102-tn.png)

# Presenter Notes

Ventajas tener centralizado todo lo que se esta haciendo con el proyecto, se puede llevar una numeración de las versiones

---

Distribuidos
============

.fx: fullimage

![](images/18333fig0103-tn.png)

# Presenter Notes

No hace falta estar conectado, mayor autonomia
La información esta en todos los desarrolladores, es resistente a caidas, no suele hacer falta backups