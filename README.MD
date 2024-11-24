# Projet : Filtres de Convolutions et Réseaux de Neurones Convolutifs (CNN)

## Description
Ce projet explore l'utilisation des filtres de convolutions et des réseaux de neurones convolutifs (CNN) pour la classification d'images. Il inclut une étude détaillée de divers filtres de convolutions, tels que Sobel, Prewitt, Roberts, Moyenneur, Gaussien, Laplacien, LoG (Laplacian of Gaussian), Hough, Gabor, et la transformation de Fourier (FTT).

Le projet aborde également des concepts essentiels des CNN, tels que le pooling, le padding, la régularisation, le dropout et les fonctions d'activations. Enfin, une application pratique est réalisée en utilisant le dataset *5 Flower Types Classification* de Kaggle pour entraîner un modèle de classification.

## Contenu du projet
Le projet est structuré comme suit :

1. **Notebooks** :
   - *Filtres de Convolutions* : Introduction aux différents types de filtres de convolutions, avec des exemples pratiques pour chaque filtre.
   - *Réseaux de Neurones Convolutifs (CNN)* : Explication des CNN, y compris les concepts de pooling, padding, et régularisation.
   - *Classification avec CNN* : Application pratique sur le dataset *5 Flower Types Classification* de Kaggle.

2. **Concepts abordés** :
   - **Filtres de Convolutions** : 
     - Sobel
     - Prewitt
     - Roberts
     - Moyenneur
     - Gaussien
     - Laplacien
     - LoG (Laplacian of Gaussian)
     - Hough
     - Gabor
     - Transformation de Fourier (FTT)
   - **Réseaux de Neurones Convolutifs** :
     - Convolution, Pooling, Padding
     - Fonction d'activation (ReLU, Sigmoid, Tanh)
     - Dropout et régularisation pour éviter le sur-apprentissage (Overfitting)
     - Strides et architectures CNN
   - **Dataset Kaggle** : Application d'un modèle de classification sur un dataset d'images de fleurs pour prédire le type de fleur à partir d'une image.

## Installation

### Prérequis
Avant de lancer ce projet, vous devez installer les bibliothèques nécessaires. Vous pouvez installer toutes les dépendances via `pip` dans le code de ce projet.

### Télécharger le Dataset
Téléchargez le dataset *5 Flower Types Classification* depuis Kaggle : [5 Flower Types Dataset](https://www.kaggle.com/datasets/alxmamaev/flowers-recognition).

Décompressez le fichier zip et placez-le dans le répertoire `data/` du projet.

## Utilisation

1. Ouvrez le notebook `Filtres_de_Convolutions.ipynb` pour une introduction détaillée aux différents filtres de convolutions (Sobel, Prewitt, Roberts, etc.) et leur application sur des images.
2. Ensuite, explorez le notebook `CNN_Introduction.ipynb` pour une explication détaillée des réseaux de neurones convolutifs (CNN), y compris l'implémentation des couches de convolutions, pooling et dropout.
3. Enfin, ouvrez le notebook `Classification_Flowers.ipynb` pour appliquer un modèle CNN sur le dataset des fleurs, évaluer les performances du modèle et visualiser les résultats.

## Résultats
Après avoir formé le modèle sur le dataset des fleurs, vous pourrez observer les performances du modèle en termes de précision, ainsi que des visualisations des prédictions du modèle sur des images de test.

## Conclusion
Ce projet fournit une vue d'ensemble complète des concepts clés derrière les filtres de convolutions et les CNN, en offrant une application pratique sur un dataset réel. Vous apprendrez comment utiliser ces techniques pour résoudre des problèmes de classification d'images, avec des insights sur la régularisation et la sélection des hyperparamètres.

## Contributions
Les contributions sont les bienvenues ! Si vous avez des idées pour améliorer le projet ou si vous trouvez des bugs, n'hésitez pas à soumettre des *pull requests*.

## Licence
Ce projet est sous licence MIT. Voir le fichier `LICENSE` pour plus d'informations.

