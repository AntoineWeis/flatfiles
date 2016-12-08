


## Étude des CMS

http://cmsmatrix.org

Communauté / volume / beaucoup sont Open source / structure en PHP

* Wordpress : moteur de blogs
* Flux BB / php BB : forum
* Joomla! / Drupal / Typo 3 /Concrete 5 / SPIP : CMS
* Prestashop / magento : e-commerce
* Mediawiki : wiki

## Github pages

Github -> Héberger des dépôts (Open-source)
Github Pages -> Site associé au dépôt pour présenter le projet.

__usernamie.github.io/flatfiles__
_http://broqunic.github.io/flatfiles_

Pour mettre en place Github pages, il suffit de se rendre dans les Settings du repository

Il faut aussi mettre en place Jekyll, un générateur de site web static, codé en ruby. On va créer une sorte de mini CMS pendant les prochains cours.

Tout d'abord il faut installer Ruby sur le machine virtuelle sous Linux, ensuite, on installe Jekyll.

### Commandes
_gem install jekyll_ -> permet d'installer jekyll

_jekyll new "monsite"_ -> si besoin de créer un nouveau site

_jekyll serve_ -> A utiliser lorsque que l'on se trouve dans le dossier racine de notre site, à partir d'une invite de commande distince, il permet de mette en place un serveur pour notre site pour aplliquer nos modifications et les prévisualiser.


### Fichiers

_congif.yml -> fichier de configuration où l'on trouve des couples clés - valeurs, ce sont les variables gloables qui serviront sur les différentes parties du template.

{{site.titre}} -> affiche la valeur associé à la clé titre présente dans le fichier de config

Pour les variables locales on les places dans l'en-tête des fihciers de templates entre les deux lignes de tiret.
