# US SBA Loan Prediction

## Description

Ce projet a pour objectif de prédire si une entreprise sera capable de rembourser un prêt garanti par la **United States Small Business Administration (US SBA)**. En tant que **data scientist**, vous êtes chargé de développer un modèle de classification binaire permettant de déterminer si un prêt peut être accordé à une entreprise en fonction de diverses caractéristiques.

Les petites entreprises jouent un rôle crucial dans l’économie américaine, et l’US SBA vise à soutenir leur croissance. Cependant, certaines entreprises font défaut sur leurs prêts. L'objectif de ce projet est donc de prédire la probabilité qu'une entreprise puisse rembourser son prêt en fonction de son profil et des données disponibles avant l'octroi du crédit.

---

## Objectifs du Projet

- **Prédire** la capacité de remboursement des prêts garantis par l'US SBA.
- **Construire** un modèle de classification binaire.
- **Explorer** les données, effectuer des analyses statistiques et appliquer des techniques de machine learning.
- **Mettre en production** le modèle via une API et une interface web (FastAPI & Django).

---

## Structure du Projet

Ce projet est organisé comme suit :

### 1. **`data_analyse_figure.ipynb`**
   - **But** : Notebook Jupyter pour l’analyse exploratoire des données (EDA).
   - **Contenu** : Visualisations, analyses statistiques et nettoyage initial des données pour comprendre leur structure et leurs relations.
   
### 2. **`data_modelisationX.ipynb`**
   - **But** : Notebook contenant les étapes de modélisation et d’évaluation des modèles.
   - **Modèle** : XGBoost, un algorithme de boosting performant pour la classification.
   - **Contenu** : Préparation des données, entraînement du modèle, évaluation des performances et visualisation des résultats.
   
### 3. **`ydata_profiling.html`**
   - **But** : Rapport généré par l'outil d’analyse automatique des données **DataProfile**.
   - **Contenu** : Vue d'ensemble détaillée du jeu de données, incluant les distributions des variables, les valeurs manquantes, les corrélations et autres statistiques utiles.

### 4. **`requirements.txt`**
   - **But** : Fichier contenant toutes les dépendances nécessaires pour exécuter ce projet.
   - **Contenu** : Bibliothèques Python comme `pandas`, `numpy`, `matplotlib`, `xgboost`, etc.

### 5. **`README.md`**
   - **But** : Ce fichier qui explique la structure du projet, les objectifs et les étapes à suivre pour comprendre et exécuter le code.

### 6. **`data/`**
   - **But** : Dossier contenant les jeux de données nécessaires à l’analyse et à la modélisation.
   - **Contenu** : Fichiers de données utilisés lors des étapes de nettoyage, d’analyse et de modélisation.

---

## Installation

### Prérequis
- Python 3.x
- Pip (gestionnaire de paquets Python)

### Installation des dépendances

1. Clonez ce dépôt :
   ```bash
   git clone https://github.com/votre-utilisateur/US-SBA-Loan-Prediction.git
   cd US-SBA-Loan-Prediction
   ```

2. Installez les dépendances à partir du fichier `requirements.txt` :
   ```bash
   pip install -r requirements.txt
   ```

---

## Utilisation

1. **Analyse des données** :
   - Lancez le notebook `data_analyse_figure.ipynb` pour explorer le jeu de données et effectuer un premier nettoyage.
   
2. **Entraînement du modèle** :
   - Ouvrez le notebook `data_modelisationX.ipynb` pour préparer les données et entraîner le modèle **XGBoost**.
   
3. **Rapport de profiling des données** :
   - Le fichier `ydata_profiling.html` contient un rapport complet sur le jeu de données généré par **DataProfile**.


## Auteurs

- **Antoine - Wael** 
