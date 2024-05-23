# Projet de Prévision Halieutique Marocaine

Ce projet vise à analyser et prévoir la production, la consommation et la contribution nutritionnelle des produits halieutiques au Maroc. Les données historiques et les prévisions sont présentées de manière à fournir une vision claire des tendances et des variations attendues jusqu'en 2030.

## Introduction

L'industrie halieutique est un pilier important de l'économie marocaine. Ce projet a pour but d'utiliser des techniques de science des données pour prévoir les tendances futures de la production, de la consommation et des exportations de produits halieutiques. Cela permettra d'orienter les décisions stratégiques et d'assurer une gestion durable des ressources halieutiques.

## Objectifs du Projet

- Prévoir les tendances futures des exportations de produits halieutiques.
- Analyser la production et la consommation nationale.
- Évaluer la contribution nutritionnelle des produits halieutiques au Maroc.
- Fournir des recommandations pour une gestion durable et stratégique des ressources.

## Données Utilisées

Les données utilisées dans ce projet proviennent de sources fiables et comprennent des informations historiques sur la production, la consommation, et les exportations de produits halieutiques au Maroc. Les données sont traitées et analysées pour extraire des tendances et des prévisions significatives.

## Contenu du Projet

### 1. Notebooks Jupyter

- *Data_Cleaning_National.ipynb* : Préparation et traitement des données historiques nationales.
- *Data_Cleaning_Exports.ipynb* : Préparation et traitement des données historiques d'exportation.
- *forecasting_exports_fish.ipynb* : Analyse et prévisions des exportations de produits halieutiques marocains.
- *Forecasting_National.ipynb* : Prévisions de la production, de la consommation et de la contribution nutritionnelle à l'échelle nationale.

### 2. Liens Additionnels

Vous pouvez trouver des fichiers et des ressources supplémentaires pour ce projet sur [Google Drive](https://drive.google.com/drive/folders/1e57Gl_ZdxNjfEx2MNIT7NjoLQ_eupwHR?usp=sharing).

## Structure des Notebooks

### Data_cleaning_national.ipynb

1. *Chargement de données initiales* : Importation des données initiales qui ne sont pas encore traités.
2. *Transformation de ces données* : Préparation et traitement des données historiques nationales.
3. *Sauvegarde* : Sauvegarde des données traitées dans des nouveaux fichiers.
   
### Data_Cleaning_Exports.ipynb

1. *Chargement de données initiales* : Importation des données initiales qui ne sont pas encore traités.
2. *Transformation de ces données* : Préparation et traitement des données historiques d'exportation.
3. *Sauvegarde* : Sauvegarde des données traitées dans des nouveaux fichiers.

### forecasting_exports_fish.ipynb

1. *Chargement des Données* : Importation des données d'exportation déjà traitées.
2. *Analyse Exploratoire des Données (EDA)* : Visualisation des tendances historiques.
3. *Modélisation et Prévisions* : Utilisation de modèles de séries temporelles pour prévoir les exportations futures.
4. *Évaluation du Modèle* : Analyse des performances du modèle (RMSE, MSE, etc.).
5. *Conclusion* : Synthèse des résultats.

### Forecasting_National.ipynb

1. *Chargement des Données* : Importation des données historiques nationales déjà traitées.
2. *Analyse Exploratoire des Données (EDA)* : Visualisation des tendances historiques de la production, de la consommation et de la contribution nutritionnelle.
3. *Modélisation et Prévisions* : Prévisions des différentes métriques à l'aide de modèles de machine learning.
4. *Évaluation du Modèle* : Analyse des performances du modèle (RMSE, MSE, etc.).
5. *Conclusion* : Analyse comparative.

## Résultats Clés
- *Augmentation des Exportations* : Les prévisions montrent une augmentation continue des exportations de produits halieutiques marocains jusqu'en 2030.
- *Stabilité Relative* : Les prévisions indiquent une stabilité relative pour la production, la consommation et la contribution nutritionnelle des produits halieutiques, avec des fluctuations mineures attendues jusqu'en 2030.
- *Variabilité Potentielle* : Les marges d'incertitude révèlent une variabilité possible dans les résultats prévisionnels, due à divers facteurs influençant le secteur halieutique.

## Recommandations

1. *Planification Stratégique* : Utiliser les prévisions pour élaborer des stratégies de développement durable.
2. *Gestion des Risques* : Mettre en place des mesures pour gérer les variations imprévues.
3. *Investissements* : Investir dans des technologies de pêche durable et des infrastructures.

## Utilisation

### Prérequis

- Python 3.x
- Jupyter Notebook
- Bibliothèques Python : pandas, numpy, matplotlib, scikit-learn, statsmodels, pmdarima, keras, pandas-datareader

### Instructions

1. *Cloner le Répertoire* : Clonez le répertoire contenant les notebooks et les fichiers associés.
   ```bash
   git clone https://github.com/MYassineBoum/Produits-Halieutiques-Maroc-DDDM.git
   ```
2. *Installer les Dépendances* : Assurez-vous d'avoir les bibliothèques nécessaires installées.
   ```bash
   pip install -r requirements.txt
   ```
