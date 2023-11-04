---
layout: default
---
# Variables et Types de Données
####  Variables et Assignation
En Python, une variable est un conteneur qui peut stocker des données. Une variable peut contenir un littéral (une valeur immédiate comprise par le langage), une collection de littéraux (comme une liste ou un dictionnaire), une expression composée de littéraux ou d'autres variables, ou même le résultat d'une opération ou d'une fonction.
Pour créer une variable,vous devez lui donner un nom (identifiant) et lui attribuer une valeur Par exemple:
```Python
nom = "Alice"
age = 30
```
Les noms de variables doivent commencer par une lettre ou un souligné _ et ne peuvent contenir que des lettres, des chiffres et des soulignés. Python est sensible à la casse, ce qui signifie que nom et Nom sont considérés comme deux variables différentes.

Définition des Variables
La définition d'une variable se fait en utilisant le signe égal =. Voici comment vous pouvez définir des variables :
```Python
nom = "Alice"
age = 30
```
### Types de Données de Base

Python prend en charge plusieurs types de données de base, notamment :

- **int (entier)** : Utilisé pour stocker des nombres entiers. Par exemple : `age = 30`

- **float (flottant)** : Utilisé pour stocker des nombres à virgule flottante. Par exemple : `pi = 3.14`

- **str (chaîne de caractères)** : Utilisé pour stocker du texte. Par exemple : `nom = "Alice"`

- **bool (booléen)** : Utilisé pour stocker des valeurs booléennes (True ou False). Par exemple : `est_vrai = True`

#### Exemples de Types de Données

Voici comment vous pouvez définir des variables de différents types :
```python
age = 30  # Un entier
pi = 3.14  # Un flottant
nom = "Alice"  # Une chaîne de caractères
est_vrai = True  # Un booléen
```
### Opérations sur les Variables
#### Opérations Arithmétiques

Python prend en charge diverses opérations arithmétiques,
notamment l'addition (+), la soustraction (-),la multiplication (*), la division (/), la division entière (//),
le modulo (%) et l'exposant (**).

Par exemple :

```python
a = 10
b = 3

addition = a + b  # addition vaut 13
soustraction = a - b  # soustraction vaut 7
multiplication = a * b  # multiplication vaut 30
division = a / b  # division vaut 3.33333 (en tant que flottant)
division_entiere = a // b  # division_entiere vaut 3 (en tant qu'entier)
reste = a % b  # reste vaut 1
exposant = a ** b  # exposant vaut 1000
```
#### Opérations Booléennes

- **Opération `et` (and)** : Renvoie `True` si les deux conditions sont vraies. Par exemple : `a and b`.
- **Opération `ou` (or)** : Renvoie `True` si au moins l'une des conditions est vraie. Par exemple : `a or b`.
- **Opération `non` (not)** : Inverse la valeur d'une condition. Par exemple : `not a`.

### Conversion de Types

Parfois, vous devrez convertir un type de données en un autre. Python offre des fonctions de conversion pour cela. Par exemple :


```python
nombre_texte = "123"
nombre_entier = int(nombre_texte)  # Convertit la chaîne en entier
```
Il est essentiel de comprendre les types de données et les opérations arithmétiques, car ils constituent les bases de la programmation en Python.
