## KPPV

Application de visualisation des K-PPV

## Description

Cette application permet de manipuler et visualiser l’algorithme des k plus proches voisins (K-PPV), utilisé en classification supervisée. Elle propose une interface graphique permettant de créer des données, tester des classifications et observer les résultats.

## Fonctionnalités

- Création de points dans un espace 2D
- Attribution automatique de classes aux points
- Classification d’un point par l’algorithme K-PPV selon 2 modèles de décision : arbre ou liste
- Modification de la valeur de k
- Visualisation du voisinage et du processus de décision
- Chargement de fichiers de données (en mode création)
- Sauvegarde des données
- Réinitialisation de la zone d’affichage
- Interface

## L’application est composée de :

- Une zone principale d’affichage des points
- Un panneau de contrôle permettant :
     - de choisir le mode (création ou K-PPV)
     - de définir la valeur de k
     - d’activer certaines options d’affichage
     - de charger ou sauvegarder des données
     - de réinitialiser la fenêtre
- Utilisation :
              1/ Lancer l’application
              2/ Sélectionner le mode création
              3/ Ajouter des points dans la zone d’affichage
              OU
              3/ Importer un fichier de points
              4/ Régler la valeur de k
              5/ Passer en mode K-PPV
              6/ Ajouter un point à classifier
              7/ Observer le résultat affiché
              8/ Vous pouvez cocher différentes options :
                 - Mode arbre
                 - Voisinage (cercle)
                 - prise de décision pour choix de classe automatique
              9/ Sauvegarder le fichier (optionnel)

Les fichiers de données doivent contenir les coordonnées des points ainsi que leur classe.

## Format fichier

1re ligne :
nb_points dimension nb_classes
n lignes restantes :
classe coord_1 coord_2 ... coord_d 

## Langages et bibliothèques

Programme codé en C, avec les bibliothèques stdio.h, stdlib.h, time.h, string.h et math.h

## Auteur

Xavier THOMAS, Maël BERDIEL et Martin CLAUDE

## Licence

Ce projet est sous licence MIT.

MIT License

Copyright (c) 2026 THOMAS, BERDIEL, CLAUDE

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software...
