# Guion - Lección 5: Introducción a CSS

Duración aprox.: 7 minutos
Archivos: `starter-files/leccion-05-introduccion-a-css` y `completed-examples/leccion-05-introduccion-a-css`
Link del Pen: (pendiente)

## Objetivo

El estudiante escribe reglas CSS correctas y usa selectores de etiqueta y de clase para cambiar colores y fuentes.

## Escenas

### Escena 1: Portada y gancho (0:00 - 0:40) - Canva

Texto en pantalla: Lección 5: Introducción a CSS

Lo que se dice: Tu página ya tiene todo su contenido. Ahora vamos a vestirla. Mira el antes y el después [mostrar capturas de la lección 4 y de la lección 7]: todo ese cambio se hace con CSS.

### Escena 2: Anatomía de una regla (0:40 - 2:00) - Canva

Texto en pantalla: diagrama de `h1 { color: blue; }` con flechas: selector: a quién, propiedad: qué cambio, valor: cómo, llaves, dos puntos, punto y coma.

Lo que se dice: Una regla de CSS tiene tres partes. El selector dice a quién le aplicamos el estilo, por ejemplo a todos los `h1`. Dentro de las llaves va la propiedad, lo que queremos cambiar, como el color. Luego dos puntos, el valor, y al final un punto y coma. Si olvidas el punto y coma, la regla puede dejar de funcionar.

### Escena 3: Selector de etiqueta (2:00 - 3:40) - CodePen

Qué se hace: en el panel CSS escribir en vivo las reglas de `body`, `h1` y `h2` del ejemplo terminado.

Texto en pantalla: `font-family` = tipo de letra, `color` = color del texto, `background-color` = color de fondo, `font-size` = tamaño

Lo que se dice: Empiezo por `body`, que es toda la página: le cambio la letra con `font-family`, el color del texto y el color de fondo. Mira cómo cambia todo de golpe. Ahora los títulos: `h1` en azul y más grande con `font-size: 36px`. Y los `h2` también en azul. CodePen conecta el HTML y el CSS por nosotros, por eso los cambios aparecen al instante.

### Escena 4: Colores en código (3:40 - 4:20) - Canva

Texto en pantalla: `blue` = `#0000ff`, busca "selector de color" en Google

Lo que se dice: Puedes escribir colores en inglés como `blue` o `red`, o usar un código que empieza con numeral, como `#1e5aa8`. Si buscas "selector de color" en Google, eliges el color que quieras y copias su código.

### Escena 5: Selector de clase (4:20 - 5:50) - CodePen

Qué se hace: en el HTML agregar `class="destacado"` al primer párrafo; en CSS escribir la regla `.destacado`.

Texto en pantalla: HTML: `class="destacado"`, CSS: `.destacado`

Lo que se dice: ¿Y si quiero cambiar solo un párrafo y no todos? Le pongo un nombre con el atributo `class`. En CSS escribo ese nombre con un punto adelante. Ahora solo ese párrafo sale rosado y en negrita.

### Escena 6: Pausa para practicar (5:50 - 6:30)

Texto en pantalla: Elige tus propios colores y crea la clase `.destacado`

Lo que se dice: Pausa el video y elige tus colores favoritos para el fondo y los títulos. Luego crea tu propia clase.

### Escena 7: Cierre (6:30 - 7:00) - Canva

Texto en pantalla: selector { propiedad: valor; }

Lo que se dice: Ya sabes escribir reglas CSS y usar selectores de etiqueta y de clase. En la siguiente lección vas a convertir tu página en una tarjeta con bordes, espacios y tu foto redonda.