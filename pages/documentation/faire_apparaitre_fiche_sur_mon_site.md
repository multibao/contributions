# Faire apparaître une fiche multiBàO sur mon site

## Introduction 

Une même fiche multiBàO peut apparaître sur plusieurs sites différents. 

* lorsque la fiche apparaît sur ton site, elle prendra automatiquement sa mise en page. C'est ce qui est présenté dans la démo ci dessus.
* si un contributeur modifie la fiche, tous les sites seront instannément actualisés. 

### une invitation ...

Plutôt que de publier vos ressources sur les approches participatives sur votre site, vous pouvez aussi:
* utiliser le dépôt commun multiBàO, y publier vos ressources, puis les faire apparaître sur votre site.
* créer votre propre dépôt (droits d'administrateur, permettant d'inviter qui on souhaite), y publier vos ressources, puis de les faire apparaître sur votre site. 

## Comment faire ? 

**1** Sur ton site web, insères la balise html suivante : 

<section id="multibao" title="titre_de_la_publication">\</section><script src="http://www.multibao.org/integration/multibao.js"></script>\</body>

**2** Remplace **titre_de_la_publication** par le titre de la contribution que tu souhaites afficher. Exemple: cercle_excentrique.
 * Tu trouveras le titre des publications depuis les dépôts contribution multiBàO ou depuis http://multibao.org. 
  * si tu te rends sur la fiche du cercle excentrique : http://www.multibao.org/contributions/multibao/contributions/cercle_excentrique, tu retrouves le nom de la fiche : **cercle_excentrique**
  * si tu te rends sur la fiche sur le vote à cinq doigts, tu retrouves aussi le nom :  http://www.multibao.org/contributions/multibao/contributions/vote_cinq_doigts  = **vote_cinq_doigts**

## La mise en page de mon site ne me plaît pas, je souhaiterais modifier la mise en page

* Si tu es prêt à mettre un peu tes mains dans le css, tu vas pouvoir te faire une très jolie mise en page personalisée, par exemple :

```css
#multibao h1 {
  color: grey;
}

#multibao ul {
  background: #fdc;
}

#multibao p {
  background: #cdf;
}

#multibao a {
  font-size: 23px;
}
```

* Dans le futur, il est possible que l'on te prépare quelques feuilles de styles pour te permettre ne pas trop te salir les mains.
