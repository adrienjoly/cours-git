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
