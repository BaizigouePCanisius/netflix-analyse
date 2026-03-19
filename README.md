# 🎬 Analyse Complète du Catalogue Netflix

> Rapport d'analyse interactif du catalogue Netflix — 8 807 titres, 6 axes d'analyse, 20 graphiques Plotly.

🌐 **[Voir le rapport en ligne](https://BaizigouePCanisius.github.io/netflix-analyse/)**

---

## 📊 Aperçu

Ce rapport présente une analyse exploratoire approfondie du dataset `netflix_titles.csv` réalisée avec **Python**, **Pandas** et **Plotly**.

| Indicateur | Valeur |
|---|---|
| 🎬 Titres analysés | **8 807** |
| 🎥 Films | **6 131 (69,6%)** |
| 📺 Séries | **2 676 (30,4%)** |
| 🌍 Pays représentés | **86** |
| 📈 Graphiques interactifs | **20** |
| 🔍 Axes d'analyse | **6** |

---

## 🗂️ Structure du rapport

```
Netflix_Rapport/
├── index.html                    ← 🏠 Page d'accueil
└── pages/
    ├── analyse1_apercu.html      ← 📊 Aperçu général
    ├── analyse2_geo.html         ← 🌍 Géographie
    ├── analyse3_genres.html      ← 🎭 Genres
    ├── analyse4_temps.html       ← 📅 Temporel
    ├── analyse5_films.html       ← 🎬 Films vs Séries
    └── analyse6_acteurs.html     ← 🌟 Acteurs & Réalisateurs
```

---

## 🔍 Analyses réalisées

### 1. 📊 Aperçu Général
- Répartition Films vs Séries (69,6% / 30,4%)
- Évolution des ajouts au catalogue 2008–2021

### 2. 🌍 Analyse Géographique
- Top 15 pays producteurs
- Carte choroplèthe mondiale
- Répartition Films/Séries par pays

### 3. 🎭 Analyse des Genres
- Top 20 genres les plus fréquents
- Stacked bar Films vs Séries par genre
- Treemap des combinaisons de genres

### 4. 📅 Analyse Temporelle
- Croissance annuelle et catalogue cumulatif
- Heatmap des ajouts mensuels (2010–2021)

### 5. 🎬 Films vs Séries en Détail
- Distribution des durées de films (~100 min)
- Distribution du nombre de saisons (67% ont 1 saison)
- Violin plot des durées par pays

### 6. 🌟 Acteurs & Réalisateurs
- Top 15 réalisateurs et acteurs
- Sunburst des collaborations
- Network graph réalisateur–acteurs

---

## 🛠️ Technologies utilisées

- **Python 3.11**
- **Pandas** — manipulation des données
- **Plotly Express & Graph Objects** — visualisations interactives
- **Jupyter Notebook** — environnement d'analyse
- **GitHub Pages** — hébergement gratuit

---

## 📁 Dataset

- Source : `netflix_titles.csv`
- **8 807 lignes** × 12 colonnes
- Colonnes : `show_id`, `type`, `title`, `director`, `cast`, `country`, `date_added`, `release_year`, `rating`, `duration`, `listed_in`, `description`

---

*Analyse réalisée avec ❤️ — Mars 2026*
