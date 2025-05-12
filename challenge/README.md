# Fix-my-code-0
Bien sûr ! Voici le contenu du fichier reformaté en Markdown pour GitHub :

```markdown
# Fix My Code Challenge

## Description

### Background Context

"Fix my code" est un nouveau type de projet où nous plongeons dans une base de code existante et la réparons !

Parfois, vous connaîtrez le langage, parfois non.

Veuillez télécharger le dépôt [Fix_My_Code_Challenge](https://github.com/holbertonschool/Fix_My_Code_Challenge) et l'utiliser comme fichiers initiaux pour toutes les solutions.

Vous ne devez pas tout recoder, juste le réparer !

Ce projet n'est **PAS** obligatoire. Il est 100% optionnel. Faire une partie de ce projet ajoutera une note de projet de plus de 100% à votre moyenne. Votre score ne sera pas affecté si vous ne le faites pas, mais si votre moyenne actuelle est supérieure à votre score sur ce projet, votre moyenne pourrait baisser. Amusez-vous bien !

## Requirements

### Général

- Éditeurs autorisés : `vi`, `vim`, `emacs`
- Tous vos fichiers seront compilés sur Ubuntu 20.04 LTS
- Tous vos fichiers doivent se terminer par une nouvelle ligne
- Un fichier `README.md` à la racine du dossier du projet est obligatoire

## Tasks

### 0. FizzBuzz

**Mandatory**

Veuillez jeter un œil à mon implémentation de FizzBuzz en Python : [source code](https://github.com/holbertonschool/Fix_My_Code_Challenge/blob/master/challenge/0-fizzbuzz.py)

Quelque chose ne va pas…

```bash
$ ./0-fizzbuzz.py 50
1 2 Fizz 4 Buzz Fizz 7 8 Fizz Buzz 11 Fizz 13 14 Fizz 16 17 Fizz 19 Buzz Fizz 22 23 Fizz Buzz 26 Fizz 28 29 Fizz 31 32 Fizz 34 Buzz Fizz 37 38 Fizz Buzz 41 Fizz 43 44 Fizz 46 47 Fizz 49 Buzz
$
```

15 devrait afficher `FizzBuzz` et non `Fizz`.

**Repo :**

- GitHub repository: [holbertonschool-Fix_My_Code_Challenge](https://github.com/holbertonschool/Fix_My_Code_Challenge)
- Directory: `challenge`
- File: `0-fizzbuzz.py`

**Score :** 0/5 pts

---

### 1. Print square

**Mandatory**

Veuillez jeter un œil à mon implémentation de l'impression d'un carré en JavaScript : [source code](https://github.com/holbertonschool/Fix_My_Code_Challenge/blob/master/challenge/1-print_square.js)

Quelque chose ne va pas…

```bash
$ ./1-print_square.js 4
####
####
####
####
$ ./1-print_square.js 10
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
################
$
```

`./1-print_square.js 10` devrait imprimer un carré de taille 10…

**Repo :**

- GitHub repository: [holbertonschool-Fix_My_Code_Challenge](https://github.com/holbertonschool/Fix_My_Code_Challenge)
- Directory: `challenge`
- File: `1-print_square.js`

**Score :** 0/20 pts

---

### 2. Sort

**Mandatory**

Veuillez trouver ici mon implémentation du tri des arguments en Ruby : [source code](https://github.com/holbertonschool/Fix_My_Code_Challenge/blob/master/challenge/2-sort.rb)

Quelque chose ne va pas…

```bash
$ ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32
31
32
12
41
2
9
-9
-1
$
```

**Repo :**

- GitHub repository: [holbertonschool-Fix_My_Code_Challenge](https://github.com/holbertonschool/Fix_My_Code_Challenge)
- Directory: `challenge`
- File: `2-sort.rb`

**Score :** 0/20 pts

---

### 3. User password

**Mandatory**

Veuillez trouver ici mon implémentation d'une classe User en Python : [source code](https://github.com/holbertonschool/Fix_My_Code_Challenge/blob/master/challenge/3-user.py)

Quelque chose ne va pas…

```bash
$ ./3-user.py 
Test User
is_valid_password should return True if it's the right password
$
```

Mes tests ne devraient pas afficher d'erreur…

**Repo :**

- GitHub repository: [holbertonschool-Fix_My_Code_Challenge](https://github.com/holbertonschool/Fix_My_Code_Challenge)
- Directory: `challenge`
- File: `3-user.py`

**Score :** 0/20 pts

---

### 4. Double linked list

**Mandatory**

Veuillez trouver ici mon implémentation d'une liste doublement chaînée en C : [source code](https://github.com/holbertonschool/Fix_My_Code_Challenge/tree/master/challenge/4-delete_dnodeint)

Quelque chose ne va pas…

```bash
$ gcc -Wall -pedantic -Werror -Wextra -std=gnu89 main.c free_dlistint.c print_dlistint.c add_dnodeint_end.c delete_dnodeint_at_index.c -o delete_dnodeint
$ ./delete_dnodeint 
0
1
2
3
4
98
402
1024
-----------------
0
1
2
3
4
0
402
1024
-----------------
1
2
3
4
0
402
1024
-----------------
2
3
4
0
402
1024
-----------------
3
4
0
402
1024
-----------------
4
0
402
1024
-----------------
0
402
1024
-----------------
402
1024
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
-----------------
$
```

Cela ne semble pas correct…

**Repo :**

- GitHub repository: [holbertonschool-Fix_My_Code_Challenge](https://github.com/holbertonschool/Fix_My_Code_Challenge)
- Directory: `challenge`
- File: `4-delete_dnodeint/`

**Score :** 0/20 pts
```

