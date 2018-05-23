# Redis

## Journée typique à Redislabs
Ce bureau est surtout un bureau "marketing / ventes", la R&D est en Israël, l'entreprise a été fondée à Tel Aviv.
Les créateurs de l'entreprise ne sont pas ceux qui ont créé Redis (Salvatore, le créateur, est sicilien, et est venu dans l'entreprise après sa création).

Les horaires dans la vallée vont en général de 9h à 18h/19h, et les entreprises payent le petit déjeuner.
Pas mal des grosses entreprises ont adopté le pair programming, notamment parce qu'elles emploient des gens avec une famille et que ça permet de borner les horaires.

Il y a énormément de meetups, et quasiment tout le monde en organise. Il y a toujours quelque chose à faire du point de vue technique.

Il y a assez peu de remote, la plupart des gens viennent au bureau. C'est important car l'entreprise grandit très vite et Dave sent le besoin d'être au contact de ses collègues.

## Process de recrutement
Le process est assez recrutement en fonction du profil recherché. Certains types de rôles sont très durs à recruter : la qualité des équipes qui constituent une start-up a un très gros impact sur la façon dont la start-up est valorisée. Du coup les profils haut niveau sont très chassés, très durs à rencontrer.
Le process peuvent aussi être assez longs, notamment pour les profils les moins expérimentés car il faut se rassurer sur leurs compétences.

Il y a une très bonne ambiance chez Redislabs, ça donne envie de rester. Dave a travaillé chez Intel, où il y a encore les "cubes" de travail, et on est très isolé finalement.
De plus l'entreprise n'est pas très grosse, et du coup il n'y a pas de lourdeurs, de besoins de passer plein de temps sur du reporting.

Lors d'un départ, le préavis moyen est de 2 semaines. Quand c'est l'entreprise qui licencie, ça peut aller jusqu'à un mois si ça se passe bien.

Il y a des gens qui passent de job en job pour rester dans des entreprises en grosse croissance (et qui en profitent pour trouver beaucoup d'argent).

## Evolution du produit
Le rôle de Dave est de demander des nouvelles fonctionnalités. C'est un travail assez frustrant parce qu'il voudrait mettre beaucoup de fonctionnalités, mais il faut être capable de prioriser sur des petites itérations qui vont rapporter des parts de marché, sur des fonctionnalités qui ont du sens pour les clients.
Les entreprises "publiques" (en bourse) ont tendance à se focaliser sur les rapports trimestriels.
La priorisation dépend aussi des développeurs avec lesquels on travaille. Certains sont assez "prédictibles" en terme de temps qu'ils passent sur leurs tâches, d'autres sont plus créatifs mais moins prédictibles.

Redislabs utilise des sprints de 2 semaines, en méthodologie agile (mais Dave ne connait pas super bien la méthodo de dev).

## Trends
### Redis trends
 - Redis a un système de modules qui permet d'étendre les structures de données stockées, et pas mal de nouveautés arrivent à travers ça (par exemple un module de recherche).
 - Il y a un système de streaming qui arrive bientôt également.
 - Le système de stockage va aussi évoluer vers un système hybride avec les indexs en mémoire et du stockage des structures de données sur de la mémoire flash.
 - Hyperlog log : un système probabiliste basé sur de la manipulation de bits, qui permet de travailler avec 12 bits clés et d'obtenir des nombres d'occurence d'une donnée (????)
 - Redis comme un cache partagé distribué 

### Generic trends
 - Le Cloud Native est un vrai mouvement de fond
 - Les micro-services deviennent un standard de fait
 - Google Cloud va continer à progresser et à gagner des parts de marché
 - OpenShift se positionne très bien, notamment dans les grandes entreprises
 - Kubernetes est une énorme vague de fond, et devient le "Linux du Cloud". Avec Kubernetes, toute la notion de service mesh.

### Effet wahou
Wardly map (?) : a map of your competitors and their products => allez voir les vidéos.
Il est très très bon dans le fait de deviner les prochains "trends".
Il dit que Serverless est une grosse vague de fond, que ceux qui vont l'utiliser vont se différencier.
A regarder : serverless application repository => une marketplace d'applications serverless.

Est-ce que Redis fera du serverless dans le futur ? Probablement, mais ce sera assez différent de ce qu'on connait aujourd'hui de Redis. L'idée serait sans doute de suivre le modèle de Firebase.

## Redis UNiversity
Le but est de former un maximum de monde à Redis.
Premier lancement de cours le 5 juin. C'est une université en ligne (gratuite).

hydra : framework pour des micro services basé sur Redis, Docker, NodeJS