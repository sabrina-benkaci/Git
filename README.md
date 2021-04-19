create a new repository on the command line
git init
git commit -m "first commit
git branch -M main
git remote add origin https://github.com/ghiles-ybeggazene/add.git
git push -u origin main
git clone --branch <branchname> url
push an existing repository from the command line
git remote add origin https://github.com/ghiles-ybeggazene/add.git
git branch -M main
git push -u origin main
git en local
git init Initialize the local directory as a Git repository

git add <ficher> repertoire de travail ===> l'index

git status Liste tous les nouveaux fichiers et les fichiers modifiés à commiter

git reset [fichier] Enleve le fichier de l'index, mais conserve son contenu

git commit -m "message" l'index ===> depot git

git diff Montre les modifications de fichier qui ne sont pas encore indexées

git diff --cached comparer l'index ===> depot git local repository

git diff HEAD comparer le fichier du travail ====> depot git local repository

git diff [premiere-branche]...[deuxieme-branche] Montre les différences de contenu entre deux branches

git log Montre l'historique des versions pour la branche courante

REFAIRE DES COMMITS git en local
git reset [commit] Annule tous les commits après [commit], en conservant les modifications localement

git reset --hard [commit] Supprime tout l'historique et les modifications effectuées après le commit spécifié

git remote set-url origin new.git.url/here changer l'url remote

git en Remote
git remote add origin remote repository URL

git remote -v

git pull Pour fusionner toutes les modifications présentes sur le dépôt distant dans le répertoire de travail local

git Branch
git branch Liste toutes les branches locales dans le dépôt courant

git branch test creation de la branche test

git checkout test se positionner sur la branche test

git checkout -b test creation et positionnement sur la branche test

git merge [nom-de-branche] Combine dans la branche courante l'historique de la branche spécifiée

git branch -d the_local_branch supprimer une branche en locale

git branch -m the_local_branch on se positionne sur la branche renommer une branche en locale

git branch -rd origin/bugfix

ENREGISTRER DES FRAGMENTS
git stash Enregistre de manière temporaire tous les fichiers sous suivi de version qui ont été modifiés ("remiser son travail")

git stash pop Applique une remise et la supprime immédiatement

git stash list Liste toutes les remises

git stash drop Supprime la remise la plus récente
