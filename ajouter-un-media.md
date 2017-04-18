# Ajouter ou mettre à jour les données d'un journal

Il suffit d'ajouter une entrée pour le journal, et une entrée pour chacun de ses actionnaires (s'ils n'y sont pas déjà). Tout se passe dans le gros fichier [`entités.yaml`](https://github.com/transpamedia/transparence.media/blob/master/data/entités.yaml).

Prenez simplement exemple sur un des médias existants, par exemple, Le Monde.

> Pour l'instant, il n'est possible d'ajouter que des journaux, on ne peut pas, par exemple, ajouter de chaine télé. Si vous voulez le faire, [lancez une discussion](https://github.com/transpamedia/transparence.media/issues/new?title=Permettre%20l%27ajout%20des%20chaines%20de%20télé) :-)


### Quelques points importants ❕

- il n'y a malheureusement pas aujourd'hui de schéma bien défini des entités, d'où l'ajout par copie d'un média existant.
- il y a des entités de plusieurs types, les principales étant `journal`, `individu` et `société`.
- les identifiants des médias sont précédés de `w:` s'ils ont une page sur Wikipedia. Cela permettra de récupérer automatiquement les images.
- beaucoup d'informations sur les médias ou entités sont déjà ou auraient leur place dans l'`infobox` des pages Wikipedia : par exemple la date de création, la forme juridique. On pourrait les récupérer automatiquement, et compléter celles qui manquent directement sur Wikipedia, ce qui faciliterait la contribution et éviterait une duplication. Si vous vous sentez prêts à mener ce chantier, [c'est parti !](https://github.com/transpamedia/transparence.media/issues/new?title=Stocker%20les%20informations%20dans%20les%20infobox%20Wikipedia) !
- essayez au possible de sourcer l'actionnariat des médias : inspirez-vous de la propriété `sources` des médias existants.
- le tableau des subventions de l'état est déjà là, mais il vous faudra y identifier votre média en ajoutant son `id` dans les deux fichiers suivants (la compensation du tarif postal n'a pas été publiée pour 2015...):
  - chiffres-ministère-culture-2015
  - compensation-tarif-postal-2014


 ### En termes pratiques 🏗

 Si vous n'avez pas le temps de créer une [PR](https://github.com/transpamedia/transparence.media/pulls) complète, n'hésitez pas à créer une issue, voir un mail, avec un brouillon de votre nouveau média et ses actionnaires.


 Voilà une liste indicative de médias connus qui n'ont pas été ajoutés faute de temps :

- Marianne
- bastamag
- Bakchich
- StreetPress
- Numérama
- Valeurs actuelles
- La tribune
- Courrier International
- Politis
- Paris Match
- Capital
