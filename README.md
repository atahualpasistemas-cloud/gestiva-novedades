# Novedades de Gestiva.NET

Las imágenes de la carpeta `flyers/` aparecen en la app móvil, en
**Novedades y avisos → pestaña Novedades**.

## Publicar una novedad

1. Entrá a la carpeta `flyers/` de este repositorio.
2. **Add file → Upload files** y subí la imagen.
3. **Commit changes**.

Listo. Aparece en los celulares en menos de 10 minutos (hay una caché de
ese tiempo en el servidor). No hay que recompilar la app ni tocar nada más.

## Cómo nombrar los archivos

El título que se ve en la app sale del nombre del archivo:

| Nombre del archivo | Título en la app |
|---|---|
| `2026-08-11 Promo de invierno.jpg` | Promo de invierno |
| `nueva_version_2_1.png` | nueva version 2 1 |

Poniendo la fecha adelante (`AAAA-MM-DD`) quedan **ordenadas de más nueva a
más vieja** en la app, y la fecha no se muestra en el título.

## Formatos

`.jpg`, `.jpeg`, `.png`, `.webp` y `.gif`. Cualquier otro archivo se ignora.

Las imágenes se muestran **enteras**, sin recortar, así que se ve bien
cualquier proporción. Como referencia, un flyer vertical tipo historia
(1080×1350) queda cómodo.

Conviene que no pesen más de 1 MB: se descargan con datos móviles.

## Borrar una novedad

Entrá al archivo dentro de `flyers/`, botón **⋯ → Delete file**, y confirmá.
Desaparece de la app en el mismo plazo.

## Ojo

Este repositorio es **público**: cualquiera con el link puede ver las
imágenes. No subas nada que no quieras que se vea.
