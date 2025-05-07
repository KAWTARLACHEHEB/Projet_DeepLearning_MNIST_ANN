
# 📘 Projet Deep Learning – Classification des Chiffres Manuscrits (MNIST) avec ANN

# Objectif du Projet

Ce projet a pour but de mettre en œuvre un réseau de neurones artificiels profond (Deep ANN) afin de reconnaître automatiquement les chiffres manuscrits présents dans le jeu de données MNIST. Il s'agit d'une application de l'apprentissage profond vue dans le cadre du module de Deep Learning.

# Données Utilisées

- **MNIST Dataset** :
  - 60 000 images pour l'entraînement
  - 10 000 images pour les tests
  - Chaque image représente un chiffre manuscrit entre 0 et 9 au format 28x28 pixels (niveaux de gris)

# Architecture du Modèle ANN

Le modèle est un réseau de neurones entièrement connecté (Fully Connected / Dense) avec :

- Couche d’entrée : 784 neurones (28x28 pixels)
- 1ère couche cachée : 128 neurones + ReLU
- 2ème couche cachée : 64 neurones + ReLU
- Couche de sortie : 10 neurones + Softmax

**Optimiseur** : Adam  
**Fonction de perte** : Categorical Crossentropy  
**Batch Size** : 128  
**Nombre d’époques** : 10  

# Environnement de Développement

Ce projet a été développé avec :

- ✅ **Anaconda** (distribution Python)
- ✅ **Jupyter Notebook**
- ✅ **Python 3.x**
- ✅ **TensorFlow / Keras**
- ✅ **NumPy**
- ✅ **Matplotlib**
- ✅ **Scikit-learn**

# Reproduction de l’environnement

```bash
# Créer et activer un environnement conda (facultatif mais recommandé)
conda create -n dl-mnist python=3.9
conda activate dl-mnist

# Installer les dépendances nécessaires
pip install tensorflow numpy matplotlib scikit-learn

# Lancer le notebook
jupyter notebook


## 📊 Résultats et Évaluation

- Accuracy sur les données de test : ~97%
Matrice de confusion :
  - Bonne précision sur toutes les classes (0 à 9)
  - Légers confusions pour certains chiffres proches visuellement (ex : 4/9, 5/6...)
- Visualisations :
  - Courbes de précision & perte
  - Matrice de confusion

## Métriques utilisées

- Accuracy
- Matrice de confusion
- Rapport de classification (precision, recall, F1-score)

## Instructions d’Exécution

1. Cloner le dépôt GitHub (ou télécharger le projet)
2. Ouvrir le fichier `Projet_DeepLearning_MNIST_ANN.ipynb`
3. Exécuter les cellules dans l’ordre pour :
   - Charger les données
   - Prétraiter les images
   - Construire et entraîner le modèle
   - Évaluer les performances

## Présentation Vidéo

La vidéo de présentation inclut :

- La configuration de l’environnement (Anaconda + Jupyter)
- L’explication du code et de l’architecture ANN
- Les résultats obtenus
 Lien vers la vidéo : [À insérer ici une fois prête

## 👩‍💻 Réalisé par

- Nom : Kawtar Lacheheb & Essaadia Jamafou
- Filière : Master Informatique et Télécommunications  
- Établissement: Faculté des Sciences, Université Mohammed V – Rabat  
- Année : 2024-2025
