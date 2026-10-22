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
* 340da75 (HEAD -> master, origin/master, origin/HEAD) rendu avec le bon site pages
* 3b35bb3 (tag: rendu) ex10: complète le rendu
* 0700e90 ex9: ajoute la page d'accueil
* 02a0929 ex8: modification depuis GitHub
*   056cc84 Merge pull request #1 from RubiaPeregrina/feature-contact
|\  
| * 8db1ca4 (origin/feature-contact, feature-contact) ex8: ajoute la page contact
|/  
* 79936e8 ex7: complète le rendu
| * 7297efe (refs/stash) WIP on master: f127475 Revert "ex7: ajoute une ligne par erreur"
|/| 
| * 977c3fb index on master: f127475 Revert "ex7: ajoute une ligne par erreur"
|/  
* f127475 Revert "ex7: ajoute une ligne par erreur"
* 2b2b81c ex7: ajoute une ligne par erreur
* fdbc2ea Revert "ex7: ajoute une ligne par erreur"
* ec908e1 ex7: ajoute une ligne par erreur
*   7047b39 ex6 résout le conflit du titre
|\  
| * 68a8cfa (origin/version-en) ex6: titre en anglais
* | e53ba1f (origin/version-fr) ex6: titre en français
|/  
*   c5c1f01 ex5: fusionne feature-menu
|\  
| * 98e0b38 (origin/feature-menu) ex5: ajoute un deuxième dessert
| * 82bc3fc ex5: crée le deuxième menu
|/  
*   15784ea ex5: fusionne feature-menu
|\  
| * 0d66d8d ex5: ajoute un dessert
| * 89a28ce ex5 :crée le menu
|/  
* 8620dd3 ex4 : fin
* d6ddf0e ex4: supprime a-supprimer.txt
* 96f5e1e ex4: renomme ancien.txt
* 7aeedc7 ex4: ajoute trois fichiers
* 0ac13ef ex3 : arrête de suivre config.local
* eb53012 ex3: ajout config.local (erreur)
* 952f62c ex3: ajoute gitignore
* 616c2cd ex2: corrige une faute
* c1614d4 ex2: ajoute trois lignes
* e7bef9e ex2 : crée les notes et texte readme
* b90c822 test 2
* 5e32645 ex1: initialise le dépôt
