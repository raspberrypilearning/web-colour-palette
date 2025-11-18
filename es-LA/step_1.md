El proyecto inicial utiliza el archivo `default.css` para asignar colores a las variables. Los colores existentes utilizan un esquema de escala de grises.

![The default colour palette showing five shades of grey.](images/greyscale.png)

**Elegir**: Cambia los códigos de color en `default.css` por los colores que deseas utilizar en tu página web. Los colores de tu página web se actualizan a medida que cambias los códigos de color.

**Sugerencia**: Puedes usar [coolors.co](https://coolors.co){:target="_blank"} para generar y personalizar paletas de colores y luego actualizar tus códigos de color en `default.css`.

--- code ---
---
language: html
filename: default.css
line_numbers: true
line_number_start: 4
line_highlights: 5-14
---

:root {
  --primary: #bccad0;
  --onprimary:#4f4e4e;
  --secondary: #495054;
  --onsecondary:#ffffff;
  --tertiary:#747474;
  --ontertiary: #ffffff;
  --page:#ffffff;
  --onpage:#000000;
  --detail: #9ba8ae;
  --detail2: #000000;
}

--- /code ---
