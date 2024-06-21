Het startproject gebruikt het `default.css` bestand om kleuren toe te wijzen aan de variabelen. De bestaande kleuren gebruiken een grijswaarden schema.

![Het standaardkleurenpalet dat vijf grijstinten laat zien.](images/greyscale.png)

**Kies**: Verander de kleurcodes in `default.css` naar de kleuren die je wilt gebruiken op je webpagina. De kleuren van de webpagina worden bijgewerkt zodra je de kleurcodes wijzigt.

**Tip**: Je kunt [coolors.co](https://coolors.co){:target="_blank"} gebruiken om kleurpaletten te genereren en aan te passen en vervolgens je kleurcodes bijwerken in `default.css`.

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
