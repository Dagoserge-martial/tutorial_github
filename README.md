# tutorial_github

![Github icon](https://www.developpez.net/forums/attachments/p358946d1/a/a/a)

## Introduction

Avez-vous récemment commencé à utiliser Git? Ou peut-être que vous l'utilisez depuis un moment, mais ses nombreux mystères sont toujours déroutants.

Git est avant tout un système de contrôle de version et un élément essentiel dans tout projet de développement logiciel. Il sert généralement à 2 objectifs principaux: la sauvegarde de code et la gestion de version de code. Vous pouvez travailler sur votre code étape par étape, en enregistrant la progression de chaque étape au cas où vous auriez besoin de revenir à une copie de sauvegarde!

Le problème commun est que Git peut être difficile à utiliser. Il y a des moments où les versions et les branches ne sont pas synchronisées et vous passez du temps à essayer de pousser votre code! Pire encore, ne pas savoir exactement comment certaines commandes fonctionnent peut facilement effacer ou écraser des bits de code!


C'est pourquoi j'ai préparé ce tutoriel, pour vous apprendre à utiliser correctement git afin que nous puissions tous passer au codage!

## Installation

### Git
Télécharger et installer git 
[ici](https://duckduckgo.com).

### Github desktop
Télécharger [ici](https://desktop.github.com/).

### Créer un compte Github

https://github.com/

### Git vs. GitHub

Je vois souvent les deux termes utilisés de manière interchangeable, mais il y a une grande différence:

- **Git** est l'outil / logiciel / programme utilisé pour garder trace de vos fichiers de projet. Il s'agit du système de «contrôle de version», où le mot «version» fait référence aux modifications ou révisions apportées à votre projet au fil du temps.
- **GitHub** , à la base, est simplement un site Web conçu pour héberger des projets suivis à l’aide de Git . Comme il ne s'agit que d'un «service d'hébergement», ce n'est pas le seul site Web qui le fait - d'autres sites Web peuvent héberger des projets Git, tels que [Bitbucket](https://bitbucket.org/) , bien que GitHub soit sans doute le plus populaire. GitHub ajoute de nombreux outils et vues de votre projet qui vont de pair avec le contrôle de version et l'aide à la collaboration avec d'autres personnes sur votre projet (plus tard dans l'article, je parlerai d'une fonctionnalité, les demandes d'extraction).

## Pourquoi utiliser Git?

En tant qu'ingénieurs en logiciel, nous ne terminons généralement pas un projet en une seule fois et nous avons généralement un plan pour structurer le travail à effectuer. Si vous travaillez sur un projet personnel pendant plusieurs jours, semaines ou plusieurs jours, il devient avantageux de garder une trace de ce que vous avez accompli un jour donné et le pouvoir de revenir en arrière, temporairement ou non, peut être modifié. Lorsque vous collaborez avec d'autres membres d'une équipe, cela devient encore plus important: **quels fichiers ont été modifiés par quels collaborateurs**? **Qu'en est-il lorsque plusieurs collaborateurs souhaitent apporter des modifications au même fichier**? Comme mentionné précédemment, la fonction principale de Git est le «contrôle de version» - l'organisation et le suivi des modifications apportées à un projet au fil du temps, que ce soit uniquement vous-même ou une équipe qui y travaille.


## Ok, On peut commencer

### Utiliser git en ligne de commande

- Ouvrir votre dossier dans l'invite de commande et executer la commande suivante

```bash
git init
```
![](/capture/gitinit.png)

- Nous verrons un exemple complet lors de la formation mais avant je vous presente quelque commande qui seront mieux expliqué au cours de la formation

## Référence de commande

- ```bash  git init ``` - initialise le répertoire actuel en tant que dépôt Git.

- ```bash git add <path>``` - ajoute le fichier ou le répertoire à la zone de transfert.
Utilisez ```bash git add -A``` pour mettre en scène tous les changements.

- ```bash git commit -m "votre message "``` - enveloppe la zone d'activation dans une validation, décrite par le message donné.

- ```bash git status``` - lister les modifications actuellement non mises en scène et mises en scène.

- ```bash git remote add <name> <URL>``` - Ajoute un nouveau référentiel distant à l'URL spécifiée, qui peut être référencé à l'aide du nom fourni.

- ```bash git remote -v``` - Voir les télécommandes actuellement configurées.

- ```bash git push <remote> <branch>``` - Pousse la branche spécifiée vers le référentiel distant. Utilisez ```bash -u``` pour configurer le suivi afin que vous puissiez l'utiliser la prochaine fois ```bash git push```.

- ```bash git clone <URL>``` - Descend le dépôt distant sur votre machine locale (recuperer un projet github sur votre machine).

- ```bash git pull <remote> <branch>``` - Descend la branche distante et fusionne toutes les nouvelles modifications dans la branche actuelle. Si vous avez déjà poussé avec l'```bash -u``` indicateur, vous pouvez omettre la télécommande et la branche.




...



**NB :** La formation sera plus basé sur github desktop prevoir github Desktop sur votre machine 



