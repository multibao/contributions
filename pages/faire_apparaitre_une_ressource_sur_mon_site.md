# Faire apparaître une fiche de n'importe quel dépôt sur mon site

> Cette technologie nous est offerte par [Stéphane et Vincent](http://Scopyleft) de l'équipe de Scopyleft, et porte le nom [Daktary](http://github.com/daktary).

### Rappel

Vous avez la possibilité de faire apparaître n'importe quelle ressource de multibao sur votre site web. Cette dernière prendra automatiquement la mise en page de votre site. Si quelqu'un modifie la ressource, elle sera modifiée sur votre site ainsi que tous les sites faisant apparaître la ressource. 

## Méthode

1. Observez bien le format d'une fiche sous multibao.org: prenons l'exemple de la fiche [La Fabrique de Roubaix](http://www.multibao.org/alecoz/democratie_ouverte/contributions/la_fabrique_roubaix.md). 

Lorsque vous ouvrez cette ressource, le lien hypertexte de la fiche est le suivant : 

> http://www.multibao.org/alecoz/democratie_ouverte/contributions/la_fabrique_roubaix.md

Toutes les fiches apparaîssent depuis des dépôts dossiers/distants qui sont présents sur github.com. Sur cette fiche "alecoz" est le propriétaire du dépôt "democratie_ouverte", et si on va dans le dossier "contributions", on trouve la fiche "la_fabrique_roubaix".

Ces données sont visibles pour toutes les fiches de multibao.

2. Pour insérer une fiche de multibào dans votre site, il vous faut le code çi dessous et remplacer les champs indiqués par les vrais noms de *propriétaire de dépôt*, *dépôt*, *dossier* et *fiche*.

>`<script src="https://cdn.rawgit.com/vinyll/anywhere/master/dist/anywhere.js"></script><script>Anywhere.config.default = {user: "nom_du_proprietaire_du_depot", repo: "nom_du_depot"};</script><div data-anywhere="nom_de_la_fiche ou dossier_ou_est_la_fiche/nom_de_la_fiche"></div>`

Démonstration pour la fiche "La fabrique de Roubaix"

>`<script src="https://cdn.rawgit.com/vinyll/anywhere/master/dist/anywhere.js"></script><script>Anywhere.config.default = {user: "alecoz", repo: "democratie_ouverte"};</script><div data-anywhere="contributions/la_fabrique_roubaix"></div>`

En insérant le présent code dans une page de site web, on arrive au résultat suivant: http://cpcoop.fr/demonstration-multibao/
