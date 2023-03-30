# course-hippique

Exemple d'utilisation de HashMap et de positionnement de curseur en mode console.

# Intallation

1. Cloner le repository
1. compiler le programme : javac Main.java
1. lancer le programme : java Main

# version

Ce programme a été créé avec les versions de java suivantes

```sh
javac --version
javac 19.0.2
```

```sh
java --version

java 19.0.2 2023-01-17
Java(TM) SE Runtime Environment (build 19.0.2+7-44)
Java HotSpot(TM) 64-Bit Server VM (build 19.0.2+7-44, mixed mode, sharing)
```

# spécification

Principe : Course de chevaux  
Bob : ------------ |  
Stephan : ------------------------ |  
StBernard : ------- |

1. Créer un hashmap contenant 6 chevaux sous forme de chaine de caractère ("Bob", "Hypotipus", "Lila")
1. Chaque cheval commence avec la valeur 0
1. Chaque cheval évoluera d'une valeur de 1 à 5 unités à chaque tour de boucle, que l'on répétera tant qu'aucun cheval ne sera arrivé (100)
1. A chaque tour de boucle, afficher sur chaque ligne le nom du cheval et une barre de progression sous la forme de '--------'
1. A la fin, afficher le nom du vainqueur
