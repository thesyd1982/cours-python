---
layout: default
---
## Fichiers et Gestion de Fichiers

La gestion des fichiers est une partie importante de la programmation, car elle permet de lire et d'écrire des données à partir de fichiers externes. Python offre des fonctionnalités puissantes pour travailler avec des fichiers. Dans cette section, nous explorerons comment lire et écrire des fichiers en Python.

### Ouverture de Fichiers

Pour ouvrir un fichier en Python, utilisez la fonction `open()` en spécifiant le nom du fichier et le mode d'ouverture (lecture, écriture, ajout, etc.). Par exemple :

```python
fichier = open("mon_fichier.txt", "r")
```
Dans cet exemple, nous ouvrons le fichier "mon_fichier.txt" en mode lecture ("r").
### Lecture de Fichiers

Pour lire le contenu d'un fichier, vous pouvez utiliser différentes méthodes, telles que read(), readline(), ou readlines(). Par exemple :
```python
contenu = fichier.read()  # Lit tout le contenu du fichier
ligne = fichier.readline()  # Lit une ligne à la fois
lignes = fichier.readlines()  # Lit toutes les lignes dans une liste
```
### Écriture de Fichiers
Pour écrire dans un fichier, ouvrez-le en mode écriture ("w") ou ajout ("a"), puis utilisez la méthode write(). Par exemple :
```python
fichier = open("nouveau_fichier.txt", "w")
fichier.write("Ceci est un exemple de texte écrit dans un fichier.")
fichier.close()  # N'oubliez pas de fermer le fichier après écriture
```
### Gestion de Fichiers avec "with"
Python offre la gestion de fichiers sécurisée à l'aide de la construction with. Cela garantit que le fichier est correctement fermé, même en cas d'erreur. Par exemple :
```python
with open("mon_fichier.txt", "r") as fichier:
contenu = fichier.read()
# À ce stade, le fichier est automatiquement fermé
```
### Manipulation de Fichiers CSV
Les fichiers CSV (Comma-Separated Values) sont couramment utilisés pour stocker des données tabulaires. Python offre des modules tels que csv pour lire et écrire des fichiers CSV de manière efficace.

C'est ainsi que se termine la section sur les fichiers et la gestion de fichiers en Python. La capacité de travailler avec des fichiers est essentielle pour traiter des données dans de nombreux domaines de programmation.
N'hésitez pas à ajouter des exemples spécifiques ou des exercices pour aider vos étudiants à maîtriser la gestion de fichiers en Python.
