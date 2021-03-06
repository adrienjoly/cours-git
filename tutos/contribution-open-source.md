## Contribuer à un projet open source

De nos jours, GitHub est une plateforme incontournable pour héberger des projets Open Source, et permettre à leurs contributeurs d'y proposer des modifications.

L'objectif de cet exercice est d'apporter votre contribution à un projet Open Source hébergé sur GitHub Pages: le [trombinoscope collaboratif des étudiants de l'EEMI](https://github.com/eemi-aj/trombi).

### Consignes et autres notes importantes

- Afin de contribuer à ce projet, vous aurez besoin d'un compte personnel sur GitHub. (gratuit)
- Pour que votre contribution vous rapporte des points, votre compte GitHub doit être à votre nom et doit être rattaché à votre adresse email EEMI.
- Vous serez noté(e) sur la base de la demande de fusion (*pull request*) que vous aurez soumise à ce projet GitHub, le bon respect des consignes de cet exercice, et la qualité des échanges qui auront éventuellement lieu au sujet de la demande de fusion.
- La demande de fusion doit être émise par votre compte GitHub personnel.
- Le ou les commits contenus dans votre demande de fusion doivent seulement ajouter une ligne dans le tableau, contenant votre prénom, nom, photo (ou avatar) et une courte présentation de vous-même. (cf l'exemple fourni)
- Votre demande de fusion ne doit pas modifier le reste du document, et ne doit pas causer d'erreur de validation sur le code HTML de la page dans laquelle elle sera intégrée. (cf [Validateur HTML du W3C](https://validator.w3.org/#validate_by_input))
- Dans la description de votre demande de fusion, vous devrez expliquer précisément comment vous vous y êtes pris: elle devra au minimum inclure les commandes `git` complètes que vous avez du taper dans votre terminal pour cloner le dépôt et y proposer votre contribution.
- Comme dans tout projet open source, vos contributions et discussions seront publiques => faites preuve de professionnalisme, de respect et de responsabilité. Tout contenu invalide, mal orthographié, irrespectueux ou illégal causera une pénalité, voire des poursuites.
- Votre demande de fusion devra être prête à être fusionnée avant le Vendredi 16 Novembre, minuit. Tout retard causera une pénalité, voire une note nulle.

### Procédure à suivre

Étapes à suivre, une par une:

1. Connectez-vous sur github.com avec un compte nominatif et associé à votre adresse email EEMI.
1. Dérivez le dépôt [github.com/eemi-aj/trombi](https://github.com/eemi-aj/trombi), en cliquant sur le bouton "Fork".
1. Téléchargez le dépôt dérivé dans un dossier de votre disque dur à l'aide de `git clone`.
1. Éditez le fichier HTML de votre classe afin d'y ajouter une ligne de tableau HTML contenant votre prénom, nom, photo (ou avatar) et une rapide présentation de vous-même.
1. Copiez votre photo ou avatar dans le sous-dossier "photos", redimensionnez-la aux dimensions 128x128 pixels puis enregistrez-la dans un fichier `png` ou `jpg` contenant votre prénom et nom(s) en minuscules et séparés par des tirets. (ex: `cyrano-de-bergerac.jpg`).
1. Ouvrez la page HTML de votre classe sur votre ordinateur, pour vous assurer qu'elle fonctionne bien.
1. Utilisez `git diff` pour vous assurer que vos modifications ne sont que des ajouts de lignes, et n'impactent pas le reste du fichier HTML.
1. Créez un commit contenant vos modifications de la page HTML + votre photo (fichier `jpg` ou `png` dans le sous-dossier "photos").
1. Envoyez votre commit dans votre dépôt distant (celui que vous avez dérivé à l'étape 2).
1. Soumettez une demande de fusion de vos modifications dans le projet d'origine: [github.com/eemi-aj/trombi](https://github.com/eemi-aj/trombi), via la page "pull requests", ou la page de votre dépôt dérivé.
1. Rédigez la description de la demande de fusion comme si c'était un email qui m'était destiné, pour me demander de bien vouloir intégrer les modifications que vous suggérez. Gardez en tête que cette demande de fusion sera visible publiquement.

## Points à vérifier avant de soumettre / valider la PR

- les messages de commit présent clairement les changements apportés et/ou la raison de ces changements.
- la description de la PR explique quels changements elle apporte, et invite courtoisement à la considération du reviewer en vue de sa fusion.
- la description de la PR décrit précisément comment cette PR a été élaborée, en incluant les commandes `git` utilisées.
- le code HTML est valide et sans erreur. (selon le W3C)
- la PR n'ajoute que le code nécessaire, et n'impacte pas le reste du code.
- le code ajouté est lisible et intenté de manière homogène avec le reste du code.
- la fiche étudiant(e) est écrite de manière professionelle, sans fautes d'orthographe.
- la PR inclue bien la photo retaillée aux dimensions 128x128 pixels.
- le nom du fichier photo respecte l'énoncé, et est correctement référencé dans le code html.

<!--

Spreadsheet utilisé pour évaluer les étudiants des classes 1-4 sur la base de leur PR: https://docs.google.com/spreadsheets/d/1GKUDq4HcVPyqLC1Zg_g8Um5dV_PABJGF1D-7NKOrmOg/edit#gid=0

Critères utilisés pour classe fast track 2018-2019:
- shipped: 1 point si PR soumise à temps + 1 point si URL fournie sur classroom
- clean commit: 2 points pour clarté des messages de commit
- good desc: 1 point pour formulation de l'objectif de PR dans la description + 1 point pour courtoisie et bonne orthographe
- git howto: 2 points pour mise en oeuvre est expliquée clairement et précisément en description de PR.
- valid code: 2 points pour code HTML 100% valide et sans erreur
- concise code: 2 points si PR n'ajoute que le code nécessaire sans impacter le reste du code.
- clean code: 2 points pour code bien intenté et lisible.
- pro content: 2 points si la fiche étudiant(e) est écrite de manière professionelle, sans fautes d'orthographe.
- image: 1 point pour présence de photo dans PR + 1 point si bien retaillée aux dimensions 128x128 pixels
- img naming: 2 points pour respect convention de nommage de la photo + référence correcte du fichier dans le code html

-->
