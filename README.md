# 🧮 Analyse de l’acceptabilité du revenu universel dans plusieurs pays européens

Ce projet vise à comprendre les **facteurs sociodémographiques et géographiques** influençant le soutien au revenu universel dans plusieurs pays d’Europe, à partir des données de l’enquête **European Social Survey (ESS)**.  
L’analyse repose sur une **approche de data science** allant du nettoyage des données jusqu’à la modélisation avec une régression logistique ordinale.

---

## 🎯 Objectif du projet
- Identifier les groupes sociaux les plus favorables ou réticents au revenu universel
- Comprendre l’impact de l’âge, du genre, du niveau d’éducation et du pays sur l’opinion des citoyens
- Fournir des visualisations et des interprétations accessibles pour orienter la réflexion sur la faisabilité de cette politique

---

## 🔍 Étapes du projet

### 1. 📥 Collecte des données
- Données issues de **l’ESS (European Social Survey) – vague 8**
- Source : [https://doi.org/10.21338/ESS8E02_2](https://doi.org/10.21338/ESS8E02_2)
- Données brutes : +44 000 individus, +500 variables

### 2. 🧹 Préparation et nettoyage
- Sélection des variables pertinentes : âge, genre, niveau d’éducation, pays, acceptabilité du revenu universel
- Suppression ou recodage des données manquantes / aberrantes
- Création de labels explicites pour faciliter l’analyse
- Regroupement des niveaux d’éducation et vérification de la cohérence globale

### 3. 📊 Analyse descriptive
- Distribution de l’âge, du genre et de l’éducation dans l’échantillon
- Répartition de l’acceptabilité par pays et par tranche d’âge
- Visualisation des tendances à l’aide d’histogrammes et tableaux croisés

### 4. 📈 Modélisation statistique
- Régression logistique ordinale (logit cumulatif)
- Variables explicatives : âge, genre, éducation, pays
- Analyse de l’effet marginal et de l’influence des variables sur l’acceptabilité

---

## 🧠 Résultats clés
- 🌍 Le **pays** est le facteur le plus déterminant dans l’opinion sur le revenu universel
- 🧓 Les **jeunes** sont plus favorables que les seniors
- 👩 Les **femmes** sont légèrement moins favorables que les hommes
- 🎓 Le **niveau d’éducation** n’a pas d’effet significatif dans cette étude

---

## 📂 Fichiers du dépôt
| Fichier | Description |
|--------|-------------|
| `DM_BDSAS_25_BALDE_NDIAYE.pdf` | Rapport complet du projet avec la méthodologie, les résultats et l’interprétation |
| `README.md` | Ce fichier de présentation du projet |

---

## 👥 Auteurs et contributions
- **Aissata BALDE** : Conception analytique, modélisation, visualisations, interprétation des résultats
- **Cheikh Mouhamadou Moustapha NDIAYE** : Préparation des données, nettoyage, gestion des bibliothèques

---

## 🧰 Compétences mobilisées
- Nettoyage de données (R)
- Statistiques descriptives et inférentielles
- Régression logistique ordinale
- Analyse critique et interprétation sociopolitique

---

## 📚 Références
- European Social Survey (ESS)
- Van Parijs, Hyafil, Duclos – Travaux sur le revenu universel