Pour réaliser et comprendre ces exercices, l'objectif est de **corriger du code existant** qui ne fonctionne pas comme prévu. Voici une explication détaillée de ce qu'il faut faire pour chaque exercice, ainsi que des conseils pour bien comprendre et résoudre les problèmes.

---

## **Objectif général**
- **Ne pas tout réécrire** : Vous devez analyser le code existant, identifier les erreurs, et les corriger sans tout refaire.
- **Comprendre le problème** : Chaque exercice a un comportement incorrect. Votre tâche est de comprendre pourquoi et de le réparer.
- **Tester vos corrections** : Après chaque correction, exécutez le code pour vérifier qu'il fonctionne comme attendu.

---

## **Exercice 0 : FizzBuzz en Python**
### **Problème**
Le programme `0-fizzbuzz.py` est censé afficher les nombres de 1 à N, en remplaçant :
- Les multiples de 3 par `Fizz`.
- Les multiples de 5 par `Buzz`.
- Les multiples de 3 et 5 par `FizzBuzz`.

Cependant, il affiche `Fizz` au lieu de `FizzBuzz` pour les multiples de 15.

### **Ce qu'il faut faire**
1. **Analyser le code** : Ouvrez le fichier `0-fizzbuzz.py` et lisez-le attentivement.
2. **Identifier l'erreur** : Le problème vient probablement de l'ordre des conditions `if`. Par exemple, si la condition pour `Fizz` est vérifiée avant celle pour `FizzBuzz`, le programme ne verra jamais `FizzBuzz`.
3. **Corriger l'erreur** : Modifiez l'ordre des conditions pour que `FizzBuzz` soit vérifié en premier.
4. **Tester** : Exécutez le script avec différentes valeurs (par exemple, `./0-fizzbuzz.py 15`) pour vérifier que `FizzBuzz` s'affiche correctement.

---

## **Exercice 1 : Print Square en JavaScript**
### **Problème**
Le programme `1-print_square.js` est censé afficher un carré de taille N x N en utilisant le caractère `#`. Cependant, il affiche un rectangle trop grand.

