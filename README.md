# Démonstration de l'utilisation de Github

Dans ce bref guide, vous allez apprendre les notions de base pour utiliser Github.

> Ce guide prend pour acquis que vous avez git d'installé sur votre machine localement.

## Étapes

### Création du référentiel sur Github

- Allez sur [Github](https://github.com/)
- S'authentifier à son compte
- Suivre les directives selon [le guide officiel](https://docs.github.com/en/github/getting-started-with-github/create-a-repo) pour la création d'un référentiel.

### Cloner le référentiel localement

- Copiez l'adresse du référentiel à récupérer localement.
- Ouvrir une invite de commandes (bash, cmd, powershell ou autres...)
- Naviguez jusqu'au répertoire parent où vous voulez ramener le référentiel.
- Exécutez la commande "git clone URL_REPO" dans le terminal.

### Ajouter du contenu dans le référentiel

Suite à l'ajout ou à la modification de fichiers existants, pour ajouter ceux-ci dans la liste des fichiers à suivre par git, il faut utiliser la commande "git add ." (cette commande ajoute tous les fichiers).

### Commiter le contenu ajouté ou modifié

Lorsque nous avons précisé des fichiers à suivre, il est possible de commiter les fichiers avec la commande "git commit -m "message du commit"".

> Ne négligez pas la qualité du message du commentaire!

### Pousser les modifications sur Github

Pour pousser les modifications locales vers Github, il faut utiliser la commande "git push origin main". Prendre note que "main" peut être "master", mais "main" représente le nom de la branche sur l'origine.

### Mettre à jour le référentiel

Utilisez la commande "git pull" pour mettre à jour votre référentiel local. Assurez-vous de ne pas avoir de modifications en cours sur votre poste de travail.

Tous droits réservés 2021 © Alexis Garon-Michaud
