---
layout: default
---
## Travailler avec des Bases de Données en Python

La gestion des bases de données est un aspect crucial de la programmation, car elle permet de stocker, organiser et récupérer des données de manière structurée. Python offre des bibliothèques telles que SQLite, MySQL, PostgreSQL, et bien d'autres, pour interagir avec des bases de données. Dans cette section, nous explorerons les bases de l'utilisation des bases de données en Python.

### SQLite - Une Base de Données Légère

SQLite est une base de données légère et autonome qui ne nécessite pas de serveur de base de données distinct. Elle est souvent utilisée pour les applications de bureau, mobiles et Web nécessitant une petite base de données intégrée.

### Utilisation de SQLite en Python

Pour utiliser SQLite en Python, vous devez importer le module `sqlite3`. Voici comment vous pouvez vous connecter à une base de données SQLite et effectuer des opérations de base :

```python
import sqlite3

# Connexion à la base de données (création si elle n'existe pas)
conn = sqlite3.connect("ma_base_de_données.db")

# Création d'un curseur pour exécuter des commandes SQL
curseur = conn.cursor()

# Exécution d'une commande SQL (par exemple, création d'une table)
curseur.execute("CREATE TABLE utilisateurs (id INT, nom TEXT, email TEXT)")

# Validation des opérations et fermeture de la connexion
conn.commit()
conn.close()
```
### Interrogation de la Base de Données
Vous pouvez interroger une base de données SQLite en utilisant des commandes SQL. Voici comment vous pouvez interroger une table utilisateurs et afficher les résultats :

```python
conn = sqlite3.connect("ma_base_de_données.db")
curseur = conn.cursor()

# Exécution d'une requête SQL (par exemple, sélection de tous les utilisateurs)
curseur.execute("SELECT * FROM utilisateurs")
resultats = curseur.fetchall()

for row in resultats:
    print(row)

conn.close()
```
### Autres Bases de Données
Outre SQLite, Python offre des bibliothèques pour interagir avec d'autres systèmes de gestion de bases de données (SGBD) tels que MySQL, PostgreSQL, MongoDB, et bien d'autres. Vous devrez installer la bibliothèque spécifique pour le SGBD que vous utilisez et utiliser des connexions et des opérations spécifiques à ce SGBD.

C'est ainsi que se termine la section sur le travail avec des bases de données en Python. La gestion de bases de données est essentielle pour de nombreuses applications, de la simple gestion de données à la création de systèmes complets.

N'hésitez pas à personnaliser cette section en ajoutant des exemples spécifiques ou des exercices pour aider vos étudiants à comprendre comment travailler avec des bases de données en Python.





