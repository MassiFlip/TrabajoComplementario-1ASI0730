##  ¿Qué es un Sitio Web?

Un sitio web se define como un **conjunto interrelacionado de archivos** —incluyendo páginas en formato HTML, recursos multimedia y hojas de estilo— alojados en un servidor web y accesibles mediante un navegador. Estos sitios representan una unidad informativa o comunicativa en el ecosistema digital, **según Britannica (s. f.)**.

A nivel técnico, las páginas web se construyen primordialmente mediante lenguajes de marcado y estilos como **HTML5 y CSS3**, que permiten definir la estructura y la presentación visual, **como se describe en el artículo de Jain et al. (2024)**. La investigación sobre la usabilidad web muestra que factores como la facilidad de navegación, la claridad del contenido y la consistencia visual son determinantes para la satisfacción del usuario, **según Sharma y Tripathi (2023)**.

Desde un enfoque comunicativo, los sitios web constituyen un medio digital esencial para la transmisión de información. Un estudio sistemático confirma que la **arquitectura de información y la navegación** son los aspectos más cruciales para garantizar una experiencia positiva, **tal como documentan Uğraş et al. (2016)**.

-----

##  Estructura Básica de HTML

**HTML (HyperText Markup Language)** es el lenguaje de marcado estándar para estructurar el contenido de las páginas web, definiendo la jerarquía semántica de los elementos. **Según Sharma y Aakanksha (2018)**, HTML "es el lenguaje de marcado estándar para desarrollar páginas web, describiendo la estructura del contenido y su significado semántico".

La estructura fundamental de un documento HTML incluye: `<!DOCTYPE html>`, el elemento raíz `<html>`, la sección de metadatos `<head>` y el contenido visible `<body>`.

HTML 5 introduce **elementos semánticos** (`<header>`, `<nav>`, `<footer>`) que optimizan la accesibilidad y la organización. La **guía de MDN sobre estructuración de contenido (s. f. a)** subraya que el **HTML semántico es "crítico para la accesibilidad, la optimización para motores de búsqueda y la mantenibilidad"**.

La separación de responsabilidades entre HTML (estructura), CSS (presentación) y JavaScript (interactividad) sigue siendo una práctica esencial. Sin embargo, **Anderson (2023)** menciona que los *frameworks* modernos están "replanteando" esta división.

-----

##  Elementos HTML Comunes

Los elementos básicos de HTML son los bloques constructivos de cualquier sitio web, incluyendo encabezados (`<h1>`–`<h6>`), párrafos (`<p>`), listas (`<ul>`, `<ol>`, `<li>`), imágenes (`<img>`) y enlaces (`<a>`).

El uso correcto de estos elementos es crucial para la accesibilidad y la interpretación. **Duckett (2011)** enfatiza que el uso correcto de los elementos HTML "no solo determina cómo se muestra la información, sino también cómo se interpreta y clasifica por motores de búsqueda y tecnologías de asistencia".

Asimismo, el **Yale University Usability Lab (s. f.)** explica que la combinación de una estructura HTML semántica y un CSS bien aplicado "hace que el contenido de un sitio web sea más fácil de consumir para todos, especialmente para personas con discapacidad visual".

-----

##  Introducción a CSS

**CSS (Cascading Style Sheets)** es el lenguaje responsable de controlar la presentación visual de los documentos HTML, permitiendo definir colores, fuentes y diseños adaptables. La **guía de MDN sobre los básicos de CSS (s. f. b)** indica que "CSS permite crear páginas web con un aspecto excelente aplicando estilos a los elementos HTML, asegurando consistencia y reusabilidad".

El CSS se aplica mediante reglas con un selector y un bloque de declaraciones. Puede aplicarse de forma **en línea**, **interna** o, preferiblemente, **externa** (con un archivo `.css`) por su escalabilidad.

El principio de separación de contenido y presentación es fundamental. Una investigación publicada en **ResearchGate (2024)** destaca que CSS 3 ha evolucionado para incluir *layouts* adaptables, animaciones y compatibilidad multidispositivo, consolidándolo como un componente esencial.

El uso coherente de hojas de estilo externas mejora la percepción de profesionalismo y reduce errores de diseño, **según Nielsen Norman Group (2018)**. Además, el **Yale University Usability Lab (s. f.)** añade que un CSS bien implementado puede ofrecer estilos alternativos para usuarios con limitaciones visuales sin afectar la estructura fundamental del contenido.

-----

##  Estilos Simples en CSS

Para centrar elementos horizontalmente, una técnica clásica es aplicar `margin: 0 auto;` sobre un elemento de bloque con un ancho definido. De hecho, la **documentación oficial de MDN (1)** indica que `div { width:50%; margin:0 auto; }` "centrará el div horizontalmente".

