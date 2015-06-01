zmosdx-walkthrough
==================
This git repo is dedicated to the writing and the maintenance of the walkthrough of the game The Legend of Zelda : Mystery of Solarus DX ( http://www.zelda-solarus.com )

About the organization of the project, it's very simple :
- HTML/Solution : contains the HTML code used in Wordpress, it's the save of the articles done after the publication on the website (it's only for backup). It can not be used to render a real HTML version of the walkthrough, it will not work.
- HTML/Bestiaire : Same as previously, it's only backup for the bestiary of the website. Actually, the folder should be called "HTML Wordpress" and not just "HTML"...
- PNG : All maps and sprites of the enemies for the bestiary. It's organized by subfolder for each chapter. There is also the worldmap, and the book used for the Billy's Interview.
- XCF : All the gimp resources used for the PNG folder. Less organized than PNG, it's a subfolder by dungeon and all the remaining maps are in other. There is at least Worldmap, Bestiary and Billy for the interview.
- Root : The text version of the walkthrough only. It's based on a gamefaqs style, with ascii tables for legends, etc. They may also have important information if you work on the maps or the walkthrough, like the map convention notation (size of the dots, style, etc).
 
About localization of the guide
-------------------------------
If you want to add a new language to the guide, please use the same name as the french file, but with the code of your country before the extension. For example, LVL2.txt will become for german LVL2.de.txt or for english LVL2.en.txt. Respect the commit messages convention (title of 50 chars max, body of the message of 72 chars max by line, second line is always empty, etc).


zmosdx-soluce
=============
Ce github est dédié à la rédaction et la maintenance de la soluce écrite du jeu amateur The Legend of Zelda : Mystery of Solarus DX ( http://www.zelda-solarus.com/ )

Concernant l'arborescence du projet, elle est très simple :
- HTML/Solution : contient le code HTML reconnu par Wordpress, c'est des sauvegardes des articles qui sont fait après la publication sur le site (du pur backup donc). Il ne doit pas être utilisé pour faire un rendu html réel de la soluce, cela ne fonctionnera pas.
- HTML/Bestiaire : de la même manière, c'est là qu'il y aura le code HTML pur pour le Bestiaire du site. En fait le dossier devrait s'appeller "HTML Wordpress" et non pas juste "HTML".
- PNG : c'est dans ce dossier qu'il y a toutes les maps et les sprites des ennemis pour le bestiaire. C'est organisé en sous-dossiers correspondant à chaque chapitre, il y a aussi la map-monde et le Book présent dans l'Interview de Billy.
- XCF : toutes les sources Gimp des images du dossier PNG. Les sous-dossiers sont un peu moins bien rangés : c'est uniquement les donjons, et le reste des maps est dans others. Il y a malgré tout les dossiers de map-monde, bestiaire et Billy...
- Root : il y a la soluce en version uniquement texte. C'est du gamefaqs style pur et dur, avec du tableau en ascii pour les légendes etc. Il y a aussi les différentes informations utiles/importantes à savoir quand on travaille sur les maps ou la soluce...
