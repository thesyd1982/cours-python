---
layout: default
---
## Structures de Données

Les structures de données sont des moyens de stocker et d'organiser des données de manière efficace en Python. Python propose plusieurs types de structures de données, chacun adapté à des besoins spécifiques. Dans cette section, nous explorerons quelques-unes des structures de données fondamentales.

### Listes

Les listes sont l'une des structures de données les plus couramment utilisées en Python. Elles permettent de stocker une collection ordonnée d'éléments, qu'ils soient de même type ou non.

#### Création de Listes

Vous pouvez créer une liste en plaçant des éléments entre crochets `[]`, séparés par des virgules. Par exemple :

```python
ma_liste = [1, 2, 3, 4, 5]
````
##### Accès aux Éléments de la Liste
Les éléments d'une liste sont indexés, ce qui signifie que vous pouvez accéder à un élément en utilisant son index (position dans la liste). Par exemple :
```python
premier_element = ma_liste[0]  # Accède au premier élément
```
#### Tuples
Les tuples sont similaires aux listes, mais contrairement aux listes, ils sont immuables, ce qui signifie qu'ils ne peuvent pas être modifiés une fois créés. Ils sont créés en plaçant des éléments entre parenthèses (). Par exemple :
```python
mon_tuple = (1, 2, 3)# Accède au premier élément
```
#### Dictionnaires
Les dictionnaires permettent de stocker des données sous la forme de paires clé-valeur. Chaque élément d'un dictionnaire a une clé unique associée à une valeur. Les dictionnaires sont créés en utilisant des accolades {}. Par exemple :
```python
mon_dictionnaire = {"nom": "Alice", "âge": 30, "ville": "Paris"}
```
##### Accès aux Éléments du Dictionnaire
Vous pouvez accéder aux éléments d'un dictionnaire en utilisant les clés. Par exemple :
```python
nom = mon_dictionnaire["nom"]
```
#### Ensembles
Les ensembles sont des collections non ordonnées d'éléments uniques. Ils sont créés en utilisant des accolades {} ou la fonction set(). Par exemple :
```python
mon_ensemble = {1, 2, 3}
```
Les ensembles garantissent que chaque élément est unique, ce qui en fait une structure de données utile pour supprimer les doublons.

C'est ainsi que se termine la section sur les structures de données en Python. Les listes, les tuples, les dictionnaires et les ensembles sont des éléments essentiels de la programmation en Python. Ils vous permettent de stocker et de manipuler des données de manière efficace.
N'hésitez pas à ajouter des exemples et des exercices supplémentaires pour aider vos étudiants à mieux comprendre ces concepts.

