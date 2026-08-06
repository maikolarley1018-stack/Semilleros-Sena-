# Flujo de trabajo con Git y GitHub

## 1. Crear el repositorio

El primer paso es crear el repositorio en GitHub, ya que allí se almacenará todo el proyecto y será el lugar donde los integrantes del equipo podrán trabajar de forma organizada.

**¿Qué riesgo evita?**

Evita que cada integrante tenga una copia diferente del proyecto y que no exista un lugar central donde guardar y controlar los cambios.

---

## 2. Crear una rama

Después de crear el repositorio, se crea una rama de trabajo (por ejemplo, `feature-presentacion`). En esta rama se realizan todas las modificaciones sin afectar la rama principal (`main`).

**¿Qué riesgo evita?**

Evita dañar la versión principal del proyecto mientras se realizan cambios o pruebas que aún no han sido revisados.

---

## 3. Hacer commits

A medida que se avanza en el proyecto, se realizan commits para guardar el progreso con mensajes que expliquen claramente qué se modificó.

**¿Qué riesgo evita?**

Evita perder el trabajo realizado y permite volver a una versión anterior si ocurre algún error. Además, facilita saber quién hizo cada cambio.

---

## 4. Abrir un Pull Request

Cuando el trabajo de la rama está terminado, se crea un Pull Request para solicitar que los cambios sean revisados antes de integrarlos a la rama principal.

**¿Qué riesgo evita?**

Evita que se agreguen cambios sin ser revisados, reduciendo la posibilidad de errores en el proyecto.

---

## 5. Corregir las observaciones

Si el revisor encuentra algún error o propone una mejora, se realizan las correcciones necesarias en la misma rama y se registra un nuevo commit.

**¿Qué riesgo evita?**

Evita integrar información incompleta, con errores o que no cumpla con los criterios de calidad establecidos por el equipo.

---

## 6. Revisar nuevamente

El revisor verifica que las observaciones fueron corregidas y, si todo está correcto, aprueba el Pull Request.

**¿Qué riesgo evita?**

Evita que se aprueben cambios que aún presentan problemas o que no cumplen con lo solicitado.

---

## 7. Fusionar (Merge)

Finalmente, cuando el Pull Request ha sido aprobado, se realiza el Merge para integrar los cambios de la rama de trabajo en la rama principal (`main`).

**¿Qué riesgo evita?**

Evita que la rama principal reciba cambios sin autorización y garantiza que únicamente se integren modificaciones revisadas y aprobadas.
