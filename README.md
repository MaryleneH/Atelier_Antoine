# Formation Vibe coding statistique — Étape 0

Ce dossier contient les premières slides Quarto Reveal.js de la formation : cadrage, destinataires, technologies, contraintes professionnelles, confidentialité, garde-fous et règles de versionnement pour maîtriser un produit vibe codé.

## Structure

```text
Atelier_Antoine/
├── README.md
└── slides/
    ├── step0_setting.qmd   ← slides de la formation (18 slides)
    └── step0-theme.scss    ← thème visuel vert-gris, fond clair
```

## Rendu local

Depuis le dossier `slides/` :

```bash
quarto render step0_setting.qmd
```

Le rendu produit un fichier HTML Reveal.js autonome (`step0_setting.html`). Le YAML utilise `embed-resources: true` — aucune ressource externe n'est appelée à l'ouverture.

## Slides couvertes

| # | Titre |
|---|-------|
| 1 | Vibe coding statistique — titre |
| 2 | Pourquoi une étape 0 ? |
| 3 | Le contrat de départ |
| 4 | À qui parle-t-on ? |
| 5 | La cible technique |
| 6 | Les briques retenues |
| 7 | Ce que l'on ne fait pas |
| 8 | Contraintes professionnelles |
| 9 | Confidentialité et données fictives |
| 10 | Le flux de production |
| 11 | Garantir la maîtrise du produit vibe codé |
| 12 | La définition du « fini » |
| 13 | La boucle de vibe coding |
| 14 | Le prompt n'est pas une demande de code |
| 15 | Le fil rouge de la formation |
| 16 | Ce que l'on va construire ensuite |
| 17 | Versionnement Git — les règles |
| 18 | Commit conseillé |

## Déploiement GitHub Pages

Déposer le HTML généré dans un dossier `docs/` ou sur une branche `gh-pages` du dépôt GitHub, puis activer GitHub Pages dans les paramètres du dépôt.

## Commit recommandé

```bash
git add slides/step0_setting.qmd slides/step0-theme.scss README.md
git commit -m "[INIT] add step 0 training slides — cadrage et garde-fous"
```
