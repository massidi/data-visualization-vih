# Visualisation des Données sur le VIH (Projet Académique)

Ce projet est une initiative académique menée en groupe pour explorer et visualiser les données sur le VIH/SIDA à travers divers outils et bibliothèques. Nous avons utilisé **AmCharts**, **Flourish**, et **Tableau** pour produire des visualisations interactives, publiées et intégrées dans le projet via des iframes.

---



## Table des Matières

1. [Aperçu](#aperçu)
2. [Structure du Projet](#structure-du-projet)
3. [Visualisations](#visualisations)
    - [Graphique à Barres : Personnes Vivant avec le VIH vs Recevant un Traitement](#graphique-à-barres-personnes-vivant-avec-le-vih-vs-recevant-un-traitement)
    - [Graphique en Anneau : Couverture des Traitements ARV](#graphique-en-anneau-couverture-des-traitements-arv)
    - [Carte de Chaleur : Répartition par Pays](#carte-de-chaleur-répartition-par-pays)
    - [Carte Interactive : Localisation des Cas de VIH](#carte-interactive-localisation-des-cas-de-vih)
4. [Traitement des Coordonnées Géographiques](#traitement-des-coordonnées-géographiques)
5. [Technologies Utilisées](#technologies-utilisées)
6. [Installation et Configuration](#installation-et-configuration)
7. [Sources de Données](#sources-de-données)
8. [Conclusion](#conclusion)

---

## Aperçu

Ce projet a pour objectif d'analyser l'impact du VIH/SIDA dans le monde en utilisant des outils de visualisation pour répondre aux questions suivantes :
- Quel est l'état actuel du VIH/SIDA à l'échelle mondiale ?
- Quels pays sont les plus touchés ?
- Quel est l'accès aux traitements ARV (antirétroviraux) dans différentes régions ?
- Y a-t-il des tendances positives dans la lutte contre l'épidémie ?

Ce travail a été réalisé dans le cadre d'un projet académique en groupe, en utilisant des données globales et des outils modernes de visualisation.

---

## Structure du Projet

Le projet est structuré comme suit :  
```php
dist/
├── index.html # Fichier principal pour visualisations
├── generate_geo_coordinate.ipynb  # Fichier principal pour visualisations
├── data/ # Données utilisées pour les visualisations
│ ├── *.csv # Données principales
└── README.md # Documentation du projet
```

Technologies Utilisées
* HTML5, CSS3 : Structuration et stylisation des visualisations.
* JavaScript (AmCharts) : Création de graphiques interactifs et dynamiques.
* Python (geopy) : Enrichissement des données avec les coordonnées géographiques.
* Flourish, Tableau : Génération de visualisations avancées publiées et intégrées.

## Installation et Configuration


Cloner le dépôt :

`git clone https://github.com/massidi/data-visualization-vih.git
`

`cd data-visualization-vih/dist
`

## Sources de Données
Le projet utilise cinq fichiers CSV principaux :

* people_living_with_hiv.csv : Nombre de personnes vivant avec le VIH.
* deaths_due_to_hiv.csv : Nombre de décès dus au VIH/SIDA.
* cases_among_adults.csv : Nombre de cas signalés chez les adultes (19-45 ans).
* mother_to_child_transmission.csv : Estimations de la transmission mère-enfant.
* art_coverage.csv : Couverture des traitements ARV parmi les personnes vivant avec le VIH

## Lien vers un autre site de visualization via github page et tableau :

* https://mbarry01.github.io/dashboard-dynamique/
* https://public.tableau.com/app/profile/barry.barry/viz/EvolutionduVIH2010-2018/volutionVIHDcsCartegographique2010-2019
