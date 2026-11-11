# Universo Anime

Sitio web educativo sobre anime creado para practicar HTML5, CSS, XML/RSS y
publicación web en 1.º DAM.

## Autoría

- **Nombre y apellidos:** Óscar Santiago Valdivia
- **Curso:** 1.º DAM
- **Módulo:** Lenguajes de Marcas
- **Centro:** IES Zaidín Vergeles
- **Fecha:** 11 de noviembre de 2026

## Sitio publicado

- **Web en GitHub Pages:** [Abrir sitio](https://xzapedev.github.io/mi-sitio-web/)
- **Repositorio:** [Abrir repositorio](https://github.com/xZapeDev/mi-sitio-web)
- **Canal RSS:** [Abrir RSS](https://xzapedev.github.io/mi-sitio-web/rss.xml)

## Estructura del proyecto

- `index.html`: presentación del sitio y avances de sus contenidos.
- `blog.html`: artículo semántico sobre novedades de anime.
- `tabla.html`: ranking comparativo de cinco franquicias.
- `galeria.html`: galería, mapa de imagen y recursos multimedia.
- `formulario.html`: formulario de inscripción con validación HTML.
- `rss.xml`: canal RSS con tres contenidos del sitio.
- `css/estilos.css`: hoja de estilos externa compartida.
- `img/`: imágenes, logotipo, favicon y recursos gráficos.
- `audio/`: versiones MP3 y OGG del audio local.
- `video/`: vídeo local.
- `subtitulos/`: pistas de subtítulos en español e inglés.

## Tecnologías utilizadas

- HTML5
- CSS
- XML y RSS
- Git
- GitHub
- GitHub Pages

## Características principales

- Navegación común entre cinco páginas.
- Uso de elementos HTML semánticos.
- Tabla accesible con `caption`, `thead`, `tbody`, `tfoot`, `rowspan` y `colspan`.
- Galería con JPG, WebP, PNG, SVG y GIF.
- Mapa de imagen con tres zonas interactivas.
- Vídeo local con controles, poster y subtítulos.
- Audio local con fuentes MP3 y OGG.
- Vídeo de YouTube y mapa de Google Maps incrustados.
- Formulario con validación nativa de HTML5.
- Canal RSS con tres publicaciones.

## Validación

La comprobación local confirma que las cinco páginas, la hoja CSS, el RSS y
los recursos multimedia se cargan correctamente desde GitHub Pages.

Las capturas de los validadores oficiales deben añadirse en `img/` cuando se
realice esa validación. Los nombres previstos son:

### HTML

`img/validacion-html.png`

### CSS

`img/validacion-css.png`

### RSS

`img/validacion-rss.png`

## Dificultades encontradas

1. **Compatibilidad del vídeo local:** el vídeo original utilizaba un códec
   poco compatible. Se configuró un vídeo local con `poster`, controles y dos
   pistas de subtítulos.
2. **Recursos multimedia ausentes:** se revisaron las rutas de imágenes,
   audio, vídeo y subtítulos, y se corrigieron las referencias que no existían.
3. **Mapa de imagen:** las zonas interactivas enlazaban inicialmente al destino
   equivocado. Se ajustaron sus coordenadas y se enlazaron con páginas de
   Wikipedia relacionadas con cada género.
4. **Publicación y rutas:** las rutas relativas funcionan en local y en
   GitHub Pages. El RSS utiliza URLs absolutas de la web publicada.

## Decisiones técnicas

- Se han organizado los documentos HTML en la raíz y los recursos en carpetas
  separadas para facilitar su mantenimiento.
- La cabecera, el menú, el pie de página y la hoja CSS se reutilizan en las
  cinco páginas.
- El contenido de `main`, el título de la pestaña y el encabezado principal
  cambian según la finalidad de cada página.
- Se ha utilizado JPG para fotografías, WebP para imágenes optimizadas, PNG
  para gráficos con transparencia, SVG para logotipo e iconos y GIF para una
  animación sencilla.
- Las rutas relativas se utilizan para enlazar páginas y recursos locales;
  las URLs absolutas se reservan para servicios externos y el RSS publicado.
- La hoja CSS externa deja preparado el proyecto para ampliar su diseño sin
  mezclar contenido y presentación.

## Uso de herramientas de IA

Se ha utilizado GitHub Copilot como apoyo puntual durante el desarrollo. La
información, la temática y las decisiones principales del proyecto son del
autor; la IA se utilizó para ampliar explicaciones y mejorar la redacción,
no para sustituir la elaboración del sitio.

También se utilizó como ayuda para dar una estructura más completa al README,
resolver dudas sobre HTML y revisar algunas soluciones técnicas. Entre ellas:

- Comprender el uso de `target="_blank"` para abrir enlaces externos en una
  pestaña nueva.
- Comprender `allowfullscreen` para permitir la pantalla completa en los
  contenidos incrustados.
- Revisar `referrerpolicy` y otros atributos de los `iframe`.
- Detectar y corregir rutas de recursos, enlaces y elementos multimedia.

La revisión final del código, las decisiones de diseño y la responsabilidad
del contenido corresponden al autor del proyecto.

## Fuentes y licencias

- Los textos descriptivos y la estructura HTML son propios del proyecto.
- Las imágenes, el audio y el vídeo deben conservar la autoría y licencia de
  sus fuentes originales. Antes de entregar, se debe completar esta sección
  con el autor, URL de origen y licencia concreta de cada recurso externo.
- No se incluyen contraseñas ni datos personales sensibles en el repositorio.
