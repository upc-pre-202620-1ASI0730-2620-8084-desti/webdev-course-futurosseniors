# Guion: Lección 7 · Proyecto: tu página de perfil

- **Duración objetivo**: 10 minutos
- **Paquete**: 4 (Proyecto y cierre)
- **Archivos**: `starter-files/leccion-07-proyecto-pagina-de-perfil` → `completed-examples/leccion-07-proyecto-pagina-de-perfil`
- **Pen de práctica**: [PENDIENTE]

## Objetivo

El estudiante integra todo lo aprendido, organiza la página con etiquetas que describen sus partes y la personaliza.

## Escenas

### 1. Portada y meta (0:00 – 0:50) [CANVA]
- **Texto en pantalla**: «Lección 7: Proyecto final» + captura del resultado terminado
- **Narración**: «¡Llegó el momento! Hoy vas a terminar tu página de perfil. Este es el resultado al que vamos a llegar. Usaremos todo lo que aprendiste: etiquetas, listas, imágenes, enlaces y CSS.»

### 2. Dibuja antes de programar (0:50 – 1:50) [CANVA]
- **Texto en pantalla**: boceto de la página dividido en tres zonas: «header = presentación», «main = secciones», «footer = pie»
- **Narración**: «Los programadores muchas veces dibujan antes de escribir código. Nuestra página tiene tres zonas: arriba una presentación con foto, nombre y frase; en el medio el contenido principal con varias secciones; y abajo un pie de página.»

### 3. Ordenar el HTML en partes (1:50 – 4:30) [CODEPEN]
- **Acción**: partiendo del Pen inicial (resultado de la lección 6), reemplazar el `<div class="tarjeta">` por `<header class="tarjeta encabezado">`, `<main class="tarjeta">` con cuatro `<section>`, y `<footer>`.
- **Texto en pantalla**: «`<header>` · `<main>` · `<section>` · `<footer>`: cajas con nombre»
- **Narración**: «En lugar de usar solo `<div>`, HTML tiene cajas con nombre que dicen qué parte de la página son. `<header>` para la presentación, `<main>` para el contenido principal, `<section>` para cada sección y `<footer>` para el pie. Se ven igual, pero ayudan al navegador, a los buscadores y a los lectores de pantalla a entender tu página. Fíjate que el `header` tiene dos clases separadas por un espacio: `tarjeta` y `encabezado`.»

### 4. Botones para los enlaces (4:30 – 6:30) [CODEPEN]
- **Acción**: cambiar la lista de enlaces por dos `<a class="boton">`. Escribir en vivo la regla `.boton` y luego `.boton:hover`.
- **Texto en pantalla**: «`text-decoration: none;` quita el subrayado · `:hover` = cuando pasas el mouse»
- **Narración**: «Vamos a convertir los enlaces en botones. Les pongo la clase `boton` y en CSS les doy fondo azul, letras blancas, `padding` y esquinas redondeadas. `text-decoration: none` quita la línea de abajo. Y un truco extra: `.boton:hover` cambia el estilo cuando pasas el mouse encima. ¡Míralo!»

### 5. Detalles finales (6:30 – 7:50) [CODEPEN]
- **Acción**: agregar `.encabezado { text-align: center; }`, línea bajo los `h2`, espacio entre `li` y estilos del `footer`.
- **Narración**: «Centro la presentación, agrego una línea debajo de cada subtítulo con `border-bottom`, separo un poquito los elementos de las listas y le doy al pie letra pequeña y gris.»

### 6. Hazla tuya (7:50 – 8:50) [CODEPEN]
- **Acción**: cambiar rápidamente textos y colores para mostrar una versión personalizada.
- **Texto en pantalla**: «Cambia: nombre · frase · pasatiempos · metas · colores»
- **Narración**: «Ahora lo más importante: no copies mi página, hazla tuya. Cambia el nombre, tus pasatiempos, tus metas y elige tus colores. Cuando termines, haz clic en "Save" para guardar tu Pen y compartir el enlace con tus amigos.»

### 7. ⏸️ Pausa para practicar (8:50 – 9:20)
- **Texto en pantalla**: «⏸️ Termina y personaliza tu página de perfil»
- **Narración**: «Pausa el video y termina tu página. ¡Tómate tu tiempo!»

### 8. Cierre (9:20 – 10:00) [CANVA]
- **Narración**: «¡Felicitaciones, creaste una página web completa desde cero! En la última lección vas a jugar a ser detective: buscaremos los errores más comunes y te contaré cómo seguir aprendiendo.»
