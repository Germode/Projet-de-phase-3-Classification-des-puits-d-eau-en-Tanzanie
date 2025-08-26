# Projet Phase 3 : Classification des puits d’eau en Tanzanie
![girl getting water](https://github.com/Germode/Projet-de-phase-3-Classification-des-puits-d-eau-en-Tanzanie/blob/main/Images/puits-d-eau-en-Tanzanie.jpg)
## Contexte
La Tanzanie, pays en développement, peine à fournir de l'eau potable à sa population de plus de 57 millions d'habitants. 
De nombreux points d'eau ont déjà été installés, mais certains nécessitent des réparations tandis que d'autres sont totalement hors service.

## Objectif
L'objectif de ce projet est de créer un **classificateur capable de prédire l'état d'un puits d'eau** (`status_group`) en utilisant des informations telles que :
- Type de pompe
- Date d’installation
- Localisation GPS
- Funder et Installer
- Qualité de l’eau et population desservie

Ce classificateur pourra être utilisé par :
- Une ONG souhaitant localiser rapidement les puits nécessitant des réparations
- Le gouvernement tanzanien pour identifier les tendances des puits non fonctionnels et optimiser la construction de nouveaux puits

## Approche ML
- Nous commencerons par une **classification ternaire** (fonctionnel / à réparer / hors service), avec la possibilité de transformer le problème en **binaire** pour simplifier la détection des puits à risque.
- Le notebook est structuré en plusieurs étapes : **EDA, nettoyage et préparation des données, modélisation ML, évaluation et insights opérationnels**.

## Impact attendu
Les résultats permettront d’orienter les décisions stratégiques pour la maintenance et la construction de nouveaux puits d’eau, optimisant ainsi l’accès à l’eau potable pour la population.
