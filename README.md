# Script d'installation des outils nécessaires
Le but de ce script est de vous faciliter la transition vers un OS différent de BLinux.
Il vous permettra notamment d'installer tous les outils nécessaires pour réussir votre première et seconde année à Epitech ainsi que différents bonus.
Ceci est une tentative de rendre le script initial universel et interactif afin qu'un maximum d'étudiants puissent en profiter pour gagner du temps à chaque changement de système d'exploitation.


Ce script fonctionne actuellement pour les OS basés sur :
- ArchLinux (Antergos & ApricityOS inclus)
- Debian (Deepin inclus)
- Korora (Toutes versions)
- Gentoo
- OpenSUSE
- Solus Project


## Utilisation :
./install "prénom.nom@epitech.eu"

Veuillez ne pas exécuter le script en SU.
Ce dernier vous demandera l'accès SuperUser lorsque nécessaire.


## Fonctionnement du script

* Mise à jour de votre système.

* Installation des paquets suivant :
    - blih
    - curl
    - filezilla
    - git
    - glibc
    - libncurses
    - make
    - ocaml
    - tree
    - valgrind
* Paquets optionnels :
    - emacs / vim (au choix)
    - makefile-gen
    - man google
    - zsh ou fish (au choix)
    - terminator

* Génère et envois votre clé ssh sur le serveur Epitech.

* Change votre shell de base en zsh ou fish en fonction de votre choix.

* Change votre Terminal de base en Terminator ou RXVT-Unicode selon votre choix.

* Installe les headers Epitech à jours (2017)


## Crédits

* montag_p - Pour avoir créé initialement le script.
* lesell_b - Pour avoir contribué au développement du script.
* cyril_l - Pour le plugin VIM Epitech que nous aimons tous.

Ce script a initialement été écrit par montag_p, pour tous remerciements veuillez le contacter par mail à paulcmdt@gmail.com
