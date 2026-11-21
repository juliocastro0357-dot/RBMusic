# RB Music — propuesta web estática

Sitio editorial bilingüe ES/EN para RB Music, creado con HTML, CSS y JavaScript vanilla. No utiliza servidor, funciones serverless, frameworks de renderizado ni Vercel.

## Publicación

El workflow de GitHub Actions despliega la raíz del repositorio en GitHub Pages al hacer push a `main`. En el repositorio, habilita **Settings → Pages → Build and deployment → Source: GitHub Actions**. Después revisa el estado en **Actions**. URL esperada: https://juliocastro0357-dot.github.io/RBMusic/ (GitHub puede tardar unos minutos en servir el primer despliegue).

## Archivos

- `index.html`: estructura, SEO, Open Graph, navegación y secciones.
- `styles.css`: sistema visual responsive, foco accesible y movimiento reducido.
- `app.js`: traducción ES/EN, directorio filtrable/buscable y catálogo estático.
- `PROPUESTA_Y_ESTRATEGIA.md`: investigación, decisiones, fuentes y lista de assets pendientes.
- `.github/workflows/pages.yml`: publicación automática en Pages.

## Datos de demostración

Las fotografías son imágenes editoriales de Unsplash y los datos de productos/artistas requieren aprobación de RB Music. Los enlaces externos apuntan a sitios públicos oficiales. Reemplazar las fotos y el lanzamiento de muestra con assets con licencia y material aprobado antes de promocionar.
