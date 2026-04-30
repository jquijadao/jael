# El pinguino de Humboldt

Sitio web informativo sobre el pinguino de Humboldt, una especie marina presente en las costas de Chile y Peru que enfrenta amenazas como la perdida de habitat, la pesca, la contaminacion, el cambio climatico y la disminucion de sus colonias reproductivas.

El proyecto esta construido como una pagina estatica con HTML y CSS. No requiere instalacion de dependencias ni proceso de compilacion.

## Estructura del proyecto

```text
jael/
|- index.html
`- assets/
   |- css/
   |  `- styles.css
   `- img/
      |- featured.jpg
      |- news1.jpg
      |- news2.jpg
      |- news3.jpg
      `- news4.jpg
```

## Contenido del sitio

La pagina presenta:

- Una portada sobre la situacion critica del pinguino de Humboldt en Chile.
- Cifras clave: colonias en Chile, parejas reproductivas y Plan RECOGE.
- Amenazas principales: perdida de habitat, pesca, contaminacion, especies invasoras, influenza aviar y cambio climatico.
- Informacion sobre la declaracion como Monumento Natural de especie.
- Explicacion de la importancia ecologica del pinguino de Humboldt.

## Tecnologias usadas

- HTML5 semantico.
- CSS3 organizado con variables.
- Diseno responsive con `grid`, `flexbox` y media queries.
- Imagenes locales en `assets/img/`.
- Posicionamiento CSS `relative` y `absolute`.

## Uso de posicionamiento CSS

El proyecto usa `position: relative` para crear contextos de posicionamiento y `position: absolute` para ubicar elementos dentro de esos contextos.

### Relative

- `.header-container`: contexto para el elemento decorativo del encabezado.
- `.featured-story`: contexto general de la historia principal.
- `.featured-image-container`: contexto para la etiqueta `Conservacion`.
- `.card-image-container`: contexto para las etiquetas de cada tarjeta.
- `.emphasis-card`: contexto para la etiqueta `Dato clave`.

### Absolute

- `.header-accent`: elemento decorativo ubicado en la parte superior derecha del encabezado.
- `.header-accent::before`: punto interno del elemento decorativo.
- `.category-badge`: etiqueta ubicada sobre la imagen principal.
- `.breaking-badge`: etiqueta de alerta sobre una tarjeta.
- `.category-label`: etiquetas de categoria sobre las imagenes de tarjetas.
- `.emphasis-label`: etiqueta `Dato clave` ubicada dentro del bloque destacado.

## Como verlo localmente

Opcion simple:

1. Abre la carpeta del proyecto.
2. Abre `index.html` en el navegador.

Opcion con servidor local:

```powershell
python -m http.server
```

Luego abre:

```text
http://localhost:8000
```

## Publicacion en Netlify

El proyecto esta preparado para desplegarse desde GitHub en Netlify.

Configuracion recomendada:

- Repository: `jael123`
- Branch: `main`
- Base directory: vacio
- Build command: vacio
- Publish directory: `.`

Como es un sitio estatico puro, Netlify solo necesita publicar la raiz del repositorio, donde se encuentra `index.html`.

## Actualizar el sitio

Despues de hacer cambios:

```powershell
git add .
git commit -m "Actualizar sitio del pinguino de Humboldt"
git push
```

Netlify detectara el `push` y publicara automaticamente una nueva version del sitio.

