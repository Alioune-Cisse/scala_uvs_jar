Télécharger le dossier complet dans votre environnement local

Définissez le chemin du dossier bin dans vos variables d'environnement si vous êtes sur windows

Pour les utilisateurs d'Unix, donnez les droits d'accès en tapant la commande : $ chmod +x /path/to/bin/scolarite_project
Noter que vous remplacerez path/to par le chemin qui mène à votre dossier bin.

Ensuite vous ouvrez votre wamp server (ou xamp si vous êtes sur lunix ou mamp sur mac) ou autre plateforme permettant de traiter du mysql; 
vous allez sur phpmyadmin et créer une nouvelle base de données que vous appellez "UVS"
Ensuite, cliquez sur la base de données nouvellement crée; allez sur l'onglet importer et choisissez le fichier UVS.sql qui 
se trouve dans le dossier que vous venez de télécharger

Enfin ouvrez votre terminal et tapez scolarite_project, vous aurez un message du genre :

C:\Users\lenovo>scolarite_project
Le système ne peut trouver le fichier C:\Program Files (x86)\scolarite_project-1.0-SNAPSHOT\bin\\\..\SCOLARITE_PROJECT_config.txt.
Play server process ID is 11164
[info] play - database [default] connected at jdbc:mysql://localhost/uvs?useUnicode=yes&characterEncoding=UTF-8&connectionCollation=utf8_general_ci
[info] play - Application started (Prod)
[info] play - Listening for HTTP on /[0:0:0:0:0:0:0:0]:9000

Parfait, tout fonctionne maintenant; pour vérifier, allez dans votre navigateur préféré (google chrome par exemple) et tapez https://localhost:9000/
