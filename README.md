# 📊 Business Intelligence & Data Visualisation — Santé Mondiale

## Contexte

Ce projet a été réalisé dans le cadre du **Master 2 Systèmes d'Information et d'Intelligence des Données** à l'Université Jean Moulin Lyon 3.

L'objectif était de concevoir un **tableau de bord analytique complet sous Power BI** répondant à la problématique suivante :

> *Quel est l'impact réel des dépenses de santé sur l'espérance de vie à travers le monde ?*

## 🗂️ Données

- **Source** : OMS — Global Health Observatory (GHO)
- **Période couverte** : 2000–2021
- **Périmètre géographique** : Monde entier (6 régions OMS)
- **Indicateurs clés** : Espérance de vie, mortalité infantile (< 5 ans), dépenses de santé par habitant (USD), causes de décès, probabilité de décès par MNT (30–70 ans)

## 🏗️ Architecture du rapport (5 pages)

| Page | Titre | Description |
|------|-------|-------------|
| 1 | **Vision d'ensemble** | KPIs globaux, carte mondiale de l'espérance de vie, Top 10 pays |
| 2 | **L'argent et la santé** | Corrélation dépenses/espérance de vie, analyse par région OMS |
| 3 | **La Cause des Décès** | Répartition des causes de mortalité infantile, analyse par quintile de richesse |
| 4 | **Focus sur un pays** | Drill-down par pays : évolution temporelle de l'espérance de vie et des probabilités de décès |

## ⚙️ Fonctionnalités techniques

- **Modèle de données en étoile** : tables de faits et dimensions reliées
- **Drill-down interactif** par pays et par région
- **Slicers croisés** : tranche d'âge, année, pays, région OMS
- **Mode daltonien** : palette de couleurs accessible
- **Mesures DAX** personnalisées pour les KPIs et les calculs de corrélation

## 📁 Contenu du dépôt

```
├── Glenn_PowerBI.pbix         # Fichier Power BI (rapport complet)
└── Rapport-power_BI.pdf       # Export PDF du rapport (4 pages)
```

## 🛠️ Technologies

| Outil | Usage |
|-------|-------|
| **Power BI Desktop** | Modélisation, visualisation, DAX |
| **Excel / Power Query** | Nettoyage et transformation des données OMS |

## 👤 Auteur

**Glenn Madzou-A-Mière** — Master 2 SIID, Université Jean Moulin Lyon 3

[![Portfolio](https://img.shields.io/badge/Portfolio-Voir%20en%20ligne-0077ff?style=flat-square)](https://glenn-mam.github.io/Portfolio/)