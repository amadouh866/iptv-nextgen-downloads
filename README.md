# iptv-nextgen-downloads
Binaires de distribution officiels pour IPTV Next-Gen — lecteur multimédia IPTV pour Windows. Téléchargez la dernière version (.exe/.msi) ici.

# IPTV Next-Gen 📺

Un lecteur multimédia IPTV moderne, rapide et élégant, conçu pour offrir la meilleure expérience de visionnage sur ordinateur (Windows/Mac/Linux).

## 🚀 À propos de l'application

IPTV Next-Gen est une "coquille vide" technique de lecture multimédia. L'application est conçue pour se connecter de manière fluide et rapide à des fournisseurs de services via l'API Xtream Codes. 

**Fonctionnalités principales :**
*   **Haute Performance** : Construit avec Tauri et Rust pour une consommation mémoire minimale.
*   **Lecteur Universel** : Support natif des flux HLS (.m3u8) et des VOD (.mp4) avec sélection des pistes audio et sous-titres.
*   **Expérience Télévision** : Interface entièrement navigable au clavier/télécommande (Spatial Navigation).
*   **Mode Hors-Ligne** : Téléchargement natif ultra-rapide des films et séries pour les regarder sans connexion.
*   **Synchronisation et Historique** : Reprenez la lecture exactement là où vous vous étiez arrêté.

## 🛠️ Technologies utilisées

*   **Frontend** : React 19, TypeScript, Vite
*   **UI & Design** : CSS Pur (Glassmorphism), Tabler Icons
*   **Moteur Vidéo** : HTML5 `<video>`, Hls.js
*   **Backend & Moteur Système** : Rust, Tauri V2
*   **Base de données** : SQLite (via Tauri SQL Plugin)

## 💻 Installation (Pour les développeurs)

Assurez-vous d'avoir installé **Node.js (v20+)** et **Rust**.

```bash
# 1. Cloner le dépôt
git clone https://github.com/votre-nom/iptv-nextgen.git
cd iptv-nextgen

# 2. Installer les dépendances
npm install

# 3. Lancer en mode développement
npm run tauri dev

# 4. Compiler l'installateur Windows (.msi)
npm run tauri build
```

## ⚖️ Avertissement Légal & Responsabilité

**Important :** Cette application ne fournit, n'héberge, ne distribue et ne vend aucun contenu vidéo, chaîne de télévision ou flux. 
L'utilisateur est seul responsable de s'assurer qu'il possède les droits légaux d'accéder aux listes M3U ou aux comptes Xtream qu'il renseigne dans l'application. Les développeurs de ce logiciel déclinent toute responsabilité en cas d'utilisation illégale à des fins de piratage.

*© 2026 Edition Premium Immersion. Tous droits réservés.*