Para texto en línea, la propiedad `text-align: center;` alinea el contenido. **Según MDN (2)**, la directiva `center` significa que "El contenido en línea se centra dentro de la línea de la caja". En técnicas modernas como Flexbox, **según MDN (3)**, `justify-content: center` coloca los ítems flexibles "hacia el centro de la línea". CSS Grid también facilita el centrado en dos dimensiones; **como explica LenguajeCSS (4)**, "Grid incorpora un sistema para alinear elementos... en dos dimensiones, así como centrar o colocar elementos hijos del contenedor Grid".

Para aplicar colores, la propiedad `color` define el color del texto. **Según Bartolomé Sintes Marco (5)**, "la propiedad `color` permite establecer el color del texto". La propiedad `background-color` define el color de fondo. Como señalan **los tutoriales de Bartolomé Sintes Marco (6)**, "la propiedad `background-color` establece el color de fondo de cualquier elemento".

En cuanto a bordes, la propiedad abreviada `border` permite definir en una sola regla el grosor, estilo y color. **Según MDN (7)**, "La propiedad `border` permite definir en una única regla todos los bordes de los elementos seleccionados". También existen propiedades específicas para cada lado, **como se explica en Bartolomé Sintes Marco (8)**.

-----

## 📄 Creación de una Página Web Básica

Una página web básica en HTML5 tiene una estructura estándar: **`<!DOCTYPE html>`**, **`<html>`**, **`<head>`** (con **`<meta charset="UTF-8">`** y **`<title>`**) y **`<body>`**.

