---
layout: post
date: '2015-07-22 12:57'
title: Des pixels et du code
backgrounds: none
thumb: ../img/2015/06/17/doc.png
show_tags: false
show_categories: false
excerpt: "Récemment, j'ai développé quelques projets (du code!),  que je stocke sur mon compte Github. Certains sont orientés photo, d'autres non, mais tous ont été fait dans le but de répondre à un besoin, en général d'automatisation, de publication. Il sont aussi fait pour être partagés!"
tags: 'code, geek, projets, carto'
author: Jonathan
---

Récemment, j'ai développé quelques projets (du code!),  que je stocke sur mon compte [Github](https://github.com/jonathanlurie/). Certains sont orientés photo, d'autres non, mais tous ont été fait dans le but de répondre à un besoin, en général d'automatisation, de publication, etc.
Tous ces projets sont open-sources et ne demandent qu'à être réutilisés, modifiés, partagés!  

Voilà la liste du plus récent au plus ancien:

* TOC
{:toc}

# Duskr
Le tout dernier! J'ai même un log o pour celui-ci:

<img src="https://www.dropbox.com/s/hvcd3okmhla5daq/logo-apha.png?dl=0&raw=1" alt="Mountain View" style="width:200px">

Il permet de générer automatiquement des développements de photos *raw* pour faire des timelapses. Il est utile dans le cas où la lumière est variante (coucher de soleil). Avec **Duskr** on ne paramètre que la première et la dernière image du timelapse, et il interpole le reste.

Au début, je pensais faire un projet entièrement *open source*, et puis avec le nombre d'heure passées dessus, l'envie de faire quelque chose de clean, j'ai finalement décidé de bien l'aboutir et de faire une version payante, en dessous de 10€. Toutefois, certaines bibliothèques que j'ai développé pour l'occasion seront, elles, *open source*.  

#DropImage
C'est un projet qui vous permet d'utiliser votre [Dropbox](www.dropbox.com) pour poster des images simplement et obtenir un lien pour les partager. Le but est d'économiser tous les clics nécessaires pour partager une image qui se trouve sur son ordi. Personnellement je m'en sers pour uploader les images que j'utilise dans mon journal en ligne ou dans ma documentation Github.

