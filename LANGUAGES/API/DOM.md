---------------------------------------------------------- **API DOM** --------------------------------------------------------------------


Le **Document Object Model** ou **DOM** est une interface de progammation pour les documents HTML, XML et SVG. Il fournit une autre manière de représenter, stocker et manipuler du document ( page web ). C'est une représentation entièrement orientée objet de la page Web, et peut être manipulé à l'aide d'un langage de script comme JavaScript.


-------- **DOM & JavaScript** ---------

Le DOM n'est pas un langage de programmation, mais sans lui le langage JavaScript n'aurait aucun modèle ni notion des pages Web.

Le contenu de la page est stocké dans le DOM et on peut y accéder et le manipuler via JavaScript, de la sorte qu'on pourait écrire cette équation approximative :

API ( Page web ou XML) = DOM + JS (langage de script)


-------- **Interfaces essentielles du DOM** ---------

**document.getElementById(id)** 
- La méthode getElementById() de Document renvoie un objet  Element représentant l'élément dont la propriété  id correspond à la chaîne de caractères spécifiée. Étant donné que les ID d'élément doivent être uniques, s'ils sont spécifiés, ils constituent un moyen utile d'accéder rapidement à un élément spécifique.


**document.getElementsByTagName(name)**
- La méthode Element.getElementsByTagName() retourne une liste des éléments portant le nom de balise donné. La recherche porte sur le sous-arbre de l'élément spécifié, à l'exception de cet élément lui-même. La liste retournée est live, c'est à dire qu'elle se met à jour automatiquement à chaque changement de l'arbre DOM. Par conséquent, il n'est pas nécessaire d'appeller plusieurs fois Element.getElementsByTagName() avec le même élément et les mêmes arguments.


**document.createElement(name)**
- Dans un document HTML, la méthode document.createElement() crée un élément HTML du type spécifié par tagName ou un HTMLUnknownElement si tagName n’est pas reconnu.


**parentNode.appendChild(node)**
- La méthode Node.appendChild() ajoute un nœud à la fin de la liste des enfants d'un nœud parent spécifié. Si l'enfant donné est une référence à un nœud existant dans le document, appendChild() le déplace  de sa position actuelle vers une nouvelle position (il n'est pas nécessaire de supprimer le noeud sur son noeud parent avant de l'ajouter à un autre).

Cela signifie qu'un noeud ne peut pas être à deux points du document simultanément. Donc, si le nœud a déjà un parent, le nœud est d'abord retiré, puis ajouté à la nouvelle position. 


**element.innerHTML**
- La propriété Element.innerHTML de Element récupère ou définit la syntaxe HTML décrivant les descendants de l'élément.


**element.style.left**
- Renvoie un objet représentant l'attribut style de l'élément.


**element.setAttribute()**
- Ajoute un nouvel attribut ou change la valeur d'un attribut existant pour l'élément spécifié. Si l'attribut existe déjà, la valeur est mise à jour ; sinon, un nouvel attribut est ajouté avec le nom et la valeur spécifiés.


**element.getAttribute()**
- getAttribute renvoie la valeur d'un attribut donné de l'élément spécifié. Si l'attribut n'existe pas, la valeur renvoyée sera soit null soit "" (une chaine vide).


**element.addEventListener()**
- La méthode addEventListener() de EventTarget attache une fonction à appeler chaque fois que l'évènement spécifié est envoyé à la cible.


**console.log()**
- La méthode console.log() affiche un message dans la console Web. Le message peut être une simple chaine de caractères (avec des valeurs optionnelles de substitution) ou peut être composé d'un ou plusieurs objets JavaScript.


**window.scrollTo()**
- Fait défiler le document jusqu'à un jeu de coordonnées particulier.
