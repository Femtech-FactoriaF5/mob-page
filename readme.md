# Proyecto: Group Page

## Intro
En este proyecto construiremos una **group page** o **mob page**). Una página grupal suele corresponder con la sección **about us** de un sitio web.

Una buena "About page" debe ser original y diferente. Debe ofrecer una visión de cómo es el negocio. Y suelen incluir intereses personales, fotos y pequeñas historias que contribuyen a escribir la historia de la compañía, grupo, etc.

## Objetivo

Diseñar y construir una página de grupo que responda a las siguientes cuestiones:

- ¿Cual es la **misión** de este grupo? Debe decir algo que se recuerde.
- ¿Un resumen de la **historia** del grupo? Como el grupo no hace demasiado tiempo que está junto se debería indicar qué os ha traído hasta aquí.
- ¿Qué os distingue de otros grupos similares? Cual es vuestra **idea**.
- ¿Cual es vuestro **portfolio**?
- ¿Quiénes formais parte del **grupo**?

## Requisitos de Usuario
- La página debe contar con los siguientes elementos:
  - Un menú con los apartados que vamos a incluir. Por ejemplo:
    - Misión
    - Historia
    - Ídea
    - Proyectos
    - Miembros

- El apartado misión debe incluir, al menos:
  - Una imagen con un texto y un título. Algo similar a esto:
![misión](https://i.imgur.com/yFOaJqo.png).

- El apartado historia del grupo puede contener un pequeño vídeo o galería de fotografías, memes, imágenes, ... Puede contener o no texto.

- La ídea debe estar expresada de forma original. Puede ser mediante animaciones, texto, etc.

- Proyectos debe ser una galería de imágenes con una breve descripción. Deben ser clicables para navegar a las webs descritas. Deben tener algún efecto de hovering.

- Miembros estará formado por una serie de cards clicables que deberán conectar con la página personal de cada miembro (futuro desarrollo), también con efecto hover.

## Requisitos técnicos

- Se deberán utilizar etiquetas semánticas.
- Debera existir una hero image con título centrado.
- Los apartados se incluirán en la misma página y la navegación del menú será vía parciales (**"#"**).
- Se debe incluir alguna fuente vía cdn o instalada.
- Se debe incluir resetCSS.
- La página debe ser responsive y adaptativa. Debe haber un formato móvil con menú hamburguesa (no es necesario que sea funcional).
- La aplicación se subirá a GitHub con la siguiente estructura:
 ```html
        proyecto/
        ├─ images/
        │  ├─ /* all images go here */
        ├─ styles/
        │  ├─ /*all style sheets go here*/
        ├─ index.html
        ├─ readme.md
 ```
- En el readme del repositorio se deberá incluir un link al diseño de la aplicación.
- La aplicación debe desplegarse como **gh-page**.

## Entrega

- Se enviará vía slack la url del repositorio de GitHub y la url de la presentación.

## Rúbrica de Evaluación del Proyecto

|Elemento|3|2|1|
|---|---|---|---|
|Diseño|La página está bien diseñada. Los elementos tienen espacio, los fondos son claros y no utilizan colores absolutos. Hay coherencia en la gama de colores. Los elemento están adecuadamente resaltados. El tamaño de las fuentes es adecuado para su lectura. No hay más de 18 - 20 palabras por línea.|La página es correcta, algunos elementos podrían mejorar en su disposición. La gama de colores no está del todo relacionada. Los colores no permiten distinguir del todo los elementos importantes. Los textos se muestran algo apelotonados.|La página tiene un mal diseño. No se han tenido cuidado en la elección de colores y tipografías. El texto aparece apelotonado.|
|Contenido|El contenido es original. Está redactado en un lenguaje adecuado. No hay faltas de ortografía. Las imágenes contribuyen a la comprensión del texto.| El contenido presenta una redacción algo confusa o contiene algunos elementos superfluos|Existen faltas de ortografía, el contenido no está bien redactado o es confuso.|
|Navegación|Los enlaces llevan correctamente a los apartados mencionados. Existe una navegación para recuperar la página inicial.|Algún enlace no funciona o no se puede recuperar la página inicial.|No funciona ningún enlace.|
|Accesibilidad|Los elementos semánticos están bien seleccionados y corresponden al contenido mostrado. Las imágenes tienen informado el atributo "alt"|Falta algún elemento semántico o no es el adecuado|Faltan todos los elementos semánticos o los que hay no se corresponden al contenido.|
|Buenas Prácticas|El código utilizado es el imprescindible. El código está documentado y es autoexplicativo|Existen clases css superfluas. Existen algunos elementos html superfluos. Falta documentación.|El código es confuso o abusa del uso de estructuras superfluas. Hay reglas CSS inválidas.|
|Trabajo cooperativo|Todas las miembro del equipo contribuyen por igual al proyecto. Hay disposición a colaborar entre todas. Las posibles diferencias se han resuelto de manera constructiva.|Hay algún desequilibrio en la distribución de trabajo|El equipo no ha funcionado.|
