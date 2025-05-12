# Generación de JavaDoc
**Javadoc** es una herramienta incluida en el **JDK** (Java Development Kit) que se utiliza para generar documentación en formato **HTML** a partir de comentarios especiales en el código fuente de **Java**. Aquí se explica el proceso de como generar documentación para proyectos de aplicaciones en Java, con Javadoc. Se usará el **IDE Apache NetBeans** para tal tarea.

---

![Logo de Java con Javadoc](https://lh5.googleusercontent.com/PLfEYBeI7eX5ht1Eubhyh5Tq4pZKHiOW49y_NfbEV6owINbD746k8t3ssaig7TE8N1B6zy6qd6HbgH1VMZmCMkVHa5qLj2Dd_EQE5qpR4EY1WnI9UKi7DCCC64pJZm779GmU2A9i)

---

## Paso 1
-Abrimos nuestro proyecto con NetBeans.
![Apertura del proyecto](javadoc_caps/javadoc1.png)

-Insertamos comentarios con /** ... */ justo antes de las clases, métodos, atributos o interfaces.
![Inserción de comentarios Javadoc](javadoc_caps/javadoc2.png)

## Paso 2
-Hacemos clic en la pestaña **Run** de NetBeans.
![pestaña Run NetBeans](javadoc_caps/javadoc3.png)

-Luego vamos a la opción **Generate Javadoc** con el nombre de nuestro proyecto y hacemos clic para generar el documento.
![Opción Generate Javadoc](javadoc_caps/javadoc4.png)

---

Esperamos unos instantes y ya se nos genera el documento Javadoc en formato HTML, además de que se nos abre automáticamente.
![Documento HTML resultante](javadoc_caps/javadoc5.png)

## Recomendaciones

- Verifica que tengas configurado el `JAVA_HOME` y que el proyecto esté compilado correctamente.
- Asegúrate de incluir etiquetas útiles como `@param`, `@return`, `@author`.

---
