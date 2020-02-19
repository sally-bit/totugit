La partie de ramsey. La commande clone : clôner les sources d'un remote github vers un ordinateur local , c'est faire une copie identique d'un repository distant. git clone "url" .


Init : initialisation d'un projet (si le projet est créé depuis github, ne pas utiliser cette commande) ou réinitialisation d'un projet existant. git init .

Add : ajoute tous les fichiers à l'index. git add "nom du dossier" .


Mv : Deplace ou renome un dossier , un repertoire ou un chemin de dossier git mv [-v] [-f] [-n] [-k] git mv [-v] [-f] [-n] [-k] ... -F --Obliger Forcer le changement de nom ou le déplacement d'un fichier même si la cible existe -k Ignorez les actions de déplacement ou de renommage qui entraîneraient une condition d'erreur. Une erreur se produit lorsqu'une source n'est ni existante ni contrôlée par Git, ou lorsqu'elle écraserait un fichier existant, sauf indication contraire -f. -n -à sec Ne fais rien; montrer seulement ce qui se passerait -v --verbeux Signalez les noms des fichiers lorsqu'ils sont déplacés .


GIT DIFF: c'est une commande de git qui permet savoir non seulement quels fichiers ont changé mais aussi ce qui a changé dans ces fichiers grace aux chat de commit dqu'on a pu voir avec .Et aussi elle permet de montre les lignes exactes qui ont été ajoutées, modifiées ou effacées. syntaxe: git diff

GIT GREP: Il est très facile de trouver des fichiers avec des mots ou des phrases avec la commande git grep. syntaxe: git grep truc_a_chercher






Restore : Restaurez les chemins d'accès spécifiés dans l'arborescence de travail avec du contenu provenant d'une source de restauration. Si un chemin est suivi mais n'existe pas dans la source de restauration, il sera supprimé pour correspondre à la source. La commande peut également être utilisée pour restaurer le contenu de l'index avec --staged ou restaurer à la fois l'arborescence de travail et l'index avec --staged --worktree. Par défaut, les sources de restauration pour l'arborescence de travail et l'index sont respectivement l'index et HEAD . --source pourrait être utilisé pour spécifier un commit comme source de restauration. Cette commande est experimentale sa fonction peut changer. git resore "nom fichier"

Rm: Supprime des fichiers de l'arborescence de travail et de l'index. git rm [-f | --force] [-n] [-r] [--cached] [--ignore-unmatch] [--quiet] [-]

Sparse-checkout : Initialise et modifie la configuration de sparse-checkout, ce qui réduit la récupération à un ensemble de chemins donnés par une liste de modèles. Son comportement est expériementale et peut changer. git sparse-checkout [options]

Bisect: Utilise la recherche binaire pour trouver le commit qui a introduit un bug. git bisect .

git rebase : la commande rebase permet modifier la description d'un commit, ainsi avec la commande rebase, vous pouvez prendre toutes les modifications qui ont été validées sur une branche et les rejouer sur une autre.

git reset :

La commande git reset est principalement utilisée pour annuler les changements apportés à l'index de staging. Un reset avec l'option --mixed déplace tout changement en attente de l'index de staging vers le répertoire de travail.

git switch :

La commande git switch est une commande expérimentale spécifique qui peut être utilisée pour remplacer dans une certaine mesure la commande git checkout.

git tag :

la commande git tgag permet d’étiqueter un certain état dans l’historique comme important.

git fetch :

La commande git fetch va récupérer toutes les données des commits effectués sur la branche courante qui n'existent pas encore dans votre version en local. Ces données seront stockées dans le répertoire de travail local mais ne seront pas fusionnées avec votre branche locale. Si vous souhaitez fusionner ces données pour que votre branche soit à jour, vous devez utiliser ensuite la commande git merge.

git pull :

La commande git pull est en fait la commande qui regroupe les commandes git fetch suivie de git merge. Cette commande télécharge les données des commits qui n'ont pas encore été récupérées dans votre branche locale puis fusionne ensuite ces données.

git push :
La commande git push est utilisée pour télécharger le contenu du référentiel local vers un référentiel distant. La transmission est la façon dont vous transférez les validations de votre référentiel local vers un référentiel distant. C'est la contrepartie de git fetch.




