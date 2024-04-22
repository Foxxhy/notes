# Notes DEVOXX - 2024
__Certaines ressources seront sur youtube.__

## Keynotes

### IA & Médecine

- Etats des lieux dans l'aide de l'IA pour le diagnostique de maladie
- L'IA permet de déceler des schémas là que l'être humain ne perçoit pas
- Dans certains cas, certains modèles entrainés sont mêmes meilleurs que les spécialistes
- Mais de gros biais: certaines IA se basaient sur le nom des hôpitaux pour déceler des maladies (hôpitaux spécialisés). Il y a donc un gros risque de biais et l'IA reste une boite noire.

__Remarque:__ Rappel de l'intervenant sur le fait que "intelligence artificielle" vient de l'anglais "intelligence articial". Et en anglais intelligence prends le sens d'analyse / analytique. Le terme d'intelligence artificielle est un abus de langage. C'est plus proche d'analyse artificielle.

[lien devoxx](https://www.devoxx.fr/schedule/talk/?id=74352)

### Les plus grandes erreurs des programmeurs

- Sensibilise sur le cas de la conception à long terme
- Des choix faits parfois des décennies auparavant peuvent avoir des conséquences dramatiques plus tard
- Exemple des fusées américaines qui étaient basées sur des processeurs 4 bits au lieu de 5 bits (à cause du prix) qui a finit par causer un grave accident car cela a eu des conséquences sur les programmes informatiques
- Rappel le lien avec le software et le hardware

[lien devoxx](https://www.devoxx.fr/schedule/talk?id=77109)

### Métaux & IT & Écologie

__Agnès Crepet  responsable de la longévité logicielle et de l'informatique chez Fairphone__

- Sensibilise au fait qu'un Téléphone nécessite plus de 100 kg de matière première
- Avec des matériaux qui sont souvent pas recyclables
- Par des travailleurs qui vivent dans des conditions misérables, des indistriels et acheteurs qui prennent pas soins de leurs produits
- Sensibilise énormément sur un changement de paradigme: l'enjeu des prochaines années ne sera pas de créer mais e maintenir le plus longtemps possible car c'est l'une des manières les plus efficaces pour avoir un impact sur la consommation

### Le monde en 2100

Basé sur les rapports **Meadows** et **Earth for all**

- Le rapport Maedows date des années 1970, il a été construit par de nombreux experts et est encore vu comme un rapport de qualité sur les scénarios possibles pour l'humanité au cours des 100 prochaines années.
- Son rapport se base des critères généraux: ressources, pollution, population, ressources par habitants etc..
- Rapport sans appel: **très peu de scénarion mènent à un équilibre** et la fenêtre de changement était il y a __30 ans__.
- Le rapport est considéré encore aujourd'hui comme valable car la situation actuelle est similaire à un des scénarions du rapport Maedows.
- Selon le rapport: __Nous allons lentement glisser vers une période d'abansce à une guerre pour la ressource__.
- Existence du rapport **Earth for all** qui est bien plus récent mais jugé moins pertinent par la communauté

[lien devoxx](https://www.devoxx.fr/schedule/talk?id=74359)
[schéma maedows](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.alternatives-economiques.fr%2Fprevisions-rapport-meadows-se-realisent-0102201988382.html&psig=AOvVaw0PfhLjIUlWs1A_uGrt-KGS&ust=1713870935311000&source=images&cd=vfe&opi=89978449&ved=0CBIQjRxqFwoTCKjI5PPY1YUDFQAAAAAdAAAAABAE)

### Cybersécurité

**GUILLAUME POUPARD - directeur général adjoint chargé du développement à l'international et du cloud, chevalier de la légion d'honneur et chevalier de l'ordre national du mérite**

- Interventions sur la cybersécurité
- La plus part des groupes de pirates ne veulent surtout pas être dans le top 10 car ce sont eux qui sont activement recherché
- Ils évitent aussi les sujets qui font parler comme les hôpitaux etc...
- Etat des lieux sur la sécurité en général où pendant de nombreuses années aucune entreprise n'était préparée à ce genre de cas de figure
- C'est l'arme préférée des états pour se faire la guerre comme l'Ukraine qui a été victime de grosses cyber attaques avant le conflit avec la Russie
- Sensibilise sur le fait que la sécurité dépend de chacun

__Conférence à conseiller__
[lien devoxx](https://www.devoxx.fr/schedule/talk/?id=77117)

## Qualité

### Discussion au stand GITLAB

__Idée à présenter à l'équipe__

- Présentation par l'équipe GITLAB des dernières évolutions & outil de la plateforme. Intégration de l'IA dans les différents outils GITLAB
- Possibilité d'intégré de l'IA dans la revue de code au moment de faire les commits & merge request. Cela permet de responsabiliser davantage les développeurs et permet de faire appel au lead développeur en cas d'alerte dans le code pour arbitrer
- Apparemment juste une option à activer "code quality" et inclut dans le forfait

[lien gitlab](https://docs.gitlab.com/ee/ci/testing/code_quality.html)

### Le craftmanship

- Présentation de l'histoire du craftmanship
- Idée que nous sommes de plus en plus dans le modèle de fast-fashion avec des applications rapidement développées, très peu qualitatives et la nécessité de souvent fait des refontes. Le fast-food de l'ingénierie en résumé
- Soutien qu'avant SCRUM, il y avait un abus sur les temps réalisés dans les tâches
- Soutien qu'après SCRUM, nous sommes passés dans le fast food de l'ingéniérie

- Sensibilise à la notion de TDD, BDD, DDD
- Avertissement sur le prod testing: symptôme du côté fast-fashion des projets web et la perte de qualité. En prenant comme habitude de réaliser les fixs directement sur la prod
- Rappelle sur le fait qu'il faut savoir être intelligent et adapter ces pratiques à son besoin
- Rappelle qu'aujourd'hui le plus gros problèmes réside dans la communication entre les membres d'une même équipe afin de proposer une solution meilleure

- Mets l'accent sur le fait qu'il faut pas avoir le craftmanship comme une réligion mais plutôt comme un état d'esprit et de bon sens
- Mets en avant le fait qu'être Développeur n'est pas un passage rapide mais bien un vrai métier avec une vraie carrière dedans

[lien devoxx](https://www.devoxx.fr/schedule/talk?id=47561)

### Architecture

__Initiation en architecture__

- Destiné à ceux qui s'intérressent à l'architecture
- Conférence basé sur la réalisation de l'exercice (lien github) par les présentateurs
- Destiné à sensibilisé sur les concepts de Chorégraphie et Orchestration dans les architectures webs
- Usage pratique des différents designs patterns: bus, observateur, mediateur, orchestrateur

[lien github](https://github.com/arolla/choreography-kata/blob/main/README.md)
[lien devoxx](https://www.devoxx.fr/schedule/talk?id=47562)

## Tranverse

### Polumi, alternative à terraform

- Outil d'infra as code orienté pour les développeurs
- Permet d'écrire des infras avec son langage préféré (e.g: typescript)
- Se présente comme une alternative à terraform
- Outil prévu pour pouvior importer directement terraform et le transformer en projet Polumi

[lien devoxx](https://www.devoxx.fr/schedule/talk?id=8861)

### Advanced Software Teaming

- Présentation en anglais
- Mélange et regroupe à la fois le management et les organisations
- Sensibilise sur le fait que manager est très proche de cette métaphore "prendre soin du plante pour qu'elle grandisse"
- Rappelle les différents biais qui peuvent arriver dans des équipes
- Considère le biais de la croyance comme l'un des plus importants et qu'il éloigne les collaborateurs les un des autres
- Explique qu'une même phrase peut être comprise différemment par deux personnes car elles ont des bagages différents
- Mets en avant le fait que le meilleur moyen de résoudre ce problème est d'avancer et valoriser les bonnes choses afin de tomber les barrières
- Décrit la notion de système et de domaine
- Un système est une structure destinée à créer quelque chose. Tandis qu'un domaine concerne l'appartenance à quelque chose
- __Averti__ que le principe même de système fait que forcer à le faire changer aura souvent des conséquences très négatives. Et qu'il faut avoir une approche d'accompagnement pour que le système change de lui même de l'intérieur
- __Averti__ que c'est une source de biais. Si un problème se rencontre et que l'on se place par rapport à la mauvaise échelle alors on analyse le mauvais système et extrait la mauvaise cause

[lien devoxx](https://www.devoxx.fr/schedule/talk/?id=44933)

## Back-end

### Architecture multitenent (Java)

__Présenté par Mirakl dont la Poste est cliente à la BGPN__

- Parti d'un principe simple: un service fourni à un utilisateur a un cout (expetise, hardware, software)
- Volonté de mutualisé les différents services afin de faire du vrai SAAS.
- Plusieurs enjeux dont le fait de ne pas avoir d'interruption de service
- Volonté d'enlever l'aspect spécifique par client, l'adhérence trop forte entre l'appli et la BDD

- Choix d'une architecture multi tenent
- Chaque pays possède un certain nombre de serveurs / base de données
- Ces clusters sont mutualisés entre plusieurs entreprises, de préférences des gros clients & petit clients (afin de limiter de concentrer trop de gros client sur un seul cluster)
- Regroupement par région
- Mise en place d'une architecture évitant la fuite de la donnée

- Usage de Springboot avec des customs scops
- Usage de plusieurs BDD avec un flux Kafka
- Toutes les appels passent par ce même tunnel

[lien devoxx](https://www.devoxx.fr/schedule/talk/?id=3673)

## Front-end

## IA