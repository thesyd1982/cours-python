---
layout: default
---
## Développement Web avec Flask

Flask est un framework web léger pour Python qui facilite le développement d'applications web. Il est flexible, simple à apprendre et offre des fonctionnalités pour la création de sites web, de services Web et bien plus encore. Dans cette section, nous explorerons les bases du développement web avec Flask.

### Installation de Flask

Pour commencer à travailler avec Flask, vous devez l'installer. Vous pouvez le faire à l'aide de `pip`, le gestionnaire de packages Python. Exécutez la commande suivante dans votre terminal :
```python
pip install flask
```

### Création d'une Application Flask

Pour créer une application web avec Flask, vous devez importer la bibliothèque et créer une instance de l'application. Voici un exemple de base :

```python
from flask import Flask

app = Flask(__name__)

@app.route('/')
def accueil():
    return 'Bienvenue sur ma première application Flask!'
```

Dans cet exemple, nous avons créé une application Flask avec une seule route ("/") qui renvoie un message de bienvenue.

### Exécution de l'Application
Pour exécuter votre application Flask, utilisez la méthode run(). Par exemple :

```python
if __name__ == '__main__':
    app.run()
```
Lorsque vous exécutez votre application, elle devrait être accessible à l'adresse http://localhost:5000/ dans votre navigateur.

### Gestion des Routes et des Vues
Flask permet de définir des routes et des vues pour gérer les URL. Vous pouvez créer des routes dynamiques, transmettre des paramètres dans les URL et personnaliser les vues pour afficher du contenu web.

### Utilisation de Modèles
Flask prend en charge l'utilisation de modèles (templates) pour générer des pages web dynamiques. Vous pouvez utiliser des moteurs de modèles comme Jinja2 pour intégrer des données dynamiques dans vos pages web.

### Création d'une API Web
Flask est également utilisé pour créer des API Web. Vous pouvez créer des routes qui renvoient des données au format JSON pour être utilisées par des applications frontales ou d'autres services.

C'est ainsi que se termine la section sur le développement web avec Flask en Python. Flask est un excellent choix pour créer des applications web légères et puissantes.

N'hésitez pas à personnaliser cette section en ajoutant des exemples spécifiques ou des exercices pour aider vos étudiants à se familiariser avec le développement web en utilisant Flask.
