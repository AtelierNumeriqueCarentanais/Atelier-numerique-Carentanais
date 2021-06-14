# La base de git

- git clone url

dossier caché .git

- gitk
    - affiche une fenetre, avec des entrées dans un arbre, les entrées sont datées, cliquer dessus pour voir ce que a été fait à chaque date

- modifier

- git status
    - ligne en rouge avec les modifications mais qui ne sont pas dans la liste de celles qui seront dans le commit

- git add fichier
    - ajoute les modifications
    - git add . 	Déconseillé, ajout de fichiers qu'on ne veut pas, fichiers cachés…

- git status
    - ligne en vert

- git commit -m "le message de description"

- gitk
    - nouvelle ligne, la modification faite

- commit en local pour le moment

- git push
    - pousse les commits sur le serveur

- modification par un tiers

- git pull -r
    - -r= --rebase	applique les changements de la machine locale à la suite du pull, commits non envoyés au serveur


git add fichier1 fichier2
ou
fichier .gitignore à la racine qui contient des regex pour les fichiers ou dossier à toujours ignorer, comme le dossier target/binary, par exemple.
