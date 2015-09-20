# Faire apparaître et synchroniser n'importe quelle ressource de multibao avec votre site

> Cette technologie conçue sous le nom d'[Anywhere](https://github.com/multibao/anywhere) nous est offerte par [Stéphane Langlois et Vincent Agnano](http://Scopyleft) de l'équipe de Scopyleft. Elle fait partie du projet [Daktary](http://github.com/daktary). En cas de difficultés dans la mise en oeuvre, n'hésitez pas à m'appeler 0642459781 ou à [m-emailer](thomas.wolff@cpcoop.fr) pour réaliser l'opération ensemble. 

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

La fiche sera automatiquement mise à jour dès qu'il y aura une modification. 

## Questions 

**Q: Sur ma fiche, il y a partout des # et des ##, mon site ne marche pas bien?**

> R: Non, c'est la fiche qui a mal été documentée. Les fiches sont écrites en langage Markdown et c'est ce que votre site devrait pouvoir reconnaître naturellement. Si cela ne marche pas c'est car la syntaxe a été mal indiquée. Les # représentent dans la syntaxe des titres. Si vous avez ce problème c'est sûrement car le rédacteur de la fiche n' a pas laissé d'espace entre le # et le titre. Comme #titre alors qu'il faudrait le rédiger sous la forme # titre (avec un espace). Je peux vous proposer de soit [directement modifier la ressource via l'éditeur](http://www.multibao.org/multibao/contributions/pages/enrichir_les_ressources_communes_existantes_via_l_editeur.md) et d'ajouter les espaces, soit de contacter le contributeur, soit de me contacter: 0642459781 ou [mail](mailto:thomas.wolff@cpcoop.fr)
