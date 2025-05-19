# Analyse comportementale, segmentation client et prévision des ventes d'un e-commerçant

🇬🇧/🇺🇸 [Read the French version](README_fr.md)

Ce projet d’analyse de données porte sur les ventes d’un site e-commerce afin d’en extraire des insights et de prévoir les revenus futurs. L’analyse couvre la segmentation client, la performance produit, l’analyse de panier et la prévision de séries temporelles via un modèle ARIMA.

Deux notebooks sont fournis :

* `ecommerce_analysis_en.ipynb` : [version anglaise](ecommerce_analysis_en.ipynb)
* `ecommerce_analysis_fr.ipynb` : [version française](ecommerce_analysis_fr.ipynb)

---

## Données utilisées

Les données sont disponibles à l’adresse suivante :  
[https://www.kaggle.com/datasets/carrie1/ecommerce-data](https://www.kaggle.com/datasets/carrie1/ecommerce-data)

Le jeu de données regroupe des transactions de vente incluant les dates de facturation, les produits et les prix. Il concerne un e-commerçant basé au Royaume-Uni sur une période d’un an entre 2010 et 2011, vendant ses produits à l’international.

---

## Organisation de l’analyse

Le projet est structuré en quatre grandes parties :

### 1 - Analyse exploratoire des ventes
- Nettoyage des données
- Analyse des performances produits
- Analyse géographique du chiffre d'affaires
- Identification des pays à contribution croissante

### 2 - Segmentation des clients
- Préparation des données RFM
- Optimisation du nombre de clusters
- Visualisation des clusters
- Interprétation des clusters

### 3 - Analyse de panier (Market Basket Analysis)
- Identification des règles d’association à plus fort lift
- Fonction permettant de retrouver les $x$ produits les plus souvent achetés avec un antécédent donné

### 4 - Prévision des ventes (modèle ARIMA)
- Choix de la granularité temporelle
- Stationnarité de la série
- Ordres $p$ et $q$ optimaux
- Significativité des coefficients
- Analyse des résidus (Ljung-Box, Jarque-Bera, Breusch-Pagan tests)
- Prévision hebdomadaire des ventes

---

## Lancer le projet

### Prérequis

Installer les bibliothèques nécessaires via pip :

```pip install -r requirements.txt```

### Lancer le notebook

Utiliser Jupyter pour lancer le notebook :

```jupyter notebook ecommerce_analysis_fr.ipynb```
