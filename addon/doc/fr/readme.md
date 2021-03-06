# placeMarkers #

* Auteurs : Noelia, Chris.
* Télécharger [version stable][1]
* Télécharger [version de développement][2]

Ce module complémentaire sert à sauvegarder et rechercher des chaînes de
caractères ou des marqueurs spécifiques sur des pages web ou des documents
en Mode navigation de NVDA. Ce module complémentaire peut également être
utilisé pour sauvegarder et rechercher des chaînes de caractères Dans des
contrôleurs multilignes; dans ce cas, s'il n'est pas possible de mettre à
jour le point d'insertion, la chaîne correspondante sera copiée dans le
Presse-papiers, afin de pouvoir la rechercher à l'aide d'autres outils. Le
module complémentaire sauvegarde les textes et les marqueurs spécifiés dans
des fichiers. Le nom des fichiers est basé sur le titre et l'url du document
en cours.   Ce module complémentaire est basé sur les modules
complémentaires SpecificSearch et Bookmark&Search, développé par le même
auteur. Vous devriez les désinstaller pour utiliser celui-ci, car ils ont
des raccourcis et des caractéristiques communes.

## Touches de commandes : ##

*	Contrôle+maj+NVDA+f : Ouvre un dialogue avec une zone d'édition qui
  affiche la dernière recherche enregistrée; Dans ce dialogue, vous pouvez
  également sélectionner les recherches précédemment enregistrées dans une
  zone de liste déroulante ou supprimer la chaîne sélectionnée de
  l'historique à l'aide d'une case à cocher. Vous pouvez choisir si le texte
  contenu dans la zone d'édition sera ajouté à l'historique de vos textes
  enregistrés. Enfin, choisissez une action du prochain groupe de boutons
  radio (entre Recherche suivante, Recherche précédente ou Ne pas
  rechercher), et spécifiez si NVDA effectuera une recherche Respecter la
  casse. Lorsque vous appuyez sur OK, NVDA recherche cette chaîne.
*	Contrôle+maj+NVDA+k : Enregistre la position actuelle comme un
  marqueur. Si vous souhaitez donner un nom à ce marqueur, sélectionner un
  texte à partir de cette position avant de l'enregistrer.
*	Contrôle+maj+NVDA+effacement : Supprime le marqueur correspondant à cette
  position.
*	NVDA+k : Déplacer vers le marqueur suivant.
*	Maj+NVDA+k : Déplacer vers le marqueur précédent.
*	Control+maj+k : Copier le nom du fichier où les données des marqueurs de
  position seront enregistrées dans le presse-papiers, sans l'extension.
*	Alt+NVDA+k : Ouvre un dialogue avec les marqueurs sauvegardés pour ce
  document. Vous pouvez écrire une note pour chaque marqueur ; Appuyez sur
  Enregistrer note pour enregistrer les modifications. En appuyant sur OK
  vous pouvez vous déplacer à la position sélectionnée.


## Sous-menu des marqueurs (NVDA+N) ##

En utilisant le sous-menu des marqueurs, dans le menu préférences de NVDA,
vous pouvez accéder à :

*	Dossier des recherches spécifiques : Ouvre le dossier des recherches
  spécifiques précédemment sauvegardées.
*	Dossier des marqueurs : Ouvre le dossier des marqueurs sauvegardés.
*	Copier le dossier des marqueurs : Vous pouvez sauvegarder une copie du
  dossier des marqueurs.
*	Restorer des marqueurs : Vous pouvez restorer vos marqueurs à partir d'un
  dossier de marqueurs précédemment sauvegardé.

Note : la position du marqueur est basé sur le nombre de caractères. Dans
les pages au contenu dynamique, il vaut mieux utiliser la recherche de texte
spécifique pour marquer une position particulière, pas les marqueurs.


## Changements pour la version 8.0 ##
*	Identificateurs de fragment Supprimé pour les noms de fichiers  des
  marqueurs, qui peut éviter des problèmes dans le lecteur VitalSource
  Bookshelf ePUB.
*	Ajout d'un dialogue Notes, pour associer des commentaires aux marqueurs
  sauvegardés et se déplacer à la position sélectionnée.

## Changements pour la version 7.0 ##
*	Le dialogue pour enregistrer une chaîne de caractères pour la recherche
  spécifique a été supprimée. Cette fonctionnalité est maintenant incluse
  dans le dialogue Recherche spécifique, qui a été redessinée pour permettre
  différentes actions lorsque vous appuyez sur le bouton OK.
*	La présentation visuelle des dialogues a été améliorée, en respectant
  l'apparence des dialogues présentés dans NVDA.
*	L'exécution d'une commande Rechercher Suivant ou Rechercher Précédent dans
  le Mode Navigation effectuera maintenant correctement une recherche
  Respecter la casse si la recherche d'origine était Respecter la casse.
*	Nécessite NVDA 2016.4 ou ultérieur.
*	Vous pouvez maintenant assigner des gestes pour ouvrir les dialogues
  Copier et Restaurer les marqueurs de position.
*	NVDA affichera un message pour notifier lorsque les marqueurs de position
  auront été copiés ou restaurés avec les dialogues correspondants.

## Changements pour la version 6.0 ##
* Lorsque les fonctionnalités du module complémentaire ne sont pas
  utilisables, les gestes sont envoyés à l'application correspondante.

## Changements pour la version 5.0 ##
* Ajout de la recherche Respecter la casse.
* L'option d'ouverture de la documentation a été retirée du menu des
  marqueurs.
* Commandes de base plus intuitives.

## Changements pour la version 4.0 ##
* Identificateurs de fragment Supprimé pour les noms de fichiers  des
  marqueurs, qui peut éviter des problèmes dans le module ePUBREADER de
  Firefox.
* L'aide du module complémentaire est disponible à partir du Gestionnaire de
  modules complémentaires.

## Changements pour la version 3.1 ##
* Mises à jour des traduction et nouvelle langue.
* La position du marqueur n'est pas annoncé dans la lecture rapide.

## Changements pour la version 3.0 ##
* Ajout du support de la lecture rapide.

## Changements pour la version 2.0 ##
* Ajout de la possibilité de sauvegarder et supprimer des recherches
  différentes pour chaque fichier ajouté.
* Correction d'un bug avec des chemins contenant des caractères non latins.
* Les raccourcis peuvent désormais être réaffectés en utilisant le dialogue
  des raccourcis de NVDA.

## Changements pour la version 1.0 ##
* Première version
* Traduit en : Portugais Brésilien , Farsi, Finnois, Français, Galicien,
  Allemand, Italien, Japonais, Coréen, Nepali, Portugais, Espagnol,
  Slovaque, Slovène, Tamil.

[[!tag dev stable]]

[1]: http://addons.nvda-project.org/files/get.php?file=pm

[2]: http://addons.nvda-project.org/files/get.php?file=pm-dev
