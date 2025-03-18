# Projet Automates Finis et Expressions Rationnelles

## Description

Ce projet vise à manipuler et analyser des automates finis afin de vérifier leurs propriétés et de les transformer en versions standardisées, déterministes et complètes. Il comprend également la reconnaissance de mots et la construction d’un automate complémentaire.

## Objectifs

- Lire et afficher un automate à partir d'un fichier.
- Vérifier si l'automate est déterministe, standard et complet.
- Standardiser un automate si nécessaire.
- Déterminiser et compléter un automate non déterministe.
- Construire un automate minimal équivalent.
- Tester la reconnaissance de mots.
- Générer un automate acceptant le langage complémentaire.

## Structure du Projet

### 1. Manipulation des Automates

- `automate.py` : Définition de la classe `Automate` et des méthodes pour la manipulation des automates.
- `main.py` : Interface principale permettant d'interagir avec le programme.
- `test_fonction.py` : Script de test automatisé des automates.

### 2. Dossiers de Données

- `dossier_automate/` : Contient les fichiers `.txt` des automates à traiter.
- `dossier_trace/` : Stocke les résultats des exécutions et transformations des automates.

## Fonctionnalités Implémentées

- Lecture et affichage d’un automate sous forme de table de transition.
- Vérification et transformation des automates :
  - Détection et correction des automates non standards.
  - Déterminisation et complétion des automates.
  - Minimisation d’un automate déterministe complet.
- Reconnaissance de mots par l’automate.
- Génération de l’automate complémentaire.
