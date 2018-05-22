# JFrog

## Personnes recontrées
Raj Panchapakesan - Senior Director Biz Dev
Le resp de l'équipe d'ingenierie de solution
Le resp du solution dev

## Possibilités de partenariat
Zenika explique sa façon de travailler (pas de partenariat exclusif, consulting et création de plateformes de delivery. 
Concernant les formations "officielles", elles sont aujourd'hui données directement par les équipes JFrog, et font partie d'un package lié à la vente de licence.

## Presentation de l'offre JFrog
JFrog a 10 ans, et évolue vers le fait de ne plus être une "single product company". 
Taille : ~300 personnes. Près de 5000 clients payants.

Concept de "liquid software update process" => pour un processus de delivery fluide, il faut du logiciel "liquide".

Dernières annonces de JFrog : outil de distribution de logiciel. 
 - JFrog distribution : les fonctionnalités de la partie SaaS (Bintray) accessibles en mode on premise
 - Ajout dans Mission Control d'un dashboard de delivery
 - Ajout d'un mode distribué

XRay : outil d'analyse des dépendances, et de scan de vulnérabilités. Permet aussi de valider la compliance au niveau des licences utilisées.

## Hot trends : 
Conteneurisation, passage vers Kubernetes

## Comment le logiciel est construit à JFrog : 
Passé d'un produit monolithique en Java à un ensemble de produits dévelopés dans différents languages de dev, dans une architecture micro-services.
Passage également à un mode SaaS en complément du logiciel en mode "boite".
Nous avons nous-même eu les challenges que nous cherchons à résoudre pour nos clients.
"Aujoud'hui on pourrait faire du continuous delivery, mais nous ne le faisons pas parce que nos clients n'ont pas ce besoin."

Historiquement, une release hebdomadaire, avec un Go/No Go pour rendre la release publique.
En interne, l'IC utilisée est Jenkins, et bien sûr les produits JFrog sont utilisés "Eat your own food".

L'architecture en micro-services était parfois compliquée à déployer pour nos clients, nous avons donc développé un service d'installation.

Travail important avec les différents partenaires qui packagent des offres Kubernetes pour intégrer Artifactory.

Une tendance (poussée par Google) : unifier la représentation des meta-datas associées aux artefacts. Jfrog travaille avec Google sur ce sujet.
JFrog pense que Helm est un très bon outil pour le déploiement de ses produits.

## Journée typique à JFrog
Il y a des stand ups, plutôt l'après-midi.
Il y a aussi des stands ups avec la communauté et les partenaires, avec comme pré-requis d'avoir un ordre du jour clair (sinon le stand up est annulé)
Les sprints de dev durent 3 semaines.
Le role du service "solutions" est d'étendre le produit, d'ajouter des fonctionnalités : d'abord comprendre le problème que le client, et chercher à combler.
Travailler avec une communauté Open Source nécessite aussi de manager cette communauté, d'être au contact fort pour récupérer les attentes.
Il y a des ateliers de brainstorm en mode "quadrant" pour déceler de nouvelles possibles fonctionnalités avec les développeurs, à chaque début de trimestre.

## "The next big thing"
