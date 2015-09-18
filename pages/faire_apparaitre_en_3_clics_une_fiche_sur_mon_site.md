# Faire apparaître en trois clics une fiche sur mon site 

## Rappels

* Vous pouvez faire apparaître n'importe quelle fiche de multiBàO sur votre site... et ça prendra automatiquement la mise en page de votre site. Cette fonctionalité est disponible pour toutes les ressources de multiBàO. 

> La technologie utilisée s'appelle un "script". C'est un lien que vous allez pouvoir incorporer dans une de vos pages web et qui fera apparaître la fiche en question avec la mise en page de votre propre site.
> La documentation explique pour l'instant comment le faire. Très bientôt ce sera faisable à partir d'une simple îcone présente sur chaque fiche.

## Faire apparaître une fiche multibao sur mon site

1. Observez bien le format d'une fiche sous multibao.org: prenons l'exemple de la fiche [La Fabrique de Roubaix](http://www.multibao.org/alecoz/democratie_ouverte/contributions/la_fabrique_roubaix.md). Lorsque vous ouvrez cette ressource, le lien hypertexte de la fiche est le suivant : 

> http://www.multibao.org/alecoz/democratie_ouverte/contributions/la_fabrique_roubaix.md

Toutes les fiches appaîssent depuis des dépôts dossiers/distants. Sur cette fiche "alecoz" est le propriétaire du dépôt "democratie_ouverte", et si on va dans le dépôt "democratie_ouverte/contributions", on trouve la fiche "la_fabrique_roubaix".

2. Ce sont ces données qu'il vous faut pour l'instant. Créez une page ou article sur votre site / blog, et insérez le code suivant en indiquant: 

> \<script src="https://cdn.rawgit.com/vinyll/anywhere/master/dist/anywhere.js">\</script>\<script>Anywhere.config.default = {user: "nom_du_proprietaire_du_depot", repo: "nom_du_depot"};\</script>\<div data-anywhere="nom_de_la_fiche">\</div>















