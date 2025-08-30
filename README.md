# Glance Dashboard

Ce projet est une configuration personnalisée de **[Glance](https://github.com/glanceapp/glance)**
Il centralise différentes informations utiles au quotidien : actualités, météo, calendrier, cours de la bourse, suivi de l’électricité Tempo, Twitch et YouTube.

---

## 📑 Fonctionnalités

### 🗓️ Colonne de gauche (small)
- **Calendrier** avec début de semaine le lundi.  
- **Widget Tempo (EDF)**  
  - Affiche la couleur du jour et de demain (🔵 Bleu, ⚪️ Blanc, 🔴 Rouge).  
- **Chaînes Twitch suivies** :  
  - TheGreatReview  
  - WhataFail  
  - Micode  
  - Binogure  
  - DevBaudo  

---

### 📌 Colonne centrale (full)
- **Barre de recherche DuckDuckGo** avec raccourcis :  
  - `!yt` → Recherche YouTube  
  - `!ai` → Recherche Perplexity AI  
- **Flux RSS d’actualité** regroupés :  
  - Korben.info  
  - The Verge  
  - Mac4Ever  
  - Le Monde  
- **Chaînes YouTube suivies** : Hydrios, Dammit Jeff, V2F, Léo Duff, Tao Gassin.  
- **Epic Games Store (jeux gratuits de la semaine)** avec images, titre et date de fin de promo.  

---

### 🌤️ Colonne de droite (small)
- **Météo** à Savigny-le-Temple.  
- **Progression temporelle** :  
  - Journée (% écoulé)  
  - Mois (% écoulé)  
  - Année (% écoulé)  
- **Marchés financiers** :  
  - CAC 40  
  - Bitcoin (BTC-EUR)  
  - NVIDIA (NVDA)  
  - Apple (AAPL)  
  - Microsoft (MSFT)  

---

## 🚀 Installation

(0). Télécharger Docker
1. Télécharger le repo: `git clone https://github.com/squach90/GlanceNewTabs.git`
2. Faire un: `docker compose up -d`
