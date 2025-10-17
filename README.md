# ML-KNN-SocialNetworkAds

## Description
Ce projet utilise le **classificateur K-Nearest Neighbors (KNN)** pour prédire si un utilisateur d'un site de réseau social achètera ou non un produit après avoir cliqué sur une publicité.  

Le dataset utilisé contient les informations suivantes sur les utilisateurs :

- **User ID** : identifiant unique (non utilisé dans le modèle)  
- **Gender** : sexe de l’utilisateur (Male/Female)  
- **Age** : âge de l’utilisateur  
- **EstimatedSalary** : salaire estimé  
- **Purchased** : variable cible (0 = non acheté, 1 = acheté)  

L'objectif est de créer un modèle ML capable de classer chaque utilisateur dans la bonne catégorie.

---

## Contenu du projet

- **Social_Network_Ads.csv** : dataset utilisé  
- **KNN_SocialNetworkAds.ipynb** : notebook contenant le code complet  
  - Importation des données  
  - Prétraitement (encodage, feature scaling)  
  - Séparation train/test  
  - Entraînement du modèle KNN  
  - Prédictions et calcul de l’accuracy  
  - Visualisation des résultats (matrice de confusion, heatmap)

---

## Résultats

- **Accuracy sans Age** : ~75%  
- **Accuracy avec Age** : ~93%  

**Interprétation** : L’âge est une feature très importante pour prédire l’achat, ce qui améliore significativement la précision du modèle.
