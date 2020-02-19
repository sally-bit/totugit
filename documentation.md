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

