# quest-spring-route

## Consignes

Tu vas devoir modifier une route dans un contrôleur **DoctorController,** contenu dans le package **controller** :

- Avec l'aide de l'annotation **@PathVariable**, modifie la route **/doctor/** pour accepter la variable **{number}**.
- Pour le numéro 13, renvoie les informations sur l'incarnation du Docteur au format **JSON**, sous la forme {"number": 13, "name": "Jodie Whittaker"}. Pour se faire, retourne une instance de **Doctor** dont tu trouveras la classe dans le package model.
- Pour les autres numéros valides -- de 1 à 12 -- renvoie un statut **303**.
- Si le numéro n'est pas valide (par exemple, le lien vers /doctor/42), renvoie un statut **404** avec comme information une chaîne de caractères contenant Impossible de récupérer l'incarnation **{number}**."
- Pousse le contenu de ton projet dans un dépôt **GitHub** et poste le lien de ton dépôt en guise de solution.


## Critères de validation :

- Les liens de la page d'accueil peuvent tous être testés.
- Il n'y a qu'une seule route dans le contrôleur.
- La route 
  - renvoie un **_JSON_** pour le numéro 13, 
  - un statut **303** pour les numéro 1 à 12, 
  - sinon elle renvoie un statut **404** avec un message adapté.
- Le code est disponible sur GitHub.
