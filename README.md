## Prédiction et Analyse des Conséquences des Séismes :

- Aperçu

Ce projet vise à collecter, préparer et analyser des données liées aux séismes, à leurs impacts humains et environnementaux, et à développer des modèles prédictifs pour estimer leurs conséquences. Le projet couvre une période allant de 2150 av. J.C. à 2023 et s’appuie sur des sources fiables comme Kaggle, la Banque Mondiale et ResearchGate.

Note :  Ce dépôt se concentre exclusivement sur la partie prédiction des conséquences des séismes. Les étapes liées à la collecte des données et à la création de l'entrepôt de données ne sont pas incluses ici.

## Objectifs

- Analyser les caractéristiques des séismes (fréquence, magnitude, localisation).

- Étudier les impacts sur les populations et l’environnement.

- Prédire les conséquences environnementales, matérielles et humaines à l’aide d’algorithmes de machine learning.

- Comprendre les types de failles tectoniques et leur potentiel à provoquer des séismes.

## Structure du projet

- `data/` : contient les données extraites de l'entrepôt pour chaque besion

- `algorithms/` : Code source pour le prétraitement des données, l’analyse et les modèles de machine learning.

- `img/` : Captures d’écran illustrant les résultats.

## Données

- [Kaggle: Global Sea Level | 1993 - 2021](https://www.kaggle.com/datasets/kkhandekar/global-sea-level-1993-2021)
- [Kaggle: CO2 Emissions](https://www.kaggle.com/datasets/ulrikthygepedersen/co2-emissions-by-country/data)
- [Kaggle: Temperature of All Countries (1995-2020)](https://kaggle.com/datasets/subhamjain/temperature-of-all-countries-19952020)
- [Kaggle: Dataset on Earthquakes -2150 BC -- 2023 AD around the world](hhttps://www.kaggle.com/datasets/bharathposa/earthquakes-from-2150bc-2023-ad-around-the-world)
- [ResearchGate: The Active Faults of Eurasia Database AFEAD)](https://www.researchgate.net/publication/354687605_The_Active_Faults_of_Eurasia_Database_AFEAD_v2021?channel=doi&linkId=6146fe9a3c6cb310697aa166&showFulltext=true)

- [World Bank Data : Poverty headcount ratio at $2.15 a day](https://data.worldbank.org/indicator/SI.POV.DDAY)
- [World Bank Data : Population density](https://data.worldbank.org/indicator/EN.POP.DNST)

## Préparation des données

La préparation des données a impliqué :

- Nettoyage et normalisation des données. Par exemple, les magnitudes sont définies avec différentes échelles selon la source de données.

- Fusion des sources pour obtenir une vue consolidée. Vu qu'il y a plusieurs sources de données pour les séismes, donc une fusion de ces sources était nécessaire pour éviter d'avoir des doublons.

- Construction d’un entrepôt de données facilitant les analyses.

## Modèles de Machine Learning

Différents modèles ont été implémentés pour :

- Prédire les dégâts matériels.

- Estimer les pertes humaines.

- Identifier les zones à risque à partir des failles tectoniques.

## Quelques Visualisations 

Carte des failles actives et les séismes

![Active faults and erthquakes](/img/active_faults_and_erthquakes.webp)


Nombre de morts en fonction de l'intensité du séisme


![Intensity and deaths](/img/intensity_and_deaths.webp)


Dommages en Millions de dollars en fonction de la magnitude du séisme

![Dammage and magnitude](/img/dammages_millions_dollars_and_magnitude.png)


## Membres du projet

- Axel Brunel
- Caroline Dorléans
- Thierno Amadou Diallo
- Maxime Emonnot
- Manon Lacombe