Dentro del `<body>` se organizan los elementos semánticos: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>` y `<footer>`. **Como explica la referencia de Eniun (9)**, "una etiqueta semántica describe su significado. Por ejemplo: `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<aside>`, `<footer>`". Este uso de etiquetas semánticas es fundamental.

-----

##  Recomendaciones y Errores Comunes

Al iniciarse en el desarrollo web, es vital seguir buenas prácticas:

  * **Etiquetas Completas y Válidas:** Siempre cierre las etiquetas. Si se deja abierta una etiqueta, el contenido puede volverse "inútil", **según Aulab Hackademy (11)**. Incluya `<!DOCTYPE html>` al inicio, pues debe ser la **"PRIMERA LÍNEA en cualquier documento HTML"** para una correcta interpretación del estándar, **como lo indica Aulab Hackademy (12)**. No use `<br>` para separar párrafos, use `<p>`, ya que el uso indiscriminado de `<br>` se considera mala práctica, **según Aulab Hackademy (13)**.

  * **Uso Semántico:** Use las etiquetas HTML correctas. **Como señala MDN (14)**, usar un elemento como `<button>` en lugar de un genérico `<div>` para botones garantiza que el control sea accesible de inmediato. Evite abusar de `<div>` y use los elementos semánticos de HTML5, pues **según Eniun (10)**, estos "definen claramente su propósito" y mejoran la accesibilidad y el SEO.

  * **Clases e IDs:** Un **`id` debe ser único** en la página, mientras que las **`class` se pueden repetir**. **Según las recomendaciones didácticas (15)**, "un ID sólo debe usarse una vez en el documento".

  * **Evitación de Estilos en Línea:** No use CSS en el atributo `style`. **Según Kinsta (16)** y **HTML Desde Cero (17)**, muchos desarrolladores "recomiendan evitar por completo el CSS inline... se debe utilizar con moderación", ya que impiden la reutilización y empeoran el mantenimiento.

  * **Accesibilidad:** Provea un texto alternativo (`alt`) en cada imagen informativa. De no hacerlo, los lectores de pantalla leerán solo el nombre del archivo, **según MDN (18)**. MDN (19) enfatiza que el **atributo `alt` siempre debe describir directamente lo que la imagen muestra**. **MDN (20)** aconseja: "nunca incluya texto importante dentro de una imagen, ya que los lectores de pantalla no lo detectan".

-----

##  Referencias


Anderson, B. (2023). Separation of Concerns: Rethinking the Blend of HTML, JavaScript and CSS. Dev.to. Recuperado de https://dev.to/blakeanderson/separation-of-concerns-rethinking-the-blend-of-html-javascri%20pt-and-css-1bkp

Aulab Hackademy. (12 de enero de 2021). HTML5: los errores más comunes de un desarrollador web novato. Recuperado de https://aulab.es/noticia/168/html5-los-errores-mas-comunes-de-un-desarrollador-web-novato (11, 12, 13)

Britannica. (s. f.). Website | Definition & Facts. Recuperado de https://www.britannica.com/technology/website

Duckett, J. (2011). HTML & CSS: Design and Build Websites. John Wiley & Sons. Recuperado de https://sites.math.duke.edu/courses/math_everywhere/assets/techRefs/HTML%20and%20CSS-%20Design%20and%20Build%20Websites_Jon%20Duckett_2011.pdf

Eniun. (s. f.). HTML5, estructura básica y elementos semánticos. Recuperado de https://www.eniun.com/html5-estructura-basica-elementos-semanticos/ (9, 10)

HTML Desde Cero. (s. f.). Estilos en Línea en HTML y CSS con Ejemplos. Recuperado de https://htmldesdecero.es/blog/estilos-linea-html-css/ (17)

Jain, R., Tomar, D. S., & Gupta, P. K. (2024). Modern Web Development Using CSS and HTML. International Journal of Engineering Science and Education, 12(6). Recuperado de https://www.ijese.org/wp-content/uploads/Papers/v12i6/G257412070624.pdf

Kinsta. (s. f.). 14 Buenas Prácticas de CSS para Principiantes. Recuperado de https://kinsta.com/es/blog/buenas-practicas-css/ (16)

LenguajeCSS. (s. f.). Alinear y centrar con Grid CSS. Recuperado de https://lenguajecss.com/css/grid/alinear-centrar-css/ (4)

Marco, B. S. (s. f. a). Bordes (1). CSS. Páginas web HTML y hojas de estilo CSS. www.mclibre.org. Recuperado de https://www.mclibre.org/consultar/htmlcss/css/css-bordes.html (8)

Marco, B. S. (s. f. b). Colores. CSS. Páginas web HTML y hojas de estilo CSS. www.mclibre.org. Recuperado de https://www.mclibre.org/consultar/htmlcss/css/css-color.html (5)

Marco, B. S. (s. f. c). Fondos. CSS. Páginas web HTML y hojas de estilo CSS. www.mclibre.org. Recuperado de https://www.mclibre.org/consultar/htmlcss/css/css-fondos.html (6)

Mozilla Developer Network (MDN). (s. f. a). CSS Styling Basics – Learn Web Development. Recuperado de https://developer.mozilla.org/en-US/docs/Learn/web_development/Core/Styling_basics

Mozilla Developer Network (MDN). (s. f. b). HTML: Una buena base para la accesibilidad. Recuperado de https://developer.mozilla.org/es/docs/Learn_web_development/Core/Accessibility/HTML (14, 18, 19, 20)

Mozilla Developer Network (MDN). (s. f. c). Structuring Content with HTML. Recuperado de https://developer.mozilla.org/en-US/docs/Learn/web_development/Core/Structuring_content

Mozilla Developer Network (MDN). (s. f. d). border - CSS. Recuperado de https://developer.mozilla.org/es/docs/Web/CSS/border (7)

Mozilla Developer Network (MDN). (s. f. e). justify-content - CSS. Recuperado de https://developer.mozilla.org/es/docs/Web/CSS/justify-content (3)

Mozilla Developer Network (MDN). (s. f. f). margin - CSS. Recuperado de https://developer.mozilla.org/es/docs/Web/CSS/margin (1)

Mozilla Developer Network (MDN). (s. f. g). text-align - CSS. Recuperado de https://developer.mozilla.org/es/docs/Web/CSS/text-align (2)

Nielsen Norman Group. (2018). Effective Use of Style Sheets. Recuperado de https://www.nngroup.com/articles/effective-use-of-style-sheets/

ResearchGate. (2024). Harnessing the Potential of CSS: An Exhaustive Reference for Web Styling. Recuperado de https://www.researchgate.net/publication/376984494_Harnessing_the_Potential_of_CSS_An_Exhaustive_Reference_for_Web_Styling

Sharma, A., & Aakanksha. (2018). Introduction to HTML (Hyper Text Markup Language) – A Review Paper. International Journal of Science and Research (IJSR), 7(5), 1337-1339. Recuperado de https://www.ijsr.net/getabstract.php?paperid=ART20182355

Sharma, H., & Tripathi, K. (2023). The Importance of Website Usability in Digital Marketing – A Review. International Journal of Innovative Research in Computer Science & Technology (IJIRCST), 11(3), 27-31.

sfpdesarrolloweb. (2019). UD 13: Etiquetas semánticas y/o estructurales. Recuperado de https://sfpdesarrolloweb.wordpress.com/2019/07/19/ud13-etiquetas-semanticas-estructurales/ (15)

Uğraş, T., Gülseçen, Ş., Çubukçu, C., Erdoğmuş, İ., Gashi, V., & Bedir, M. (2016). Research Trends in Web Site Usability: A Systematic Review. Springer International Publishing. Recuperado de https://doi.org/10.1007/978-3-319-40409-7_49

Yale University Usability Lab. (s. f.). HTML and CSS: Web Accessibility Guidelines. Recuperado de https://usability.yale.edu/web-accessibility/articles/html-and-css
