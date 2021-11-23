----------------------------------------------- **GIT** ------------------------------------------------------

C'est un logiciel de gestion de versions décentralisé. Il utilise un système de connexion pair à pair. Le code informatique développé est stocké sur l'ordinateur de chaque contributeur du projet, mais peut également l'être sur un server dédié.

--------------------------- **FONTIONNEMENT** ---------------------------

Git possède deux structures de données : une base d'objets et un cache de répertoires. Il existe quatre types d'objets :

**L'objet blob** 
Binary Large Object
Qui représente le contenu d'un fichier.

**L'objet tree** 
Désigne une arborescence de fichiers.

**L'objet commit**
Qui correspond à une arborescence de fichiers enrichie de métadonnées.

**L'objet tag**
Qui est une manière de nommer un commit pour l'identifier plus facilement.


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