# OPEO — Site institutionnel v0

Site vitrine statique pour OPEO Consulting, cabinet de conseil en transformation industrielle.

## Structure

```
Opeo-site-v3/
├── index.html
├── a-propos.html
├── article-example.html
├── carrieres.html
├── contact.html
├── expertises.html
├── expertise-digital.html
├── expertise-excellence.html
├── expertise-rd.html
├── expertise-strategie.html
├── expertise-supply-chain.html
├── mentions-legales.html
├── publications.html
├── secteurs.html
├── transformation.html
├── styles.css
├── .nojekyll
└── assets/
    ├── images/        → photos de fond et visuels de section
    ├── logos/         → tous les logos SVG et PNG
    ├── videos/        → vidéos hero et présentation
    └── photos/        → photos de l'équipe et illustrations
```

## Déploiement sur GitHub Pages

1. Créer un nouveau repo GitHub (ex. `opeo-site-v3`)
2. Pousser ce dossier sur la branche `main`
3. Dans les **Settings** du repo → **Pages** → Source : `Deploy from a branch` → branche `main`, dossier `/root`
4. Le site sera disponible sur `https://<username>.github.io/opeo-site-v3/`

> Le fichier `.nojekyll` à la racine est nécessaire pour que GitHub Pages serve correctement tous les fichiers.

## Stack technique

- HTML / CSS / JavaScript natifs — aucun framework
- Zéro dépendance externe (pas de npm, pas de build step)
- Hébergement statique compatible GitHub Pages, Netlify, Vercel

## Couleurs de marque

| Nom | Hex |
|-----|-----|
| Navy | `#03266A` |
| Cyan | `#1DBDF2` |
| Orange | `#E05A2B` |
