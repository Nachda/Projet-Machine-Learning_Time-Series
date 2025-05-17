 **Projet GSTR1 (BAC+3) ENSA Tétouan 2024-2025**

# Origine des données: SNCF Transilien

## 📘 Description du projet

Ce projet de **Machine Learning_Time Series** a été réalisé dans le cadre du module **Apprentissage Automatique & Applications**

Il s'agit d'un challenge portant sur les données de la **SNCF-Transilien** disponible sur *challengedata.ens.fr*

L’**objectif** est de **prédire le nombre de validations de titres de transport** par jour et par gare, à moyen-long terme, pour optimiser la gestion et la planification des flux voyageurs.

## 📊 Données utilisées

Les données sont structurées comme suit :

- `date` : date de collecte des validations (format YYYY-MM-DD)
- `station` : identifiant anonymisé de la gare (ex : 7RP, J3V…)
- `y` : nombre de validations par jour et par gare
- `job` : 1 si jour ouvrable (lundi à vendredi), 0 sinon
- `ferie` : 1 si jour férié, 0 sinon
- `vacances` : 1 si jour de vacances scolaires, 0 sinon

Les années couvertes dans ce projet sont de 2015 à 2022.

## 🧠 Objectifs

- Explorer et comprendre les tendances temporelles des validations
- Prendre en compte les effets calendaires (vacances, jours fériés…)
- Construire un modèle prédictif robuste (**Persistent model**, **Autoregressive model**, **Random Forest**, **ARIMA**) pour les années futures
- Évaluer les performances des modèles en fonction du RMSE et d’autres métriques

## ⚙️ Technologies utilisées

- Python 3, Scikit-learn
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook, etc.
