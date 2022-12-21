# ProjetPython
Projet python ENSAE Ismail Jacques-Yves Thibault

OBJECTIFS (LANGAGE NATUREL) :

PREDIRE, par ML, à partir de la bdd DEMANDE DE VALEURS FONCIERES (https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres),
ou de la bdd DVF géolocalisée (https://www.data.gouv.fr/fr/datasets/demandes-de-valeurs-foncieres-geolocalisees/),
le prix au m² de toutes les parcelles de la région Nouvelle Aquitaine (plan cadastral : https://www.data.gouv.fr/fr/datasets/cadastre/ ou seulement les adresses issues du plan https://www.data.gouv.fr/fr/datasets/adresses-extraites-du-cadastre/) qui n'ont pas de prix annoncé par la DVF.

VISUALISER sur la carte de la Nouvelle Aquitaine le prix au m² de chaque parcelle de la base de données DEMANDE DE VALEURS FONCIERES (DVF) enrichie des prix des parcelles prédits par ML.
Pour ce faire, utiliser la librairie Folium afin d'obtenir une carte interractive.
