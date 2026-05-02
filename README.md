# GROUPE-4-PROJET-BLOC-2

# 🚀 DevStart Architecture — Module 2

## 📌 Description du projet

Ce projet s’inscrit dans le cadre du **Module 2 – Génie Logiciel** de l’Académie de Programmation (IFRI L1).

L’objectif principal est de **concevoir et implémenter une architecture logicielle modulaire** pour le site *DevStart*, en appliquant le principe fondamental :

> **Une partie du code = une seule responsabilité**

Contrairement au Module 1, ce projet ne porte pas sur le design ou le contenu, mais sur **l’organisation du code** afin de garantir sa maintenabilité et son évolutivité.



## 🎯 Objectifs

* Comprendre et appliquer les principes de **modularité**
* Structurer un projet web de manière professionnelle
* Séparer clairement :

  * la structure (HTML)
  * le style (CSS)
  * les responsabilités
* Préparer le projet à évoluer (Portfolio, Blog, Espace Client)



## 🧠 Concept clé

Le projet repose sur une règle simple :

👉 **Un fichier = une responsabilité unique**

Exemples :

* `header.css` → gère uniquement le header
* `footer.css` → gère uniquement le footer
* `base.css` → styles globaux (polices, couleurs, reset)



## 🏗️ Structure du projet

```bash
devstart/
│
├── index.html
│
├── styles/
│   ├── base.css
│   ├── header.css
│   ├── hero.css
│   ├── services.css
│   ├── about.css
│   ├── testimonials.css
│   ├── contact.css
│   └── footer.css
│
├── assets/
│   ├── images/
│   └── icons/
│
└── pages/
    ├── portfolio.html
    ├── blog.html
    └── client.html
```



## ⚙️ Méthodologie

Le projet a été réalisé en 3 phases :

### 1️⃣ Cartographie

* Identification des sections :

  * Header
  * Hero
  * Services
  * About
  * Testimonials
  * Contact
  * Footer
* Analyse des styles CSS existants
* Regroupement des styles par responsabilité

### 2️⃣ Conception

* Création d’une architecture modulaire
* Définition des fichiers CSS
* Identification des composants réutilisables
* Anticipation des futures pages

### 3️⃣ Implémentation

* Découpage du fichier `style.css`
* Réorganisation des fichiers
* Vérification du rendu (identique à l’original)



## 🔄 Gestion Git

* `main` → version originale (Module 1)
* `module2` → version restructurée

Bonnes pratiques :

* Commits réguliers
* Messages clairs
* Travail collaboratif



## 📈 Évolutivité

L’architecture a été conçue pour :

* Ajouter facilement de nouvelles pages
* Réutiliser les composants existants
* Maintenir un code lisible et organisé



## ⚠️ Contraintes respectées

* ✅ Aucun changement visuel
* ✅ Code fonctionnel après refactorisation
* ✅ Justification de chaque choix
* ✅ Structure claire et compréhensible



## 👥 Équipe

* Ricardo Koukoui
* SIKIROU kounouz
* GBESSEMEHLAN Sènami Léoncelle
* Charbelle Enam MEVO
* DJEHONNON  Jésugnon Geoffroy



## 📅 Durée

Projet réalisé sur **5 jours **



## 📚 Conclusion

Ce projet montre l’importance de **penser avant de coder**.
Une bonne architecture permet de :

* gagner du temps
* éviter les bugs
* faciliter le travail en équipe
* rendre le projet évolutif



