# Cómo publicar una reseña

1. Sube tus GIFs y capturas a `media/reviews/` (Add file → Upload files).
2. En la carpeta `_posts/` pulsa **Add file → Create new file**.
3. Nombre del archivo: `AAAA-MM-DD-nombre-del-juego.md`, por ejemplo `2026-11-15-hades-ii.md`.
   La fecha va delante obligatoriamente y el nombre sin espacios ni tildes.
4. Copia el contenido de `_drafts/ejemplo-resena.md`, cámbialo y pulsa **Commit changes**.
5. En 1-2 minutos aparece en `/reviews/`.

## Campos de la cabecera (entre los `---`)

| Campo | Para qué sirve | ¿Obligatorio? |
|---|---|---|
| `title` | Título de la reseña | Sí |
| `game`, `studio`, `platform`, `hours` | Datos que salen en la cabecera de colores | No |
| `cover` | Imagen o GIF de portada, p. ej. `/media/reviews/hades-portada.gif` | No |
| `summary` | Frase que sale en la tarjeta del listado | Recomendado |
| `score`, `verdict` | Nota y veredicto en el bloque rojo final | No |

## Formato del texto

- Párrafos: sepáralos con una línea en blanco.
- Títulos de sección: `## Combat & game feel`
- Imagen o GIF: `![Descripción](/media/reviews/archivo.gif)`
- Negrita: `**texto**` · Lista: líneas que empiezan por `- ` · Cita destacada: línea que empieza por `> `
