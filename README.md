# Projet Beatbox
Ce projet, développé à l'Université Toulouse III - Paul Sabatier sous la supervision de la Professeure Sandrine Mouysset, se concentre sur la détection et la reconnaissance de divers sons de beatbox à partir d'enregistrements audio. En utilisant des méthodes d'apprentissage supervisé et non supervisé, ce projet vise à classifier avec précision 12 sons de beatbox distincts.

[Notebook](https://github.com/GuileRTB/Sound-Classification-Beatbox/blob/main/ProjetBeatbox.ipynb) + [Report](https://github.com/GuilleRTB/Sound-Classification-Beatbox/blob/beatbox.pdf)

## Aperçu du Projet
En tirant parti des techniques modernes de science des données, le projet explore le potentiel de l'apprentissage automatique dans le domaine du traitement audio. Les sons de beatbox sont transformés en une forme traitable sur le plan informatique à l'aide d'une analyse cepstrale, ouvrant la voie à une classification algorithmique sophistiquée.

## Description des Données
Le jeu de données comprend des échantillons audio de 12 sons de beatbox uniques, chacun représenté au format .wav. Ces sons sont transformés en données riches en caractéristiques à l'aide des coefficients cepstraux en fréquences de Mel (MFCC) pour faciliter les processus d'apprentissage automatique.

## Techniques d'Apprentissage Automatique Utilisées
### Apprentissage Supervisé
- **Support Vector Machine (SVM)** : Ce modèle est la principale technique de classification utilisée pour ce projet, optimisée pour classifier efficacement plusieurs classes de sons de beatbox.

### Apprentissage Non Supervisé
- **K-Means Clustering** : Utilisé pour explorer les structures inhérentes aux sons de beatbox sans données pré-étiquetées. De plus, l'Analyse en Composantes Principales (ACP) est employée pour gérer la haute dimensionnalité, améliorant ainsi la maniabilité du jeu de données et la performance du modèle.

## Méthodologie

1. **Prétraitement des Données** : Conversion des fichiers audio en MFCC, réduction de la dimensionnalité si nécessaire en utilisant l'ACP.
2. **Entraînement du Modèle** : Application de SVM pour l'apprentissage supervisé et K-Means pour le clustering non supervisé.
3. **Évaluation** : Les modèles sont évalués en fonction des métriques de précision dérivées des matrices de confusion et des scores de performance.

## Résultats
Le projet a montré des résultats prometteurs dans la classification des sons de beatbox avec des comparaisons détaillées entre les performances des modèles supervisés et non supervisés, avec ou sans prétraitement.

## Auteurs

- EL AMRANI Wadie
- RATABOUIL Guilhem