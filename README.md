1-
	YAML signifie YAML Ain't Markup Language,
	et cette technologie de format de fichier est utilisée dans les documents.
	Ces documents sont enregistrés au format texte brut et sont accompagnés 
	de l'extension .yml.
	La sérialisation efficace des données était l'objectif principal 
	des développeurs du format .yml,
	car il permet aux utilisateurs de créer des fichiers 
	.yml avec un contenu indépendant de tout langage de balisage particulier.
 
2- 

	Le fichier .gitlab-ci.yml est un fichier YAML que vous créez à la racine
	de votre projet.
	Ce fichier s'exécute automatiquement chaque fois que vous envoyez 
	un commit au serveur.
	Cela déclenche une notification au runner, 
	puis il traite la série de tâches que vous avez spécifiées.

3- 	
	GitLab Runner est une application qui fonctionne avec GitLab CI/CD 
	pour exécuter des tâches dans un pipeline 
	( specifier dans fichier yml).
4- 
	si les etapes ne sont pas deffine dans .gitlab-ci.yml il y a celle 
	qui sont par defaut : 
	- build 
	- test
	- deploy
	 
