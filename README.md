# Justice

Un template Jekyll pour les cabinets d'avocats.
[live demo](https://grey-grouse.cloudvent.net/) en français sur http://maroon-iris1.cloudvent.net/

Accroître la présence web d'un cabinet d'avocats avec ce thème paramétrable

![Modèle Justice](images/_screenshot.png)

Justice a été produit par [CloudCannon](http://cloudcannon.com/), un CMS Cloud pour Jekyll.
D'autres thèmes peuvent être trouvés sur les [trucs jekyll](http://jekyll.tips/templates/).

Pour en savoir plus sur Jekyll, suivez les tutoriels sur [Jekyll Tips](http://jekyll.tips/).

## Fonctionnalités

* Formulaire de contact
* Pages pré-construites
* Composants mis en forme
* Blog avec pagination
* Pages Catégories
* Commentaires Disqus pour les posts
* Système de publication pour le staff et auteurs
* Pied de page configurable
* Optimisation pour la modification dans [CloudCannon](http://cloudcannon.com/)
* Flux RSS/Atom
* Tags SEO
* Google Analytics

## Installation

1. Ajoutez votre site et détails de publication dans `_config.yml`.
2. Ajoutez vos clés Google Analytics et Disqus keys sur `_config.yml`.
3. Réglez un workflow pour voir la production de votre site (avec [CloudCannon](https://app.cloudcannon.com/), SiteLeaf ou en local avec Jekyll).

## Développement

Justice a été construit avec la version 3.3.1 de [Jekyll](http://jekyllrb.com/), mais devrait supporter tout aussi bien les versions plus récentes.

Installez les dépendances avec [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Lancez les commande `jekyll` avec Bundler pour vous assurer d'avoir les bonnes versions :

~~~bash
$ bundle exec jekyll serve
~~~

## Edition

Justice est déjà optimisé pour ajouter, mettre à jour et enlever des pages, staff, conseil, détails sur la société et éléments de pied de page dans le [CloudCannon](https://app.cloudcannon.com/).

### Posts

* Ajout, mise à jour ou retrait d'un post dans la collection *Posts*.
* Le champ **Staff Author** fait un lien vers les membres dans la collection **Staff**.
* Les pages de documentation sont organisées dans la navigation par catégories, avec des URLs basées sur le chemin à l’intérieur du dossier `_docs`.
* Changez les réglages par défaut quand de nouveaux posts sont créés dans `_posts/_defaults.md`.

### Formulaire de Contact

* Pré-configuré pour fonctionner avec [CloudCannon](https://app.cloudcannon.com/), mais facilement modifiable vers un autre fournisseur (par exemple  [FormSpree](https://formspree.io/)).
* Envoi d'email à l'adresse listée dans les détails de la société.

### Staff

* Réutilisé sur tout le site pour sauvegarder plusieurs endroits sujets à modifications.
* Ajout `excluded_in_search: true` à tout front matter de documentation de page pour exclure cette page des résultats de recherche.

### Pied de Page

* Exposé sous forme de fichier de données pour donner aux clients un meilleur accès.
* Réglé dans la section Data* / *Footer*.

### Détails sur la société

* Réutilisé sur tout le site pour sauvegarder plusieurs endroits à modifier
* Réglé dans la section *Data* / *Company*.