[Voir le projet.](https://github.com/jonathanlurie/dropImage)

# Arte+1000
Un petit site web fait sur un coin de table pour télécharger les vidéos du site [Arte+7](http://www.arte.tv/guide/fr/plus7). Il suffit de rentrer l'URL de l'emmission dans le champ, et on accède aux différentes versions : résolution, langue, qualité d'image...
Pour télécharger une vidéo : clic droit, enregistrer la cible sous.  
On peut aussi simplement regarder la vidéo en streaming, utile depuis l'étranger!

[Voir le site.](http://stuff.jonathanlurie.fr/arte+1000/)

# BLANK_PY
C'est un micro-framework qui sert de base à (presque) toutes mes applications *console*  en Python. Les applications faites avec *BLANK_PY* s'exécutent avec un simple double clic et possèdent un fichier de configuration. Rien de fancy mais ça évite de partir de zéro pour chaque nouveau projet. L'avantage d'utiliser cette base est d'avoir un fonctionnement uniforme à tous mes projets.  

[Voir le projet.](https://github.com/jonathanlurie/BLANK_PY)

# MapboxDownloader
Vous connaissez [Mapbox Studio](https://www.mapbox.com/mapbox-studio/)? C'est un logiciel créé par [Mapbox](https://www.mapbox.com/), une société basée à San Francisco qui se concentre sur la cartographie et le design. L'idée derrière Mapbox Studio est de créer des cartes avec des designs sympa, paramétrables à souhait! Ce logiciel est vraiment complet mais ne permet pas d'exporter des zones **TRÈS** larges à **TRÈS** haute définition.  
Dans le but de faire des affiches contenant des cartes géographiques de grande précision, j'ai développé *MapboxDownloader*. Il télécharge les données par petits morceaux pour tous les assembler ensuite en une carte gigantesque!

Vous pouvez voir un de mes projets d'affiches sur ma [boutique Etsy](https://www.etsy.com/fr/listing/207605214/manhattan-new-york-black-and-white?ref=shop_home_active_1).

[Voir le projet.](https://github.com/jonathanlurie/MapboxDownloader)

# The Map Crafter

Il s'agit d'un boutique Etsy, que j'ai créé pour vendre des affiches représentant des cartes géographiques. Ces cartes sont conçus par mes soins, sur mon temps libre (y'en a bien qui peignent des figurines...). Je choisis les données à afficher sur la carte, je décide du design et je la fais imprimer. J'utilise [MapboxStudio](https://www.mapbox.com/mapbox-studio/) pour la partie technique, qui lui-même utilise les données D'[OpenStreetMap](http://www.openstreetmap.org/).  
Pour l'instant j'ai conçu l'affiche de New York et l'affiche de Paris est bientôt prête.

[Visiter la boutique Etsy.](https://www.etsy.com/fr/listing/207605214/manhattan-new-york-black-and-white?ref=shop_home_active_1)

# ImageMarkdown
Mon [blog photo](www.jonathanlurie.fr) utilise un kit [Wordpress](https://wordpress.org/). C'est facile à utiliser, c'est complet et bien customisable. Quand il s'agit de publier des photos par contre, c'est vraiment nul. L'éditeur d'article mélange tout, aligne les photos n'importe comment, crée des marges... Il m'est arrivé de passer une bonne heure juste pour aligner les photos pour que ce soit propre et simple.
Puis, j'ai découvert le [Markdown](http://fr.wikipedia.org/wiki/Markdown). Brièvement, c'est une syntaxe d'écriture qui permet de faire de la mise en page de manière très simple (bien plus simple qu'avec *LateX*), juste en utilisant des symboles du claviers. C'est ce qui est utilisé pour écrire sur Wikipédia, Github et la plupart des forums modernes.  J'ai donc installé le plugin Wordpress WP-Markdown, qui me permet d'écrire des articles en *Mardown* plutôt que d'utiliser l'éditeur tout naz par défaut.  
Ensuite, j'ai codé *ImageMardown* pour générer une base d'article contenant déjà les photos bien mises en page ainsi que les informations EXIF. Ce qui me prenait parfois 1h avant, me prend une vingtaine de secondes maintenant.

[Voir le projet.](https://github.com/jonathanlurie/ImageMarkdown)

# MidiCombo
Ce projet est mon plus important en terme de temps passé. Il est fonctionnel mais n'est pas finalisé. Disons que c'est encore expérimental.
*MidiCombo* permet de brancher un clavier *midi* en usb et de s'en servir pour simuler des raccourcis clavier, ou des sequences de frappes de touches (nuance subtile). Je me sers du clavier [Akai LPK25](http://www.akaipro.com/product/lpk25) car il fait la largeur d'un laptop 13" et qu'il n'est pas cher. De plus il possède un bouton pour changer d'octave, en rendant ansi 10 accessibles, soit 120 notes (=120 raccourcis claviers).  

Je m'en sers à chaque fois que je dois trier ou traiter des photos avec *Adobe Ligntroom* car ça me permet d'accéder facilement à des fonctionnalités qui nécessitent normalement des raccourcis clavier de 3 ou 4 touches.

Je vais bientôt procéder à un refactoring de ce projet pour le rendre plus clean et simplifier les dépendances. Il n'utilise pas encore le modèle de BLANK_PI car il a été fait avant...

[Voir le projet.](https://github.com/jonathanlurie/MidiCombo)

# et sinon...
L'idée est de fournir des outils qui simplifient les choses. Si c'est pour se retrouver avec un logiciel impossible à faire fonctionner, c'est pas la peine.  
La philo qu'il y a derrière est la suivante :
> **Le plus difficile en programmation est de rendre les choses simples et accessibles.**  
Si l'utilisateur galère, c'est que le développeur n'a pas terminé son travail. Inversement, si l'utilisation est simple, c'est que le développeur a pensé aux cas particuliers et à l'ergonomie.

Même s'il s'agit d'applications *console* (c.a.d. moches), j'ai tenté de respecter cette philo le plus possible.

Tshuss!
