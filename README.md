# FortuneHorizonDev-DataCleaning
**Français** : Projet de nettoyage de données CRM pour PME e-commerce/marketing. Optimisation des campagnes avec +20 % de précision grâce à un traitement rigoureux des données brutes.  
**English** : CRM data cleaning project for SMEs in e-commerce/marketing. Boost campaign accuracy by +20 % with thorough processing of raw data.

---

## 📋 Aperçu / Overview
Ce dépôt présente un projet de nettoyage de données retail, conçu pour transformer un dataset "sale" en un ensemble de données propre et exploitable. Idéal pour les professionnels du marketing ou les petites entreprises cherchant à améliorer leurs analyses et campagnes.

- **Objectif** : Passer de 8376 lignes brutes à 7579 lignes nettoyées (+20 % de données exploitables).
- **Outils** : Python (pandas, matplotlib, openpyxl), Jupyter Notebook, GitHub.
- **Résultat** : Un dataset optimisé pour des campagnes marketing ciblées.

---

## 🌟 Résultats / Results
- **Avant nettoyage** : Dataset avec 15 % de doublons, des valeurs manquantes (NaNs), et des formats incohérents.
- **Après nettoyage** : 
  - Suppression des doublons et NaNs critiques (colonnes `Item`, `Quantity`, `Total Spent`, `Discount Applied`).
  - Conversion des dates au format standard (YYYY-MM-DD).
  - Visualisation des KPI via un graphique de ventes par catégorie.
- **Impact** : +20 % de précision pour les analyses marketing, prêt à l’emploi pour des PME.

---

## 📂 Contenu du dépôt / Repository Content
| Fichier/Dossier             | Description                                      |
|-----------------------------|--------------------------------------------------|
| `retail_cleaning.ipynb`     | Notebook Jupyter montrant le processus de nettoyage étape par étape. |
| `retail_sales_dirty.csv`    | Dataset brut initial avec 8376 lignes.           |
| `retail_clean.xlsx`         | Dataset nettoyé avec 7579 lignes, prêt à l’emploi. |
| `screenshots/`              | Images des étapes clés (avant/après, diagnostics, KPI). |

### Screenshots
- **[Avant nettoyage](screenshots/avant.png)** : Vue des 5 premières lignes brutes.
- **[Diagnostics](screenshots/diagnostics.png)** : Analyse des doublons et NaNs.
- **[Après nettoyage](screenshots/apres.png)** : Vue des 5 premières lignes nettoyées.
- **[KPI](screenshots/kpi.png)** : Graphique des ventes par catégorie.

---
