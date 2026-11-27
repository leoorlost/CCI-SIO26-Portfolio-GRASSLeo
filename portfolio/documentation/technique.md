---
title: Dossier d'étude - Documentation Technique
author: Léo GRASS
creator: VS Code / Typora
subject: Atelier de professionnalisation 1 - BTS SIO
header: Dossier d'étude - Technique
footer: ${title} -${author} - Page ${pageNo} /${totalPages}
date: 2026-11-27

---

# Dossier d'étude : Documentation Technique du Portfolio

**Version** : 1.1  
**Auteur** : Léo GRASS  
**Date de création** : 16/10/2026  
**Date de modification** : 27/11/2026  

**Sommaire :**

> [TOC]

<div style="page-break-after:always"></div>

## 1. Technologies et logiciels utilisés

### 1.1. Langages de programmation et de structuration

- **HTML5** : Langage de balisage sémantique utilisé pour structurer le contenu des pages du portfolio (respect des standards W3C).
- **CSS3** : Langage de feuilles de style utilisé pour la mise en forme graphique, la gestion des variables de couleurs et l'adaptation responsive (*Flexbox*, *CSS Grid*, *Media Queries*).
- **JavaScript (ES6+)** : Langage de script côté client utilisé pour les interactions dynamiques (menu hamburger mobile, validation de formulaires).
- **Markdown (CommonMark)** : Langage de balisage léger utilisé pour la rédaction structurée de l'ensemble du dossier d'étude.

### 1.2. Outils de développement et justifications techniques

- **Visual Studio Code (v1.95+)** : Éditeur de code source principal. *Justification* : Léger, extensible (extensions Live Server, W3C Validation, Prettier) et offrant une intégration native de Git et du terminal WSL.
- **Git (v2.43+)** : Système de contrôle de version décentralisé. *Justification* : Permet d'assurer la traçabilité de l'avancement du projet grâce à des commits atomiques et réguliers sur une branche unique (`main`).
- **GitHub** : Plateforme d'hébergement de dépôts Git (`CCI-SIO26-Portfolio-GRASSLeo`). *Justification* : Permet la sauvegarde distante du code source, le partage sécurisé avec les formateurs et la préparation au déploiement.
- **Figma (Version Web)** : Outil de conception d'interfaces UI/UX. *Justification* : Permet de formaliser la charte graphique, les wireframes et les maquettes responsives (Desktop/Mobile) avant la phase d'intégration.
- **Typora (v1.9+)** : Éditeur Markdown WYSIWYG. *Justification* : Permet de générer des exports PDF paginés propres avec en-têtes, pieds de page et sommaire automatique à partir des fichiers `.md`.

<div style="page-break-after:always"></div>

## 2. Architecture technique de l'environnement de développement

### 2.1. Description de l'environnement système

- **Système d'exploitation hôte** : Windows 11 Professionnel (64 bits).
- **Environnement de développement (Virtualisation légère)** : WSL 2 (Windows Subsystem for Linux) avec distribution **Ubuntu 24.04 LTS**.
- **Justification technique** : L'utilisation de WSL 2 avec Ubuntu permet de travailler directement dans un environnement Linux natif (ligne de commande Bash, gestion fine des droits Unix, utilisation native d'OpenSSH et Git) tout en conservant la compatibilité avec les outils graphiques Windows (VS Code, navigateur, Figma). Cela reproduit fidèlement l'environnement des serveurs de production Linux.

### 2.2. Organisation des répertoires du projet

Le projet est stocké dans le répertoire utilisateur Linux (`~/projets/CCI-SIO26-Portfolio-GRASSLeo`) et respecte strictement l'arborescence imposée :

```text
CCI-SIO26-Portfolio-GRASSLeo/
├── .git/                     # Dépôt Git local et historique des versions
├── documentation/            # Dossier d'étude complet
│   ├── charte.md             # Charte graphique et maquettes
│   ├── contenu.md            # Contenu textuel et visuel brut du site
│   ├── technique.md          # Documentation technique (présent fichier)
│   └── medias/               # Ressources images intégrées aux fichiers .md
├── html/                     # Racine du site web (DocumentRoot)
│   ├── assets/               # Ressources statiques du site
│   │   ├── css/
│   │   │   └── style.css     # Feuille de style unique et responsive
│   │   ├── fonts/            # Polices locales si hébergées en interne
│   │   ├── img/              # Images optimisées pour le web (WebP/PNG/SVG)
│   │   └── js/
│   │       └── main.js       # Scripts d'interaction JavaScript
│   ├── index.html            # Page d'accueil
│   ├── parcours.html         # Page formations et expériences
│   ├── projets.html          # Page liste des projets
│   ├── atelier3.html         # Page dédiée à l'Atelier 3
│   ├── veille.html           # Page veille technologique
│   ├── mentions-legales.html # Page mentions légales
|   └── contact.html
└── README.md                 # Présentation générale du dépôt GitHub
```

