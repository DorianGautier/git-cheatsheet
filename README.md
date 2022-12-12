# git-cheatsheet

## Initiation de l'exercice

A partir de ce dépôt-ci, réalisez une cheatsheet de git. 

Dans un premier temps réalisez un fork de ce dépôt et répartissez vous ce projet pour travailler à deux ou trois. 

Le livrable final attendu :
- Avoir un sommaire
- Avoir des sections pour chaque fonctionnalité de git. Cette section doit contenir les commandes de base 
	- commit / add / log / squash / branch / checkout / revert / reset ...
- Pour chaque instruction, il est attendu d'avoir une description textuelle
- Pour chaque section il est attendu d'avoir un petit graph mermaid



Comment envoyer un fichier sur son dêpot GIT

Dans un second temps, voyons comment envoyer ses fichiers et ses répertoires sur GitHub, cette étape est a répété autant de fois que nécessaire.

Pour envoyer vos fichiers/répertoires sur GitHub il faut suivre plusieurs étapes :
```git
git status : permet de visualiser quel est l'état du repository.
```
```git
git add [fichiers ou repertoires] : permet d'indiquer que ces fichiers/répertoires doivent être ajouter au repository.
```
```git
git commit -m "Un commentaire" : permet de valider le ou les git add effectué avant.
```
```gitGraph
    commit
    commit
```
```git
git push : permet d'envoyer vos commits en attentes sur GitHub.
```

Le fichier .gitignore

Un fichier global .gitignore permet de s’assurer que Git ne valide pas certains types de fichiers, tels que des fichiers binaires compilés, dans un référentiel local. Pour cela il suffit d'ajouter le nom du fichier/dossier que vous ne voulez pas ajouter ou vous pouvez ignorer toutes les extension en mettant un point devant le nom de l'extension example .env


## Livraison de l'exercice

En fin de journée, réaliser une merge request au formateur. 
  - Attention, l'historique des commits doit être propre. 
  - Ainsi un commit par fonctionnalité présentée
  - Utilisation des branches
  - Une feature par fonctionnalité