### **Ce qu'il faut faire**
1. **Analyser le code** : Ouvrez le fichier `1-print_square.js` et lisez-le attentivement.
2. **Identifier l'erreur** : Le problème vient probablement de la boucle qui génère les lignes ou les colonnes. Par exemple, la boucle pourrait être exécutée trop de fois.
3. **Corriger l'erreur** : Ajustez la logique de la boucle pour qu'elle génère exactement N lignes et N colonnes.
4. **Tester** : Exécutez le script avec différentes valeurs (par exemple, `./1-print_square.js 4` et `./1-print_square.js 10`) pour vérifier que le carré est correct.

---

## **Exercice 2 : Sort en Ruby**
### **Problème**
Le programme `2-sort.rb` est censé trier les arguments passés en ligne de commande. Cependant, il ne les trie pas correctement.

### **Ce qu'il faut faire**
1. **Analyser le code** : Ouvrez le fichier `2-sort.rb` et lisez-le attentivement.
2. **Identifier l'erreur** : Le problème vient probablement de la manière dont les arguments sont traités. Par exemple, les nombres pourraient être traités comme des chaînes de caractères, ce qui explique le tri incorrect.
3. **Corriger l'erreur** : Convertissez les arguments en nombres avant de les trier, ou ajustez la logique de tri pour qu'elle fonctionne correctement.
4. **Tester** : Exécutez le script avec différents arguments (par exemple, `ruby 2-sort.rb 12 41 2 C 9 -9 31 fun -1 32`) pour vérifier que le tri est correct.

---

## **Exercice 3 : User Password en Python**
### **Problème**
Le programme `3-user.py` implémente une classe `User` avec une méthode `is_valid_password`. Cependant, les tests ne fonctionnent pas comme prévu.

### **Ce qu'il faut faire**
1. **Analyser le code** : Ouvrez le fichier `3-user.py` et lisez-le attentivement.
2. **Identifier l'erreur** : Le problème vient probablement de la méthode `is_valid_password`. Par exemple, elle pourrait ne pas vérifier correctement le mot de passe.
3. **Corriger l'erreur** : Modifiez la méthode pour qu'elle retourne `True` si le mot de passe est correct, sinon `False`.
4. **Tester** : Exécutez le script et vérifiez que les tests passent sans erreur.

---

## **Exercice 4 : Double Linked List en C**
### **Problème**
Le programme `4-delete_dnodeint` implémente une liste doublement chaînée en C. Cependant, la suppression d'un nœud ne fonctionne pas correctement.

### **Ce qu'il faut faire**
1. **Analyser le code** : Ouvrez les fichiers dans le dossier `4-delete_dnodeint` et lisez-les attentivement.
2. **Identifier l'erreur** : Le problème vient probablement de la fonction `delete_dnodeint_at_index`. Par exemple, les pointeurs `prev` et `next` pourraient ne pas être correctement mis à jour lors de la suppression.
3. **Corriger l'erreur** : Modifiez la fonction pour qu'elle mette correctement à jour les pointeurs lors de la suppression d'un nœud.
4. **Tester** : Compilez et exécutez le programme pour vérifier que la suppression fonctionne correctement.

---

## **Conseils généraux**
1. **Lisez attentivement le code** : Prenez le temps de comprendre ce que le code est censé faire avant de chercher à le corriger.
2. **Utilisez des outils de débogage** :
   - En Python : Utilisez `print()` pour afficher des valeurs intermédiaires.
   - En JavaScript : Utilisez `console.log()`.
   - En Ruby : Utilisez `puts` ou `p`.
   - En C : Utilisez `printf()` pour afficher des informations de débogage.
3. **Testez souvent** : Après chaque correction, testez le code pour vérifier que le problème est résolu.
4. **Consultez la documentation** : Si vous ne connaissez pas bien le langage, consultez la documentation officielle pour comprendre les fonctions et les concepts utilisés.

---

En suivant ces étapes, vous devriez être en mesure de comprendre et de résoudre chaque exercice. Bon courage ! 🚀