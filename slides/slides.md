class: center, middle

![Logo git](../logo.png)

# Outils: `git`
# EEMI (2018)
## [adrienjoly.com/cours-git](https://adrienjoly.com/cours-git/)

<!-- forked from https://github.com/adrienjoly/cours-javascript/tree/gh-pages/M -->

---
class: dbl-size
# Objectifs

- Comprendre l’**intérêt** de `git` et GitHub
- Maîtriser les **commandes** de base
- Savoir résoudre les **conflits**
- Projets **Open Source** et principes de collaboration

Application: ajouter sa photo à un trombi web.

---
class: dbl-size
# Programme - Partie 1

- Introduction: terminologie, flot, commandes de base
- TP: [Créer un dépôt git sur gitlab de l'EEMI](../tutos/creer-depot-gitlab-eemi.html)
- TP: [Collaborer sur un dépôt gitlab](../tutos/collaborer-sur-un-depot-gitlab.html)

---
class: dbl-size
# Programme - Partie 2

- Cours: collaboration avec git
- TP: Régler un conflit de fusion
- TP: Contribuer à un projet open source sur GitHub

---
class: dbl-size
# Git, pour quoi faire ?

.wide[![Linux](./img/linux-code.png)]
.wide[![Code civil](./img/codecivil-code.png)]

---
class: dbl-size
# Git, pour quoi faire ?

- **éditer** fichier à plusieurs
- **garder** historique des modifs
- **isoler** les améliorations

???

- éditer des fichiers à plusieurs, de manière concurrente, en évitant les pertes de données
- garder un historique des modifications et des versions
- isoler les améliorations en cours de la version qui fonctionne
- (illustration: linux-code.png)

---
class: dbl-size
# Avant git

- 1990: CVS
- 1994: Microsoft SourceSafe
- 2000: Subversion
- 2005: Git, Mercurial

???

- git créé par Linus Torvalds, pour intégrer les contributions sur son projet Linux
- critères: vitesse, décentralisation, intégrité des données

---
class: dbl-size
# Plateformes git

.wide[![Logos GitHub GitLab Bitbucket](./img/logos.jpg)]

---
class: dbl-size
# Modèle de git: branches et commits

.center[![git master branches](./img/master-and-branches.png)]

---
class: dbl-size
# Terminologie git

- **Repository** (dépôt)
- **Staging** (index)
- **Commit**
- **Branch**
- **Merge** (fusion)

???

- **Repository** (dépôt): espace de stockage du code source, local ou distant (remote)
- **Staging** (index): une mise à jour en cours d'assemblage
- **Commit**: une mise à jour du code source: lignes de code de fichier(s)
- **Branch**: une suite de commits liés entre eux
- **Merge** (fusion): intégrer les mises à jour d'une branche dans une autre

---
background-image: url(./img/git-local-remotes.png)

---
class: dbl-size
# Commandes git

- `git clone` (ou `git init`)
- `git status`
- `git pull`
- `git add`
- `git commit`
- `git push`

???

- `git clone` (ou `git init`): importer ou créer un dépôt localement
- `git status`: afficher l'état de l'index
- `git pull`: récupérer mises à jour depuis dépôt distant
- `git add`: ajouter les mises à jour de fichier(s) dans l'index
- `git commit`: empaqueter les mises à jour de l'index
- `git push`: envoyer les commits dans le dépôt distant

---
class: dbl-size
# 🏋 Mise en pratique

1. [Créer un dépôt git sur gitlab de l'EEMI](../tutos/creer-depot-gitlab-eemi.html)
2. [Collaborer sur un dépôt gitlab](../tutos/collaborer-sur-un-depot-gitlab.html)

---
class: dbl-size
# 🏆 Pro tips

- Harmoniser l'encodage des fin de lignes (`autocrlf` / `safecrlf`) avec git config, cf ([1](https://githowto.com/setup)) ou ([2](https://help.github.com/articles/dealing-with-line-endings/))
- Visualisation de l'historique dans le terminal: [`git lola`](http://blog.kfish.org/2010/04/git-lola.html)
- Éviter d'avoir à taper son mot de passe à chaque fois:
  - [Stockage des identifiants](https://git-scm.com/book/fr/v2/Utilitaires-Git-Stockage-des-identifiants),
  - ou [Configure SSK key](https://docs.gitlab.com/ee/university/training/topics/env_setup.html#configure-ssh-key),
  - ou encore [GitLab and SSH keys](https://docs.gitlab.com/ee/ssh/) (plus détaillé)
