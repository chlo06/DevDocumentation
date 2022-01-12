----------------------------------------------- **JAVASCRIPT** ------------------------------------------------------

**JavaScript** ou JS, est un language de script léger, orienté objet. Il permet de créer du contenu mis à jour de façon dynamique, contrôler du contenu multimédia , d'animer des images ... Fonctionnalités grâce aux API*. D'est un language qui s'execute autant côté client que côté serveur.


--------- **Ordre d'exécution du JavaScript** ---------

Quand le navigateur rencontre un bloc de JavaScript, il l'execute généralement dans l'ordre, de haut en bas. Il faut donc faire attention à l'ordre dans lequel on écrit les choses. Par exemple penser à déclarer avant d'appeller.


--------- **Ajout du JavaScript à une page** ---------

**JavaScript Interne** Dans une balise SCRIPT, avant la balise fermante du HEAD.

**JavaScript Externe** Dans un fichier .js à part & appelé dans une balise SCRIPT src, avant la balise fermante du BODY.


--------- **ASYNC & DEFER** ---------

- Si les scripts n'ont pas besoin d'attendre l'analuse et peuvent s'executer indépendamment sans dépendances, utiliser **ASYNC**.

- Si les scripts doivent attendre l'analyse et dépendent d'autres scripts, les charger à l'aide de **DEFER** et placer leurs éléments script correspondants dans l'ordre dans lequel on souhaite que le navigateur les exécute.

Async & Defer sont à placer dans la balise Script, entre le SCRIPT et le SRC.


--------- **COMMENTAIRES** ---------

- Un commentaire sur une ligne s'écrit après un double slash.
- Un commentaire sur plusieurs lignes d'écrit entre deux balises /* et */.