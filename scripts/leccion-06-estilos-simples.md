# Guion - Lección 6: Estilos simples: colores, bordes y centrado

Duración aprox.: 8 minutos
Archivos: `starter-files/leccion-06-estilos-simples` y `completed-examples/leccion-06-estilos-simples`
Link del Pen: (pendiente)

## Objetivo

El estudiante aplica fondo, bordes, esquinas redondeadas, `padding` y `margin`, y centra contenido.

## Escenas

### Escena 1: Portada y repaso (0:00 - 0:30) - Canva

Texto en pantalla: Lección 6: Colores, bordes y centrado

Lo que se dice: En la lección anterior cambiaste colores y letras. Hoy tu página se va a convertir en una tarjeta de perfil, como las de las redes sociales.

### Escena 2: Todo es una caja (0:30 - 2:00) - Canva

Texto en pantalla: dibujo de una caja con capas: contenido > padding > border > margin

Lo que se dice: Para el navegador, cada elemento es una caja. Adentro está el contenido. Alrededor, el `padding`, que es el espacio interior, como el aire dentro de un globo. Luego el borde. Y afuera el `margin`, la distancia entre una caja y otra. Recuerda: `padding` es adentro, `margin` es afuera.

### Escena 3: Crear la tarjeta (2:00 - 4:00) - CodePen

Qué se hace: en HTML envolver todo con `<div class="tarjeta">...</div>`. En CSS escribir en vivo `.tarjeta` con `background-color`, `padding`, `border` y `border-radius`.

Texto en pantalla: `<div>` = una caja para agrupar, `border: 2px solid #1e5aa8;` = grosor, tipo, color

Lo que se dice: Primero agrupo todo el contenido dentro de un `<div>`, que es una caja vacía para agrupar cosas, y le pongo la clase `tarjeta`. En CSS le doy fondo blanco y `padding` de 24 píxeles para que el texto no quede pegado al borde. El borde se escribe con tres valores: grosor, tipo de línea y color. Y con `border-radius` redondeo las esquinas.

### Escena 4: Centrar la tarjeta (4:00 - 5:20) - CodePen

Qué se hace: agregar `max-width: 600px;` y `margin: 0 auto;`. Mostrar cómo se centra al cambiar el tamaño del panel de resultado. Agregar `text-align: center;` al `h1`.

Texto en pantalla: Centrar una caja: `max-width` + `margin: 0 auto;`, Centrar texto: `text-align: center;`

Lo que se dice: La tarjeta ocupa todo el ancho. Le digo que como máximo mida 600 píxeles con `max-width`, y con `margin: 0 auto` el navegador reparte el espacio sobrante a los dos lados: queda centrada. Ojo: para centrar el texto dentro de una caja se usa otra propiedad, `text-align: center`.

### Escena 5: Foto redonda (5:20 - 6:30) - CodePen

Qué se hace: escribir la regla `img` con `display: block`, `margin: 0 auto`, `border-radius: 50%` y `border`.

Texto en pantalla: `border-radius: 50%;` + imagen cuadrada = círculo

Lo que se dice: Ahora el truco favorito: si a una imagen cuadrada le pones `border-radius: 50%`, se vuelve un círculo. Para centrarla le digo `display: block`, que la hace comportarse como una caja, y le pongo `margin: 0 auto`, igual que a la tarjeta.

### Escena 6: Pausa para practicar (6:30 - 7:15)

Texto en pantalla: Crea tu tarjeta, céntrala y haz tu foto redonda

Lo que se dice: Pausa el video y arma tu tarjeta. Prueba otros colores de borde y otros valores de `border-radius` para ver qué pasa.

### Escena 7: Cierre (7:15 - 8:00) - Canva

Texto en pantalla: padding = adentro, margin = afuera, margin: 0 auto = centrado

Lo que se dice: ¡Tu página ya parece una tarjeta de verdad! En la siguiente lección vamos a juntar todo y terminar tu página de perfil.