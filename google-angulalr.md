# Interview Stephen - Google / Angular team

## Developer advocate life
Est-il compliqué de donner plusieurs fois le même talk ?
Non en fait je donne rarement le même talk, je l'adapte au public, essentiellement en essayant d'identifier le problème de l'audience.

Je voyage environ 20% de mon temps, et j'ai l'impression que c'est à la fois beaucoup et pas assez.

Vous ne remplissez plus les CFP ?
Non, en général on est invités. Ceci-dit de temps en temps on le fait quand même.

Quel est ton parcours ?
J'étais dans une société de service, qu'on a mené de 2 à 400 personnes. A la fin j'étais responsable de l'équipe de Solution Architects.
Ensuite j'ai été dev advocate pour Trello.
Il y a un peu plus de 2 ans, Google m'a contacté en me disant de venir pour une interview sur un sujet top secret. Ça m'a accroché (même si au final le job n'était pas du tout secret).

Angular VS React
Si vous avez une techno que vous aimez, tant mieux. Angular comme React cherche à faire un meilleur Web, et c'est tant mieux.
Pour ceux qui disent qu'Angular est mauvais, j'ai surtout besoin de comprendre pourquoi ils le disent.
Les raisons pour lesquelles certaines personnes choisissent Angular : 
 - C'est "opiniated" : un choix d'outil intégrés
 - C'est "trustworthy" : une roadmap publique et respectée
 - C'est "Familiar" : pour les gens qui viennent de AngularJS, mais aussi pour ceux qui viennent de Java et de .Net
 - Ça scale : Google l'utilise, beaucoup de grosse compagnies l'utilisent, ça fonctionne très bien dans de grosse équipes
 - L'écosystème : beaucoup de contributeurs autour du framework sur les libs, sur l'outillage, ...

Penses-tu qu'à un moment on n'aura plus besoin de framework ?
Non, ou alors dans très très longtemps. Si on prend l'exemple des Web Components, la spécification apporte beaucoup de chose sur le sujet des composants, mais il y a plein de choses qui ne sont pas possible avec du "vanilla" (par exemple le Server Side Rendering). Ou alors peut-être qu'un jour les browsers embarqueront directement Angular ? (joke). Plus sérieusement, même si les équipes Chrome sont aussi chez Google, elles ne mettent dans le browser que des choses dont elles pensent qu'elles ont du sens dans tous les browsers (donc pas de version de Chrome privilégiant le framework Angular).

Le travail en remote?
J'ai pas mal travaillé en remote, et ici les gens peuvent le faire quand ils veulent. Mais personnellement j'apprécie aussi beaucoup le fait d'être à proximité des gens avec qui je travaille.

Les challenges dans le dev d'Angular ?
Il y en a pas mal. Par exemple les Zones sont un très bon concept mais ça casse certaines parties du framework. 

Collaboration avec Microsoft (sur TypeScript par exemple) ?
Nous travaillons pas mal avec eux, mais il n'y a pas réellement d'équipe intégrée Google/Microsoft.

Google travaille sur différents projets qui sont potentiellement concurrents (par exemple Angular / Polymer).
Je n'ai pas vraiement l'impression que ce soit des projets concurrents. Par exemple pour Angular et les Web Components, ces projets peuvent collaborer.
D'une manière générale, si il y a plusieurs technologies, c'est qu'il y a un public pour toutes.

Pourquoi tu aimes travailler ici ?
Parce que j'ai l'impression de travailler pour une startup, mais qui a un énorme impact. De plus, j'adore mon rôle en tant qu'advocate, parce que j'ai vraiment l'impression qu'on apporte des choses à la communauté, aux développeurs.

C'était quoi le process de recrutement pour entrer chez Google ?
Des entretiens tel, des entretiens physiques, et des entretiens avec l'équipe cible pour voir si il y a un "fit".
Typiquement c'est 4 ou 5 entretiens.
Le processus est optimié pour minimiser les faux positifs. On préfère dire non à une très bonne personne que dire oui à quelqu'un qui ne fera pas l'affaire.

Faites-vous du support en interne aux équipes Google qui utilisent Angular ?
Oui, surtout aux grosses équipes. Le plus gros projet interne utilisant Angular est GCP, mais ils n'ont pas fini la migration et il y a encore du AngularJS.

Anecdote sur la blague du 1er avril (une version de RS.js publiée avec un -smoosh, qui a remplacé la -rc dans npm à cause du classement alphabétique de npm).

Team building ?
On fait du "human vs zombies" : pendant 1 heure par jour on joue avec des Nerfs. Les zombies ont un bandeau pour les reconnaître. Si ils touchent un humain il devient Zombie, par contre si un humain shoote un zombie il est "frozen" pendant 60 secondes (?).

La vie quotidienne à Google : 
ça dépend des équipes. Certaines font des daily stand up, d'autre non.

Si tu devais partir sur un nouveau projet avec une nouvelle techno, ce serait quoi ?
Je ne sais pas, il y a plein de trucs sympas... Android, Chrome, Flutter, ...

Quel est la prochaine révolution technologique ?
La productivité des développeurs : schematics -> depedency update "magique". Des outils de migration automatique (par exemple RX.js qui a un outil de migration permettant de ré-écrire le "mauvais code" en bon code). Maintenant les applications peuvent évoluer presque automatiquement, les librairies et framework poussent des update jusqu'au code produit. 
Le fait d'avoir un seul ordinateur, et de multiples terminaux pour l'utiliser.

Comment tu sépares la vie privée et la vie pro ?
Plutôt bien en fait. Par exemple je ne bosse pas dans l'avion.

Processus de choix des nouvelles fonctionnalités dans Angular.
Triage des issues dans Github : pas super scientifique
 - on commence par prioriser les corrections de régressions
 - puis on regarde ce qui permet au framework de rester "agile"
 - et ce qui apporte de la valeur aux utilisateurs

Angular-dart : 
C'est une équipe à part qui le maintien maintenant.