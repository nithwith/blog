+++
categories = ["Numérique"]
date = 2019-09-19T22:10:00Z
description = ""
draft = false
image = "https://blog.theomarty.fr/content/images/2020/01/DSC_0595-min.jpg"
slug = "le-nas-un-premier-pas-vers-lemancipation-des-gafam"
tags = ["Numérique"]
title = "Le NAS :  un premier pas vers l'émancipation des Gafam"

+++


Salut, aujourd'hui je vous partage une expérience que je mène depuis six mois maintenant avec un petit outil bien pratique : le NAS.

Pour bien commencer qu'est qu'un NAS ?  Derrière ce nom un peu barbare se cache un petit ordinateur tout mignon. Un NAS (Network Attached Storage) est un serveur de fichiers autonomes. Il est relié au réseau qui permet de stocker des données en un volume centralisé pour des clients hétérogènes.

Ce qui m'amène à la seconde question, pourquoi un NAS ? Pour répondre à  cette question, il faut placer le décor dans lequel il s'intègre.

## Le constat

Depuis une dizaine années, les GAFAM, (Google, Amazon, Facebook, Apple, Microsoft) des entreprises à la croissance fulgurante ont accaparé les données que nous produisons en surfant sur internet afin de les revendre à des annonceurs.

> "Si c'est gratuit c'est que c'est vous le produit". Bruce Willis

Aujourd'hui, ces entreprises disposent d'énormes quantités de données personnelles (en particulier Google et Facebook). Ces données sont vos habitudes d'achat, les photos de vos dernières vacances ou la position GPS de  votre smartphone Android.

[Voici l'historique de vos positions ... Merci Google !    ;)](https://www.google.fr/maps/timeline?pb)

Face à la montée en puissance exponentielle de ces acteurs, quelques organisations militantes ont décidé de proposer des services alternatifs.

C'est le cas notamment de Framasoft qui propose des services analogues à ceux de Google mais sans intervenir dans votre vie privée. On peut noter aussi le réseau social Mastodon qui veut se substituer à Facebook. Ces services sont proposés dans le cadre de l'open-source (c'est à dire des logiciels dont le code est disponible gratuitement sur internet).

 <a href="https://blog.theomarty.fr/le-nas-un-premier-pas-vers-lemancipation-des-gafam/framasoft.org">framasoft.org</a>" >

## Le choix

Alarmé par l’étendue  des données que stockent et revendent les GAFAM,  je me suis mis en tête depuis plusieurs années de me détacher de cet écosystème numérique toxique. Ceci dans l'objectif de garder une "souveraineté" sur mes données .

J'ai décidé de commencer par le service que j'utilise le plus : Google drive. Ce service propose un stockage de fichier en ligne (15Go en version gratuite) et une suite bureautique pour éditer ses documents. Durant mes études j'ai beaucoup utilisé ce service car équipé de Linux (alternative open-source de Windows), je n'avais pas de bonne suite bureautique à disposition.

Pour remplacer Google drive, je suis allé voir dans un premier temps du coté de Framasoft qui ne propose pas de solution de stockage car trop coûteux à mettre en place de leur coté pour proposer le service gratuitement.

Si personne ne veux me donner un serveur, alors je vais créer le mien ! :) C'est ce que j'ai fait  avec mon NAS.

J'ai acheté un NAS (petite boite, contenant des disques durs ) qui me permet de me créer un espace de numérique en ligne. Plus exactement le NAS DS218J de Synology équipé de deux disques durs  de 2To.

Mon NAS propose les services suivants  :

• Stockage de fichier (remplace Google Drive)• Sauvegarde des photos de mon téléphone (remplace Google Photos)• Gestionnaire de notes (remplace Google Keep)• Media center (remplace Spotify)

Tant de choses dans une si petite boite ....

## Google Drive vs NAS



**Le coût**

A coté de la protection de mes données personnelles, il y a aussi un argument économique au choix du NAS.

Les données dont je disposai sur Google drive étaient à la limite de l'offre gratuite (15Go) et je voulais y centraliser mes films (+900Go)  et mes photos (+300Go). Après une rapide recherche, je me suis aperçu que si je voulais stocker ces données sur Google drive, il me faudrait souscrire un abonnement de  9,99euros/mois pour disposer de 2To de stockage.

J'ai comparé le coût de cet abonnement au coût de l'amortissement d'un NAS sur 4 ans

|  Google Drive |  NAS |
|---|---|
| Abonnement : 9.99e/mois  | Achat NAS : 100e + Achat 2 To Stockage : 150e + 4 ans d'électricité (4W) : 15e = 5 euros/mois |
| 9.99e/mois | 5 euros/mois |

Au niveau financier, le NAS est gagnant sur le long terme  ! Youhou !

**Le débit**

Maintenant qu'en est-il de la qualité de service ? C'est là que ça pêche malheureusement pour le NAS.

Son principal défaut est que contrairement aux serveurs de Google, il est relié à internet par ma box ce qu'il limite son débit. Comme je dispose d'un accès ADSL, la vitesse de lecture sur mon NAS est vraiment moyenne à distance (très gênant pour consulter des photos hors de son réseau domestique). Ce problème serait en partie  réglé si j'avais la fibre à mon domicile ce qui augmenterait le débit du NAS de manière significative.

Bref, pour que la NAS soit vraiment exploité il faut le connecter avec de la fibre (même s’il il reste utilisable en ADSL).

**La perte de données**

La grande force de Google est de disposer d'énormes data center aux 4 coins du monde associés à des technologies avancées de sauvegarde de données. En effet, la data est son fond de commerce, donc Google y fait très attention. Il y a très peu de chance que vos données soient perdues. Coté NAS, la perte de données est gérée par une réplication des données sur deux disques durs.  En effet, j'ai indiqué  plus haut que j'ai équipé mon NAS de deux disques durs de 2To et je n'ai que 2To de stockage car le stockage est répliqué entre les deux disques  durs . Si un des disques lâche, Je l'enlève, en remets  un autre à la place et la réplication se refait automatiquement. Je ne risque pas de perte de données.

{{< figure src="https://blog.theomarty.fr/content/images/2020/01/S-lection_102.png" caption="Interface d'analyse de la santé des disques de stockage" >}}



## Retour d'expérience après 6 mois d'utilisation



**Avantages**
- Facilité de mise en place
- Sécurité des données
- Synology Moment (synchronisation photos)
- Écosystème d'application mobile complet et performante
- Service Client au top
-  Coût

**Inconvénients**
-   Accès aux données long (NAS connecté en ADSL)
-   Certaines applications mobiles mal pensées  (media center)
-   Système dépendant d'une entreprise privée (Synology)



Le retour après 4 mois d'utilisation est positif. Dans un premier temps, l'objectif premier est atteint : je me suis débarrassé de plusieurs services Google (Drive, Keep, Photo).

De plus, j'ai pu centraliser et sécuriser toutes les données qui traînaient sur les disques durs de la famille (films, photos sur une dizaine d'années, documents importants, etc).

J'ai été surpris par la qualité de l'écosystème mis en place par Synology. Par exemple le service de synchronisation photo NAS <> smartphone (Copie conforme de Google Photo) qui marche très bien.

Malgré  tout, l'accès aux données hors du réseaux domestique reste très limité avec mon accès ADSL. Relier son NAS à la fibre est obligatoire pour l'exploiter a son maximum.

