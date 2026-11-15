# Guion - Lección 2: Estructura HTML: etiquetas, elementos y atributos

Duración del video: 7 minutos y 17 segundos
Archivos: `starter-files/leccion-02-estructura-html` y `completed-examples/leccion-02-estructura-html`
Link del Pen: (pendiente)

## Objetivo

El estudiante reconoce la estructura básica de un documento HTML y distingue etiqueta, elemento y atributo.

## Escenas

### Escena 1: Portada y repaso (0:00 - 0:36) - Canva

Diapositivas del Canva: 9 y 10

Texto en pantalla: Lección 2: Estructura HTML

Lo que se dice: En la lección anterior viste que HTML es el esqueleto de una página. Hoy vas a conocer cómo se ve ese esqueleto y vas a escribir tu primer título y tu primer párrafo.

### Escena 2: Etiqueta, elemento y atributo (0:36 - 2:17) - Canva

Diapositivas del Canva: 11 y 12

Texto en pantalla: diagrama de `<p title="hola">Mi texto</p>` con flechas: etiqueta de apertura, contenido, etiqueta de cierre, atributo.

Lo que se dice: HTML usa etiquetas, que son palabras entre los signos menor y mayor. Por ejemplo, `<p>` significa párrafo. Casi todas las etiquetas se abren y se cierran; la de cierre lleva una barra: `</p>`. Todo junto, apertura, contenido y cierre, se llama elemento. Y si queremos darle información extra a una etiqueta, usamos un atributo, que se escribe dentro de la etiqueta de apertura con un nombre, un igual y un valor entre comillas.

### Escena 3: El esqueleto de toda página (2:17 - 3:38) - Canva y archivo del repositorio

Diapositiva del Canva: 13

Qué se hace: mostrar `index.html` del ejemplo terminado y resaltar cada parte.

Texto en pantalla: `<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`

Lo que se dice: Toda página empieza con `<!DOCTYPE html>`, que le avisa al navegador que es HTML moderno. Luego viene `<html>`, que envuelve todo. Fíjate en `lang="es"`: es un atributo que dice que la página está en español. Dentro hay dos partes: `<head>`, la cabeza, con información para el navegador como el título de la pestaña, y `<body>`, el cuerpo, con todo lo que tú ves.

### Escena 4: Primer código en CodePen (3:38 - 5:28) - CodePen

Diapositiva del Canva: 14, luego cambias a CodePen

Qué se hace: abrir el Pen inicial (vacío con comentarios). Escribir en vivo:
  ```html
  <h1>¡Hola! Soy Alex</h1>
  <p>Tengo 14 años y estoy aprendiendo a crear páginas web.</p>
  ```

Texto en pantalla: En CodePen solo escribes lo que va dentro de `<body>`

Lo que se dice: CodePen ya prepara el `<head>` y el `<body>` por nosotros, así que solo escribimos el contenido. Escribo `<h1>`, que es el título más importante... mi texto... y lo cierro con `</h1>`. Mira cómo aparece grande en el resultado. Ahora un párrafo con `<p>`... y lo cierro.

### Escena 5: Probando un atributo (5:28 - 6:13) - CodePen

Sigues en CodePen (sin diapositiva)

Qué se hace: escribir `<p title="Este texto aparece gracias al atributo title">Pasa el mouse sobre este párrafo.</p>` y pasar el mouse encima.

Lo que se dice: Probemos un atributo. Le agrego `title` a un párrafo y, si paso el mouse por encima, aparece un mensajito. Ese mensaje lo puso el atributo.

### Escena 6: Pausa para practicar (6:13 - 6:41)

Diapositiva del Canva: 15

Texto en pantalla: Escribe tu `<h1>` con tu nombre y un `<p>` sobre ti

Lo que se dice: Pausa el video y escribe un título con tu nombre y un párrafo contando algo de ti. No olvides cerrar las etiquetas.

### Escena 7: Cierre (6:41 - 7:17) - Canva

Diapositiva del Canva: 16

Texto en pantalla: Abre y cierra tus etiquetas, head = oculto, body = visible

Lo que se dice: Ya conoces el esqueleto de una página, la diferencia entre etiqueta, elemento y atributo, y escribiste tu primer contenido. En la siguiente lección vas a llenar tu página con secciones y listas.
