# TP 2 Bash



# Exercice 1 : Variables d'environnement

 - Question 1 
	 Il trouve les commandes tapées par l'utilisateur dans la variable $PATH
	 /usr/local/bin
	 
 - Question 2 
	 C'est la variable d'environnement $HOME.
	 
 - Question 3 
	 La variable LANG détermine la langue que les logiciels utilisent pour communiquer avec l’utilisateur
	 La variable PWD affiche le chemin absolu du répertoire courant (celui dans lequel vous vous trouvez).
	 La variable OLDPWD permet de retourner au dernier répertoire visité par l'utilisateur connecté.
	 La variable SHELL contient l'interpréteur de commande préféré de l'utilisateur tel qu'il est défini dans le fichier « /etc/passwd » .
	 
 - Question 4 
	 On crée tous d'abord la variable locale avec la commande MY_VAR="12345"
	 Puis on l'affiche avec la commande echo$MY_VAR
	 
 - Question 5 
	 En tapant la commande bash nous allons lancé un nouvel interpréteur de commande, la commande MY_VAR va donc disparaître étant donné qu'elle était en locale.
	 
 - Question 6 
	 On transforme la variable MY_VAR en variable d'environnement avec la commande export MY_VAR="12345".
	 Puis lorsque nous faisons la commande bash et que nous essayons d'afficher la variable avec printenv MY_VAR, on remarque que celle-ci existe toujours. On peut en conclure que celle-ci apparaît toujours car elle a été déclaré en tant que variable d'environnement.
	 
 - Question 7
	 On crée la variable d'environnement avec la commande export NOM="Prénom Nom"
	 Puis on l'affiche avec printenv NOM.
	 
 - Question 8
	 On utilise la commande echo 'Bonjour à vous' $NOM '!'
	
 - Question 9
	La variable unset supprime définitivement la variable d'environnement alors que donner valeur vide à une variable ne la supprime pas mais la laisse juste vide.
	
 - Question 10
	Avec la commande echo '$HOME'="$HOME" cela permet d'indiquer que $HOME indique le chemin du dossier personnel
	
Voir screenshot sur l'autre document. 

