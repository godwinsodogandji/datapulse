### Repository

Un repository est un composant de votre application qui gère les opétations de persistence (CRUD) sur les entités dans un BDD. En gros c'est la couche qui nous permet de parler à la BDD sans se soucier des détails.

## Annotation @Repository

Elle sert à marquer une classe comme étant un repsitory, c'est-à-dire un endroit où vous allez interagir avec votre BDD.

## Est-ce obligatoire

Non ! Quand on implémente déjà une interface comme `JpaRepository`, Spring détecte automatiquement notre repository

## @PathVariable et @RequestBody et @RequestParam

## @PathVariable

On l'utilise pour extraire une partie variable dans notre chemin d'URL.

## @RequestBody

On l'utilise quand on reçoit des données via post

## @RequestParam

On l'utilise quand on a des paramètres dans l'URL sous la forme `?param=valeur`
