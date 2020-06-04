# Fonctionnement git et github

**GIT** est un outil qui permet de mieux gérer son code, en créant des branches etc.

**GITHUB** est un outil qui permet de stocker des donnèes sur un dépôt distant, récupérers des données, et c'est qui permet de bosser avec des personnes plus facilement.

## Quelque commande importantes

$ git clone adresseDuDepôt
> permet de clôner un dépôt github sur son ordinateur

$ git remote add origin adresseDudepôt

>permet d'ajouter un dépôt distant pour ensuite l'appeller avec le nom donné "dans ce cas là le nom par défault est origin"

$ git branch nomdelabranch

> permet de créer une nouvelle branch

$ git checkout nomdelabranch

> permet de ce déplacer vers une branche donnée.

$ git branch -d [nom-branche]

$ git branch -D [nom-branche]

>Les deux options renseignés sont assez facile à deviner :

>-d est l'abbréviation de --delete qui indique de supprimer la branche

>-D est l'abbréviation de --delete --force qui permet la suppression peut importe si elle a été mergé ou pas

$git commit -m "nom du commi"

>Permet de créer un commit (indique les modification qu'on a effectué)

$ git add fichier.extension
> permet en quelque sorte de prendre une photo d'un fichier à un instant t

$ git add -all

>permet de faire une photo de tous les fichiers.

$ git push origin master

> permet de faire un push sur son dépôt github de la branche master