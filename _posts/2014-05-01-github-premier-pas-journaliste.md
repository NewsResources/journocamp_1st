---
title: Premier pas sur GitHub
layout: post
date: 2014-05-01 18:45:16
categories: jekyll testing
---

#### Initiateur / Animateur : [Tom Wersinger](https://github.com/tomplays)
#### Rapporteur : [Florent Maurin](http://florentmaurin.com/)
##### Editeur : [Cédric Motte](https:twitter.com/chouing)


GitHub - [site officiel](https://github.com/) ? Git est un système qui vient de Linux, (créé pendant le processus de développement du Kernel).

**Principe : faire du contrôle de version sur des fichiers** afin de garder un historique complet, la plupart du temps sur des fichiers textes, mais ça marche pour n’importe quel fichier, jusqu’à des objets en 3D (prévisu dans GitHub directement).

![Tom Wersinger présente GitHub au #journocamp]({{ site.baseurl }}/images/github_tom_wersinger_journaliste_journocamp.jpg)


Aujourd’hui, 10 millions de codes sont déposés sur GitHub.
De plus, GitHub propose maintenant des features de type réseaux sociaux : on suit les gens avec qui on a bossé, etc. Mais c’est + « sérieux » que sur Twitter.
GitHub propose même des groupes selon les centres d’intérêt.

L’intérêt est qu’à tout moment dans le processus de développement, on peut créer des branches, qui dérivent d’une branche « officielle ».
Par ex : sur des sites, une nouvelle version est développée sur une branche, puis remise sur le « master » une fois que la version est OK.

 
### Comment ça marche ?
 
On installe Git sur un serveur, et de là, chaque utilisateur peut travailler sur son code et le synchroniser avec le serveur (par défaut, on peut utiliser le serveur de GitHub).
Un « repo » (repository) est un morceau de code.
Sur GitHub, on déclare un nouveau « repo », et github nous attribue une adresse correspondante.

Ensuite, il faut installer un client sur son ordi, et on peut travailler en local.
Une fois qu’on veut ajouter, on tape la commande « Git add » -> on ajoute à une file d’attente. Puis une fois qu’on a tous les fichiers qu’on veut, on les rassemble pour les mettre en ligne avec la commande « Git commit ».
**Dans un commit, il vaut mieux ne pas faire trop de modifications, sinon ça perd tout son intérêt : le but est de pouvoir suivre pas à pas les modifications, comme ça si ça merde, on sait où.**

Troisième commande : « git push » -> on envoie les données de la machine locale sur le serveur (upload).

Sinon, « git pull » pour récupérer les fichiers. « Request » pour travailler en parallèle sur le code d’un inconnu.
 
Pour utiliser GitHub, il suffit d’installer un client. Ce qui est complexe, c’est de s’y retrouver ensuite.

Une fois qu’on a modifié un fichier, on tape git status, et Git nous donne la différence entre le master sur le serveur et ma copie en local.
 
Si on modifie le code de qqn d’autre, la personne décide de l’accepter ou de le refuser.

### Fun facts !
GitHub est open source, ça veut dire que le code même de GitHub est disponible sur GitHub (paie ta mise en abîme !)
 
GitHub est payant si tu as du code fermé. Tant que tu travailles en open source, pas de souci, jusqu’à 1 go de code, et 100 mo en upload unique. Il existe un “clône” de GitHub, qui est gratuit pour tous les usages : [Bit Bucket](https://bitbucket.org/)
 
Git est très utile pour Node.js, car tous les modules qui composent Node.js sont mis à jour.
 

Selon les best practices de GitHub, quand tu crées un “repo”, tu dois mettre un readme et il vaut mieux dire sous quelle licence tu crées ton projet. Les gens sur GitHub sont bien élevés ;-)
 
Sur la page de chaque “repo” est indiqué le nombre de fois où il est copié : s’il l’est beaucoup, c’est que le code est bon/intéressant.

Il suffit de récupérer l’URL d’un projet, d’ouvrir une console et de taper « git clone + url » pour copier tous les fichiers de ce projet dans son ordi, et commencer à bosser.
 
Des utilisateurs de GitHub :

Parmi les membres de la communauté  
* [Tom Wersinger](https://github.com/tomplays), qui est donc l'initiateur de cet atelier  
* [Newsresources, maintenu par Cédric Motte](https://github.com/newsresources), avec surtout ce site hébergé sur github,  
* [j++, le réseau développé par Nicolas Kayser-Bril et Pierre Romera (entre autres)](https://github.com/jplusplus)  
* [Jean Abbiateci](https://github.com/JeanAbbiateci)  

Et plus largement  
[le Guardian](https://github.com/guardian),  
[le NY Times](https://github.com/nytimes),  
[La maison Blanche](https://github.com/whitehouse)  
[Open knowledge foundation](https://github.com/okfn)  
[Pro Publica](https://github.com/propublica)  
La librairie responsive du Boston Globe  
…
 
Pourquoi utiliser GitHub ? Surtout si ce n’est pas pour du code ? 
-> décentralisation, ouverture de la création
-> facilité de suivre quelle est la “vraie” version d’un travail, et ses modifications...
-> documentation, propreté du code, facilité pour quelqu’un d’autre de reprendre le projet.
-> c’était antérieur aux services genre Dropbox.
-> on peut se faire son propre serveur.

Il y a tout une communauté, et des analytics, pour repérer les mouvements intéressants sur Git, et donc les projets sur lesquels il peut être intéressant de se pencher quand on veut apprendre.

**Pour aller plus loin**

Système de gists : des fichiers volants avec des bouts de code, pour pouvoir poser des questions rapide et coder des réponses tout aussi rapidement.

[Prose.io](http://prose.io/) : éditeur de fichier directement en ligne. Il met à jour directement en ligne.

[Jekyll](jekyllrb.com/) : système de blogging, qui fait des fichiers statiques html. Du coup on peut créer un blog sans base de données, complètement statique.





-------------
