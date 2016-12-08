

# Initiation à github et au markdown

### Mardown
-> langage de balise léger pour des fichiers clairs et lisibles, présentation aérée, pratique pour des fichiers d'explication tels que les fichiers **readme.md**
=> Flatfiles, des fichiers plats, uniquement du texte

---

## Commandes linux :
* cd -> se déplacer dans l'architecture
* pwd -> savoir où on est
* ls, ls -l, ls -al... -> permet de voir les fichiers présents dans le dossier courant
* touch -> créer un fichier

---

## Définition Github
C'est un système d'hébergement web qui fonctionne sur le principe du versioning, qui permet de mettre à jour son projet et pouvoir retourner à n'importe quel moment à une version antérieur. Il est aussi possible de travailler sur une branche autre afin de pas impacter la branche principal lorsque l'on travaille en groupe par exemple.
Les projets sur github sont la plupart du temps accessible à tous, mais ils peuvent être privés. Il est aussi possible de travailler avec des collaborateurs.

Github dispose d'une interface en ligne qui permet le dépôt de fichier mais aussi l'édition en ligne. L'autre solution est de travailler en local et d'envoyer régulièrement son travail en ligne. On appelle ça le **commit**, en actualisant son fichier, on ajoute ensuite un commentaire pour faire savoir à son groupe ou sois-même ce qui a été modifié.

---

## Démarche à suivre

### Première utilisation

Création du compte en ligne.

Création du dossier flatfiles qui contient l'ensemble des projets du cours de CMS.

Installation de github sur un linux sur machine virtuel.

Commande **git clone http://lelien.com**, permet de clonner l'architecture du compte github pour travailler en locale.

Commande **git config ** pour configurer le compte.

### Autres utilisation

_git pull_ -> permet de récupérer la version la plus à jour du projet.

** /!\ Il faut toujours récupérer la version la plus à jour du projet avant de commancer à travailler pour éviter les conflits**.

_En cas de conflit, github ajoutera les lignes de codes conflictuelles en commentaire, il faut alors les modifier sur l'interface en ligne._

_git init_ -> dit à Github de se concenter sur le dossier.

_git status_ -> permet de voir l'état des fichiers, s'ils doivent être envoyé en ligne ou non.

_git add "nomfichier" / git add *_ -> permet d'ajouter les fichiers dans la liste d'attente pour l'envoie.

_git commit -m "le message"_ -> permet de préparer le commit et d'y ajouter un messgae.

_git push_ -> dernière étape qui permet d'envoyer les fichiers en ligne.

### Commandes suplémentaires

_git branch_ -> permet de créer une nouvelle branche pour travailler dessus sans risque.

_git merde_ -> permet de fusionner les branches.

_git checkout_ -> permet de basculer entre les branches.

_git remote_ -> permet de supprimer une branche.

Devoir sur les tumblr, création d'un fichier config.md avec titre, description, baseline, mots clés, polices, couleurs, url. Intégration d'un favicon et d'une bannière dans les options de template du tumblr.
