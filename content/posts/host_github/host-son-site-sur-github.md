+++
author = "Alex"
title = '🌐 Héberger son site gratuitement sur GitHub'
date = 2024-05-22T15:28:18+02:00
draft = true
description = "Il est possible d'héberger son site web sur Github gratuitement, voici comment le faire."
tags = [
    "github", "website"
]
categories = [
    "Web",
]
aliases = ["posts"]
+++

Vous avez un site web et vous souahitez le publier et montrer au monde vos travaux, cependant vous n'avez pas ou très peu d'argent.

Il existe une solution pour héberger votre site web gratuitement avec GitHub, c'est ce que nous allons apprendre à faire dans ce tutoriel.

<!--more-->

## Mise en place du repository
Dans un premier temps, rendez vous sur Github et et au niveau de votre photo de profil, cliquer sur le + et créez un nouveau repo.

![new-repo](/posts/host-github/new-repo.png)

Une nouvelle page appareit ensuite, votre repo doit avoir le nom *username*.github.io, faite également en sorte qu'il soit *public*. Vous pouvez donner une description à votre repository, mais ça n'est pas obligatoire.

![name-repo](/posts/host-github/name-repo.png)

À présent, il faut push votre dossier sur lequel vous avez durement travaillé. 

## Mise en ligne du site

Une fois votre repo créé et vos fichier uploadés, il est temps de publier votre site.

Dans les paramètres, rendez vous dans la partie *pages*.

![pages-github](/posts/host-github/settings-repo.png)

Dans la partie **Build and deployment** sélectionnez la *Source*, qui est: 

- soit *GitHub Actions* 
- soit *Deploy from a branch*

À vous de sélectionner le bon en fonction de votre configuration, mais dans la majorité des cas ça sera la la deuxième option.

Sélectionnez également la *Branch* de votre repo et sauvegardez. Dans quelques instant un message vous disant que votre site est publié devrait apparaitre.

![site-published](/posts/host-github/site_published.png)

Et voilà ! Votre site est publié ! Vous pouvez le partager au monde entier !


## Nom de domaine personnalisé

Votre site est publié c'est très chouette, mais vous n'êtes pas très satisfait du nom de domaine par défault donné par GitHub. Pas de panique vous pouvez le changer, et ceci très facilement !
Moyennant l'achat du nom de domaine vous pourrez rediriger 