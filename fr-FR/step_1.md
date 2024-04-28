Le projet de démarrage utilise le fichier `default.css` pour attribuer des couleurs aux variables. Les couleurs existantes utilisent un niveau de gris.

![La palette de couleurs par défaut affichant cinq nuances de gris.](images/greyscale.png)

**Choisir** : change les codes de couleur dans `default.css` pour les couleurs que tu souhaites utiliser dans ta page web. Les couleurs de ta page web se mettent à jour au fur et à mesure que tu changes les codes couleur.

**Astuce** : tu peux utiliser [coolors.co](https://coolors.co){:target="_blank"} pour générer et personnaliser des palettes de couleurs, puis mettre à jour tes codes couleur dans `default.css`.

## --- code ---

language: html
filename: default.css
line_numbers: true
line_number_start: 4
line_highlights: 5-14
----------------------------------------------------------

:root {
\--primary: #bccad0;
\--onprimary:#4f4e4e;
\--secondary: #495054;
\--onsecondary:#ffffff;
\--tertiary:#747474;
\--ontertiary: #ffffff;
\--page:#ffffff;
\--onpage:#000000;
\--detail: #9ba8ae;
\--detail2: #000000;
}

\--- /code ---
