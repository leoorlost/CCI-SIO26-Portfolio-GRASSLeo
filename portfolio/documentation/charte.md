# Charte graphique du Portfolio

**Date de création** : 22/12/2021 - F. SCHOSSIG

**Date de modification** : 30/10/2026 - [Ton NOM Prénom]

**Sommaire :**

> [TOC]

## 1. Contexte du projet

Ce document constitue la charte graphique officielle pour la réalisation du site web portfolio de GRASS Léo, étudiant en BTS SIO (Services Informatiques aux Organisations) à CCI Campus.

L'objectif de ce portfolio est de présenter mon parcours de formation, mes compétences techniques, mes projets informatiques ainsi que ma veille technologique dans un cadre professionnel et moderne. Ce document sert de guide de référence pour le développement HTML5 / CSS3 afin de garantir une cohérence visuelle sur l'ensemble des pages.

## 2. Explication de l'identité visuelle

L'identité visuelle retenue pour ce portfolio s'appuie sur une esthétique sobre, sobrement axée sur le domaine du numérique et de l'informatique.

Le choix s'est porté sur un style minimaliste et épuré (Flat Design / Dark Mode léger) afin d'assurer une lisibilité optimale des contenus techniques tout en transmettant une image de rigueur, de modernité et de professionnalisme.

## 3. Éléments de déclinaison de cette identité visuelle

### 3.1. Couleurs

La palette de couleurs principale est déclinée comme suit :

- **Couleur principale (Fond)** : `#0F172A` (Bleu nuit très sombre) — apporte du contraste et une ambiance moderne style console / éditeur de code.
- **Couleur secondaire (Cartes / Blocs)** : `#1E293B` (Bleu ardoise) — permet de structurer les sections et de hiérarchiser l'information.
- **Couleur d'accent (Boutons / Liens / Highlights)** : `#38BDF8` (Bleu cyan) — attire l'attention sur les éléments interactifs.
- **Couleur de texte principal** : `#F8FAFC` (Blanc cassé) — assure une excellente lisibilité sur fond sombre.
- **Couleur de texte secondaire** : `#94A3B8` (Gris clair) — utilisé pour les sous-titres, dates et descriptions secondaires.

### 3.2. Typographie

- **Police principale (Titres et Corps de texte)** : `Inter`, sans-serif (Google Fonts) — pour sa clarté et sa lisibilité sur écran.
- **Police secondaire (Code / Éléments techniques)** : `Fira Code`, monospace — pour l'affichage d'extraits de code, de commandes ou de balises.
- **Tailles et hiérarchie** :
  - `h1` : 2.25rem (36px), bold
  - `h2` : 1.75rem (28px), semi-bold
  - `h3` : 1.25rem (20px), medium
  - `p` / `body` : 1rem (16px), regular

### 3.3. Logo, icônes et boutons

- **Logo** : Un monotype ou initiales stylisées `[Initiales]` intégrées dans la barre de navigation.
- **Icônes** : Utilisation de la bibliothèque SVG *Lucide Icons* ou *FontAwesome* (ex: icône GitHub, LinkedIn, messagerie, terminal).
- **Boutons** :
  - *Bouton principal* : Fond cyan `#38BDF8`, texte sombre, coins légèrement arrondis (`border-radius: 6px`).
  - *Bouton secondaire* : Fond transparent avec bordure cyan `#38BDF8`.
  - *Effets survol (Hover)* : Légère variation de luminosité et transition fluide (`transition: all 0.3s ease`).

## 4. Maquettage responsive de chaque page

...

### 4.1. Page d'accueil (`index.html`)

- **Version Desktop** : `...`
- **Version Mobile** : `...`

### 4.2. Page Parcours & Compétences (`parcours.html`)

- **Version Desktop** : `...`
- **Version Mobile** : `...`

### 4.3. Page Projets (`projets.html`)

- **Version Desktop** : `...`
- **Version Mobile** : `...`

## 5. Logique de navigation dans le site

La navigation globale repose sur une barre de menu fixe (header sticked) accessible sur l'ensemble des pages :

1. **Menu principal (Desktop)** : Liens horizontaux vers `Accueil`, `Parcours`, `Projets`, `Veille`, `Contact`.
2. **Menu mobile (Hamburger)** : Menu escamotable déclenché en JavaScript pour les écrans < 768px.
3. **Sélecteur de langue** : Un bouton de bascule `FR / EN` présent dans le header pour la gestion du bilinguisme.
4. **Pied de page (Footer)** : Liens vers les mentions légales, le dépôt GitHub du projet et les réseaux professionnels (LinkedIn).
