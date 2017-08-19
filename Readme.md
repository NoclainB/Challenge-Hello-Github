Description des Etapes pour crée un nouveau commit.

Création d'un dossier grace à mkdir ~/Nom du fichier

On entre dans le dossier récement crée grace à cd ~/Nom du fichier

Rendre le dossier apte à recevoir des balises git : git init

Création d'un commit depuis zero :

1/Entrer la commande touch, qui signifie "crée"

2/Vérifier que le fichier crée est bien dans le dossier. Il apparait alors en untracked 
puisque ignoré par Git pour le moment.

3/Rendre le fichier visible à Git avec git add Readme.md

4/On consigne, ou commit, le fichier afin d'en faire une sauvegarde d'un instant T avec 
git commit m- "Ajout Readme.md"

5/On vas connecter le depot local au depot en ligne grace à 
" git remote add origin https://github.com/NoclainB/Challenge-Hello-Github.git " 
et vérifie qui reconnait le depot en ligne et si on peut push ou fetch avec git remote -v 

6/On téléverse notre fichier de notre depot local ---> depot en ligne 
avec la commande git push ou comme 
dans notre cas nous somme sur la branche master on tape la commande 
git push --set-upstream origin master pour push la branche master 
de mon depot.

Pour la seconde modification du Readme.md que vous lisez en ce moment même, il suffit tous simplement de modifier le fichier, puis gitt add, on commit ensuite un indiquant les modifications apportées puis on vérifie que l'on peut push grace à git remote -v et on finis pas push grace à git push.
Les modification sont désormais visible sur le site Github.