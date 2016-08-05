# Compétences

Cette section a pour but de donner des axes de formation et de préciser l'organisation du support aux développeurs.

## Formation

### JavaScript

L'utilisation de JavaScript n'est pas nouvelle à l'Insee, mais son utilisation jusqu'à présent n'a pas permis de mettre en place un travail de formation de fond (cf. paragraphe précédent). De plus, comme nous l'avons également mentionné plus haut, le langage se transforme en profondeur.

Il est donc nécessaire de donner les moyens aux développeurs Insee d'être former correctement.

Le premier axe de formation devrait être l'apprentissage du langage lui-même : bien souvent, les développeurs apprennent à utiliser un framework ou un module, une bibliothèque, à un degré d'expertise plus ou moins grand. Or, s'agissant d'un filière nouvelle, c'est sur le langage qu'il faut porter d'abord l'effort de formation.

JavaScript est un langage puissant mais faussement simple à maîtriser ; par ailleurs EcmaScript 2015 est [riche en fonctionnalités](http://es6-features.org).

Les contours d'une formation de base au langage :

- assignement et portée,
- types et structure de base,
- prototypage / classe,
- modules,
- iterateurs / générateurs.

Elle devrait aussi couvrir les outils permettant de transformer le code (compilation, minification, packaging), voir ci-dessous.

[Fonctionnalités ES6](http://es6-features.org/)

### Paradigmes, patterns

Comme tout langage de programmation de niveau industriel, JavaScript met en oeuvre ou privilégie des paradigmes de développement.

On en retiendra trois importants : programmation fonctionnelle, orientée objet et asynchronisme.

#### Programmation fonctionnelle

Le retour en force de la [programmation fonctionnelle](https://fr.wikipedia.org/wiki/Programmation_fonctionnelle) s'explique par la capacité des langages fonctionnels à être optimisés pour les exécutions concurrentes et leur gestion de l'état d'un programme de manière plus sûre, ce qui permet d'éliminer un certain nombre de bugs.

JavaScript supporte en partie ce modèle de programmation (par exemple, la capacité à passer des fonctions en argument d'autres fonctions) ; c'est également dans les patterns et les bibliothèques que l'on retrouve l'influence de la programmation fonctionnelle. Par exemple, React est basé sur l'application de ce principe aux composants graphiques qui sont en représentés sous la forme de fonctions pures, renvoyant le même rendu pour les mêmes paramètres en entrée (c'est le moteur React qui s'occupe de modifier la page web de manière optimisée mais transparente).

Développer ce principe améliore par ailleurs la testabilité des applications, les tests unitaires étant par nature plus simple à mettre en oeuvre sur des fonctions ou méthodes [transparente référentiellement parlant](https://fr.wikipedia.org/wiki/Programmation_fonctionnelle#Transparence_r.C3.A9f.C3.A9rentielle).

#### Programmation orientée objet

> TODO

#### Asynchronisme

> Callback / Promise / Generators

### Web API

...

[API du web sur MDN](https://developer.mozilla.org/fr/docs/Web/Reference/API)

### Outils

(cf. liste section II)

### Resources

>Pour l'autoformation et la documentation. (cf. starterkit)

On liste ici les ressources plus généralistes que celles citées par ailleurs.

[Mozilla Developer Network](https://developer.mozilla.org/fr/)

## Support

Le support sera assuré par la cellule architecture dans la phase de développement de la filière.

En premier lieu, il s'agira de la proposer ou pas dans le cadre de l'étude d'architecture et des réunions de macro-analyse en fonction à la fois des besoins anticipés, mais également des compétences de l'équipe de développement.

Ensuite, la cellule apportera un support aux développeurs directement. Il pourra s'agir d'aide à la prise en main des outils et du langage, mais aussi discuter de l'architecture des applications clientes, des bonnes pratiques de développement appliqués à cette filière, etc.

Le premiers projets de la filière bénéficieront d'un accompagnement proche ; par la suite, la compétence se diffusant au sein des SDs, ce sont les différentes communautés qui prendront naturellement le relais. Disposer de pôles de compétences dans les centres n'est pas à exclure.

La cellule a aussi en charge de s'assurer que l'atelier de développement JavaScript soit disponible (cf. la section Outils plus haut).
