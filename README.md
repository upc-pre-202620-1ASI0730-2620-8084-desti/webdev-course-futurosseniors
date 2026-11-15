# Fundamentos de Desarrollo Web: crea tu primera página con HTML y CSS

## Resumen del Curso

Este curso de aproximadamente 1 hora enseña a estudiantes de secundaria a crear una página web sencilla con HTML y CSS. A lo largo de 8 lecciones cortas construirás, paso a paso, **una sola página de perfil personal**: cada lección agrega algo nuevo a lo que hiciste en la anterior. **¡No necesitas descargar ni instalar nada!** Solo abre tu navegador.

- **Duración total**: ~60 minutos (8 lecciones de 6 a 10 minutos)
- **Público objetivo**: Estudiantes de 12 a 17 años sin experiencia en programación
- **Prerrequisitos**: Ninguno
- **Herramientas necesarias**: solo tu navegador web (Chrome, Firefox, Safari o Edge) y [CodePen](https://codepen.io), que es gratis y funciona en línea
- **Resultado final**: Tu propia página de perfil con foto, listas, enlaces y estilos
- **Repositorio de código fuente**: [webdev-course-futurosseniors](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors)
- **Lista de reproducción**: [Ver todas las lecciones en YouTube](https://www.youtube.com/playlist?list=PLerLN6CaKp7o)

### Ruta de aprendizaje

| Bloque | Lecciones | Qué aprenderás |
|---|---|---|
| 1. Contenido con HTML | 1, 2, 3, 4 | Qué es una página web, etiquetas, textos, listas, imágenes y enlaces |
| 2. Estilo con CSS | 5, 6 | Selectores, colores, fuentes, bordes y centrado |
| 3. Proyecto y cierre | 7, 8 | Terminar tu página de perfil, corregir errores y qué aprender después |

---

## Secuencia de Lecciones

### Bloque 1: Contenido con HTML

#### Lección 1: ¿Qué es un sitio web? (5 minutos y 58 segundos)

- **Descripción**: Descubre qué pasa cuando abres una página web y por qué HTML y CSS son sus piezas básicas. Abrirás CodePen por primera vez.
- **Enlace**: [Ver la lección](https://youtu.be/hfDvDBgne0k)
- **Consejos clave**:
  - Sitio web = contenido (**HTML**) + apariencia (**CSS**). HTML es el esqueleto; CSS es la ropa.
  - En cualquier página, haz clic derecho → **Inspeccionar** para ver su HTML real.
  - No necesitas memorizar nada: el objetivo es entender la idea.
- **Empieza a programar**: [Abrir en CodePen](https://codepen.io/editor/Msa-ware/pen/01a1cd22-66df-7483-a5ce-01793d604130) (no necesitas registrarte)

#### Lección 2: Estructura HTML: etiquetas, elementos y atributos (7 minutos y 17 segundos)

- **Descripción**: Conoce el esqueleto de toda página (`<!DOCTYPE html>`, `<html>`, `<head>`, `<body>`) y la diferencia entre etiqueta, elemento y atributo. Escribe tu primer título y tu primer párrafo.
- **Enlace**: [Ver la lección](https://youtu.be/em0WxdLbrFE)
- **Consejos clave**:
  - Casi todas las etiquetas se abren `<p>` y se cierran `</p>`.
  - Lo que va en `<head>` es información para el navegador; lo que va en `<body>` es lo que se ve.
  - Un **atributo** da información extra a una etiqueta: `<html lang="es">`.
- **Práctica**: [Clic para programar](https://codepen.io/editor/Msa-ware/pen/01a1cc16-740c-700e-973e-c7dd74a8c78f)

#### Lección 3: Textos y listas (7 minutos)

- **Descripción**: Organiza tu página con títulos (`<h1>` a `<h6>`), párrafos (`<p>`), texto importante (`<strong>`, `<em>`) y listas (`<ul>`, `<ol>`, `<li>`).
- **Enlace**: [Ver la lección](https://youtu.be/kGPFOk86c6c)
- **Consejos clave**:
  - Usa un solo `<h1>` por página y `<h2>` para las secciones.
  - `<ul>` = lista con viñetas; `<ol>` = lista numerada. Cada elemento va en `<li>`.
- **Práctica**: [Clic para programar](https://codepen.io/editor/jimopbja-the-sans/pen/01a1db27-ce8b-7022-bcbd-ac692cddc5ad)

#### Lección 4: Imágenes y enlaces (8 minutos)

- **Descripción**: Agrega tu foto de perfil con `<img>` y enlaces a tus páginas favoritas con `<a>`. Aprende los atributos `src`, `alt`, `href` y `target`.
- **Enlace**: [Ver la lección](https://youtu.be/SiYTj6elxc4)
- **Consejos clave**:
  - `<img>` no tiene etiqueta de cierre.
  - Siempre escribe un `alt` que describa la imagen: ayuda a personas con discapacidad visual.
  - `target="_blank"` abre el enlace en una pestaña nueva.
- **Práctica**: [Clic para programar](https://codepen.io/editor/jimopbja-the-sans/pen/01a1db29-3273-7e96-8b54-85043292105e)

### Bloque 2: Estilo con CSS

#### Lección 5: Introducción a CSS (7 minutos)

- **Descripción**: Aprende cómo se escribe una regla CSS (selector, propiedad y valor) y cambia por primera vez colores y fuentes. Conoce los selectores de etiqueta y de clase.
- **Enlace**: [Ver la lección](https://youtu.be/2tS7VE-bo7c)
- **Consejos clave**:
  - Estructura de una regla: `h1 { color: blue; }`
  - Después de la propiedad van dos puntos `:` y al final punto y coma `;`.
  - Una clase se escribe `class="destacado"` en HTML y `.destacado` en CSS.
- **Práctica**: [Aplicar estilo con un clic](https://codepen.io/editor/Msa-ware/pen/01a1d639-d299-72a9-9b50-263e576e43a3)

#### Lección 6: Estilos simples: colores, bordes y centrado (8 minutos)

- **Descripción**: Convierte tu página en una tarjeta: fondo, bordes, esquinas redondeadas, espacios (`padding` y `margin`) y contenido centrado. ¡Tu foto será redonda!
- **Enlace**: [Ver la lección](https://youtu.be/zQcOkcPOsRc)
- **Consejos clave**:
  - `padding` = espacio **dentro** de la caja; `margin` = espacio **fuera** de la caja.
  - Para centrar una caja: dale `max-width` y `margin: 0 auto;`.
  - `border-radius: 50%;` en una imagen cuadrada la vuelve un círculo.
- **Práctica**: [Clic para programar](https://codepen.io/editor/Msa-ware/pen/01a1d63b-0742-72c0-ad72-5f7c42fe3003)

### Bloque 3: Proyecto y cierre

#### Lección 7: Proyecto: tu página de perfil (10 minutos)

- **Descripción**: Junta todo lo aprendido. Ordena tu página en `<header>`, `<main>`, `<section>` y `<footer>`, convierte tus enlaces en botones y personalízala con tus datos.
- **Enlace**: [Ver la lección](https://youtu.be/sClsCTWrlHU)
- **Consejos clave**:
  - Haz un dibujo rápido en papel de tu página antes de programar.
  - Avanza por partes: un bloque de HTML, sus estilos, revisas y continúas.
  - ¡Cambia los textos y colores para que sea **tuya**!
- **Proyecto final**: [Crea tu perfil](https://codepen.io/curso-web-html-css/pen/YPZMPNY)

#### Lección 8: Errores comunes y próximos pasos (6 minutos)

- **Descripción**: Juega a ser detective: encuentra y corrige 7 errores típicos de principiantes. Además, descubre dónde seguir aprendiendo.
- **Enlace**: [Ver la lección](https://youtu.be/H8skdJS9jws)
- **Consejos clave**:
  - Si algo no funciona, revisa: etiquetas sin cerrar, comillas que faltan, `;` olvidados y nombres mal escritos.
  - Usa el validador gratuito [W3C Markup Validation Service](https://validator.w3.org/#validate_by_input).
  - Sigue aprendiendo en [MDN Web Docs](https://developer.mozilla.org/es/docs/Learn).
- **Práctica**: [Encuentra los errores](https://codepen.io/curso-web-html-css/pen/GgWLgrG)

---

## Todas las Actividades Prácticas

| Lección | Actividad | Archivo inicial | Ejemplo terminado | Empezar a programar |
|---|---|---|---|---|
| 1 | Enciende el CSS de tu primera página | [starter](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/starter-files/leccion-01-que-es-un-sitio-web) | [completo](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/completed-examples/leccion-01-que-es-un-sitio-web) | [CodePen](https://codepen.io/editor/Msa-ware/pen/01a1cd22-66df-7483-a5ce-01793d604130) |
| 2 | Tu primer título y párrafo | [starter](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/starter-files/leccion-02-estructura-html) | [completo](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/completed-examples/leccion-02-estructura-html) | [CodePen](https://codepen.io/editor/Msa-ware/pen/01a1cc16-740c-700e-973e-c7dd74a8c78f) |
| 3 | Secciones y listas de tu perfil | [starter](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/starter-files/leccion-03-textos-y-listas) | [completo](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/completed-examples/leccion-03-textos-y-listas) | [CodePen](https://codepen.io/editor/jimopbja-the-sans/pen/01a1db27-ce8b-7022-bcbd-ac692cddc5ad) |
| 4 | Foto de perfil y enlaces favoritos | [starter](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/starter-files/leccion-04-imagenes-y-enlaces) | [completo](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/completed-examples/leccion-04-imagenes-y-enlaces) | [CodePen](https://codepen.io/editor/jimopbja-the-sans/pen/01a1db29-3273-7e96-8b54-85043292105e) |
| 5 | Tus primeros colores y fuentes | [starter](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/starter-files/leccion-05-introduccion-a-css) | [completo](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/completed-examples/leccion-05-introduccion-a-css) | [CodePen](https://codepen.io/editor/Msa-ware/pen/01a1d639-d299-72a9-9b50-263e576e43a3) |
| 6 | Tarjeta centrada con foto redonda | [starter](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/starter-files/leccion-06-estilos-simples) | [completo](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/completed-examples/leccion-06-estilos-simples) | [CodePen](https://codepen.io/editor/Msa-ware/pen/01a1d63b-0742-72c0-ad72-5f7c42fe3003) |
| 7 | Página de perfil completa | [starter](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/starter-files/leccion-07-proyecto-pagina-de-perfil) | [completo](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/completed-examples/leccion-07-proyecto-pagina-de-perfil) | [CodePen](https://codepen.io/curso-web-html-css/pen/YPZMPNY) |
| 8 | Detective de errores | [starter](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/starter-files/leccion-08-errores-comunes-y-proximos-pasos) | [completo](https://github.com/upc-pre-202620-1asi0730-8084-destilatech/webdev-course-futurosseniors/tree/main/completed-examples/leccion-08-errores-comunes-y-proximos-pasos) | [CodePen](https://codepen.io/curso-web-html-css/pen/GgWLgrG) |

- **Comparte**: #WebDevBeginners

---

## Cómo usar este repositorio

No necesitas instalar nada. Tienes dos formas de practicar:

1. **La más fácil (recomendada)**: abre el enlace de CodePen de cada lección. El código inicial ya está cargado. Para guardar tus cambios, haz clic en **Fork** (necesitas una cuenta gratuita de CodePen solo si quieres guardar).
2. **Desde GitHub**: entra a la carpeta de la lección en `starter-files/`, abre `index.html` y `style.css`, y copia su contenido en un [nuevo Pen](https://codepen.io/pen/):
   - En el archivo `index.html` del Pen, borra lo que viene por defecto y pega todo el contenido de `index.html`.
   - En el archivo `style.css` del Pen, borra lo que viene por defecto y pega todo el contenido de `style.css`.

### Estructura del repositorio

```
webdev-course-futurosseniors/
├── README.md                 ← Este plan de curso
├── starter-files/            ← Código inicial de cada lección (con instrucciones de práctica)
├── completed-examples/       ← Resultado esperado al terminar cada lección
└── scripts/                  ← Guiones de narración de cada video
```

Cada lección usa el mismo nombre de carpeta en las tres carpetas, por ejemplo `leccion-04-imagenes-y-enlaces`. El ejemplo terminado de una lección es el punto de partida de la siguiente.

---

**¡Gracias por completar el curso!**

---

## Resumen de la Elaboración en Equipo

El curso se dividió en cuatro paquetes de trabajo equivalentes. Cada integrante fue responsable de dos lecciones completas (guion, código inicial, ejemplo terminado, Pen de práctica, grabación y edición) y de una tarea transversal.

| Paquete | Lecciones | Duración | Tarea transversal | Responsable |
|---|---|---|---|---|
| 1. Bases de HTML | 1 y 2 | ~13 min | Plan de curso (`README.md`) y exportación a PDF | Jairo Mathias Santiago Atanacio |
| 2. Contenido HTML | 3 y 4 | 15 min | Cuenta del equipo en CodePen y enlaces de práctica | Mario Alonso Fernandez Seer |
| 3. Estilos CSS | 5 y 6 | 15 min | Plantilla visual compartida (diapositivas y textos en pantalla) | Jean Pierre Condor Sandoval |
| 4. Proyecto y cierre | 7 y 8 | 16 min | Lista de reproducción de YouTube | Pierina Marysabel Almandroz Carbajal |

---

## Elaboración

Universidad Peruana de Ciencias Aplicadas

Carrera de Ingeniería de Software

Período 202620

1ASI0730 Aplicaciones Web

NRC 8084

**Nombre del equipo**: FuturosSeniors

**Líder del equipo**: Mario Alonso Fernandez Seer

**Integrantes del equipo**:

- Mario Alonso Fernandez Seer
- Jairo Mathias Santiago Atanacio
- Pierina Marysabel Almandroz Carbajal
- Jean Pierre Condor Sandoval

**Fecha de entrega**: 14 de noviembre de 2026
