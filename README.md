# 📚 Evaluación Continua – Lenguaje de Marcas  
Proyecto realizado para la asignatura Lenguaje de Marcas, impartida por **Raúl Albiol** en **Prometeo**.  
Autor: **Jorge Sánchez** – Estudiante de DAW

---

## 📝 Descripción del proyecto

Este repositorio contiene el trabajo correspondiente a la parte práctica de la evaluación continua de Lenguaje de Marcas. El objetivo es trabajar con XML, XSD y DTD en diferentes ejercicios, validando correctamente la estructura y los datos según lo aprendido en clase.

La nota de este trabajo forma parte del **40%** de la evaluación continua, concretamente un **10%**, ya que el **30%** restante se corresponde con la primera entrega (la web).


---

## 📂 Estructura del proyecto

El proyecto se organiza en **tres carpetas**, una por ejercicio:
📦 ProyectoEvaluacionContinua
┣ 📁 ejercicio1
┃ ┣ 📄 ejercicio1.xml
┃ ┣ 📄 ejercicio1.xsd
┃ ┗ 📄 ejercicio1.dtd
┣ 📁 ejercicio2
┃ ┣ 📄 ejercicio2.xml
┃ ┣ 📄 ejercicio2.xsd
┃ ┗ 📄 ejercicio2.dtd
┗ 📁 ejercicio3
┣ 📄 ejercicio3.xml
┣ 📄 ejercicio3.xsd
┗ 📄 ejercicio3.dtd

---

## ✅ Validación de documentos

Cada XML incluye un comentario en la cabecera que **desactiva temporalmente la referencia al DTD**:

```xml
<!-- Referencia al DTD comentada para evitar conflicto con la validación XSD -->
Esto permite que la validación priorice el esquema XSD sin errores.
Si en algún momento se quiere comprobar el DTD, únicamente debe:

Eliminar la referencia al XSD dentro del XML.

Quitar el comentario de la línea del DTD.

🎯 Objetivo académico

El propósito de esta práctica es reforzar los conocimientos en:

Creación y estructuración de documentos XML

Definición de esquemas XSD

Construcción de DTD

Validación y comprobación de datos
