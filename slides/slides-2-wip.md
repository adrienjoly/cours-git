class: center, middle

![Logo git](../logo.png)

# Outils: `git`
# EEMI (2018)
## [adrienjoly.com/cours-git](https://adrienjoly.com/cours-git/)

<!-- forked from https://github.com/adrienjoly/cours-javascript/tree/gh-pages/M -->

---
class: dbl-size
# De git à Github Pages

- `git` est un outil en ligne de commande
- Github est un site permettant d'héberger ses *repositories* en ligne
- Github permet à plusieurs utilisateurs de collaborer sur un *repo*
- Github Pages permet de publier des pages web hébergées au format HTML dans un repo Github (à condition d'utiliser la branche *gh-pages*)

---

# Exercice 1: Créer un repo git local

0. Aller dans votre répertoire personnel (`cd` sans paramètre), créer un répertoire `todolist` avec la commande `mkdir`, puis y entrer avec la commande `cd`
1. Initialiser un repo local dans ce nouveau répertoire avec `git init`
2. Y copier le fichier `index.html` du TP précédent, vérifiez sa présence avec `ls`
3. Lancer `git status` pour constater que `index.html` n'est pas encore indexé
4. Intégrer ce fichier à l'index avec `git add`
5. Lancer `git status` à nouveau pour constater que `index.html` a bien été indexé
6. Valider et décrire vos modifications avec `git commit -m "mon premier commit"`
7. Vérifier que ce commit apparait bien dans l'historique du repo avec `git log`

---

# Branches ?

.column[
* Un repo git a une structure de graphe
* Par défaut les commits se succèdent sur la branche `master`
* Pour se placer sur le dernier commit d'une branche, il faut taper `git checkout <nom_de_la_branche>`
* Toute branche se base sur un commit
* Une branche peut être *mergée* dans une autre branche
* Github publie les fichiers HTML trouvés dans la branche `gh-pages`
]

.column[
    ![branches](./img/git-branches.png)
]

---

# Exercice 2: Publier l'app TODO-list

1. Créer un compte sur Github
2. Créer un repo public "todolist" sur votre compte Github, sans cocher la case "README.md"
3. Une fois sur la page Github de votre repo, poussez le(s) commit(s) de votre repo local (cf exercice 1) dans votre repo Github, en suivant les instructions proposées:
    - `git remote add` pour associer le repo local au repo Github,
    - puis `git push` pour envoyer vos commits
4. Créer une *branche* "gh-pages" dans votre repo local avec la commande `git checkout -b`
5. Pousser cette branche locale vers celle de votre repo Github, avec `git push origin gh-pages`
6. Vérifier que votre TODO-list s'affiche bien depuis `http://<votre_username>.github.io/todolist`

---

# Exercice 2: Publier l'app TODO-list (suite)

7. Créer un fichier `CONTRIBUTORS.md` contenant votre nom dans votre repo local.
8. Créer et pousser un commit à partir de ce fichiers avec les commandes `git add`, `git commit -m "message"` (cf exercice 1) puis `git push`
9. Chaque personne de l'équipe va ajouter son nom dans CONTRIBUTORS.md depuis son propre repo local puis pousser son commit sur le repo Github. Pour cela:
    - Le créateur du repo Github doit autoriser les contributions depuis les comptes Github de ses co-équipiers, via l'interface d'administration du repo
    - Chaque co-équipier à son tour va: cloner le repo Github dans son répertoire personnel (cf Mise en pratique), ajouter son nom dans CONTRIBUTORS.md, créér puis pousser un commit pour enregistrer cette modification (cf étape 8)
10. Envoyer l'URL de votre repo Github par email à votre enseignant, avec vos co-équipiers en copie, avant Mardi prochain 8h.
