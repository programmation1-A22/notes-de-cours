# Procédure pour publier des fichiers Mardown dans divers formats (HTML et Power Point)

## Installation et configuration des outils requis

### Télécharger et installer Python

1. Télécharger la dernière version de Python en fonction de votre système d'exploitation : https://www.python.org/downloads/
2. Installer Python en suivant la procédure d'installation 


### GitHub

GitHub est ...

1. Créer un compte ou une organisation
2. Créer un "repository" au nom username.github.io ou organisation.github.io
3. Optionnel : Créer un "repository" qui servira à stocker vos fichiers source 
4. Cloner les "repository" sur le poste de travail

### MkDocs

MkDocs est un outil permettant de générer un site Web à partir de fichiers écrits au format [MarkDown](#ressources)

1. Installer MkDock 

Ouvrir un terminal et exécuter la commande suivante (Python)[t%C3%A9l%C3%A9charger-et-installer-python] doit être installé sur le poste) : 

```pip install mkdocs```

2. Créer votre site 

Ouvrir un terminal dans le dossier qui contiendra les fichiers sources de votre site (les .md) et exécuter la commande suivante :
``` 
mkdocs new ./ 
```

Pour créer le site dans un sous-dossier, exécuter plutôt la commande suivante :
``` 
mkdocs new nomDuDossier 
``` 

Cette commande créera : 
* Un fichier mkdocs.yml. Celui-ci contiendra le plan du site 
* Un dossier docs. Celui-ci contiendra les fichiers .md dans lequel le contenu du site sera rédigé. 
* Un fichier index.md. Celui-ci se trouve dans le dossiers docs et contient un gabarit (template) de page d'accueil.

3. Rédiger le contenu. Fait un fichier .md par thématique
4. Finaliser la navivgation. Éditer le fichier mkdocs.yml pour offrir un navigation simple et efficace

## Générer le site web en HTML sur GitHub Pages

GitHub Pages est ...

1. Déployer le site dans le dossier de destination 

Dans le dossier désirez, ouvrir un terminal et exécuter la commande suivante (adapter les chemins d'accès selon vos besoins)

```
cd ../organisation.github.io/
mkdocs gh-deploy --config-file ../mes-sources/mkdocs.yml --remote-branch main
```

2. Accéder au contenu via l'url https://username.github.io ou https://organisation.github.io

## Générer un présentation PowerPoint en utilisant Pandoc

1. ...

## Mise à jour de contenu

1. Modifier le contenu
2. Mettre à jour le contenu sur GitHub
3. Générer le code HTML
4. Générer la présentation PowerPoint

À venir : Est-ce possible de générer le site automatiquement lorsque le code est déployé??

# Ressources {#ressources}

* Guide Markdown : https://www.markdownguide.org/
* MkDocs : 
* Pandoc : https://pandoc.org/ 