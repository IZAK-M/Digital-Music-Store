# digital-music-store

Petits exercices autour de la bdd d'un disquaire en ligne ("ChinookCorp"). La base de données est au format SQLite pour plus de simplicité.  

Partie 1: Exploration de la base de données
Partie 2: Mise en oeuvre des vues sous SQLite

### Prérequis :

* Python version 3.8.5
* git version 2.30.0.windows.2

### Contexte du projet :

Une base de données (de type SQLite) contenant les données d'un commerce de musique digital vous est fournie pour exploration et mise en pratique des langages SQL et Python. L'accent est mis ici sur des requêtes à multiples jointures et la mise en oeuvre des vues.

### Contenu du dépôt Git :

* Fichier README
* Fichier requirements.txt, listant les librairies python nécessaires qui seront installées sur l'environnement virtuel
* Notebook p1-exploration.ipynb
* Notebook p2-vues-sql.ipynb
* Dossier db/, contenant la base de données utilisée

### Étapes à suivre pour installer et lancer le projet : 

Copier le dépôt de travail digital-music-store
> git clone https://github.com/IZAK-M/Digital-Music-Store.git

Créer son environnement virtuel avec Git Bash
> python3 -m venv nom_de_l'environnement

Activer son environnement sous Windows avec GitBash
> source nom_de_l'environnement/Scripts/activate

Installer jupyter-lab et toutes les librairies python nécessaires
> pip install -r requirements.txt

Aller dans le dépôt Digital-music-store
> cd digital-music-store

Afin d'accéder aux scripts il nous faut lancer jupyter lab : 
> jupyter-lab