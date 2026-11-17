# Cómo publicar una nota

Las notas son archivos Markdown en la carpeta `_posts/`. GitHub Pages las publica solo.

## Desde la web de GitHub (sin instalar nada)

1. Entrá al repo en GitHub y abrí la carpeta `_drafts/`, archivo `plantilla-nota.md`. Copiá su contenido.
2. Volvé a la raíz del repo, tocá **Add file → Create new file**.
3. En el nombre escribí `_posts/AAAA-MM-DD-titulo-corto.md`, por ejemplo `_posts/2026-12-01-por-que-desarmo-cosas.md`.
   La fecha del nombre es la fecha de la nota; el resto será la URL (`matiasaraujo.ar/notes/2026/por-que-desarmo-cosas/`).
4. Pegá la plantilla, completá `title`, `description` y `lang`, y escribí debajo de la segunda línea `---`.
5. **Commit changes**. En uno o dos minutos aparece en la sección Notas de la home y en `matiasaraujo.ar/notes/`.

## Pidiéndosela a Claude

Pasale el texto (o la idea) y pedile que la publique como nota.

## Imágenes

Subilas a `assets/images/notes/` y usalas así: `![descripción](/assets/images/notes/archivo.jpg)`.

## Borradores

Lo que esté en `_drafts/` no se publica. Para publicarlo, movelo a `_posts/` con la fecha en el nombre.
