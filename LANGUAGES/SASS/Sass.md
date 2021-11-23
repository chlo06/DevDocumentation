----------------------------------------------- **SASS** ------------------------------------------------------


**Sass** : Syntactically Awesome Style Sheets,
C'est un langage de script préprocesseur qui est compilé ou interprété en CSS et donc permet d'ajouter une surcouche de fonctionnalités au CSS. 
Sass introduit le principe d'encapsulation, d'inclusions, permet de créer des variables contenant des règles CSS et de les réutiliser partout dans le code et bien plus encore...


----------------------------------- **INSTALLATION** -----------------------------------


Il y a deux méthodes d'installation pour Sass:

* L'installation grâce à **Nodejs**, avec la commande -> npm install -g sass
Et npm le gestionnaire de paquets de Nodejs, va installer Sass avec toutes ses dépendances automatiquement.

* Télécherger la dernière release de Dart-Sass sur Github, et de l'ajouter au PATH pour pouvoir l'executer partout.
Il est préférable de suivre un tuto pour ça.

Une fois intallé, on peut commencer à coder dans un fichier avec l'extention **.scss**.
Et une fois le code fini, entrer la commande : **sass input.scss output.css**  
où input est le nom de notre fichier de code, et où output sera le nom du fichier de destination contenant le résultat.

Où, encore mieux on peut utiliser l'argument: **sass --watch input.scss output.css**
pour pouvoir générer le CSS à chaque modification du fichier SCSS. C'est plus rapide et ça permet de pouvoir visualiser le résultat et de débugger le code en temps réel.
