# Analyse en Composantes Principales (PCA) - Performance Sportive

## Description du Projet
Ce notebook propose une analyse statistique avancée basée sur la **PCA (Principal Component Analysis)** pour explorer les performances des athlètes dans le dataset *Decathlon*. L'objectif est de réduire la dimensionnalité des données tout en conservant un maximum d'informations, afin de mieux comprendre les corrélations entre les différentes épreuves.

## Workflow Technique
Le notebook est structuré autour des étapes suivantes :
1. **Préparation des données** : Nettoyage et normalisation des variables.
2. **Analyse Statistique** : Application de la PCA via la bibliothèque `FactoMineR`.
3. **Interprétation** : Analyse des valeurs propres (eigenvalues) pour déterminer le nombre de dimensions nécessaires.
4. **Visualisation** : Utilisation de `factoextra` pour générer des cercles de corrélations et des projections d'individus, facilitant la lecture métier.

## Technologies Utilisées
- **Langage** : R
- **Packages principaux** : `FactoMineR`, `factoextra`, `ggplot2`

## Objectif Métier
En tant qu'analyste de données, ce type de travail permet :
- De simplifier des jeux de données complexes comportant de nombreuses variables.
- De regrouper les individus (athlètes) ayant des profils de performance similaires.
- D'extraire des insights actionnables pour le suivi de la performance sportive.

---
*Projet réalisé pour démontrer mes compétences en statistiques appliquées et en manipulation de données.*
