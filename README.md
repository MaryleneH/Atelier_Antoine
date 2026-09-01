# Formation Vibe coding statistique — Étape 0

Ce dossier contient les premières slides Quarto Reveal.js de la formation : cadrage, destinataire, technologies, diffusion et garde-fous pour maîtriser un produit vibe codé.

## Fichiers

```text
formation_vibe_quarto_step0/
├── README.md
└── slides/
    ├── step0_setting.qmd
    └── step0-theme.scss
```

## Rendu local

Depuis le dossier `slides/` :

```bash
quarto render step0_setting.qmd
```

Le rendu produit un fichier HTML Reveal.js. Le YAML utilise `embed-resources: true` pour viser un fichier autonome.

## Déploiement GitHub Pages

Déposer le dossier dans un dépôt GitHub personnel, puis publier le HTML généré via GitHub Pages.

Commit conseillé :

```bash
git add README.md prompt_copilot_step0.md slides/step0_setting.qmd slides/step0-theme.scss
git commit -m "[INIT] add step 0 training slides"
```
