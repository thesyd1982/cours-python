---
layout: default
---
## Structures de Contrôle

Les structures de contrôle sont des éléments essentiels de la programmation qui permettent de gérer le flux d'exécution d'un programme. Python propose diverses structures de contrôle, notamment les instructions conditionnelles (`if`, `elif`, `else`) et les boucles (`for`, `while`). Commençons par explorer ces concepts.

### Conditions (if, elif, else)

Les instructions conditionnelles (`if`, `elif`, `else`) permettent d'exécuter différentes parties du code en fonction de conditions spécifiques.

#### L'instruction `if`

L'instruction `if` permet d'exécuter un bloc de code si une condition est vraie. Par exemple :

``` python
age = 18
if age >= 18:
    print("Vous êtes majeur.")
```
Dans cet exemple, le code sous l'instruction if sera exécuté uniquement si l'âge est supérieur ou égal à 18.

#### L'instruction elif
L'instruction elif (abréviation de "else if") permet de vérifier une condition supplémentaire si la condition précédente est fausse. Par exemple :

``` python
score = 75
if score >= 90:
    print("Excellent!")
elif score >= 70:
    print("Bien joué!")
```
Dans cet exemple, si le score est inférieur à 90 mais supérieur ou égal à 70, le message "Bien joué!" sera affiché.

#### L'instruction else
L'instruction else permet de spécifier un bloc de code à exécuter si aucune des conditions précédentes n'est vraie. Par exemple :

```python
age = 15
if age >= 18:
    print("Vous êtes majeur.")
else:
    print("Vous êtes mineur.")
```
Dans cet exemple, si l'âge est inférieur à 18, le message "Vous êtes mineur" sera affiché.

#### Boucles (for, while)
Les boucles permettent de répéter un bloc de code plusieurs fois.

Boucle for
La boucle for est utilisée pour parcourir une séquence (comme une liste) et exécuter un bloc de code pour chaque élément de la séquence. Par exemple :

```python
nombres = [1, 2, 3, 4, 5]
for nombre in nombres:
    print(nombre)
```
Cette boucle for affichera chaque nombre de la liste nombres.

Boucle while
La boucle while permet d'exécuter un bloc de code tant qu'une condition est vraie. Par exemple :

```python
compteur = 0
while compteur < 5:
    print(compteur)
    compteur += 1
```
Cette boucle while affichera les nombres de 0 à 4, puis s'arrêtera lorsque compteur atteindra 5.

#### Instructions break et continue
Python offre également les instructions break et continue pour gérer le flux d'exécution dans les boucles. L'instruction break permet de sortir d'une boucle, tandis que l'instruction continue permet de passer à l'itération suivante de la boucle.

C'est ainsi que se termine la section sur les structures de contrôle. Les instructions conditionnelles et les boucles sont fondamentales en programmation, car elles permettent de créer des programmes flexibles et réactifs. Dans la section suivante, nous aborderons les fonctions en Python.

Cette section aborde les structures de contrôle en Python, notamment les instructions conditionnelles et les boucles, et explique leur fonctionnement. Elle peut être complétée par des exemples et des exercices pour aider les étudiants à mieux comprendre ces concepts.






