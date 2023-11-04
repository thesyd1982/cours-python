---
layout: default
---

## Instructions de Contrôle de Boucle

Les boucles sont des structures de contrôle puissantes qui vous permettent de répéter un bloc de code plusieurs fois. Python propose des instructions de contrôle de boucle pour gérer le flux d'exécution à l'intérieur des boucles.

### L'instruction `break`

L'instruction `break` permet de sortir d'une boucle prématurément si une certaine condition est remplie. Par exemple, vous pouvez l'utiliser pour arrêter une boucle `while` ou `for` dès qu'une condition spécifique est satisfaite.

```python
compteur = 0
while compteur < 5:
    print(compteur)
    if compteur == 3:
        break  # Sort de la boucle lorsque compteur atteint 3
    compteur += 1
```
Dans cet exemple, la boucle while s'arrêtera lorsque compteur atteindra 3 grâce à l'instruction break.

### L'instruction continue
L'instruction continue permet de passer à l'itération suivante de la boucle, en sautant le reste du code à l'intérieur de la boucle. Elle est souvent utilisée pour éviter l'exécution de certaines instructions en fonction de conditions spécifiques.

```python
for i in range(5):
    if i == 2:
        continue  # Passe à l'itération suivante lorsque i est égal à 2
    print(i)
```
Dans cet exemple, la valeur 2 est sautée, car l'instruction continue passe à l'itération suivante sans exécuter le print(i).

### Boucles Infinies
Les boucles infinies sont des boucles qui continuent de s'exécuter indéfiniment, sauf si elles sont interrompues par une instruction break ou une autre condition de sortie. Il est essentiel de les utiliser avec prudence pour éviter de bloquer votre programme.

```python
while True:
    reponse = input("Voulez-vous continuer (o/n) ? ")
    if reponse.lower() == "n":
        break
```
Dans cet exemple, la boucle while continuera de demander si l'utilisateur veut continuer jusqu'à ce que la réponse soit "n" (grâce à l'instruction break).

C'est ainsi que se termine la section sur les instructions de contrôle de boucle. Les instructions break et continue permettent de gérer le flux d'exécution de manière plus fine à l'intérieur des boucles, tandis que les boucles infinies peuvent être utiles dans certains scénarios. Dans la prochaine section, nous explorerons les listes et les structures de données en Python.
N'hésitez pas à ajouter des exemples ou des explications supplémentaires en fonction de vos besoins.
