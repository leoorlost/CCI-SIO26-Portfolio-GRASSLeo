---
title: Dossier d'étude - Documentation Technique
author: Léo GRASS
creator: VS Code / Typora
subject: Atelier de professionnalisation 1 - BTS SIO
header: Dossier d'étude - Technique
footer: ${title} - ${author} - Page ${pageNo} / ${totalPages}
date: 2026-10-16
---

# Dossier d'étude : Documentation Technique du Portfolio

Date de création : 16/10/2026
Date de modification : 16/10/2026

Sommaire :
> [TOC]

<div style="page-break-after:always"></div>

## 1. Technologies et logiciels utilisés

### 1.1. Langages de programmation et de mise en forme
- HTML5 : Langage de balisage pour structurer le contenu des 6 pages du portfolio.
- CSS3 : Langage de style pour la mise en forme graphique.
- JavaScript : Langage de script pour dynamiser certaines fonctionnalités de la page.
- Markdown : Langage de balisage léger utilisé pour la rédaction des documentations du projet.

### 1.2. Outils de développement et d'environnement
- Éditeur de code : Visual Studio Code (VS Code)
- Système de contrôle de version : Git
- Hébergement de code source : GitHub (dépôt distant)
- Outil de maquettage : Figma (pour la charte graphique et les wireframes)
- Outil de conversion de documents : Typora ou extension Markdown PDF (pour l'export en PDF paginé)

<div style="page-break-after:always"></div>

## 2. Architecture technique de l'environnement de développement

### 2.1. Description de l'environnement
- Système d'exploitation hôte : Windows 11
- Environnement de travail / Virtualisation : WSL Ubuntu 26.04
  - Justification technique : Utilisation de WSL Ubuntu 26.04 pour disposer d'un terminal bash natif compatible avec les normes de développement web professionnelles et la gestion fluide des commandes Git.

### 2.2. Organisation des répertoires du projet
- Le projet respecte une arborescence stricte et normalisée :
  - portfolio/ : Racine du projet contenant le suivi Git.
  - documentation/ : Contient les fichiers Markdown (contenu.md, charte.md, technique.md) et le sous-dossier medias/.
  - html/ : Contient l'ensemble du site web, avec le dossier assets/ (css/, fonts/, img/, js/) et la page index.html.

<div style="page-break-after:always"></div>

## 3. Environnement de production (à compléter en fin de projet)

### 3.1. Description de la cible de déploiement
- Hébergeur web : ...
- Type de serveur : Serveur Web Apache

### 3.2. Procédure de transfert (Déploiement)
- Étapes pour basculer du développement à la production :
  1. Validation et fusion du code sur la branche principale (main) du dépôt Git.
  2. Vérification de la validité du code HTML/CSS (W3C Validator).
  3. Transfert des fichiers du dossier html/ vers le serveur de production via SSH / Git clone.
  4. Test de bon fonctionnement de l'ensemble des liens et des pages sur le serveur distant.
