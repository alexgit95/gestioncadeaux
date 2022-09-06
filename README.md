# gestioncadeaux


Cette application permet de preparer et de suivre l'achat des cadeaux de Noel de toute la famille.

Il suffit de recuperer le html et de creer un fichier data.js à coté. Vous pourrez en retrouver un exemple dans le REPO.

Chaque personne doit etre créer en rajout dans le data.js ceci :

```

pers = new Person("Name 2",100,);
allPersons.push(pers);

```

Le champ 1 est le prenom de la personne, le second est le budget max autorisé pour celle ci.


La page utilise le stockage local, ainsi qu'une fonction d'import export permettant de sauvegarder un objet json que vous pourrez de nouveau importer plus tard, ce qui vous permet de faire perdurer les données en dehors du stockage local.

Aucune fonctionnalité de sauvegarde dans le cloud n'a encore été developpé.