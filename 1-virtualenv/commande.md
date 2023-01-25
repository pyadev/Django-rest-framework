## **Environement virtuel**


### Création d'un dossier pour le projet
```
mkdir mon_projet
```

### Ouvrir le dossier dans le terminal 
```
cd mon_projet
```
### Vérifier si python est installé dans le pc 
```
python -V (pour linux python3 -V) 
output: Python 3.9.2
```
### Installer virtual env
```
pip install virtualenv (pip3 pour linux)
```
### Vérifier si virtualenv est bien  installé
```
virtualenv --version 
output: virtualenv 20.4.0
```
### Création d'un environnement virtuel nommée env 
```
virtualenv env
```
### Activation de l'environnement dans le terminal **pour linux**
```
env/bin/activate 
```
### Activation de l'environnement  dans le terminal **pour windows**
```
env\Scripts\activate
```
### Désactivation de l'environnement **linux/windows**
```
deactivate
```
### Installation de Django et django-rest-framework
```
pip install Django djangorestframework
```
### Lister les packages installés
```
pip freeze

output: asgiref==3.6.0
        Django==4.1.5
        djangorestframework==3.14.0
        pytz==2022.7.1
        sqlparse==0.4.3
```
### Enregistrement les noms des packages dans un fichier nommé requirements.txt
```
pip freeze > requirements.txt
```
### Installation des packages à partir d'un fichier 
```
pip install -r requirements.txt
```
### Désinstaller un package
```
pip uninstall djangorestframework
```
