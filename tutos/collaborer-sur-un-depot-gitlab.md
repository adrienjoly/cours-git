## Collaborer sur un dépôt `gitlab`

L'objectif de ce tuto est d'ajouter un fichier dans le dépôt d'un autre étudiant.

Par défaut seul le créateur d'un dépôt peut y ajouter des commits.

Si un autre développeur souhaite contribuer au dépôt, il existe deux manières de procéder:
- *forker* le dépôt puis proposer une contribution à l'aide d'un *pull request*;
- ou obtenir la permission d'ajouter des commits directement dans le dépôt.

Nous découvrirons les *pull requests* dans le TP suivant.

Dans ce TP, nous allons chacun:
- donner les droits à un autre étudiant d'ajouter des commits dans un dépôt personnel;
- et ajouter des commits dans le dépôt personnel d'un autre étudiant, après qu'il nous ait donné les droits nécessaires.

### Procédure pour ajouter un développeur dans une équipe Gitlab:

1. Depuis la barre latérale de la page du dépôt, cliquer sur "Paramètres"
1. Cliquer sur "Membres"
1. Taper le ou les noms d'utilisateurs (ou adresse email) du/des développeurs à ajouter
1. Sélectionner le rôle (ou niveau de permissions) à donner à ce(s) développeur(s)
1. Vérifier que le(s) développeur(s) est/sont bien capables d'ajouter et pusher un commit dans la branche de travail du dépôt (ex: `master`)

### Procédure pour ajouter un commit dans le dépôt d'un autre développeur

1. Utiliser `git clone` pour importer le dépôt de l'autre étudiant
1. S'assurer qu'on a bien les dernières mises à jour (`git pull`)
1. Créer un nouveau fichier dans le dépôt local, puis l'ajouter à l'index (`git add`)
1. Créer un commit contenant ce fichier (`git commit`) puis l'envoyer sur le dépôt de l'autre étudiant (`git pull`)
