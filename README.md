# EY-Challenge

Résumé du challenge : https://challenge.ey.com/challenges/level-3-frog-counting-tool-ey/data-description
GitHub du challenge avec des informations utiles : https://github.com/EY-Data-Science-Program

Une idée pour trouver les variables prédictives est de tester plusieurs variables importantes pour l'habitat des grenouilles (élévation, humidité, etc...) venant de différents DataSets de Microsoft Planetary (par exemple NDWI = (Green – NIR)/(Green + NIR) pour JRC Global Surface Water Data, et NDVI = (Red - NIR)/(Red + NIR) pour Sentinel-2 Level-2A). Une autre métrique intéressante est le taux d'urbanisation (donc zones construites) dans la zone étudiée, à creuser !

# Idées proposées

Faire une régression linéaire à effet mixtes (https://www.tensorflow.org/probability/examples/Linear_Mixed_Effects_Models) en choississant quelles facteurs seront à effet fixe ou aléatoire.

## Liste des variables de la base de donnée TerraClimate qui ont une valeur prédictive intéressante

- aet (évapotranspiration réelle)
- soil (humidité du sol à la fin du mois)
- vap (pression de vapeur à 2m)
- vpd (déficit de pression de vapeur)
- ws (vitesse du vent à 10m)

## Choix des facteurs fixes



## Choix des facteurs aléatoires
