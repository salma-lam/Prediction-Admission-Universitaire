# Prédiction des Chances d'Admission Universitaire

Ce mini-projet utilise le dataset "Graduate Admission" pour prédire les chances d'admission d'un étudiant dans une université en fonction de critères académiques et personnels. Le but est de développer et comparer plusieurs modèles de régression pour identifier le plus performant.

## Objectif
Ce projet vise à appliquer des techniques de régression pour prédire les chances d'admission en université en se basant sur divers critères comme le GRE, le TOEFL, le GPA, et d'autres facteurs pertinents. Les étudiants auront l'occasion d'explorer les données, de prétraiter les informations, et d'entraîner différents modèles pour sélectionner celui qui offre la meilleure précision.

## Tâches

### 1. Exploration des données
   - Visualiser la distribution des variables (GRE, TOEFL, GPA, etc.).
   - Étudier la corrélation entre les variables et la variable cible "Chance of Admit".

### 2. Prétraitement des données
   - Standardiser les variables et observer l’effet de cette transformation.
   - Gérer les valeurs manquantes ou incohérentes si nécessaire.

### 3. Entraînement des modèles
   - Tester plusieurs modèles de régression, notamment :
     - Régression linéaire
     - Régression Ridge et Lasso
     - Forêt aléatoire (Random Forest)
   - Analyser les performances et comprendre pourquoi certains modèles surpassent les autres.

### 4. Tuning des hyperparamètres
   - Optimiser les hyperparamètres des modèles à l’aide de GridSearchCV ou RandomSearchCV.

### 5. Présentation et analyse des résultats
   - Comparer les performances des modèles à l’aide d'indicateurs tels que RMSE et R².
   - Visualiser les résultats à l’aide de graphiques pour les prédictions et les erreurs.

## Prérequis

- Python 3.x
- Bibliothèques Python : `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`


