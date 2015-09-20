# Enrichir des fiches

Si vous venez sur cette ressource pour apprendre le langage Markdown, sautez le premier paragraphe. Bonne utilisation.

## Je veux écrire / enrichir ma première fiche

ça y est, j'ai eu mon accès [contributeur](https://github.com/multibao/documentation/blob/master/fiches/obtenir_donner_acces_contributeur.md), à moi la liberté ! Une proposition ? ;)

1. Rends toi dans le dossier https://github.com/multibao/contributions/tree/master/contributions où sont stockées toutes les fiches du dépôt. On va imaginer que tu as accès au dépôt « multibao », rends toi alors dans le dossier https://github.com/multibao/contributions/tree/master/contributions. Ouvre le dans un nouvel onglet pour pouvoir surfer entre cette fenêtre et l'autre. 
2. Dans ce dossier, il y a une fiche qui s'appelle [« Mur des nouveaux contributeurs »](https://github.com/multibao/contributions/blob/master/contributions/mur_nouveaux_contributeurs.md), cliques dessus
3. Bienvenue sur une fiche multiBàO, celle ci présente la fiche méthode « mur des nouveaux contributeurs ». A vrai dire c'est une fiche sur laquelle tu vas pouvoir t'entraîner, laisser une trace (ou pas), …
4. **Il y a plein d'exercices qui te sont proposés ci dessous**
4. Sur la fiche, à coté de * Raw *, * Blame * et * History * il y a un dessin de crayon (option éditer). Cliques dessus.
5. Bienvenue sur ta première fiche multiBàO. Et mince, c'est pas un document word;) ! Le langage avec lequel nous co-écrivons les fiches s'appelle * Markdown *. Son but est d'offrir une syntaxe très facile à lire et écrire. Nous te décrivons ci dessous quelques exercices. Dès que tu auras modifié ta fiche, descens en bas de ton écran et cliques sur «commit changes». Tu pourras alors à la fois consulter la fiche sous  https://github.com/multibao/contributions/blob/master/contributions/mur_nouveaux_contributeurs.md et sur [multibao](http://www.multibao.org/contributions/multibao/contributions/mur_nouveaux_contributeurs) où elle sera instanément actualisée.
6. On y va ! 

# Exercice 1 : écris quelques titres

En langage Markdown 

# Titre 1 : exercice 1 : écris quelques titres

# Titre 1

s'écrit \# Titre 1

## Titre 2 

s'écrit  \#\# Titre 2 

De même pour \#\#\# Titre 3, \#\#\#\# Titre 4, etc. 

# Exercice 2 : écris un texte, mets des parties en gras, d'autres en italique

**je suis un peu gras** s'écrit \*\* je suis un peu gras\*\*
*je suis italique* s'écrit \*je suis italique\* (ça se dit, ça?)

# Exercice 3 : insères tes « puces »

* à la claire fontaine
* j'ai bu d'leau cristaline®

s'écrit 

\* à la claire fontaine

\* j'ai bu d'leau cristaline®

# Exercice 4 : mets un lien vers un site web 

[lien vers multiBàO](http://multibao.org) s'écrit \[lien vers multiBàO\]\(http://multibao.org\) 
 
## Exercice 5 : insères une image à ta fiche

### Si on l'a sous la forme d'un lien hypertexte

\!\[indiquer un titre pour l'image\]\(indiquer l'url de l'image\)

Exemple :

\!\[Outils-reseaux.org CoursInkscape\]\(http://outils-reseaux.org/files/CoursInkscape_inkscapelogo_vignette_209_209_20130614154853_20130614155446.png)

Donne cela :

![Outils-reseaux.org CoursInkscape](http://outils-reseaux.org/files/CoursInkscape_inkscapelogo_vignette_209_209_20130614154853_20130614155446.png)

Il n'est pour l'instant pas possible d'ajouter directement de photo dans l'édition d'une fiche multiBàO.

### Où trouver des images Creative Commons (autorisant réutilisation)?

http://search.creativecommons.org/ 

### Si on l'a sous la forme d'un fichier jpeg, png,...

Stocker l'image sur ton site ou sur https://framapic.org/

Framapic est un des nombreux services libres, sécurisés et gratuits de Framasoft. En un clic, tu ajoutes ta photo et récupères le lien hypertexte. A partir de ce lien hypertexte, tu peux ajouter la photo sous multiBàO.

### Recommandations pour l'image

* inférieure ou égale à 640 px de largeur
* privilégier des images "légères" pour que l'affichage des fiches soit facilité

# Exercice 6:  insérer des notes 

### A l'endroit où on souhaite insérer la note

on insère juste le code suivant qui indique que cela est une note avec le numéro correspondant 

Exemple : 

\*\*\[1\]\(\#note\)\*\*  donne **[1](#note)**

\*\*\[2\]\(\#note\)\*\*  donne **[2](#note)**

### A l'endroit où l'on veut que la note pointe

Par exemple à la fin de mon document je créer un paragraphe Source

\#\# Sources

Dans lequel j'insère le code suivant : 

\<a id="note"\> <a id="note">

Puis les notes en question :

\* \*\*\[1\]\(\#note\)\*\* Vincent Kober [infolabs.io](http://infolabs.io/sites/default/files/files/dataviz_pieds_V1.pdf), selon les termes de la licence Creative Commons BY-NC-SA 

\* \*\*\[2\]\(\#note\)\*\* Merci a netalloy et openclipart pour les pieds, [openclipart](https://openclipart.org/detail/154855/green-steps-by-netalloy), selon les termes de la licence Creative Commons  CC0 1.0 universel [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.fr)

Ce qui donne :

* **[1](#note)** Vincent Kober [infolabs.io](http://infolabs.io/sites/default/files/files/dataviz_pieds_V1.pdf), selon les termes de la licence Creative Commons BY-NC-SA 

* **[2](#note)** Merci a netalloy et openclipart pour les pieds, [openclipart](https://openclipart.org/detail/154855/green-steps-by-netalloy), selon les termes de la licence Creative Commons  CC0 1.0 universel [CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/deed.fr)
