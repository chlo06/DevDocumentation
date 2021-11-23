--------------------------- **COMMANDES** ---------------------------

Git dispose notamment de commandes (qui permettent de gérer le flot de données):

* git init -> crée un nouveau dépôt;

* git clone -> clone un dépôt distant;

* git add -> ajoute de nouveaux objets **blobs** dans la base des objets pour chaque fichier modifié depuis le dernier commit.

* git commit -> intègre la somme de contrôle **SHA-1** d'un objet **tree** et les sommes de contrôle des objets **commit** parents pour créer un nouvel objet **commit**;

* git branch -> liste les branches;

* git merge -> fusionne une branche dans une autre;

* git rebase -> déplace les commits de la branche courrante devant les nouveaux commits d'une autre branche;

* git log -> affiche la liste des commits effectués sur une branche;

* git push -> publie les nouvelles révisions sur le **remote**. (La commande prend différents paramètres);

* git pull -> récupère les dernières modifications distantes du projet ( depuis le Remote ) et les fusionne dans la branche courante;

* git remote -> gestion des remotes.

ETC ...