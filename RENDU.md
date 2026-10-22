# Rendu : RubiaPeregrina

- Dépôt : https://github.com/RubiaPeregrina/tp-git-exo
- Site GitHub Pages : https://rubiaperegrina.github.io/tp-git-exo/
## Ex2
git log --oneline :

616c2cd (HEAD -> master, origin/master) ex2: corrige une faute
c1614d4 ex2: ajoute trois lignes
e7bef9e ex2 : crée les notes et texte readme
b90c822 test 2
5e32645 ex1: initialise le dépôt


## Ex3
- config.local est-il encore dans l'historique ? Pourquoi ?
il a été suivi donc le fichier reste dans l'historique même s'il n'est  plus suivi 
## Ex4
- git status après avoir retiré brouillon.txt du staging :
On branch master
Your branch is ahead of 'origin/master' by 3 commits.
  (use "git push" to publish your local commits)

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   brouillon.txt

no changes added to commit (use "git add" and/or "git commit -a")

- Différence entre annuler une modification et retirer du staging ?
annuler une modification c'est retourner à la dernière  version commit. Retirer du staging c'est retirer le fichier pour le prochain commit

## Ex6
- À quoi servent <<<<<<<, ======= et >>>>>>> ?
à marquer un conflit entre deux versions les flèches correspondant à chaque branch et = les séparant 

## Ex7
- git stash list (avant récupération) :
-stash@{0}: WIP on master: f127475 Revert "ex7: ajoute une ligne par erreur"

- Pourquoi annuler un commit plutôt que l'effacer de l'historique ?
risque de doublons ?

## Ex8
- git pull = git fetch + quoi ?

+ git merge 

## Ex10
git log --oneline --graph --all :
```
