# Turtle Crossing Game

## Description
Ce projet est un jeu simple de traversée de rue développé en Python avec la bibliothèque `turtle`. Le joueur contrôle une tortue qui doit traverser une route remplie de voitures en mouvement. Chaque fois que la tortue traverse la route avec succès, le niveau de difficulté augmente, et les voitures se déplacent plus rapidement. Le jeu se termine si la tortue entre en collision avec une voiture.

## Fonctionnalités
- **Joueur** : Une tortue contrôlable par l'utilisateur qui peut se déplacer vers le haut de l'écran.
- **Voitures** : Des voitures de différentes couleurs apparaissent aléatoirement et se déplacent de droite à gauche.
- **Niveaux** : Chaque fois que la tortue traverse la route avec succès, le niveau augmente, et les voitures se déplacent plus rapidement.
- **Scoreboard** : Affiche le niveau actuel et un message "GAME OVER" lorsque la tortue entre en collision avec une voiture.

## Fichiers du projet
1. **`main.py`** : Le script principal qui initialise le jeu, gère la boucle principale et détecte les collisions ou les traversées réussies.
2. **`player.py`** : Contient la classe `Player` qui représente la tortue contrôlée par le joueur.
3. **`car_manager.py`** : Contient la classe `CarManager` qui gère la création et le mouvement des voitures.
4. **`scoreboard.py`** : Contient la classe `Scoreboard` qui gère l'affichage du niveau et du message de fin de jeu.

## Comment jouer
1. **Démarrage** : Exécutez le fichier `main.py` pour lancer le jeu.
2. **Contrôles** : Utilisez la touche **"Up"** (flèche vers le haut) pour déplacer la tortue vers le haut de l'écran.
3. **Objectif** : Faites traverser la tortue à travers la route sans entrer en collision avec les voitures.
4. **Niveaux** : Chaque traversée réussie augmente le niveau, rendant les voitures plus rapides.

## Installation
1. Assurez-vous d'avoir Python installé sur votre machine.
2. Téléchargez ou clonez ce dépôt.
3. Exécutez le fichier `main.py` pour lancer le jeu.

```bash
python main.py