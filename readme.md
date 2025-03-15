# 🚗 Projet d'Analyse des Clusters Uber NYC

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-2.0+-green.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-red.svg)
![Plotly](https://img.shields.io/badge/Plotly-5.0+-blue.svg)
![NumPy](https://img.shields.io/badge/NumPy-1.20+-yellow.svg)

##  DISLAIMER
Attention le fichier permettant les visualisations (uber_dfclean.csv) étant trop volumineux celles-ci ne sont pas possibles.
Les fichiers sources sont disponibles ici
👉👉<a href="https://full-stack-bigdata-datasets.s3.eu-west-3.amazonaws.com/Machine+Learning+non+Supervis%C3%A9/Projects/uber-trip-data.zip" target="_blank"> Uber Trip Data</a> 👈👈
Et sont à décompresser dans un répertoire /src

## 📋 Description
Ce projet analyse les données des courses Uber à New York pour identifier les zones chaudes (hotspots) et optimiser le positionnement des chauffeurs à travers différentes périodes de la journée.

## 🎯 Objectifs
- Analyser les patterns de demande de courses Uber
- Identifier les zones chaudes selon les jours et heures
- Comparer différentes approches de clustering
- Fournir des recommandations pour le positionnement des chauffeurs

## 📊 Structure du Projet
1. **Préparation et EDA** (01-Uber_Pickups-1-base.ipynb)
   - Nettoyage des données
   - Analyse exploratoire
   - Visualisations préliminaires

2. **Analyse DBSCAN** (01-Uber_Pickups-2-DBSCAN-.ipynb)
   - Implémentation de DBSCAN
   - Optimisation des paramètres
   - Visualisation des clusters

3. **Analyse KMeans** (01-Uber_Pickups-3-Kmeans.ipynb)
   - Implémentation de KMeans
   - Recherche du nombre optimal de clusters
   - Visualisation des résultats

4. **Visualisation Interactive** (01-Uber_Pickups-4-prod.ipynb)
   - Carte dynamique des clusters
   - Animation temporelle
   - Centres des clusters

## 📈 Résultats Principaux
- Identification des hotspots par période
- Comparaison KMeans vs DBSCAN
- Visualisation interactive des patterns temporels
- Recommandations opérationnelles

## 🔍 Méthodes de Clustering Utilisées
### DBSCAN
- Avantages : détection naturelle des outliers
- Paramètres optimisés : eps=0.05, min_samples=200

### KMeans
- 40 clusters pour l'analyse horaire
- Filtrage des clusters avec minimum 200 points

## 🎥 Visualisations
- Cartes interactives avec Plotly
- Animation temporelle des clusters
- Représentation des centres de clusters