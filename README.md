# ProjetPython
Projet python ENSAE "Prédiction des prix immobiliers de la région Nouvelle Aquitaine par le Machine Learning", Jacques-Yves Guilbert-Ly, Ismail Jamal-Eddine, Thibault Maillet

OBJECTIFS de notre projet :

PREDIRE, par ML, à partir de la bdd DEMANDE DE VALEURS FONCIERES (https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres),
le prix au m² sur la région Nouvelle Aquitaine.

VISUALISER sur la carte de la Nouvelle Aquitaine le prix au m² de chacun de ses départements grâce à nos prédictions par ML, puis faire une carte interractive avec la librairie Folium parcelles par parcelles du prix au m² du département de la Gironde (afin d'éviter les problèmes de lags) selon un gradient vert - bleu (du prix au m² le moins cher en vert à celui le plus cher en bleu).

Nous avons compressé nos différents programme sur un unique Notebook Jupyter projet_final.ipynb .

Nous avons appuyé notre réflexion sur une bibliographie composée des diverses réutilisations de la base DVF disponibles sur Data.gouv, ainsi que de l'article https://hureauxarnaud.medium.com/projet-estimateur-de-prix-dun-bien-immobilier-bas%C3%A9-sur-du-machine-learning-ae578fdacaca .
