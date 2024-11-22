# Portafolio Digital (CV) - Michelle Gamboa Palma

## Resumen Tarea 3 - Entrega A
- [En esta entrega](https://github.com/Michelle-7/starter/tree/main/Tareas/Tarea_03) se escribió todo el texto del CV, copiando la info de mi portafolio original.
- Se completó el <head> con el título, un favicon y metadatos.
- Se establecieron secciones junto a sus id (section id="contacto"), párrafos (p), encabezados (h) y una fotografía mía.
- Se utilizaron listas para organizar la información.
- Se añadieron links para contacto teléfonico, por correo y al instagram de la tienda en que trabajo.
- Se añadió un footer.
  
## Cambios realizados para Tarea 3 - Entrega B

## 1. Separación de archivos HTML y CSS:
   - Para la entrega anterior, ya había personalizado algunos aspectos de la página web en CSS, pero en el mismo archivo html. Luego de la última clase en donde analizamos CSS en profundidad, conocí más sobre sus características y separé el código en dos archivos distintos, para mantener un orden y que así cualquier cambio, en estructura o en diseño visual, sea fácil de realizar. 

     **- index.html:** Contiene toda la estructura y contenido de la página.

     **- style.css:** Contiene los estilos visuales y de formato.
     
## 2. Tipografía y estilo de texto
  - La tipografía de la primera entrega era Arial, pero para esta decidí usar **Times News Roman** después de probar con varias fuentes, con el fin de que la página sea más atractiva visualmente.
  - El tamaño de letra se debió aumentar a 18px.
  - Las fechas y los niveles de conocimiento en "Software" e "Idiomas" se cambiaron a **negrita**.
  - Los colores, morado para los encabezados y negro para los textos, se mantuvieron.
    
## 3. Inclusión de líneas divisorias bajo los encabezados:
   - Se agregó una línea de color morado **(#6a0dad)** debajo de los encabezados **Información de contacto**, **Experiencia**, **Formación**, **Habilidades**, **Software** e **Idiomas** en el archivo CSS, utilizando **'border-bottom'** para las etiquetas **'h2'**, para una mejor organización visual.
   - Con **'padding-bottom'** y **'margin-bottom'** se establecieron los márgenes para estas líneas divisorias.

## 4. Estilo de las listas:
   - Se ajustaron las listas para que todas utilicen un estilo de viñetas consistentes (puntos negros), estableciendo **'list-style-type: disc;'** en el archivo CSS. 

## 5. Ajuste del estilo de los enlaces:
   - Los enlaces al número de teléfono, correo y al instagram de la tienda **Wonder Doll Store**, fueron configurados para tener un color morado **(#6a0dad)** con un efecto ***hover***, que subraya el texto al pasar el cursor por encima. Esta característica la conocí consultando a ChatGpt, pues es común en sitios web y quería aplicarla en este caso para que se notara que existe un link.

## 6. Texto alternativo:
   - Con **'alt='** después de mi fotografía añadí un texto alternativo por temas de accesibilidad o en caso de que la imagen no cargue bien.

## 7. Archivo CSS:
   - **Fondo de la página:** Se configuró un fondo rosado claro para toda la página utilizando **'background-color: #fff5f7;'**
   - **Tipografía:** Se estableció una fuente para todo el texto con **'font-family: 'Times New Roman', Times, serif;'** y se alineó con **'text-align: center;**
   - **Secciones:** Se mantuvieron las medidas y margenes realizados en la primera entrega pero esta vez en el archivo CSS.
   - **Imagen:** Se mantuvieron las medidas y margenes de la primera entrega, ahora en el archivo CSS, dejando la imagen con una forma ovalada con las siguientes idicaciones: **img {
  max-width: 200px;
    border-radius: 50%;
    margin-top:10px;
}**

## 8. Publicación sitio web:
  - Creé un nuevo repositorio llamado **Michelle-Gamboa-CV**, en donde subí el archivo html, el css, la imagen del CV y el favicon.
  - Seguí los pasos para que el sitio web se publicara en GitHub Pages y puede visualizarse **[aquí](https://michelle-7.github.io/Michelle-Gamboa-CV/)**


