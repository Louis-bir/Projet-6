# Projet : Classification automatique de biens de consommation

**Autor :** Louis BIRENHOLZ  
**Date :** 20/06/2020  
**Durée totale :** 100 heures  

## Background du projet : 

Ce projet explore une problématique de **marketplace e-commerce** voulant classer automatiquement des articles. Sur cette marketplace, des vendeurs proposent des articles à des acheteurs en postant une photo et une description.

Pour rendre l’expérience utilisateur des vendeurs **(faciliter la mise en ligne de nouveaux articles)** et des acheteurs (faciliter la recherche de produits) la plus fluide possible et dans l'optique d'un passage à l'échelle, il devient nécessaire d'automatiser cette tâche.

Ce projet est découpé en 2 grosses parties : **Partie NLP** & **Partie Computer Vision**

## Key point du projet :

- **Preprocessing & Vectorization** du corpus (création d'un Bag of Word avec NLTK
- Réduction dimensionnelle (**PCA**)
- Clustering (**Kmeans**, **Gaussian Mixture Model**) et mesure de qualité des clusters avec le **coefficient de silhouette**
- Mesure de similarité entre du Clustering via **Indice de Rand Ajusté** (ARI)
- **Preprocessing** des images et création d'un Bag of Visual Word (BOVW) via l'algorithme **ORB**
- **Partie Deep Learning :** Transfer Learning sur VGG16 (**CNN**)
- Stacking de l'approche NLP & Computer Vision et création de features puis utilisation d'une **RandomForest**


## Overview performances :

| Metrics       | Perf          |
| ------------- |:-------------:|
| Accuracy      | 0.844         |
| Precision     | 0.853         |


