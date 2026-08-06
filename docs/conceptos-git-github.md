# Conceptos de Git y GitHub

## 1. ¿Qué puede hacer Git aunque GitHub no exista?

Git puede funcionar perfectamente sin necesidad de utilizar GitHub, ya que es una herramienta que se instala directamente en el computador. Con Git puedo crear un repositorio, guardar el historial de todos los cambios que voy realizando en el proyecto y volver a una versión anterior si cometo algún error. También puedo crear diferentes ramas para trabajar en nuevas funciones sin afectar el proyecto principal. En pocas palabras, Git me ayuda a llevar un control organizado de mi trabajo, incluso si nunca me conecto a Internet.

---

## 2. ¿Por qué una rama reduce el riesgo de dañar main?

Las ramas son una forma segura de trabajar porque permiten realizar cambios sin modificar directamente la rama principal, que es donde se encuentra la versión estable del proyecto. De esta manera puedo agregar nuevas funciones, corregir errores o hacer pruebas sin preocuparme por afectar el trabajo que ya está funcionando. Cuando todo está revisado y comprobado, los cambios se pueden integrar a la rama principal mediante un Pull Request. Esto reduce mucho la posibilidad de cometer errores que afecten a todo el equipo.

---

## 3. ¿Qué diferencia existe entre guardar un archivo y crear un commit?

Guardar un archivo simplemente significa que los cambios quedan almacenados en mi computador, pero esos cambios todavía no hacen parte del historial del proyecto. En cambio, cuando realizo un commit, estoy registrando oficialmente una versión del trabajo junto con un mensaje que explica qué fue lo que hice. Gracias a los commits es posible conocer la evolución del proyecto, saber quién realizó cada modificación y recuperar versiones anteriores si llega a ser necesario.

---

## 4. ¿Por qué un Pull Request no es lo mismo que un Merge?

Un Pull Request es una solicitud para que los cambios realizados en una rama sean revisados antes de agregarlos a la rama principal. Durante esa revisión, otros integrantes del equipo pueden leer el código, hacer observaciones, pedir correcciones o aprobar el trabajo. El Merge ocurre después de que el Pull Request ha sido aceptado y consiste en unir definitivamente los cambios con la rama principal. Es decir, el Pull Request sirve para revisar y el Merge sirve para integrar.

---

## 5. ¿Qué evidencia permite saber quién cambió algo y por qué?

La mejor evidencia es el historial de commits que queda registrado en GitHub. Cada commit muestra el nombre del autor, la fecha en la que realizó el cambio y un mensaje donde explica el propósito de la modificación. Además, GitHub permite comparar los cambios realizados mediante el historial y el Pull Request, lo que facilita identificar exactamente qué archivos fueron modificados y por qué se hicieron esos cambios. Esto hace que el trabajo sea mucho más organizado y transparente para todo el equipo.
