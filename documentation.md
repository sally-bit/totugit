
GIT DIFF: c'est une commande de git qui permet savoir non seulement quels fichiers ont changé mais aussi ce qui a changé dans ces fichiers grace aux chat de commit dqu'on a pu voir avec .Et aussi elle permet de montre les lignes exactes qui ont été ajoutées, modifiées ou effacées. syntaxe: git diff

GIT GREP: Il est très facile de trouver des fichiers avec des mots ou des phrases avec la commande git grep. syntaxe: git grep truc_a_chercher

GIT LOG Après avoir créé plusieurs validations, ou si vous avez cloné un référentiel avec un historique de validations existant, vous voudrez probablement regarder en arrière pour voir ce qui s'est passé.cette commande répertorie tous les commit effectuées dans ce référentiel dans l'ordre chronologique inverse. cette commande est faire pour ca.et pour y sortir on appuye sur la lettre q. syntaxe: git log

GIT SHOW: disont que cette commande faire un peu pret le meme travail que git log mais a la difference de git log , git show affiche plusieurs autres elements comme le nom du commit ,les parties qui ont ete modifier,les etiques et autres plus d'autres detailles Exemple: commit1 --- a/documentation.md +++ b/documentation.md @@ -0,0 +1,7 @@ +GIT DIFF: +c'est une commande de git qui permet savoir non seulement .Et aussi elle permet de montre les lignes exactePS

GIT STATUS

L'outil principal que vous utilisez pour déterminer quels fichiers sont dans quel état est la git status. Si vous exécutez cette commande directement après un clone, vous devriez voir quelque chose comme ceci:

$ git status On branch master Your branch is up-to-date with 'origin/master'. nothing to commit, working directory clean. pour faire simple git status permet de voir la status de vos fichiers. s'ils ont ete modifier ou enregistre.

GIT BRANCH


cette une commande de git qui permet de voir la liste des branches qui se trouve sur votre repository.Il suffit de faire git branch.

GIT COMMIT c'est la commande de git la plus utilise car elle permet de faire des enregistre de tous les modifications que vous avez effectue sur vos fichiers.Juste apres le git add on execute la commande

syntaxe: git commit -m "message du commit". ce message vous permet de retrouve dans vos commits si vous en faites plusieurs.

GIT MERGE

cette commande git intervient dans le cas ou voous avez cree plusieurs pour travail desus avec vos collaborateur et que vous desirez les fusionnes ,rien de plus simple avec cette commande git. syntaxe: git merge .


