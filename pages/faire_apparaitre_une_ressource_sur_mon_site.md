# Faire apparaître une fiche de n'importe quel dépôt sur mon site

> Cette technologie nous est offerte par [Stéphane Langlois et Vincent Agnano](http://Scopyleft) de l'équipe de Scopyleft, et porte le nom [Anywhere](https://github.com/multibao/anywhere). Elle fait partie du projet [Daktary](http://github.com/daktary). 

## Rappel

Vous avez la possibilité de faire apparaître n'importe quelle ressource de multibao sur votre site web. Cette dernière prendra automatiquement la mise en page de votre site. Si quelqu'un modifie la ressource, elle sera modifiée sur votre site ainsi que tous les sites faisant apparaître la ressource. 

## Méthode

### Première étape: repérez les informations nécessaires 

Pour pouvoir faire apparaître une ressource multiBàO sur votre site, il faut que vous connaissiez quelques petites informations très visibles : le nom de propriétaire de la fiche, le nom de la fiche et là où elle est stockée. 

Prenons l'exemple de la fiche [Fabrique de Roubaix](http://www.multibao.org/alecoz/democratie_ouverte/contributions/la_fabrique_roubaix.md) que vous pouvez voir apparaître dans le dépôt [Démocratie Ouverte](http://www.multibao.org/alecoz/democratie_ouverte/contributions)

Le lien hypertexte de la fiche est le suivant : 

> http://www.multibao.org/alecoz/democratie_ouverte/contributions/la_fabrique_roubaix.md

La fiche "la_fabrique_de_roubaix" se trouve dans le dossier "contributions", lui même sous-dossier du dossier "démocratie_ouverte", dont "alecoz" est le propriétaire.

### Deuxième étape: insérez le code dans la page de votre site souhaitée et mettez à jour les informations

Pour insérer une fiche de multibào dans votre site, il vous faut insérer code çi dessous et remplacer les champs indiqués par les vrais noms de *propriétaire de dépôt*, *dépôt*, *dossier* et *fiche*. Ne vous laissez pas impressionner par ce code, un simple copier coller suffit. ;)

>`<script src="https://cdn.rawgit.com/vinyll/anywhere/master/dist/anywhere.js"></script><script>Anywhere.config.default = {user: "nom_du_proprietaire_du_depot", repo: "nom_du_depot"};</script><div data-anywhere="nom_de_la_fiche ou dossier_ou_est_la_fiche/nom_de_la_fiche"></div>`

Démonstration pour la fiche "La fabrique de Roubaix"

> http://www.multibao.org/alecoz/democratie_ouverte/contributions/la_fabrique_roubaix.md

Le code à insérer et le suivant: 

>`<script src="https://cdn.rawgit.com/vinyll/anywhere/master/dist/anywhere.js"></script><script>Anywhere.config.default = {user: "alecoz", repo: "democratie_ouverte"};</script><div data-anywhere="contributions/la_fabrique_roubaix"></div>`

### Troisième étape: validez

En insérant le présent code dans une page de site web, on arrive au résultat suivant: http://cpcoop.fr/demonstration-multibao/

La fiche sera automatique mise à jour
