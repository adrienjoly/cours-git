## Proposer une contribution à l'aide d'une demande de fusion (*Pull Request*)

Un *pull request* est une branche dérivée (aussi appelée *fork*) de la branche de travail de ce dépôt qu'un développeur demande à intégrer (en Anglais: *merge*) dans cette branche de travail d'origine.

Mise en œuvre par le développeur "contributeur":

1. Dériver (en Anglais: *fork*) le dépôt d'origine, dans son propre compte `gitlab`
2. Cloner le dépôt dérivé depuis son propre compte `gitlab`: `$ git clone <adresse_https_du_dépôt>` puis `$ cd <nom_du_dépôt>`
3. Effectuer des modifications, les enregistrer dans un commit (`git commit`), puis les pousser (`git push`) sur `gitlab`
4. Depuis la barre latérale de `gitlab`, cliquer sur "Demandes de fusion"
5. Cliquer sur "Nouvelle demande de fusion"
6. S'assurer que la "source" correspond bien à la branche du dépôt dérivé dans laquelle le(s) commit(s) a/ont été ajouté(s), et que celle de destination (*target*) correspond bien à la branche de travail (ex: `master`) du dépôt d'origine
7. Valider pour passer à l'étape de comparaison
8. Taper un intitulé décrivant de manière claire et concise quelle valeur apporte la contribution proposée au dépôt d'origine (ex: *correction du bug #143*), en respectant les consignes de `CONTRIBUTING.md`. (ex: langue employée + éventuellement respect de conventions de nommage)
9. Penser à ajouter une description précise de ce qu'apporte la contribution et de comment l'évaluer en vue de son intégration, puis valider la demande de fusion.
10. Se tenir à la disposition du/des relecteur(s) (*reviewers) pour répondre aux éventuelles questions et demandes de modifications.
11. Une fois la demande fusionnée dans le dépôt d'origine, vous pouvez supprimer la branche que vous aviez créée, voire même le dépôt dérivé. (si vous n'en avez plus besoin)
