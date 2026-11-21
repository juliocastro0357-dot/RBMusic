# Propuesta y estrategia — RB Music

**Propuesta de sitio estático bilingüe · 21 de noviembre de 2026**  
**Repositorio:** [juliocastro0357-dot/RBMusic](https://github.com/juliocastro0357-dot/RBMusic)  
**URL esperada de pruebas:** https://juliocastro0357-dot.github.io/RBMusic/

## Hallazgos de la revisión pública

- El sitio oficial de RB Music presenta a la compañía como fundada por Ricardo Bobadilla en 2017 en Los Ángeles; destaca la idea de una familia que no se rinde, una historia ligada a Premios de la Calle y una tienda de mercancía. El home también muestra gorras de El Jerry, ropa de Cuisillos y artículos RB Music. [RB Music oficial](https://rbmusicoficial.com/home)
- El portal de RB Music publica perfiles o contenido de Grupo Marca Registrada, Pancho Barraza, Gerardo Coronel “El Jerry”, Larry Hernández, José Manuel Figueroa, Roberto Tapia, Pequeños Musical, Coyulitos y Banda Cuisillos. La presencia editorial no se interpreta aquí como confirmación de un contrato vigente o representación exclusiva. [Publicaciones RB Music](https://rbmusic.mx/publicado/)
- “De la Calle al Éxito Récords” dispone de sitio propio y perfiles de artistas. Sus páginas cuentan historias concretas de desarrollo y colaboración, por ejemplo las de Grupo Debate y Banda Tlaquepaquense; el sitio describe recorridos particulares, no una promesa universal de firma o éxito. [Grupo Debate](https://delacallealexito.com/artist/grupo-debate) · [Banda Tlaquepaquense](https://delacallealexito.com/artist/banda-tlaquepaquense)
- El sitio de Premios de la Calle invita a pre-registrarse por rol (artista, influencer o prensa), recuerda la edición 2024 y muestra mensajes de su comunidad y patrocinadores. No se presentan fechas futuras ni categorías no anunciadas como hechos. [Premios de la Calle oficial](https://premiosdelacalleoficial.com/)
- El portal [RB Ticket](https://rbticket.com/) anuncia eventos y lista artistas de la red, pero al momento de la consulta mostraba que no había eventos disponibles. Por eso el diseño enlaza a canales oficiales y no inventa una agenda.
- La fecha de fundación difiere en fuentes antiguas y secundarias. Se usó la fecha que comunica actualmente la web oficial (2017); validar con el equipo antes de fijarla en una biografía corporativa.

## Dirección y arquitectura

La propuesta usa una estética editorial nocturna inspirada en concierto: negro carbón, papel cálido y lima eléctrica; tipografía condensada para titulares, fotografía a sangre, gran jerarquía y animación discreta. La navegación lleva a seis objetivos: elenco, música, movimiento, premios, shop y contacto.

- **RB Music:** hero de marca, enlaces directos y bloque de historia/autoridad.
- **Artistas:** selección visible con filtros por categoría, búsqueda rápida y ficha modal. La taxonomía es funcional para la muestra, no atribuye género definitivo a cada artista.
- **Música:** escaparate para lanzamientos con enlace a escucha. El arte y el título actuales son muestra.
- **De la Calle al Éxito:** relato de descubrimiento, desarrollo y escenario, con salida al canal del proyecto. No promete resultados de carrera.
- **Premios de la Calle:** bloque de marca y llamada al sitio oficial, que mantiene la convocatoria y la información vigente.
- **Shop:** catálogo de referencia filtrable y salida al shop oficial para disponibilidad, precio, tallas y compra.
- **Contacto:** correo general que RB Music publica en su perfil de Ricardo Bobadilla; confirmar la bandeja correcta para booking, prensa, artistas y mercancía.

## Alcance que respalda la inversión propuesta de $15,000 MXN

La inversión propuesta contempla la adaptación de identidad y narrativa a una presencia propia, una arquitectura enfocada en distintas intenciones (escucha, contratación, descubrimiento de talento, premios y mercancía), presentación bilingüe de los contenidos, catálogo interactivo sin backend, interacción accesible, SEO técnico inicial, metadatos sociales, rendimiento de archivos estáticos y una ruta de publicación documentada. La suma describe el valor del alcance propuesto; no es una cotización aceptada ni representa el precio oficial de RB Music.

## Tecnología y experiencia

- HTML semántico, CSS moderno y JavaScript vanilla; archivos estáticos servibles desde GitHub Pages o cualquier hosting estático.
- Selector ES/EN que actualiza encabezados, textos, etiquetas, placeholder, `lang`, título y descripción SEO, con preferencia guardada en el navegador.
- Diseño adaptable, navegación móvil, búsqueda, filtros, diálogo modal accesible, foco visible y `prefers-reduced-motion`.
- Open Graph, descripción y color de tema; enlaces externos con `rel="noopener"`.
- GitHub Pages sirve la raíz de `main` directamente, sin proceso de compilación ni workflow adicional. No se requiere Vercel ni infraestructura serverless.

## Muestra y validación pendiente con cliente

1. Sustituir las fotos de Unsplash por fotografía autorizada y optimizada; confirmar permisos de imagen/nombres/logotipos de artistas.
2. Aprobar lista de artistas, sus categorías, biografías y enlaces oficiales de booking/streaming.
3. Conectar el bloque de música a lanzamientos vigentes y carátulas aprobadas; el perfil oficial de catálogo deberá confirmar qué estrenos priorizar.
4. Sustituir nombres/fotos referenciales de productos por artículos disponibles, variantes, tallas, precios, moneda, inventario, envíos y política de cambios; usar el checkout de la tienda oficial.
5. Confirmar fecha, sede, categorías, galerías y formulario vigente de Premios de la Calle. La convocatoria del sitio consultado está rotulada 2025, por tanto no se reproduce como convocatoria actual.
6. Validar correo de contacto por área, redes oficiales, identidad visual y año de fundación con RB Music.
7. GitHub Pages está configurado en **Settings → Pages → Build and deployment → Deploy from a branch → main → /(root)**. GitHub reconstruye desde la raíz de `main`; esperar unos minutos después de cambios antes de probar la URL.

## Cómo revisar

1. GitHub Pages publica automáticamente la rama `main` desde `/(root)`.
2. Espera unos minutos tras los cambios iniciales y abre [https://juliocastro0357-dot.github.io/RBMusic/](https://juliocastro0357-dot.github.io/RBMusic/) para revisar navegación, selector de idioma, búsqueda/filtros, modales y enlaces en móvil/escritorio.
3. Antes del lanzamiento comercial, completa las validaciones y assets pendientes anteriores.
