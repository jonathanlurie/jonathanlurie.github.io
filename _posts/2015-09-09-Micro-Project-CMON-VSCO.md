---
layout : post
date : 2015-09-09
title : C'MON-VSCO!
thumb : https://im.vsco.co/1/52cacb4939dc8257393/55e66cd32b331e193e8b456d/3db54071-8336-40d4-8265-3cb332feca66.jpg
backgrounds : https://im.vsco.co/1/52cacb4939dc8257393/55e66dbe49331e7d728b456e/634dba59-60d5-4110-a7b2-f15b31d641fa.jpg
show_tags : false
show_categories : false
excerpt : "Enfin, on peut récupérer facilement les images de VSCO!"
author : "Jonathan"
---

Un nouveau *micro-projet* vient d'arriver sur mon espace [Github](https://github.com/jonathanlurie/cmonvsco), ça s'appelle *C'mon, VSCO!* et on peut le tester [ici](http://stuff.jonathanlurie.fr/cmonvsco/)!  

## À quoi ça sert?
Vous connaissez la plateforme de partage d'images [VSCO](vsco.co)? Elle va de paire avec l'excellente appli de filtre photo [VSCO-CAM](http://vsco.co/vscocam) dispo sur Android et iPhone.  

Pour l'utilisation que j'en fais, le site de partage d'image à une grosse faiblesse (voulue) : on ne peux pas y récupérer les images ou même en obtenir les liens, même pour ces propres images qu'on a pris avec son smartphone! **C'mon, VSCO!**  sert à contourner cette limitation et permettre de récupérer les images sans devoir naviguer dans le code source du site!  

## Pourquoi je voudrais faire ça?

Admettons que je veuille utiliser une de mes photos prise avec VSCO dans un article de blog, ou que je veuille la mettre en fond d'écran. L'appli VSCO permet bien d'exporter la photo, mais il faut ensuite la récupérer dans la mémoire du téléphone, se l'envoyer par mail ou la ranger dans un dossier de sa *Dropbox*... Tout ça pour finalement la poster sur le web alors qu'elle est déjà hébergée par VSCO, un peu fastidieux!  

## Comment ça marche?

Depuis le mini-site  [*C'mon, VSCO!*](http://stuff.jonathanlurie.fr/cmonvsco/), il suffit de mettre le lien de la page où se trouve la photo qu'on veut récupérer. Par exemple, si on va sur [ma page VSCO](http://jonathanlurie.vsco.co/) et qu'on clique sur la première photo, on aura une URL comme ça :

```
http://jonathanlurie.vsco.co/media/55ecdb4326331e967e8b4575
```

On copie cette adresse dans *C'mon, VSCO!*  et on appuie sur *Entrer* :
![](../img/2015/09/09/cmonvsco.png)

Ensuite, l'image s'affiche, ainsi que son lien!  

## Comment ça marche?

Rien de vraiment compliqué, le code source du mini-site est disponible en open-source (Licence MIT) et hébergé sur [Github](https://github.com/jonathanlurie/cmonvsco). Ça tient dans deux fichiers *php* de 50 lignes chacun, en-tête comprise!


