# Bienvenue, sur La page Shell-Tutos , Infos pratiques et plein d'autres ressources.... 

### Ce n'est pas parce que vous ne savez pas vous servire d'un marteau qu'il faut planter des clous au tournevis !!!

				############################
				#       Dr.redfish         #
				#       Developper	   #
				#       -----------        #
				#       Version : 0.1.0    #
				############################

----

# La Base

----

## vous desirez apprendre les bases du Shell et des commandes en terminal sous linux voici quelques endroits sympas a visité

[Lea-Linux](https://lea-linux.org/documentations/Shell)

**des tutoriels web en français**

[Ineumann](https://ineumann.developpez.com/tutoriels/linux/exercices-shell/)

**des tutoriels web en français**

## vous preferez la video et bien pas de soucis 

[FormationVideos](https://www.youtube.com/watch?v=py1E14pXfAM&list=PLrSOXFDHBtfHKxuz6NySItyf4iSEcTw97)
**une playlist complete sur les commandes en terminal sous linux**

[Multixvers](https://www.youtube.com/watch?v=U-KmLopaOiw)
**video Formation bash linux et terminal**

[ordirepar](https://www.youtube.com/channel/UCIHVyohXw6j2T-83-uLngEg)
**pas mal de mobile mais autres petit truc sympas**



----

# Naviguer dans les fichiers
----
### Déplacer , lister , copier , allez dans un dossier

*Pour manipuler des fichiers/dossiers plusieurs commandes sont disponibles, parfois certaine commande peuvent prendre des parametres comme "-r", "-p", parfois un chemin doit etre présicé mais nous aborderons ses sujets dans le prochain tutoriel :*

_les mot "entre quotes" sont a remplacer par la cible (fichier ou dossier) ou un chemins_

**cd "dossier"**

_vous permet de rentrer dans un répértoir_

**ls**

_vous permet de lister le contenu d'un dossier_

**cp "dossier/fichier source" "dossier/fichier cible"**

_vous permet de copier un dossier en spécifiant le dossier source et le nouveaux nom du dossier copié_

**ps x**

_Vous permet de lister les processus actif_

**mv "dossier source" "emplacement cible"**

_permet de deplacer un dossier/fichier dans un emplacement ciblé_

_Attention au chemins relatif ou absolue _
[debian-facile chemins](https://docs.python.org/fr/3.5/tutorial/appetite.html)




----

# Connaitre son materiel 

----
## Identifier sa carte graphique
*Pour connaître les caractéristiques de la ou des cartes graphiques, vous pouvez utiliser depuis un terminal les commandes suivantes, à copier-coller :*

>	lspci -vnn | grep -A 12 '\''[030[02]\]' | grep -Ei "vga|3d|display|kernel"

>	sudo lshw -enable pci -class display

>	xrandr 

----

## Connaitre les informations sur le processeur , la mémoire

>	cat /proc/cpuinfo

----

## Connaitre la distribution   

>	lsb_release  -a

----

# Savoir ce qu'il ce passe sur le reseau
>
## netstat est un tres bon outils de monitoring

	* netstat -l

*pour lister les port*
	
	* netstat -lntu

**TODO**		 


----




# Vendors. Retrouvez sur le depots suivant, des liens pour divers ressources et domaines
>	
[link-utils sur github](https://github.com/JeanSairien/link-utils)
	
**Ce dépot est mise a jours de temps en temps n'hesitez pas a aller y faire un tours régulierement et a me soumettre par email vos liens, merci**


## La page sera alimenter au fur et a mesure si vous souhaiter participer merci d'envoyer un mail a l'adresse suivant:
[redfishaw@gmail.com](redfishaw@gmail.com)
