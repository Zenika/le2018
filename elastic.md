# Visite Elastic

## Les visas
Christoph nous explique qu'il va retourner travailler à Berlin. Point d'étonnement de notre côté (quitter la vallée ?)
Explication : il est compliqué d'obtenir des visas de travail aux States. Et une fois qu'on en a obtenu un, il est très compliqué de changer de job, même dans la même société.
Christoph veut repasser côté ingenierie, et c'est plus simple pour lui de le faire en retournant travailler à Berlin (et sa femme est à Berlin).

## Entreprise distribuée
Mouvement de fond : Elastic est une "ditributed company" par ADN. Ce sont les contributeurs Open Source d'origine qui ont été les premiers employés, et cette culture a perduré.
Ça permet d'employer les bonnes personnes
Utilisation de Slack, de Github (utilisation des `issues` pour la prise de décision/les discussions). 
Conséquence : parfois la prise de décision est un peu plus longue, car il faut s'assurer que les contributeurs des différentes timezone aient pu participer à la discussion.
Environ 200 personnes travaillent au siège, mais c'est très mouvant, et il n'y a pas d'obligation d'être présent sur le lieu de travail.
Utilisation de Zoom pour les meetings en conf call. Il y a des channels "always on" qui permettent aux gens de se rencontrer quand ils sont en remote.

## Entreprise "Open"
La communication est faite sur un Github public => tout le monde peut participer, y compris des personnes exterieures à Elastic. Un des gros intérêts est d'avoir un feedback très rapide de la communauté des utilisateurs, de pouvoir très rapidement s'adapter aux réactions des utilisateurs => permet de faire beaucoup de "try & learn" ("Do not ask for permission, ask for forgiveness"). Cela implique aussi une exigence de qualité importante, car tout le monde peut voir les décisions / le code / les issues / ...
Les ingénieurs ont un "community duty day" : ils doivent passer du temps avec les utilisateurs, à traiter leurs demandes.

## Pourquoi publier les sources de xPack ?
C'est une décision presque dogmatique : "si nous pouvions, nous publierions tout en Open Source, malheureusement le business ne fonctionne pas comme ça".
Mais publier le code permet de créer de la confiance. C'est également meilleur pour la transparence et pour la communication avec la communauté.
La question qui s'est posée : est-ce que ça va être mauvais pour le business ? Dans les faits les gens qui payent une licence le font de toute façon, et ceux qui pourraient "pirater" le code n'auraient de toute façon pas payé.

## Recrutement et vie de l'entreprise
Passage rapide de 200 à 1000 personnes. Recrutement de 50 personnes par mois, énorme croissance. 
Comment ne pas perdre la culture dans une croissance importante ? Le CEO met beaucoup d'efforts dans le fait de conserver cette culture, de donner la vision. 
Le niveau d'ouverture et de transparence permet aux gens de se sentir "chez eux", et de partager la culture par le partage de l'information.
Quelques points importants : 
 * Faire se recontrer les gens en physique
 * Avoir de la socialisation "face to face"
 * Le fait de "répondre à tous" est encouragé

Dans le cas d'acquisition d'autres entreprises, une attention particulière est mise sur le fait de donner le plus rapidement possible accès aux outils de communication aux nouveaux employés Elastic (adresse email, Slack, Github, ...)

Le turnover est assez bas, notamment vis à vis des employés les plus anciens.

Il y a une "zero tolerance policy" : pour conserver une culture il est aussi important de pouvoir rapidement éliminer les éléments qui rament dans le sens inverse.

### Processus de recrutement d'un "solution architect"
Process particulièrement complexe parce que les solution architects sont ceux qui sont au contact des clients.
Le process commence de manière assez classique, avec le fait de repérer des candidats et de traiter avec les RH.
Ensuite il y a un "technical deep dive" : le but est de vérifier que le candidat a un niveau technique suffisant pour comprendre le produit.
Ensuite il y a le "pannel" : le candidat est invité à une interview avec tous les gens avec qui ils sont susceptibles de travailler, et doit présenter une technologie, "pitcher" à un public non technique.
Ensuite il y a des interviews avec des managers, parfois jusqu'à un VP. Cela peut faire 6 ou 7 interviews, jusqu'à 2 mois.
Question de Manu : "est-ce que le fait d'avoir un process aussi long n'est pas un risque de perdre des candidats ?". La réponse est qu'en effet le risque existe, et ils font des efforts pour réduire ces délais. Mais ils ont une conviction : le recrutement est le process le plus important, parce qu'à partir du moment où on recrute les bonnes personnes, la compagnie fonctionnera.

## Product delivery
Des releases sont planifiées à intervalle régulier. Les ingénieurs ont beaucoup de liberté sur ce sur quoi ils travaillent. Lorsqu'ils ont fini une fonctionnalité, ils peuvent "s'accrocher" à un train de release.
Le pari : la culture de la transparence permet au ingénieurs de décider eux-même des nouvelles fonctionnalités et d'imaginer des choses utiles pour les utilisateurs.
La vision du CEO, c'est de ne pas avoir une "one product company", mais d'éditer un ensemble d'outils et de les enrichir au fur et à mesure des besoins de utilisateurs (par exemple les besoins de sécurité adressés par xPack). Dans ce cadre il y a notamment des acquisitions de petites compagnies qui se branchent sur la technologie Elastic.
Le CEO n'a pas d'attachement émotionnel aux différents produits, c'est ce qui permet d'avancer. L'entreprise n'est pas définie par ses produits mais par sa communauté.

Organisation autour de features, et communication inter-équipes : chaque équipe fait une sorte de newsletter hebdomadaire pour permettre aux autres employés de savoir ce qui se passe dans les autres équipes. 
Points quotidiens d'avancement, et point hebdomadaire sur le delivery (30 minutes) par équipe.
Pas de suivi particulier sur les horaires des ingénieurs. La règle est la confiance, et l'important c'est que les tâches avancent.

## Les sales
La culture de l'entreprise s'étend jusqu'aux commerciaux : l'idée est d'avoir de bons commerciaux, qui cherchent à vendre ce dont le client a besoin mais pas à faire du forcing, à rester dans un esprit communautaire.

## A glimpse of the future
"Qu'est-ce qui sera la techno du futur ?"
 * Chatops : la possibilité de faire de la recheche conversationnelle, de discuter avec un moteur de recherche. Chez Elastic il y a pas mal de gens qui travaillent sur les concepts de reconnaissance du langage naturel.
 * Côté Kibana : des nouvelles fonctionnalités autour de la présentation de la data, de l'interfaçage avec du SIG.
 * Le côté "Serverless" : un nouveau niveau d'abstraction, la suite logique du passage vers le Cloud => focalisation vers la création de valeur métier
 * "Kubernetes has won" : la grande majorité dans la Silicon Valley utiliser AWS, et est en train de migrer vers des conteneurs et vers Kubernetes
 * Self driving car : aujourd'hui la technologie est quasi prête. 



