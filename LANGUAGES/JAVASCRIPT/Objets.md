------------------------------------------ **Les Objets** --------------------------

Les Objets JavaScript sont écrits en JSON (Javascript Object Notation).
Ce sont des séries de paires clés-valeurs séparées par des virgules, entre des accolades. Les Objets peuvent être enregistrés dans une variable.

-------- **Déclaration d'Objet** ---------

Exemple : 
let myBook = {
    title: 'Tintin en asie',
    author:'PPDA',
    numberOfPage : 250,
    isAvailable : true
};
-------- **Les classes** ---------

Pour créer une classe dans JavaScipt, on utilise le mot clé "class", suivi par un nom et une paire d'accolades.

Exemple: 
class Book {
    constructor (title, author, pages) {
        this.title = title;
        this.author = author;
        this.pages = pages;
    }
}

**Constructor** est la fonction qui est appelée quand on crée une nouvelle instance de cette classe avec le mot clé "new".


-------- **Acces au données d'un Objet** ---------

- Notation pointée ( Dot notation) : let bookTitle = myBook.title;

- Notation bracket ( Bracket notation) : let bookTitle = myBook["title"];


-------- **Résumé** ---------

- Les objets avec les paires clé-valeurs en notation JSON. Ils permettent d'enregistrer plusieurs éléments de données associés dans une même variable.

- La notation pointée ( dot ) qui donne accès aux valeurs d'un objet et à la possibilité de les modifier.

- Les classes, et comment l'utilisation de classes peut permettre de créer des objets plus facilement et de façon plus lisible.
