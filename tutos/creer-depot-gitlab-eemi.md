## Créer un dépôt `git` sur le serveur `gitlab` de l'EEMI

> Note: le signe dollar (`$`) permet d'indiquer que la commande qui suit sera à saisir dans le terminal. Pour que la commande fonctionne, il ne faut pas copier le `$` dans le terminal, seulement la commande qui suit.

> Note: "dépôt" se traduit "repository", en Anglais.

1. Ouvrir l'interface `gitlab` de l'EEMI: [gitlab.eemi.tech](https://gitlab.eemi.tech/)
1. Cliquer sur "Nouveau projet"
1. Donner un nom de projet concis, en minuscules, et séparé par des tirets
1. Ne pas utiliser "privé" pour les travaux à rendre !
1. Copier l'adresse HTTPS (au lieu de SSH) fournie dans la page du dépôt
1. Dans le terminal: `$ git clone <adresse_https_du_dépôt>` puis `$ cd <nom_du_dépôt>`
1. Premier commit:
    - `$ echo "Bonjour" >README.md` pour créer `README.md` (documentation du projet)
    - `$ git status` (optionnel) pour constater qu'un fichier a été créé mais pas encore ajouté dans le dépôt
    - `$ git add README.md ` pour ajouter le fichier `README.md` dans l'espace de staging
    - `$ git status` (optionnel) pour afficher le contenu actuel de l'espace de staging
    - `$ git commit -m "first commit: documentation"` pour créer un commit à partir de l'espace de staging
    - `$ git status` (optionnel) pour constater que l'espace de staging a été réinitialisé et qu'aucun fichier n'a été modifié depuis notre commit
    - `$ git push` pour uploader notre commit sur le serveur git de l'EEMI.
1. Le fichier `README.md` devrait maintenant être visible depuis la page web du dépôt.
