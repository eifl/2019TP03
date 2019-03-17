# 2019TP03
Informations:
- Outils

La programmation se fera à l'aide de l'ide Arduino en C.

- Fonctionnement

La partie SETUP permet de faire les initialisations nécessaires au paramétrage.
Le code est exécuté une seule fois au démarrage et à chaque redémarrage.

La partie LOOP est l'équivalent d'un While sans condition d'arrêt.
Le code est exécuté juste après le SETUP jusqu'à la dernière ligne et recommence sans arrêt.
C'est ici que ce trouve le coeur du programme.

Tous les define, int, function, etc sont identiques au C

Le fichier contenant le code par exemple "toto.ino" doit obligatoirement se trouver dans le dossier "toto".

- Quelques instructions...
1) On peut définir des constantes etc...
2) Il faut définir l'utilisation de chaque Entrée/Sortie (E/S, Input/Output, I/O) donc soit en entrée soit en sortie.
Les E/S standardes vont de D2 à D13. D0, D1, D13 sont particulières.
3) Il faut ensuite lire ou écrire sur les E/S utilisées.
4) Les temporisations (pause) se font avec Delay(n), n en milliseconde.
5) Les 2 boutons en haut de l'IDE servent à compiler pour l'un et compiler et téléverser pour l'autre.
