Objectif du Projet
Le but de ce projet est de développer un modèle d'apprentissage automatique capable de classifier les tweets en fonction de leur sentiment, à savoir s'ils sont positifs ou négatifs. Nous disposons d'un jeu de données de 160 000 tweets étiquetés pour mener à bien ce projet.

Procédure
Feature Engineering

Sélection des caractéristiques pertinentes : nous allons sélectionner uniquement les colonnes cible (sentiment) et texte (tweet) du jeu de données.
Nettoyage des Données

Nettoyage des textes : nous utiliserons les méthodes de la bibliothèque NLTK pour nettoyer les tweets. Cela inclut la suppression des mots inutiles, des caractères spéciaux, des liens, et la normalisation des textes (par exemple, conversion en minuscules).
Vectorisation

Vectorisation des mots : nous utiliserons TfidfVectorizer pour transformer les tweets en une matrice de caractéristiques en termes de fréquence inverse de document.
Modélisation

Modèle de Régression Logistique : nous utiliserons une régression logistique pour entraîner notre modèle sur les données vectorisées.
Normalisation

Standardisation des données : nous appliquerons StandardScaler pour normaliser les caractéristiques afin d'améliorer la performance du modèle.
Validation Croisée

Validation croisée : nous utiliserons la validation croisée pour évaluer la performance de notre modèle et éviter le surapprentissage.