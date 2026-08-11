# Soporte fotográfico

Las imágenes están separadas **por torre**, y dentro de cada torre hay una subcarpeta por
evidencia documental de la línea de tiempo correspondiente.

| Torre | Carpeta | Imágenes | Línea de tiempo |
|---|---|---|---|
| T009 · L2146 | [`T009/`](T009/) | Imagen 6 a 25 | [`docs/linea-temporal-T009.md`](../docs/linea-temporal-T009.md) |
| T010 · L5022 | [`T010/`](T010/) | Imagen 1 a 14 | [`docs/linea-temporal-T010.md`](../docs/linea-temporal-T010.md) |

La numeración de las imágenes es **independiente en cada torre**: proviene de la columna
*Soporte fotográfico* del archivo Excel de esa torre. Por eso existen, por ejemplo, una
`Imagen 11` en T009 y otra `Imagen 11` en T010, que son fotografías distintas.

Cada carpeta de torre tiene su propio `README.md` con el mapa imagen → evento:

- [`T009/README.md`](T009/README.md)
- [`T010/README.md`](T010/README.md)

## Convención de nombres

Los archivos se nombran con el número de imagen de la línea de tiempo de su torre:
`Imagen 6.jpeg`, `Imagen 7.jpeg`, etc.

Para material nuevo:

- Si un mismo número tiene varias tomas, añade un sufijo de letra: `Imagen 21a.jpeg`,
  `Imagen 21b.jpeg`.
- Puedes agregar una descripción corta después del número —
  `Imagen 19 - escarpe bajo C.jpeg` — indicando la pata de referencia (A, B, C o D) cuando la
  foto sea de un apoyo concreto.
- Formatos: `.jpg`/`.jpeg` para fotografías de campo, `.png` para figuras, mapas y capturas de
  informes.

## Recomendaciones

- Conserva las fotografías **georreferenciadas** con sus metadatos EXIF (no las recortes ni
  reexportes si se puede evitar).
- Las carpetas vacías se mantienen con un `.gitkeep`; puedes borrarlo al subir contenido.
