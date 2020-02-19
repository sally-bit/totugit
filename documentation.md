La partie de ramsey. La commande clone : clôner les sources d'un remote github vers un ordinateur local , c'est faire une copie identique d'un repository distant. git clone "url" .

Init : initialisation d'un projet (si le projet est créé depuis github, ne pas utiliser cette commande) ou réinitialisation d'un projet existant. git init .

Add : ajoute tous les fichiers à l'index. git add "nom du dossier" .

Mv : Deplace ou renome un dossier , un repertoire ou un chemin de dossier git mv [-v] [-f] [-n] [-k] git mv [-v] [-f] [-n] [-k] ... -F --Obliger Forcer le changement de nom ou le déplacement d'un fichier même si la cible existe -k Ignorez les actions de déplacement ou de renommage qui entraîneraient une condition d'erreur. Une erreur se produit lorsqu'une source n'est ni existante ni contrôlée par Git, ou lorsqu'elle écraserait un fichier existant, sauf indication contraire -f. -n -à sec Ne fais rien; montrer seulement ce qui se passerait -v --verbeux Signalez les noms des fichiers lorsqu'ils sont déplacés .

Restore : Restaurez les chemins d'accès spécifiés dans l'arborescence de travail avec du contenu provenant d'une source de restauration. Si un chemin est suivi mais n'existe pas dans la source de restauration, il sera supprimé pour correspondre à la source. La commande peut également être utilisée pour restaurer le contenu de l'index avec --staged ou restaurer à la fois l'arborescence de travail et l'index avec --staged --worktree. Par défaut, les sources de restauration pour l'arborescence de travail et l'index sont respectivement l'index et HEAD . --source pourrait être utilisé pour spécifier un commit comme source de restauration. Cette commande est experimentale sa fonction peut changer. git resore "nom fichier"

Rm: Supprime des fichiers de l'arborescence de travail et de l'index. git rm [-f | --force] [-n] [-r] [--cached] [--ignore-unmatch] [--quiet] [-]

Sparse-checkout : Initialise et modifie la configuration de sparse-checkout, ce qui réduit la récupération à un ensemble de chemins donnés par une liste de modèles. Son comportement est expériementale et peut changer. git sparse-checkout [options]

Bisect: Utilise la recherche binaire pour trouver le commit qui a introduit un bug. git bisect .



