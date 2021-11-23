---------------- **VOCABULAIRE** ----------------

**SÉLÉCTEURS** 

Il sagit de l'élément auquel nous allons appliquer un style.
Il est suivi de crochets {} où l'on ajoutera les propriétés & les valeurs ( il est possible d'en définir plusieurs à la suite).


**PROPRIÉTÉS**

Les propriétés permettent de choisir quels aspects nous allons styliser. Par exemple la couleur, la police de caractère, la taille ...
Les propriétés se mettent entre les crochets {}.
<u>Elles ne peuvent pas être inventées.</u>


**VALEURS**

Elle indique le changement à opérer.
La valeur doit se mettre après les :. Aussi il faut un ; pour fermer la ligne et pouvoir passer à une autre propriété.



**Média Querys**

Les Média Querys ( Requêtes Média ) permettent de modifer l'apparence d'un site ou d'une application en fonction du type d'appareil utilisé.
Ce sont des régles qui indiquent quand on doit appliquer des propriétés CSS.

Il y a deux façons de les utilisés :
* En chargeant une feuille de style .css différente en fontion de la régle.
Pour cela il faut ajouter un nouveau link dans notre HTML et y ajouter l'attribut **media** et le point de rupture.

* En écrivant la régle directement dans le fichier .css habituel.
En utilisant un @ media et le point de rupture.


**Responsive Design**

C'est un terme utilisé pour décrire une approche de la conception web, ou un ensemble de bonnes pratiques utilisées pour créer une mise en page qui peut correspondre à l'appareil utilisé pour visualiser le contenu.
Ce terme décrit la combinaison de 3 techniques :
* Les grilles fluides
* Les images fluides, avec la technique de réglage de la propriété max-width à 100%. ( Les images s'adaptent à leur colonne )
* Les média Querys.