# Projet Python : prévision du salaire d'un joueur et analyse par équipe
Projet pour le 1e semestre de 2A à l'ENSAE | Adam Guiffard et Naël Farhan

Dans ce github sont répertoriées les différentes étapes de notre projet, et comporte un notebook faisant office de rapport final nomé **Rapport final**.
Le but de ce projet est le suivant : à partir de certaines variables fréquemment utilisées pour décrire l'impact d'un joueur, nous avons tenté de prédire son salaire. A partir du meilleur modèle obtenu, nous avons ensuite tenté de savoir si des équipes arrivaient à payer peu de très bon joueurs, où à l'inverse payer trop des joueurs médiocres.

## Description des fichiers présents :
- *Rapport final* : Rapport final du projet, répertoriant toutes les étapes de notre projet et présentant les résultats ainsi que les conclusions par rapport à la problématique, les limites de nos études et des pistes d'amélioration (en fichier ipynb et html)
- *web scraping to create data* : notebook permettant de scraper les données sur l'API sportsipy 
- *scraped data* : les données scrapées des saisons 2018-19 à 2020-21
- *other players indicators* : création des données avec les variables "points_per_game", "reb_per_game", "ast_per_game"
- *modified data* : données avec ajout des variables "points_per_game", "reb_per_game", "ast_per_game"
- *remove duplicates* : création des données  aléatoirement une ligne pour les joueurs transférés (voir les raisons dans le rapport final)
- *unduplicated data* : données en gardant aléatoirement une ligne pour les joueurs transférés (voir les raisons dans le rapport final)
- *descriptive statistics* : récapitulatif des statistiques descriptives utilisées dans le rapport
- *first remarks*,*salary stat desc* et *retained explanatory variables* : statistiques descriptives regroupées par domaine, permettant un affichage avec peu de cellules de code dans le rapport final
- *analysis and models* : répertoire des différents modèles étudiés avec leur score et détermination du meilleur modèle obtenu (en fichier ipynb et html)
- *model_results* : coefficients R^2 des 6 modèles étudiés dans le notebook *analysis and models*
- *reg_linear_regression* : meilleur modèle retenu, chargé en fichier pkl grâce au module pickle


