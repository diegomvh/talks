Terminología
============

Repository (repositorio)

Working copy (Copia de trabajo)

# Presenter Notes

La copia de trabajo es la copia local de los ficheros de un repositorio, en un momento del tiempo o revisión específicos.
Todo el trabajo realizado sobre los ficheros en un repositorio se realiza inicialmente sobre una copia de trabajo, de ahí su nombre.
Conceptualmente, es un cajón de arena o sandbox.
Versión determinada de la información que se gestiona.
Hay sistemas que identifican las revisiones con un contador. 
Hay otros sistemas que identifican las revisiones mediante un código de detección de modificaciones (Ej. Git usa SHA1). 
A la última versión se le suele identificar de forma especial con el nombre de HEAD. 
Para poner especial a una revisión concreta se usan los rótulos o tags

---

Terminología
============

Trunk (tronco)

.notes: La línea principal de desarrollo, donde se llevan a cabo los cambios menos complejos del día a día. Idealmente debería poder compilarse y pasar todas las pruebas en todo momento (ver Integración continua). La persona que rompa la compilación, debe ser públicamente humillada, y debe pagar una penitencia en donuts
    
Branch (rama)

.notes: Cuando se van a llevar a cabo cambios importantes que romperán la compilación, pruebas, experimentos o intentos de optimización, debe crearse una nueva rama de desarrollo, con la que no molestemos a los compañeros, esto es un branch: una copia del código o la rama de la que deriva. En esta copia haremos nuestros cambios, integraremos los arreglos que puedan haberse ido haciendo en el trunk, y, una vez terminado el desarrollo en la rama, integraremos (o no) los cambios en el trunk. También puede crearse una rama para una versión terminada, hacer mantenimiento de esta versión sobre esta rama, y continuar el desarrollo de la nueva versión en el trunk.

Tag (etiqueta)

.notes: Etiquetas que sirven para identificar un cierto momento en el desarrollo que queremos preservar. Se utilizan habitualmente para marcar cambios de versión (alfas, betas, RC, RTM) y puntos de interés. Sobre un tag no se puede / no se debe hacer cambios

---

Terminología
============

Checkout (desplegar)
    
.notes:
    Un despliegue crea una copia de trabajo local desde el repositorio. Se puede especificar una revisión concreta, y por defecto se suele obtener la última.

Commit (cometer)

.notes:
    Un commit sucede cuando una copia de los cambios hechos a una copia local es escrita o integrada sobre repositorio.

---

Terminología
============

Version

Change (cambio)

.notes:
    Un cambio representa una modificación específica a un documento bajo control de versiones. La granularidad de la modificación considerada un cambio varía entre diferentes sistemas de control de versiones.
    
Changelist (Lista de cambios)

.notes:
    En muchos sistemas de control de versiones con commits multi-cambio atómicos, una lista de cambios identifica el conjunto de cambios hechos en un único commit. Esto también puede representar una vista secuencial del código fuente, permitiendo que el fuente sea examinado a partir de cualquier identificador de lista de cambios particular.
    
Merge (integración o fusión)

.notes:
    Una integración o fusión une dos conjuntos de cambios sobre un fichero o un conjunto de ficheros en una revisión unificada de dicho fichero o ficheros.
