# BIBLE STRAINS SYSTEM 🌿

> **L'Encyclopédie Botanique Numérique.**
> Une interface minimaliste pour l'exploration et l'analyse de données variétales.

![Version](https://img.shields.io/badge/version-1.0.0-black?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-gray?style=flat-square)
![Stack](https://img.shields.io/badge/stack-HTML%20%7C%20Tailwind%20%7C%20VanillaJS-white?style=flat-square)

## 📋 À propos

**Bible Strains** est une application web ultra-légère conçue pour cataloguer, trier et visualiser une vaste base de données de variétés botaniques. 

Le projet se distingue par son approche **"Software-like"** : bien qu'hébergé sur le web, il est conçu pour s'ouvrir et se comporter comme un logiciel de bureau natif, sans les distractions de l'interface du navigateur, grâce à un lanceur JavaScript dédié.

L'esthétique repose sur un design monochrome, inspiré du *Swiss Style*, privilégiant la lisibilité, la typographie et l'espace négatif.

## ✨ Fonctionnalités Clés

### 🖥️ Landing Page (Launcher)
*   **Design Immersif :** Interface d'accueil épurée en noir et blanc.
*   **Mode Application :** Script de lancement ouvrant l'encyclopédie dans une fenêtre dédiée (popup chromeless) pour une immersion totale.
*   **Mise en avant :** Section dynamique présentant des spécimens clés (Acapulco Gold, Afghani, AK-47).

### 📂 L'Encyclopédie (Core App)
*   **Base de Données Embarquée :** Gestion de milliers d'entrées via un objet JSON local (aucune latence serveur).
*   **Recherche Instantanée :** Filtrage en temps réel par nom.
*   **Tri Dynamique :** Organisation par Nom, Type (Sativa/Indica/Hybride) ou Note.
*   **Interface "Drawer" :** Volet latéral coulissant pour afficher les détails techniques (Terpènes, Effets, Description complète) sans quitter la liste.
*   **Performance :** Utilisation de Vanilla JS pour une rapidité d'exécution maximale.

## 🛠️ Stack Technique

Le projet est construit sans dépendances lourdes ni processus de build complexe (No-Build).

*   **Structure :** HTML5 Sémantique.
*   **Style :** [Tailwind CSS](https://tailwindcss.com/) (via CDN) pour un design utility-first rapide.
*   **Logique :** Vanilla JavaScript (ES6+).
*   **Données :** JSON intégré directement dans le DOM pour une portabilité totale (fichier unique).

## 🚀 Installation & Utilisation

Aucune installation de serveur (Node.js, PHP, etc.) n'est requise. Le projet fonctionne en local ou sur n'importe quel hébergement statique.

1.  **Cloner le dépôt :**
    ```bash
    git clone https://github.com/votre-username/bible-strains.git
    ```

2.  **Lancer l'application :**
    *   Ouvrez simplement le fichier `index.html` dans votre navigateur web moderne (Chrome, Firefox, Safari, Edge).
    *   Cliquez sur le bouton **"Lancer l'Application"**.

3.  **Note importante sur les Popups :**
    *   Le lanceur utilise `window.open` pour simuler une fenêtre logicielle.
    *   ⚠️ Si rien ne se passe, vérifiez que votre navigateur ne bloque pas les fenêtres contextuelles (popups) pour ce site. Autorisez-les pour profiter de l'expérience complète.

## 📂 Structure des Fichiers

```text
bible-strains/
├── index.html          # Page d'accueil & Lanceur (Landing Page)
├── biblestrains.html   # Application principale & Base de données
└── README.md           # Documentation
```

## 🎨 Design System

*   **Police :** Inter (Google Fonts).
*   **Palette :** Monochrome (Black `#000000`, White `#FFFFFF`, Gray Scale).
*   **Iconographie :** SVG Inline minimalistes.

---

*© 2026 Bible Strains System. Conçu pour l'archivage et la clarté.*
