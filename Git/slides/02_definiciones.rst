Terminología
============

Repositorio
    Lugar en el que se almacenan los datos
    
Copia de trabajo
    La copia de trabajo es la copia local de los ficheros de un repositorio, en un momento del tiempo o revisión específicos.
    
.. note::
    Todo el trabajo realizado sobre los ficheros en un repositorio se realiza inicialmente sobre una copia de trabajo, de ahí su nombre. Conceptualmente, es un cajón de arena o sandbox.
    
Revisión ("version")
    Versión determinada de la información que se gestiona.
.. note::
    Hay sistemas que identifican las revisiones con un contador. Hay otros sistemas que identifican las revisiones mediante un código de detección de modificaciones (Ej. Git usa SHA1). A la última versión se le suele identificar de forma especial con el nombre de HEAD. Para poner especial a una revisión concreta se usan los rótulos o tags
    
Rotular ("tag", "etiqueta" o "rótulo")
    Darle a alguna versión en desarrollo en un momento preciso un nombre común para asegurarse de reencontrar ese estado de desarrollo posteriormente bajo ese nombre.
.. note::
    En la práctica se rotula a todos los archivos en un momento determinado. Para eso el módulo se "congela" durante el rotulado para imponer una versión coherente. Pero bajo ciertas circunstancias puede ser necesario utilizar versiones de algunos ficheros que no coinciden temporalmente con las de los otros ficheros del módulo.
    Los tags permiten identificar de forma fácil revisiones importantes en el proyecto. Por ejemplo se suelen usar tags para identificar el contenido de las versiones publicadas del proyecto.
    En algunos sistemas se considera un tag como una rama en la que los ficheros no evolucionan, están congelados.
    
Abrir rama ("branch")
    Un módulo puede ser branched o bifurcado en un instante de tiempo de forma que, desde ese momento en adelante se tienen dos copias (ramas) que evolucionan de forma independiente siguiendo su propia línea de desarrollo. El módulo tiene entonces 2 (o más) "ramas". La ventaja es que se puede hacer un "merge" de las modificaciones de ambas ramas, posibilitando la creación de "ramas de prueba" que contegan código para evaluación, si se dedice que las modificaciones realizadas en la "rama de prueba" sean preservadas, se hace un "merge" con la rama principal. Son motivos habituales para la creación de ramas la creación de nuevas funcionalidades o la corrección de errores.

Desplegar ("Check-out", "checkout", "co")
    Un despliegue crea una copia de trabajo local desde el repositorio. Se puede especificar una revisión concreta, y por defecto se suele obtener la última.

"Publicar" o "Enviar"("commit", "check-in", "ci", "install", "submit")
    Un commit sucede cuando una copia de los cambios hechos a una copia local es escrita o integrada sobre repositorio.

Conflicto
    Un conflicto ocurre cuando dos o mas usuarios introducen cambios entre las líneas n1 y n2 de un mismo archivo.

Cambio ("change", "diff", "delta")
    Un cambio representa una modificación específica a un documento bajo control de versiones. La granularidad de la modificación considerada un cambio varía entre diferentes sistemas de control de versiones.
    
Lista de cambios ("changelist", "change set", "patch")
    En muchos sistemas de control de versiones con commits multi-cambio atómicos, una lista de cambios identifica el conjunto de cambios hechos en un único commit. Esto también puede representar una vista secuencial del código fuente, permitiendo que el fuente sea examinado a partir de cualquier identificador de lista de cambios particular.
    
Integración o fusión ("merge")
    Una integración o fusión une dos conjuntos de cambios sobre un fichero o un conjunto de ficheros en una revisión unificada de dicho fichero o ficheros.
