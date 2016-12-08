---
layout: cours
nom: Cours 5  Boucles jekyll
---


## Généralités

Les valeurs présentent dans l'en-tête sont en YAML, Front Matter.

---

# Structure


Création du fichier _page.html_ dans le dossier layouts => imbrication de template.


 Accueil | Contact | Equipe
 --- | --- | ---
 layout : default | layout : page | layout : page
  | #titre | #titre


 Flatfiles, fichiers MD.
 dossier site, répertoire des fichier générés, à ne pas modifier.

 ---

## Boucles


 {% for page in site.pages %}
  < a href="page.url">{{page.title}}</a >
 {% endfor %}


 Permet d'afficher le titre de la page dans la page elle-même, sans fichier de template ou autre.

 ---

## Billets de blog

 Créer dossier _posts pour les posts et dans le dossier _layouts le fichier posts.html.


 2016-11-09-titre.md

 post.date / post.title


 Utiliser les boucles pour afficher les articles.


 Dans index.html :

 {% for post in site.posts %}
  < h3>{{post.title}}</h3 >
  < p>{{post.content}}</p >
  < a href="{{post.url}}">Lire l'article seul</a >
 {% endfor %}


 Cette boucle utilise des méthodes communes à plusiers CMS, pour afficher ke titre, l'url, le contenu, le résumé...

 -> Placer la boucle dans la page avec l'article.
