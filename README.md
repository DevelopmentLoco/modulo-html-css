# Rueda Libre v2.0 y Rueda Nocturna

## Descripción del proyecto

Rueda Libre es un sitio web para consultar bicicletas, recorridos, tarifas y realizar reservas. El ecosistema se amplía con **Rueda Nocturna**, una landing de campaña para descubrir recorridos nocturnos en bicicleta por Medellín y realizar una inscripción.

El proyecto integra el sitio principal desarrollado con Bootstrap y la landing desarrollada con Tailwind CSS. Ambos productos comparten la identidad visual y sus enlaces de navegación.

## Enlaces del proyecto

- [Repositorio en GitHub](https://github.com/DevelopmentLoco/modulo-html-css)
- [Sitio Rueda Libre — página de inicio](./index.html)
- [Landing Rueda Nocturna](./nocturna/index.html)

## Páginas

### Sitio Rueda Libre v2.0

- [Inicio](./index.html): portada, navegación y acceso a las secciones del sitio.
- [Reservas](./pages/reservas.html): formulario para reservar una bicicleta.
- [Tarifas y recorridos](./pages/tarifas.html): información de tarifas y recorridos.
- [Catálogo Bootstrap](./pages/catalogo-bootstrap.html): catálogo de bicicletas.

### Landing Rueda Nocturna

- [Landing principal](./nocturna/index.html): campaña, rutas, funcionamiento, planes e inscripción.
- [Kit de componentes](./nocturna/componentes.html): botones, tarjetas, alertas y campos de formulario.
- [Prototipo inicial](./nocturna/prototipo.html): primera propuesta de la sección principal con Tailwind Play CDN.

## Tecnologías

- **HTML5:** estructura y contenido de las páginas.
- **CSS3:** estilos propios del sitio principal en `css/styles.css`.
- **Bootstrap 5.3.8:** sistema de componentes, navegación, tarjetas y grillas del sitio Rueda Libre.
- **Bootstrap Icons 1.11.3:** iconografía del sitio.
- **Tailwind CSS 4.3.5:** utilidades, tema de marca, diseño responsive y modo oscuro de Rueda Nocturna.
- **Tailwind CLI:** generación del archivo local `nocturna/src/output.css`.
- **Git y GitHub:** control de versiones y repositorio del proyecto.
- **GitHub Pages:** destino de publicación del sitio estático.

## Decisión técnica: Bootstrap y Tailwind CSS

El sitio principal conserva Bootstrap porque sus componentes y clases predefinidas (`card`, `row`, `col-*`, `btn` y `nav-link`) permiten organizar la navegación, las tarjetas y las grillas con rapidez.

Para la landing Rueda Nocturna, la recomendación es **Tailwind CSS con CLI**. En este proyecto, `@theme` permite centralizar los colores y las tipografías de la campaña, mientras que las utilidades responsive y las variantes `dark:` permiten adaptar la interfaz a distintos tamaños de pantalla y al modo oscuro. La CLI genera una hoja CSS local (`nocturna/src/output.css`) con las utilidades utilizadas.

## Identidad visual

El sitio Rueda Libre utiliza la paleta definida para la marca:

- Crema: `#FAF6EF`
- Azul Noche: `#14213D`
- Gris Asfalto: `#5B6470`
- Verde Ruta: `#1E7A4F`
- Naranja Pedal: `#F39A2B`

La landing Rueda Nocturna utiliza fondos oscuros, superficies en tonos azulados, texto claro y acento amarillo farol `#E4B86B`.

## Capturas e imagen de campaña

Imagen utilizada en la campaña Rueda Nocturna:

![Ciclista recorriendo la ciudad de noche](./img/rueda-nocturna.png)

## Aprendizajes

- La estructura semántica permite organizar el contenido y diferenciar las secciones de una página.
- Bootstrap facilita la construcción de interfaces mediante componentes y patrones predefinidos.
- Tailwind CSS permite construir interfaces combinando utilidades de layout, espaciado, tipografía, color y estados.
- El enfoque mobile-first permite adaptar la presentación a celulares, tabletas y escritorio mediante breakpoints.
- Las variantes `dark:` y la configuración de `@custom-variant` permiten aplicar el tema oscuro mediante la clase `dark`.
- `@apply` permite reutilizar grupos de utilidades en clases de componentes como `.btn-nocturna`.
- La CLI de Tailwind analiza los archivos del proyecto y genera el CSS correspondiente a las clases utilizadas.
- Los formularios pueden organizarse con `fieldset`, `legend`, etiquetas asociadas y validaciones nativas del navegador.
- La integración de productos requiere mantener coherentes la navegación, los enlaces, los colores y los datos de contacto.

## Autor

**Juan Pablo Rodriguez**
