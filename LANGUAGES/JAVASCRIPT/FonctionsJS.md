--------------------------------- **Fonctions** -----------------------------

Une fonction est une procédure JavaScript, un ensemble d'instructions effectuant une tâche ou calculant une valeur. Pour utiliser une fonction, il est nécessaire de l'avoir auparavant définie au sein de la portée dans laquelle on souhaite l'appeler.



---------- **Déclaration de fonctions** ----------

Une déclaration de fonction ( aussi appelée définition de fonction ou instruction de fonction ) est construite avec le mot-clé **function**, suivi par :
- Le nom de la fonction;
- Une liste d'arguments à passer à la fonction, entre parenthèses et séparés par des virgules;
- Les instructions JavaScript définissant la fonction, entre accolades.



---------- **Appel de fonctions** ----------

Le fait de définir une fonction ne permet pas de l'exécuter, cela permet de lui donner un nom et de définir ce qui doit être fait lorsque la fonction est appelée.
Appeler la fonction permet donc d'effectuer les actions des instructions.
On appele une fonction avec :
- Son nom;
- Un ou des arguments entre paranthèses;
- Un point virgule, pour terminer l'appel.


---------- **Fonctions imbriquées et fermetures** ----------

Il est possible d'imbriquer une fonction dans une autre.
- La fonction imbriquée ne peut être utilisée qu'à partir des instructions de la fonction parente.
- La fonction imbriquée forme une fermeture: elle peut utiliser les arguments et les variables de la fonction parente. En revanche, la fonction parente ne peut pas utiliser les arguments et les variables de la fonction fille.