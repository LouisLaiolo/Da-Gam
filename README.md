# Da-Gam

Développement d'un jeu de réflexion plateforme sur le moteur Construct 2. Le projet part sur des bases déjà établies, bien que rudimentaires. L'environnement 2D comprend 3 couleurs : Noir, Blanc, Rouge. Le joueur peut être coloré en Noir ou en Blanc. 

- Un élément noir ne peut interagir qu'avec un élément de la même couleur, et réciproquement.
- Un élément rouge peut interagir avec n'importe quel objet de n'importe quel couleur.

L'environnement 2D est supposé être un petit archipel tricolore. Chaque île représente un puzzle.

Le joueur se déplace avec les touches ZSQD. Il peut utiliser la souris pour alterner ses couleurs comme bon lui semble. Le joueur peut également soulever et déplacer des objets en plaçant son curseur dessus, puis en appuyant sur E.

## Modules existants

A l'heure actuelle, le projet comprend 8 modules considérés stables :

- Mouvements du joueur
- Interactions joueurs/objets
- Changement de couleurs du joueur
- Lumiére dynamique
- Camera
- Gestion de l'objet téléporteur
- Gestion de plateformes mouvantes
- Gestion des JumpPad

Pour 3 modules en travaux, également stables :

- Gestion des jointures entre objets (en travaux - stable)
- Sons (en travaux - stable)
- Gestion de l'energie cinétique (en travaux - stable)
- Gestion de l'inversion des couleurs (en travaux - stable)

## Features à rajouter

- Implémentation d'un ou de plusieurs nouveaux puzzles
- Améliorations graphiques diverses (notamment, rajouter des backgrounds)

## Comment jouer

Récupérez le build du projet (DaGamBuild) puis lancez son index.html.

Le jeu peut normalement se lancer en local, sans upload nécéssaire. Un message d'erreur indiquera qu'il est conseillé de passer par une upload, vous pouvez l'ignorer. S'il n'est pas possible de le lancer tel quel, uploadez le build sur un serveur en ligne ou en local, via WAMP par exemple.

Les contrôles sont plutot simples : 

- Avancer : D
- Reculer : Q
- Sauter : Z
- Colorer le joueur en noir : Clic gauche
- Colorer le joueur en blanc : Clic droit
- Interargir avec un objet : Curseur sur l'objet + E

Sur chaque environnement, il faut atteindre puis activer tous les triggers (leviers) puis revenir à l'entrée.

## Prérequis

Navigateur Chrome ou Firefox conseillés. Actuellement peu compatible sur Edge ou Internet Explorer.

## Utilisés pour le Build

* [Construct 2](https://www.scirra.com/construct2) - Le moteur de jeu utilisé
* [Sprite DLight](http://www.2deegameart.com/) - Outil de création de Normal maps
* [Spriter](https://brashmonkey.com/) - Outil de création d'animations 2D

## License

Ce projet est sous licence MIT - voir le fichier [LICENSE.md](LICENSE.md) pour plus de détails.
