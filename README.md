# Titanic Survival Prediction Project
## Introduction

Ce projet explore le célèbre dataset Titanic, issu de Kaggle, pour développer un modèle de machine learning capable de prédire si un passager aurait survécu au naufrage. C'est une excellente introduction aux fondamentaux du machine learning et à l'analyse exploratoire des données (EDA).
Objectif

L'objectif principal est de créer un modèle prédictif performant en suivant ces étapes :

    Explorer les données pour comprendre les relations entre les variables.
    Prétraiter et nettoyer les données.
    Construire, entraîner, et évaluer plusieurs modèles de machine learning.
    Comparer les performances des modèles pour choisir le meilleur.

Données utilisées

Le dataset Titanic contient les informations suivantes pour chaque passager :

    Variables principales : Survived (variable cible), Pclass, Sex, Age, Fare, etc.
    Défis des données : valeurs manquantes (Age, Cabin), déséquilibre des classes (Survived), et transformation des variables catégoriques.

Approche méthodologique
### 1. Analyse exploratoire des données (EDA)

    Visualisation des données avec des bibliothèques comme Matplotlib et Seaborn.
    Identification des relations entre les caractéristiques (ex. : le genre ou la classe influencent-ils la survie ?).
    Traitement des données manquantes et des outliers.

### 2. Prétraitement des données

    Encodage des variables catégoriques (Sex, Embarked).
    Normalisation et standardisation des variables numériques.
    Création de nouvelles fonctionnalités pertinentes (ex. : regrouper les âges en catégories).

### 3. Modélisation

    Modèles testés : Random Forest, SVM, Gradient Boosting, Decision Tree, Regression linear.
    Validation croisée et recherche des hyperparamètres pour optimiser les performances.
    Évaluation des modèles avec des métriques comme la précision, le rappel et l'AUC-ROC.

### 4. Résultats et interprétation

    Meilleur modèle obtenu : Pas de score pour le moment, à mettre à jour.
    Précision obtenue : À mettre à jour.
    Analyse des principales variables influençant les prédictions.

## Technologies utilisées

    Langages : Python
    Bibliothèques : pandas, numpy, scikit-learn, matplotlib, seaborn
    Outils : Jupyter Notebook, GitHub

## Structure du projet

    data/ : Contient le dataset Titanic (train.csv, test.csv).
    notebooks/ : Les notebooks Jupyter pour l'EDA et la modélisation.
    models/ : Fichiers modèles sauvegardés pour prédictions futures.
    README.md : Ce fichier explicatif.


## Contributeur

    KANDJI Mouhamadou KANDJI - Développeur principal

## Références

    Dataset Titanic - Kaggle
    Documentation scikit-learn