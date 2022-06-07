The starter project uses the `default.css` file to assign colours to the variables. The existing colours use a greyscale scheme. 

![The default colour palette showing 5 shades of grey.](images/greyscale.png)

**Choose** Change the colour codes in `default.css` to the colours you would like to use in your web page. Your web page colours will update as you update them.

**Tip:** You can use [coolors.co](https://coolors.co){:target="_blank"} to generate and customise colour palettes then update your colour codes in `default.css`.

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
