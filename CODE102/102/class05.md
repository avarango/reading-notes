# CSS (Cascading Style Sheets)

1. ¿Cuál es el propósito de CSS?
   El CSS es un lenguaje informático. Su propósito es definir el estilo y presentación del documento
   html, separando el contenido del diseño. La CSS permite a los programadores a que puedan ver los elementos HTML
   en una página incluyendo aspectos de diseño como color, fuente, espaciado y más.
3. ¿Cuáles son las tres formas de insertar CSS en tu proyecto?
   - Puedes simplemento incorporar los estilos directamente en el HTML usando el atributo `style`:
     
     `<p> style="color: red; font-size: 12px;">Texto</p>`
   - Usar la sección style en la cabecera HTML.
   - 
    ` <style>`

        `p {`
     
            `color: red;`
     
            `font-size: 12px;`
     
        `}`
     
   `</style>`
   - Enlazar un archivo  CSS con el HTML.
     
    ` <link href="styles/style.css" rel="stylesheet" type="text/css" />`

5. Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos `<p>`

   p {
   
   color:red;
   
   }
