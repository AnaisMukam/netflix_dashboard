# Power BI Dashboard – Analyse du catalogue Netflix

## Description du projet

Ce projet consiste à analyser un dataset Netflix afin de visualiser et comprendre la répartition des contenus (films et séries) selon différents critères : genres, pays, durée et évolution dans le temps.

L’objectif est de construire un dashboard interactif avec Power BI permettant une exploration claire et efficace des données.

---

## Dataset

Le dataset utilisé contient les colonnes suivantes :

* title : titre du contenu
* type : Film ou Série
* country : pays de production
* listed_in : genres
* duration_value : valeur numérique de la durée
* duration_type : unité (minutes ou saisons)
* date_added : date d’ajout sur la plateforme

---

## Préparation des données (Power Query)

Les transformations suivantes ont été effectuées :

* Séparation de la colonne duration en deux colonnes :

  * duration_value
  * duration_type
* Conversion de duration_value en nombre entier
* Fractionnement de la colonne listed_in en lignes pour permettre l’analyse des genres
* Nettoyage de la colonne country (suppression des espaces et simplification)
* Création d’une colonne conditionnelle pour distinguer les films et les séries

---

## Visualisations réalisées

Le dashboard comprend les éléments suivants :

### Indicateurs clés

* Nombre total de films
* Nombre total de séries

### Graphiques

* Répartition des contenus par type (films vs séries)
* Évolution du nombre de contenus ajoutés dans le temps
* Analyse des genres les plus représentés
* Répartition des contenus par pays

---

## Carte

Une carte permet de visualiser la distribution géographique des contenus en fonction du pays de production.

---

## Personnalisation

* Mise en forme cohérente des couleurs
* Titres explicites
* Organisation claire des visuels
* Utilisation de la mise en forme conditionnelle

---

## Objectifs

* Développer des compétences en data visualisation
* Maîtriser Power BI et Power Query
* Construire un projet de portfolio

---

## Outils utilisés

* Microsoft Power BI
* Power Query

---

## Aperçu

Ajouter ici une capture d’écran du dashboard.

---

## Améliorations possibles

* Ajout de filtres interactifs
* Analyse plus fine par année
* Segmentation avancée par durée
* Amélioration de l’expérience utilisateur

---

## Auteur

Projet réalisé dans le cadre d’un apprentissage en data analysis.
