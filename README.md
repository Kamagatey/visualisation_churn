# visualisation_churn
Visualisation des données de churn avec analyse de la variable 'Exited' par rapport aux autres facteurs comme l'âge, le genre, et le nombre de produits.
# Analyse des Données Clients et Fidélité Bancaire

## Objectif
L'objectif de ce projet est d'analyser les données clients afin de mieux comprendre les facteurs influençant la fidélité bancaire, et en particulier de visualiser la variable de churn (clients ayant quitté la banque). Nous avons comparé cette variable avec d'autres attributs des clients pour identifier des tendances et comportements.

## Détails du Projet
Ce projet a été réalisé en collaboration entre KAMAGATE YOUSSOUF,SORO DOBA et CROLEY AUDRET tous étudiants en Mester Data science. L'analyse s'est concentrée sur la variable cible `Exited` (binaire : 1 pour les clients ayant quitté la banque, 0 pour ceux qui sont restés) et sur l'influence de facteurs tels que :
- **Âge** (`Age`) : Influence de l'âge sur la fidélité bancaire.
- **Score de crédit** (`CreditScore`) : Impact du score de crédit sur le taux de churn.
- **Genre** (`Gender`) : Différences entre hommes et femmes en termes de fidélité.
- **Revenu estimé** (`EstimatedSalary`) : Relation entre le niveau de revenu et le churn.
- **Nombre de produits** (`NumOfProducts`) : Le nombre de produits souscrits par les clients et leur effet sur la fidélité.

## Outils et Packages Utilisés
- **R** : Pour le traitement des données et les visualisations.
- **Packages R** : 
  - `tidyverse`, `dplyr` : Pour la manipulation des données.
  - `plotly`, `ggplot2` : Pour créer des visualisations interactives et statiques.
  - `corrplot` : Pour l'analyse de corrélation entre les variables.
  - `knitr`, `kableExtra` : Pour la présentation des résultats et la création du rapport.
  
## Visualisations Produites
Nous avons généré plusieurs visualisations afin de mieux comprendre les relations entre les différentes variables et la fidélité bancaire :
- **Corrélations** : Matrice de corrélation pour évaluer la force des relations entre les variables.
- **Graphiques en barre et boxplots** : Comparaison des distributions de `Exited` par rapport à l'âge, le genre, le nombre de produits, etc.
- **Graphiques interactifs** : Utilisation de `plotly` pour explorer les données de manière plus interactive.

## Résultats
L'analyse a révélé plusieurs tendances intéressantes :
- Les clients plus âgés avaient un taux de churn moins élevé.
- Une différence notable entre les hommes et les femmes, les femmes ayant un taux de churn légèrement plus élevé.
- Les clients avec plus de produits souscrits étaient plus susceptibles de quitter la banque.

## Conclusion
Cette étude a permis de dégager plusieurs facteurs influençant la fidélité bancaire. Les résultats peuvent être utilisés pour orienter des actions de rétention et mieux comprendre les profils de clients à risque de churn.

