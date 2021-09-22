# Informations

Ce cours va vous permettre de vous familiariser avec des techniques de traitement du signal appliqué à des problématiques concrêtes. Le cours `VisIndus` est  réalisé sous la forme séances théoriques, d'exercices et de travaux de laboratoires. 

Le but de ce cours est de vous faire développer **une bibliothèque d'outils en Python** pour la vision industrielle.

Lors des évaluations, vous devrez utiliser ces outils que vous avez mis au point pour résoudre de nouveaux problèmes.

Pour les exercices et les labos, un lien (google classroom) vous est envoyé par courriel, lien qui vous permet de récupérer :
- la donnée du labo, 
- les modèles pour le travail à réaliser,
- les données à utiliser,
- les résultats attendus.

## Évaluation

Pour l'évaluation, la note finale est calculée à partir des résultats de 2 labos tests notés (50% + 50%).

## Outils nécessaires

- OS X ou Windows 10 (pas la version Home Edition),
- Google Classroom (lien sur les labos), 
- GitHub Desktop (outil pour interagir avec GitHub depuis votre ordinateur),
- Docker-desktop (outil de virtualisation),
- Jupyter Lab (outil de développement en Python depuis le navigateur Web).

## Installation sous OS X

### GitHub Desktop

- téléchargez et installez l'outil GitHubDesktop depuis le site https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-github-desktop,
- créez un compte sur GitHub https://github.com/,
- envoyez l'identifiant de votre compte par email à pierre.bressy@heig-vd.ch,
- SignIn sur GitHub Desktop avec le compte créez précédemment.

### Docker-desktop

- téléchargez l'outil Docker-desktop depuis le site https://www.docker.com/products/docker-desktop,
- créez un compte (mail HEIG-VD + un mot de passe spécifique pour  ce compte),
- téléchargez le fichier,
- exécutez le fichier  que vous venez de télécharger,
- laissez les options par défaut lors de l'installation,
- démarrez Docker-desktop.

### Configuration de l'espace de travail

- acceptez l'assignement du classroom Visindus-A-L1 / 2021-2022 (lien recu par e-mail - si pas reçu, consultez le site https://classroom.github.com/classrooms/91197937-visindus-a-2021-2022),
- choisissez un répertoire pour le cours TSA : `/Users/pierre/VisIndus`,
- démarrez GitHub Desktop,
- menu File -> Clone Repository ; sélectionnez le repository "labo00-pythonbasics-[github Username]" et le repertoire de travail créé pour VisIndus. Puis cliquez sur "Clone".

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -p 8888:8888 -v /Users/pierre/VisIndus/:/home/VisIndus 314rch/visindus`

Docker-desktop va, la première fois uniquement, télécharger le container `314rch/visindus` qui contient l'environnement Jupyter Lab et les librairies Python nécessaires à ce cours.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.

### Commit & Push

- depuis Jupyter Lab, ouvrez le fichier "ex_template.ipynb",
- répondez à la première question (i=42),
- depuis GitHubDesktop, cliquez "Commit to master" pour sauver votre modification sur le local repository,
- cliquez "Push origin" pour mettre votre modification sur le remote repository.

La dernière opération de `Push` va sauvegarder sur le serveur vos dernières modifications. Vos modifications vont pouvoir ainsi être consultées par le(s) professeur(s).

## Installation sous Windows

### GitHub Desktop

- téléchargez et installez l'outil GitHubDesktop depuis le site https://docs.github.com/en/desktop/installing-and-configuring-github-desktop/installing-github-desktop,
- créez un compte sur GitHub https://github.com/,
- envoyez l'identifiant de votre compte par email à pierre.bressy@heig-vd.ch,
- SignIn sur GitHub Desktop avec le compte créez précédemment.

### Docker-desktop

- téléchargez l'outil Docker-desktop depuis le site https://www.docker.com/products/docker-desktop,
- créez un compte (mail HEIG-VD + un mot de passe spécifique pour  ce compte),
- téléchargez le fichier,
- exécutez le fichier `.exe` que vous venez de télécharger,
- laissez les options par défaut lors de l'installation,
- en fin d'installation, se déconnecter et se reconnecter,
- Docker-desktop demande à activer Hyper V ; oui puis redémarrer,
- démarrez Docker-desktop.

### Configuration de l'espace de travail


- acceptez l'assignement du classroom Visindus-A-L1 / 2021-2022 (lien recu par e-mail - si pas reçu, consultez le site https://classroom.github.com/classrooms/91197937-visindus-a-2021-2022),
- choisissez un répertoire pour le cours TSA : `D:\Documents\VisIndus`,
- démarrez GitHub Desktop,
- menu File -> Clone Repository ; sélectionnez le repository "labo00-pythonbasics-[github Username]" et le repertoire de travail créé pour TSA. Puis cliquez sur "Clone".

### Démarrage de l'environnement Jupyter Lab

Ouvrez un terminal et tapez la commande suivante :

`docker run -p 8888:8888 -v D:\Documents\VisIndus\:/home/VisIndus 314rch/visindus`

Docker-desktop va, la première fois uniquement, télécharger le container `314rch/visindus` qui contient l'environnement Jupyter Lab et les librairies Python nécessaires à ce cours.

En fin d'installation, un lien http local (http:127.0.0.1:8888/?token=....) est affiché ; ouvrez ce lien dans le navigateur.

### Commit & Push

- depuis Jupyter Lab, ouvrez le fichier "ex_template.ipynb",
- répondez à la première question (i=42),
- depuis GitHubDesktop, cliquez "Commit to master" pour sauver votre modification sur le local repository,
- cliquez "Push origin" pour mettre votre modification sur le remote repository.

La dernière opération de `Push` va sauvegarder sur le serveur vos dernières modifications. Vos modifications vont pouvoir ainsi être consultées par le(s) professeur(s).
