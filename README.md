# NexaLab — Site web officiel

Projet réalisé dans le cadre de l'Académie de Programmation IFRI
Bloc 2 — Projet Intégrateur · Modules 3 & 4

---

## Présentation du projet

NexaLab est un laboratoire fictif spécialisé dans l'innovation technologique
pour les entreprises africaines. Ce site vitrine a été conçu et développé de
zéro par notre groupe dans le cadre d'un projet compétitif entre 6 groupes.

Identité visuelle : sombre, épurée, technologique.
Audience cible : directeurs d'entreprise, investisseurs, jeunes talents tech.
Objectif : convaincre en moins de 10 secondes.

---

## Membres du groupe

- Charbelle MEVO — Cheffe de groupe
- Kounouz SIKIROU
- Geoffroy DJEHONNON
- Léoncelle GBESSEMEHLAN
- Ricardo KOUKOUI

---

## Structure du projet

nexalab/
│
├── index.html
│
├── styles/
│   ├── base.css
│   ├── header.css
│   ├── hero.css
│   ├── about.css
│   ├── services.css
│   ├── stats.css
│   ├── team.css
│   ├── testimonials.css
│   ├── contact.css
│   └── footer.css
│
├── assets/
│   ├── images/
│   └── icons/
│
└── README.md


---

## Architecture CSS — Tableau des fichiers

| Fichier | Responsabilité | Éléments gérés |
|---|---|---|
| `base.css` | Styles globaux de toute la page | Reset, variables CSS, `body`, typographie |
| `header.css` | Barre de navigation | `.navbar`, `.navbar-logo`, `.navbar-links` |
| `hero.css` | Section d'accroche principale | `.hero`, `.hero-title`, `.hero-subtitle`, `.hero-cta` |
| `about.css` | Section à propos et mission | `.about`, `.about-image`, `.about-content` |
| `services.css` | Section services | `.services-grid`, `.service-card`, `.service-icon` |
| `stats.css` | Chiffres clés | `.stats`, `.stat-item`, `.stat-number`, `.stat-label` |
| `team.css` | Section équipe | `.team-grid`, `.team-card`, `.team-photo`, `.team-name` |
| `testimonials.css` | Témoignages clients | `.testimonials-grid`, `.testimonial-card`, `.testimonial-quote` |
| `contact.css` | Formulaire de contact | `.contact-form`, `.form-input`, `.form-textarea`, `.form-btn` |
| `footer.css` | Pied de page | `.footer`, `.footer-links`, `.footer-socials`, `.footer-copy` |

---

## Choix de design

### Palette de couleurs
```css
:root {
  --color-bg: #0a0a0f;         /* fond principal — noir profond */
  --color-surface: #13131a;    /* fond des cartes et sections */
  --color-accent: #7c3aed;     /* violet — couleur d'accentuation */
  --color-text: #ffffff;       /* texte principal — blanc */
  --color-text-secondary: #aaaaaa; /* texte secondaire — gris clair */
  --color-border: #1e1e2e;     /* bordures subtiles */
}
```

### Typographie
- Police principale : **Inter** (Google Fonts) — moderne, lisible, technologique
- Titres : gras, grande taille, espacement des lettres élargi
- Corps de texte : 16px, line-height 1.7

### Décisions visuelles
- Fond sombre sur toute la page — cohérent avec l'ADN technologique de NexaLab
- Accent bleu pour les boutons, bordures et éléments clés — couleur distinctive
- Cartes avec fond légèrement plus clair que le fond principal — effet de profondeur
- Flexbox pour toutes les mises en page principales

---

## Logique de nommage des classes

Toutes les classes CSS suivent la convention **BEM simplifiée** :
- `.section-nom` pour les conteneurs de section
- `.element-role` pour les éléments à l'intérieur
- Exemples : `.service-card`, `.hero-title`, `.team-photo`

Règle appliquée : **une classe = un rôle lisible sans lire le code autour**.

---

## Responsive design

Trois breakpoints définis dans chaque fichier CSS :

| Breakpoint | Cible | Ce qui change |
|---|---|---|
| `max-width: 768px` | Mobile | Flex en colonne, padding réduit, texte plus petit |
| `max-width: 1024px` | Tablette | Grilles à 2 colonnes, ajustements intermédiaires |
| Par défaut | Desktop | Mise en page complète |

---

## Comment ajouter une nouvelle page

1. Créer le fichier HTML dans le dossier racine (ex: `portfolio.html`)
2. Dans le `<head>`, lier au minimum :
```html
<link rel="stylesheet" href="styles/base.css">
<link rel="stylesheet" href="styles/header.css">
<link rel="stylesheet" href="styles/footer.css">
```
3. Créer un fichier CSS spécifique dans `styles/` (ex: `portfolio.css`)
4. Lier ce fichier dans le `<head>` après les fichiers communs
5. Commiter avec un message explicite

Aucun fichier existant n'a besoin d'être modifié.

---

## GitHub

- Branche de travail : `projet-integrateur`
- Branche principale : `main` (non modifiée)
- Convention des messages : `feat:`, `fix:`, `docs:`, `style:`, `assets:`, `test:`

---

## Niveau | IFRI · Licence 1 · Académie de Programmation · 2025–2026
