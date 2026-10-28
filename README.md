# gonzalolinan.com · Portfolio

Portfolio de Gonzalo Liñán Aldana (Combat Designer & Gameplay Programmer).
Web estática alojada gratis en GitHub Pages.

## Estructura

| Carpeta / archivo | Qué es |
|---|---|
| `index.html` | Portada |
| `the-9th-dragon/`, `ghunter/`, `hobo-league/`, `monster-evicter/` | Páginas de cada proyecto |
| `reviews/` | Listado de reseñas (se genera solo a partir de `_posts/`) |
| `_posts/` | Tus reseñas, una por archivo `.md` |
| `_drafts/ejemplo-resena.md` | Plantilla de reseña (no se publica) |
| `media/projects/` | GIFs, imágenes y MP4 de los proyectos |
| `media/reviews/` | GIFs y capturas de las reseñas |
| `cv/Gonzalo-Linan-CV.pdf` | El CV que descarga el botón "Download Resume" |

## Publicar por primera vez

1. En GitHub crea un repositorio **público** llamado exactamente `maltrak007.github.io`.
2. Dentro del repo: **Add file → Upload files** y arrastra TODO el contenido de esta carpeta
   (los archivos y carpetas, no la carpeta que los contiene). Pulsa **Commit changes**.
3. **Settings → Pages**: en *Source* elige **Deploy from a branch**, rama **main**, carpeta **/ (root)**. Guarda.
4. En 1-2 minutos la web estará en `https://maltrak007.github.io`.

## Conectar tu dominio (comprado en Wix)

1. En GitHub: **Settings → Pages → Custom domain**, escribe tu dominio (p. ej. `gonzalolinan.com`) y guarda.
2. En Wix: **Dominios → (tu dominio) → Administrar registros DNS** y deja estos registros:
   - 4 registros **A** para el dominio raíz (host `@`):
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
   - 1 registro **CNAME** para `www` apuntando a `maltrak007.github.io`
   - Borra los registros A/CNAME antiguos que apunten a Wix.
3. Espera a que propague (de minutos a unas horas) y marca **Enforce HTTPS** en Settings → Pages.

## Añadir GIFs y vídeos a un proyecto

1. Sube el archivo a `media/projects/` (Add file → Upload files).
2. Abre `the-9th-dragon/index.html` (o el proyecto que sea), pulsa el lápiz ✏️ y busca `EDIT HERE`.
3. Escribe la ruta en el hueco de la sección correspondiente, en orden (01, 02, 03…):
   ```js
   "the-9th-dragon": ["../media/projects/combat-loop.gif", "", "", "", ""],
   ```
   También puedes pegar un enlace de YouTube. Commit y listo.

Consejo: GitHub no acepta archivos de más de 100 MB y los repos deben quedarse por debajo de ~1 GB.
Para vídeos largos, mejor YouTube; usa GIF o MP4 cortos (menos de ~25 MB) para los clips.

## Escribir una reseña

Mira `COMO-ESCRIBIR-UNA-RESENA.md`.
