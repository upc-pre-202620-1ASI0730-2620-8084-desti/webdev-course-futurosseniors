# Guion: Lección 8 · Errores comunes y próximos pasos

- **Duración objetivo**: 6 minutos
- **Paquete**: 4 (Proyecto y cierre)
- **Archivos**: `starter-files/leccion-08-errores-comunes-y-proximos-pasos` (con 7 errores) → `completed-examples/leccion-08-errores-comunes-y-proximos-pasos` (corregido)
- **Pen de práctica**: [PENDIENTE]

## Objetivo

El estudiante reconoce y corrige errores típicos de principiantes y conoce recursos gratuitos para seguir aprendiendo.

## Escenas

### 1. Portada y reto (0:00 – 0:30) [CANVA]
- **Texto en pantalla**: «Lección 8: ¡Detective de errores! 🔍 7 errores escondidos»
- **Narración**: «Todos los programadores se equivocan, incluso los más expertos. La diferencia es que saben buscar sus errores. Esta página tiene siete errores escondidos. ¿Puedes encontrarlos?»

### 2. ⏸️ Reto inicial (0:30 – 0:50)
- **Texto en pantalla**: «⏸️ Abre el enlace de la descripción e intenta encontrar los errores antes de ver la solución»
- **Narración**: «Pausa el video, abre el Pen de la descripción e intenta encontrar los errores tú solo. Luego vuelve para revisarlos juntos.»

### 3. Errores en HTML (0:50 – 2:40) [CODEPEN]
- **Acción**: mostrar cada error, explicarlo y corregirlo en vivo. Resaltar cada línea con un recuadro rojo en la edición.
  1. `<h2>Sobre mí</h3>`: la etiqueta se abre como `h2` y se cierra como `h3`.
  2. `<strong>` sin cerrar: todo el texto siguiente sale en negrita.
  3. `href="https://es.wikipedia.org/wiki/HTML target="_blank"`: falta la comilla de cierre y el botón lleva a una dirección equivocada.
  4. `<img>` sin `alt`: la página se ve bien, pero no es accesible.
- **Texto en pantalla**: «Error 1: apertura y cierre deben coincidir» · «Error 2: lo que abres, lo cierras» · «Error 3: las comillas van en pares» · «Error 4: siempre escribe `alt`»
- **Narración** (ejemplo del error 2): «¿Ves que todo el párrafo salió en negrita? Es porque abrimos `<strong>` pero nunca lo cerramos. El navegador no sabe dónde termina. Lo cierro después de "dibujar"… y listo.»

### 4. Errores en CSS (2:40 – 4:00) [CODEPEN]
- **Acción**: corregir en vivo:
  5. `colr` en lugar de `color`: el título no cambia de color.
  6. Falta `;` después de `background-color: #ffffff`: la tarjeta pierde el fondo blanco y su ancho máximo.
  7. `encabezado` sin punto: la presentación ya no se centra.
- **Texto en pantalla**: «Error 5: revisa la ortografía · Error 6: no olvides el `;` · Error 7: las clases llevan punto»
- **Narración**: «En CSS, si escribes mal una propiedad, el navegador simplemente la ignora, sin avisarte. Por eso es importante revisar con calma.»

### 5. Herramientas para encontrar errores (4:00 – 4:50) [navegador]
- **Acción**: mostrar el W3C Markup Validation Service con el HTML con errores pegado y la lista de errores que muestra.
- **Texto en pantalla**: «validator.w3.org: revisa tu HTML gratis»
- **Narración**: «Hay una herramienta gratuita llamada W3C Validator. Pegas tu HTML y te dice en qué línea está cada error. Otro truco: si una caja no se ve como esperas, ponle temporalmente `border: 2px solid red;` para ver dónde está y cuánto mide.»

### 6. Próximos pasos (4:50 – 5:40) [CANVA]
- **Texto en pantalla**: «Sigue aprendiendo: MDN Web Docs · freeCodeCamp · después: diseño responsivo y JavaScript»
- **Narración**: «¿Y ahora qué? Puedes seguir aprendiendo gratis en MDN Web Docs y en freeCodeCamp, que tienen contenido en español. Los siguientes temas que te recomiendo son el diseño responsivo, para que tu página se vea bien en celulares, y JavaScript, para hacerla interactiva.»

### 7. Cierre del curso (5:40 – 6:00) [CANVA]
- **Texto en pantalla**: «¡Gracias por completar el curso! Comparte tu página 👉 enlace en la descripción»
- **Narración**: «¡Terminaste el curso! Empezaste sin saber qué era HTML y ahora tienes tu propia página web. Compártela usando el formulario de la descripción. ¡Nos vemos en tu próximo proyecto!»
