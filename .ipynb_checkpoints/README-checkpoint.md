# Movies3
Explorer une nouvelle base de données de type cinématographique.


### Contexte du projet :
Une base de données (de type MySQL et hébergée dans le cloud AWS) contenant un certain nombre de données cinématographiques nous est fournie.

Les données de connexion sont les suivants:

user: student

host: simplon-mysql.cpreezidasug.eu-west-1.rds.amazonaws.com

port: 3306

Le mot de passe est lui précisé en session.

Afin de suivre les bonnes pratiques d'usage, les paramètres de connexion doivent être sauvegardées dans des variables d'environnement locales comme suggéré dans le document Jupyter Notebook joint.


### Prérequis : 
* Python version 3.8.2
* Git version 2.29.1.windows.1

### Étapes pour installer et lancer le projet : 


Copier le repository de travail floupics
> git clone https://github.com/phil3in/Movies3

Aller dans le repository floupics
> cd Movies3

Créer son environnement virtuel
> python3 -m venv nomDeEnv

Activer son environnement sous Windows avec GitBash
> source nomDeEnv/Scripts/activate

Installer jupyter-lab et toutes les librairies python nécessaires
> pip install -r requirements.txt

Afin d'accéder aux scripts il nous faut lancer jupyter lab : 
> jupyter lab