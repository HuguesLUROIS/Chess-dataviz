# ♟ Chess Dataviz

Analyse de 5 093 parties d'échecs personnelles jouées sur Chess.com de 2018 à 2026. Un projet de data storytelling construit en JavaScript et D3.js, directement depuis un export CSV depuis le site https://chessinsights.xyz/.

🔗 **[Voir le projet en ligne](https://hugueslurois.github.io/Chess-dataviz/index.html)**

---

## Visualisations

**Progression Elo & précision** — Évolution mensuelle du classement Elo et de la précision moyenne par trimestre selon les trois cadences, avec filtres interactifs et infobulle en survolant les graphiques.

**Explorateur d'ouvertures** — Échiquier interactif : jouez un coup et visualisez les réponses les plus fréquentes avec leur winrate. Les flèches partent de la case réelle de chaque pièce ; les cavaliers tracent leur déplacement en L.

**Heatmap des déplacements** — Fréquence de déplacement de chaque pièce sur chaque case. Cliquez sur une pièce pour afficher sa heatmap individuelle.

**Distribution des coups** — Comparaison de la distribution du nombre de coups par partie selon le résultat, complétée par les modes de fin de partie.

---

## Démo

Une vidéo de démonstration est disponible dans le dossier [`demo/`](demo/).

---

## Stack technique

[D3.js v7](https://d3js.org/) · JavaScript vanilla · HTML / CSS · GitHub Pages
