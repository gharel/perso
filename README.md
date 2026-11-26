# Projets perso · Guillaume Harel

Page d'index de mes projets perso : petits outils web gratuits et sans compte.

**En ligne : https://gharel.github.io/perso/**

| # | Projet | Pour quoi faire | Adresse |
|---|---|---|---|
| 01 | Piscine | Calculer les doses d'une piscine au sel | https://gharel.github.io/piscine/ |
| 02 | Tea Time | Apprendre l'anglais avec une prof vocale IA locale | https://gharel.github.io/teatime/ |
| 03 | Bacchus | Estimer son taux d'alcoolémie (formule de Widmark) | https://gharel.github.io/bacchus/ |
| 04 | Hometastic | Application du foyer : courses, tâches, maison, voitures, papiers | https://gharel.github.io/hometastic/ |
| 05 | Fournée | Batch cooking : plats de la semaine, courses, session de cuisine guidée, frigo | https://gharel.github.io/cooking/ |

## Fichiers

- `index.html` : la page, HTML et CSS sans dépendance ni build (polices Google Fonts : Syne, comme le logo, et JetBrains Mono).
- `logo.svg` : le logo « gh. » (Syne 800 vectorisé, point vert acide), aussi utilisé comme favicon.
- `apple-touch-icon.png` : icône 180 px pour l'écran d'accueil iOS.

## Ajouter un projet

Copier un bloc `<li>` de la liste `.index` dans `index.html`, changer le lien, le numéro, le glyphe SVG, le nom, la description et les tags, puis mettre à jour le compteur `(06)` du titre, la phrase d'introduction et `og:description`.

Chaque push sur `main` met la page à jour sur GitHub Pages, par le workflow `.github/workflows/publier.yml`. Il ne publie que `index.html`, `logo.svg` et `apple-touch-icon.png` (pas ce README) : un nouveau fichier du site s'ajoute à sa liste.
