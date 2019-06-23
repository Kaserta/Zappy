|Résumé||
|---:|:---|
|**Nom du projet**|Zappy|
|**Chef de groupe**|theo.desprez@epitech.eu|
|**Promo**|Tech2|

## Fiche du projet  
1. ### Description du projet  

Le but de ce projet est de créer un jeu en réseau.
Dans ce jeu, plusieurs teams devront chercher sur une carte différente ressources
afin de s'élever (gagner un niveau).
La premiere équipe dont 6 joueurs ont atteint le niveau maximum (niveau 8) gagne la partie.
  
2. ### Managment du projet
Ce projet est un projet a réalisé à 6 personnes. Des taches ont donc été assigné à chacun des différents membres du groupe.

 - Front End (Une partie graphique en JS).  
 - Back End (Serveur en C et une intelligence artificielle en Python).  
 - DevOps Processes (Gestion d'un Github ségmenté en 3 parties distinctes)  

* Theo DESPREZ (IA): theo.desprez@epitech.eu   
* Alexandre GUILMIN (IA): alexandre.guilmin@epitech.eu   
* Gregory VOLOIR (Serveur): gregory.voloir@epitech.eu   
* Audrey TRIBILLAC (Serveur): audrey.tribillac@epitech.eu   
* Theo ARMENGOU (Graphique) : theo.armengou@epitech.eu  
* Hicham TNACHERI (Serveur) : hicham.tnacheri@epitech.eu  

Configuration et gestion du GitHub:   
* Aucun push sur la branch master (utilisation de nombreuses branches).
* Code commenté (Doxygen).  

Outils utilisés:
* Git Glo
* Github
* Gitkraken
* Doxygen

## Fonctionnalité
1.  ## Les binaires 

  Pour ce projet, nous devons créer 2 binaires différents:

*  ### A. Le serveur du Zappy (Compilation : make server)  
  Le serveur générerar le monde inhabité. Le serveur prendra 6 parametres:

  -> Port (-p) : Numéro du port.  
  -> Largeur (-x) : Largeur de la carte.  
  -> Longueur (-y) : Longueur de la carte.  
  -> NameX (-n) : Nom des différentes teams sur le serveur.  
  -> ClientsNb (-c) : Nombre de joueurs autorisés par team.  
  -> Freq (-f) : Unité de temps pour l'execution de chaques actions.  
  -> Helper (-help) : Donnes des informations necessaires pour lancer le binaire.  

*  ### A. Les IAs du Zappy (Compilation : make ia)  
  Ce binaire créera les IA (les joueurs du zappy). L'IA prendra 3 parametres:
  -> Port (-p) : Numéro du port.  
  -> Name (-n) : Nom de la team a laquelle sera assigné le joueur.  
  -> Machine (-h) : Longueur de la carte.  
  -> Helper (-help) : Donnes des informations necessaires pour lancer le binaire.  
