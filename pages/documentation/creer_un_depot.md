# Créer un dépôt sous multiBàO

L'opération de création d'un dépôt distant sous multiBàO est pour l'instant manuelle. 

* Tout d'abord, il faut que vous ayez un identifiant [Github](http://github.com)

* Créez un nouveau "repository" (c-à-dire "dépôt"). Vous trouverez l'option dans la partie en haut droite de votre écran, à coté de votre nom d'utilisateur : il s'agit du "+". Ou vous pouvez cliquez sur ce [lien](https://github.com/new).
 * ce nom de "dépôt" est celui qui apparaîtra sous multiBàO. Prenez du temps à bien le choisir car il sera difficilement changeable par la suite (une opération de changement de nom de dépôt demandera de l'aide de l'équipe de développement).
 * exemple: agfr (pour l'évènement agile games france), reseau_transition (pour l'association réseau transition Wallonie Bruxelles), ...
 * dans "Description", spécifiez quelle est votre structure et comment il est possible de vous joindre. 
 * choisissez "Public" + "Initialise this repository with a Readme" (ça vous permettra plus tard d'informer les contributeurs sur l'utilisation de votre dépôt)
 * puis validez

* Maintenant, créez votre première fiche et dossier "contributions"
 * cliquez sur "create a new file" (le + à coté de votre nom de dépôt)
 * créez d'une pierre 2 coups à la fois votre dossier "contributions" (indispensable) + le nom de votre première fiche.
 * exemple: monnomdedepot/**contributions/mafiche.md**
 * validez 

> A cette étape, en étant sur votre fiche, vous devriez avoir un lien du style : 
> https://github.com/VotreIdentifiantGithub/VotreNomDeDepôt/blob/master/contributions/LeNomDeVotreFiche.md

* Vient l'étape d'interconnexion
 * Rendez vous sur https://github.com/multibao/site/edit/master/packages/pntbr:contribution/lib/client/repos.js
 * A cet endroit précis, vous êtes dans l'architecture du site web.
 * Cliquez sur "edit" (le stylo) et ajoutez votre ligne de code : 

>   {owner: 'votrenomindentifiantgithub', repo: 'lenomdevotredepot'},

* Ecrivez un [mail](mailto:stephane.langlois@scopyleft.fr) ou [tweet](https://twitter.com/langlois_s) à Stéphane Langlois qui activera votre dépôt
* N'hésitez pas à joindre Thomas Wolff pour vous accompagner dans la création du dépôt
