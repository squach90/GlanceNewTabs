# Glance Dashboard

Ce projet est une configuration personnalisée de **[Glance](https://github.com/glanceapp/glance)** / This project is a custom configuration of **[Glance](https://github.com/glanceapp/glance)**
Il centralise différentes informations utiles au quotidien : actualités, météo, calendrier, cours de la bourse, suivi de l’électricité Tempo, Twitch et YouTube. / It centralizes various useful daily information: news, weather, calendar, stock prices, Tempo electricity tracking, Twitch, and YouTube.

---

## 📑 Fonctionnalités / Features

### 🗓️ Colonne de gauche (small) / Left column
- **Calendrier** avec début de semaine le lundi. / **Calendar** with week starting on Monday.
- **Widget Tempo (EDF)**  
  - Affiche la couleur du jour et de demain (🔵 Bleu, ⚪️ Blanc, 🔴 Rouge). / Displays the color of today and tomorrow (🔵 Blue, ⚪️ White, 🔴 Red).
- **Chaînes Twitch suivies** : / **Followed Twitch Channels**:
  - TheGreatReview  
  - WhataFail  
  - Micode  
  - Binogure  
  - DevBaudo  

---

### 📌 Colonne centrale (full) / Center Column
- **Barre de recherche avec raccourcis :  /  **Search bar** with shortcuts
  - `!yt` → Recherche YouTube / YouTube Search
  - `!ai` → Recherche Perplexity AI / Perplexity AI Search
- **Flux RSS d’actualité** regroupés :  / **Grouped RSS News Feeds**
  - Korben.info  
  - The Verge  
  - Mac4Ever  
  - Le Monde  
- **Chaînes YouTube suivies** / **Followed YouTube Channels** : Hydrios, Dammit Jeff, V2F, Léo Duff, Tao Gassin.  
- **Epic Games Store (jeux gratuits de la semaine)** avec images, titre et date de fin de promo. / **Epic Games Store (free games of the week)** with images, titles, and sale end date.

---

### 🌤️ Colonne de droite (small) / Right column 
- **Météo** à Savigny-le-Temple. / *Weather** in Savigny-le-Temple (France)
- **Progression temporelle** / **Time progression**:  
  - Journée (% écoulé) / Day (% elapsed)
  - Mois (% écoulé) / Month (% elapsed)
  - Année (% écoulé) / Year (% elapsed)
- **Marchés financiers** / **Financial markets** :  
  - CAC 40  
  - Bitcoin (BTC-EUR)  
  - NVIDIA (NVDA)  
  - Apple (AAPL)  
  - Microsoft (MSFT)  

---

## 🚀 Installation (Docker)

(0). Télécharger Docker / Download Docker
1. Télécharger le repo: `git clone https://github.com/squach90/GlanceNewTabs.git` / Clone the repo : `git clone https://github.com/squach90/GlanceNewTabs.git`
2. Faire un: `docker compose up -d` / Do a : `docker compose up -d`

--

## 🔌 Installation (Extension)

(0). Télécharger Chrome/Chromium / Download Chrome/Chromium
1. Télécharger le repo: `git clone https://github.com/squach90/GlanceNewTabs.git` / Clone the repo : `git clone https://github.com/squach90/GlanceNewTabs.git`
2. Aller dans les extension settings (Chrome) / Go to extension settings (Chrome)
3. Activer le mode Développeur / Enable Developer Mode
4. Cliquer sur *Load unpacked* et renseigner le dossier *chromeExtension* / Click *Load unpacked* and enter the *chromeExtension* folder


### License

Fait ce que vous voulez / Do what ever you want
