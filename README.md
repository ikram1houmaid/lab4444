# TP Java — Lab4444

## Présentation

Ce dépôt contient des exercices pratiques en Java permettant de maîtriser les bases de la programmation orientée objet.

## Exercices réalisés

### Exercice 1 : Gestion d’un étudiant

- Création de la classe `Etudiant`.
- Gestion des identifiants auto-incrémentés avec un compteur `static`.
- Stockage des notes dans un tableau dynamique.
- Agrandissement automatique du tableau lorsque sa capacité est atteinte.
- Calcul de la moyenne des notes.
- Affichage des informations avec `toString()`.

### Exercice 2 : Gestion des points

- Création de la classe `Point`.
- Représentation des coordonnées cartésiennes `x` et `y`.
- Translation d’un point avec la méthode `translation()`.
- Calcul de la distance entre deux points avec la méthode `distance()`.
- Redéfinition de `toString()` pour afficher les coordonnées.

### Exercice 3 : Gestion des articles

- Création des classes `Categorie` et `Article`.
- Gestion des identifiants auto-incrémentés.
- Association entre un article et sa catégorie.
- Utilisation de tableaux pour stocker les catégories et les articles.
- Utilisation de boucles imbriquées pour afficher les articles par catégorie.
- Redéfinition de `toString()` pour afficher les informations des articles.

## Technologies utilisées

- Java
- JDK 8 ou version ultérieure
- Eclipse IDE

## Structure du projet

```text
lab4444/
└── src/
    ├── com/example/tp/
    │   ├── Etudiant.java
    │   └── Main.java
    └── ma/projet/
        ├── bean/
        │   ├── Article.java
        │   └── Categorie.java
        └── test/
            └── TestApp.java
```

La classe `Point` et sa classe de test peuvent également être ajoutées selon l'organisation retenue dans le projet Eclipse.

## Objectifs pédagogiques

- Comprendre les classes et les objets.
- Utiliser les constructeurs, les attributs et les méthodes.
- Appliquer l'encapsulation.
- Manipuler les tableaux et les boucles.
- Comprendre les associations entre objets.
- Utiliser les compteurs `static`.
- Redéfinir la méthode `toString()`.

## Auteur

Ikram Houmaid
