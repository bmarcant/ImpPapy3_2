ImpPapy3 : importation de documents dans le logiciel Papyrus2000
================================================================

Introduction
------------

Le logiciel [Papyrus2000](http://www.papyrus2000.com) est un très bon logiciel de gestion de bibliothèque, compatible avec toutes les versions de Windows, de XP à Windows 8.

Ce logiciel est désormais disponible en téléchargement gratuit en version complète. 

Pour entrer de nouveaux documents dans Papyrus2000, il y a la possibilité d'importer un fichier au format WK1 ([Lotus 1-2-3](https://fr.wikipedia.org/wiki/Lotus_1-2-3)).

Mais, ce format n'est plus disponible dans les versions récentes d'Excel. Et LibreOffice ne le gère pas non plus.

Objet
-----

Le script `ImpPapy3` permet d'insérer des documents dans Papyrus (Titre, Auteur, Editeur, ...) à partir d'un fichier au format CSV.

Utilisation
-----------

Ce script est à insérer dans la définition des scripts dans Papyrus2000 : `Papyrus 2000 > Spécifique`.

Le fichier CSV, en entrée, est celui qui découle de l'export de Papyrus2000 : `ExpPapy3.xls`.

Version
-------

La version courante est la 1.0.

Note
----

J'ai aussi créé le script [ModPapy3](https://github.com/bmarcant/ModPapy3.git) pour modifier des documents dans Papyrus2000.

