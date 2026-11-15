# Guion - Lección 4: Imágenes y enlaces

Duración aprox.: 8 minutos
Archivos: `starter-files/leccion-04-imagenes-y-enlaces` y `completed-examples/leccion-04-imagenes-y-enlaces`
Link del Pen: (pendiente)

## Objetivo

El estudiante inserta imágenes y enlaces usando correctamente los atributos `src`, `alt`, `width`, `height`, `href` y `target`.

## Escenas

### Escena 1: Portada y repaso (0:00 - 0:30) - Canva

Texto en pantalla: Lección 4: Imágenes y enlaces

Lo que se dice: Una página sin fotos ni enlaces es como un cuaderno sin dibujos. Hoy vas a ponerle tu foto de perfil y enlaces a tus páginas favoritas.

### Escena 2: La etiqueta img (0:30 - 2:00) - Canva

Texto en pantalla: diagrama de `<img src="..." alt="..." width="160" height="160">` con flechas: de dónde sale la imagen, descripción, tamaño.

Lo que se dice: Para una imagen usamos `<img>`. Es una etiqueta especial: no tiene cierre. Todo lo que necesita va en sus atributos. `src` es la dirección de la imagen. `alt` es una descripción en palabras: la usan los lectores de pantalla de personas con discapacidad visual y aparece si la imagen no carga. `width` y `height` son el ancho y el alto en píxeles.

### Escena 3: Agregar la foto (2:00 - 3:30) - CodePen

Qué se hace: escribir en vivo arriba del `<h1>`:
  ```html
  <img src="https://placehold.co/160x160/png?text=Alex" alt="Foto de perfil de Alex" width="160" height="160">
  ```

Texto en pantalla: Nunca olvides el `alt`

Lo que se dice: Uso una imagen de ejemplo de internet. Escribo `src` con su dirección, un `alt` que describa la foto y el tamaño. Si borro una letra del `src`, mira: la imagen no carga y aparece el texto del `alt`. Por eso es tan útil.

### Escena 4: La etiqueta a (3:30 - 5:00) - Canva y CodePen

Qué se hace: escribir la sección Mis enlaces favoritos con una lista y dos `<a>`.
  ```html
  <li><a href="https://developer.mozilla.org/es/docs/Learn" target="_blank" rel="noopener">MDN: aprende desarrollo web</a></li>
  ```

Texto en pantalla: `href` = a dónde va, texto = lo que se ve, `target="_blank"` = pestaña nueva

Lo que se dice: Los enlaces se hacen con `<a>`. El atributo `href` dice a dónde lleva y el texto entre las etiquetas es lo que la persona ve y puede hacer clic. Si agrego `target="_blank"`, el enlace se abre en otra pestaña y tu página no se cierra. El `rel="noopener"` acompaña a `target` por seguridad; solo cópialo siempre junto a él.

### Escena 5: Probar los enlaces (5:00 - 5:50) - CodePen

Qué se hace: hacer clic en ambos enlaces y mostrar que se abren en pestaña nueva.

Lo que se dice: Hago clic... y se abre en otra pestaña. ¡Funciona!

### Escena 6: Pausa para practicar (5:50 - 6:40)

Texto en pantalla: Agrega tu imagen con `alt` y dos enlaces a tus páginas favoritas

Lo que se dice: Pausa el video. Agrega una imagen y dos enlaces a páginas que te gusten. Si no tienes una foto en internet, usa la misma dirección de ejemplo y cambia la palabra al final por tu nombre.

### Escena 7: Cierre (6:40 - 8:00) - Canva

Texto en pantalla: Resumen del bloque HTML: estructura, textos, listas, imágenes, enlaces

Lo que se dice: ¡Terminaste el bloque de HTML! Tu página ya tiene todo el contenido: título, secciones, listas, foto y enlaces. Pero todavía se ve simple, ¿no? En la siguiente lección empieza la parte divertida: vas a darle estilo con CSS.
