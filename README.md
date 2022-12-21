# ProjetPython
Projet python ENSAE "Prédiction des prix immobilier de la région Nouvelle Aquitaine par le Machine Learning", Jacques-Yves Guilbert-Ly, Ismail Jamal-Eddine, Thibault Maillet

OBJECTIFS de notre projet :

PREDIRE, par ML, à partir de la bdd DEMANDE DE VALEURS FONCIERES (https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres),
le prix au m² de toutes les parcelles de la région Nouvelle Aquitaine qui n'ont pas de prix annoncé par la DVF.

VISUALISER sur la carte de la Nouvelle Aquitaine le prix au m² de chaque département grâce à nos prédictions par ML, puis faire une carte interractive grâce à Folium parcelles par parcelles du prix au m² du département de la Gironde (pour éviter les lags) selon un gradient vert - bleu (du prix au m² le moins cher en vert à celui le plus cher en bleu).

Nous avons compressé nos différents programme sur un unique Jupyter Notebook projet_final.ipynb .

Nous avons appuyé notre réflexion sur une bibliographie composée des diverses réutilisations de la base DVF disponibles sur Data.gouv, ainsi que de l'article https://hureauxarnaud.medium.com/projet-estimateur-de-prix-dun-bien-immobilier-bas%C3%A9-sur-du-machine-learning-ae578fdacaca .
