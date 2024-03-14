# Jeu d'Othello 

## Description du projet 

Ce projet consiste à la programmation d'un jeu d'Othello (jeu sur grille) comportant une interface graphique de jeu. 
Le langage utilisé pour ce projet est le C++ et la biblliothèque d'interface graphique ... 

## Description du jeu

Le jeu d'Othello est un jeu de stratégie sur grille à deux joueurs. 
Il se joue sur un plateau de 8 sur 8, soit 64 cases appelé othellier. 
Les 64 pions on chacun une face noire et une face blanche. 

Le but du jeu est d'avoir plus de pions de sa couleur que l'adversaire à la fin de la partie. 
Le jeu s'arrête lorsque les 64 cases de l'othellier sont occupées ou qu'aucun coup n'est possible. 

La position de départ du jeu est : deux pions noirs en e4 et d5 et deux pions blancs en d4 et e5. 
C'est toujours le joueur ayant les pions noirs qui commence et les joueurs jouent à tour de rôle. 

À chaque tour de jeu, le joueur doit poser un pion de sa couleur sur une case vide de l'othellier, adjacente à un pion adverse. 
En posant son pion, il doit également encadrer un ou plusieurs pions adverses avec un pion déjà posé de sa couleur. 
Cet encadrement peut se faire horizontalement, verticalement, ou diagonalement. 
Le joueur retourne alors le ou les pions encadrés qui deviennent alors de sa couleur. 
Les pions ne sont ni retirés de l'othellier, ni déplacés. 

Table of contents 

How to install and run the project 

How to use the project 

Credits 

License
