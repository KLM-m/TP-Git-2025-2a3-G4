Structure du projet Git

Le projet contient la branche main avec toutes les modifications finales. Chaque élève a sa branche personnelle (branch/Adam-Habbadi, branch/Jakub, branch/eleve3). Une branche detached a été créée pour expérimenter un commit isolé. L’historique montre merges, conflits résolus, un revert et un reset hard.
Commande utile :

git log --oneline --graph --all

git fetch vs git pull

git fetch : récupère les changements distants sans les fusionner.

git pull : récupère et fusionne directement.
Exemple : fetch pour examiner avant de fusionner, pull pour mettre rapidement à jour sa branche.

git reset vs git revert

git reset : supprime les commits après un point précis.

git revert : crée un nouveau commit annulant un commit existant.
Risqué : reset --hard sur une branche partagée peut écraser le travail des autres.
