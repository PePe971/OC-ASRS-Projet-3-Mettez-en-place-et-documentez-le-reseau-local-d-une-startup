# OC-ASRS-Projet-3-Mettez-en-place-et-documentez-le-reseau-local-d-une-startup
OpenClassrooms : Administrateur Systèmes, Réseaux et Sécurité 2024-2025
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Qu'allez-vous apprendre dans ce projet ?
Dans cette mission, vous serez responsable de la conception du réseau, y compris l'élaboration d'un schéma physique détaillant l'emplacement des équipements et la capacité de chaque switch, ainsi qu'un schéma logique décrivant l'architecture du réseau avec les VLAN, les adresses réseau et les masques. Vous définirez également un plan d'adressage réseau précisant les configurations DHCP et statiques. Pour réaliser ces tâches, vous utiliserez des outils tels que draw.io pour les schémas et Excel. Cette mission vous permettra de mettre en pratique les meilleures pratiques de l'ANSSI en matière de sécurité réseau et de gestion de l'infrastructure.


En quoi ces compétences sont-elles importantes pour votre carrière ?
Les compétences acquises au cours de ce projet sont essentielles pour tout administrateur réseau visant à assurer la fiabilité et la sécurité des systèmes d'information dans un environnement professionnel dynamique. Vous apprendrez à concevoir une architecture réseau qui non seulement répond aux besoins opérationnels immédiats mais est également évolutive pour accompagner la croissance de l'entreprise. La capacité à documenter de manière exhaustive le réseau à travers un Document d’Architecture Technique est cruciale pour assurer une gestion efficace et pour faciliter les futurs développements et maintenances du réseau.

 

Prêt à démarrer votre projet ?
Vous allez réaliser un projet réaliste, présenté sous forme de mission en entreprise. Il se rapproche d'une mission typique effectuée sur le terrain.

Le projet est découpé en trois sections :

Mission - Présentation, qui présente le contexte de votre mission,
Mission - Détails, qui présente les détails de la mission, sous forme d’échanges avec les collègues,
Livrables et Soutenance, qui décrit les livrables à fournir et le déroulement de la soutenance de validation.
Prenez soin de lire le projet en entier avant de commencer, pour comprendre ce qui est attendu de vous.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Mission - Présentation

Vous travaillez en tant qu’administrateur systèmes et réseaux chez Hill Start, un incubateur d’entreprises qui accueille déjà plusieurs startups et PME. 

Votre entreprise vient de louer un nouveau bâtiment pour étendre sa capacité d’accueil.


 

Vous êtes chargé de mettre en place le réseau de ce nouveau bâtiment. Pour l’instant, il est vide, mais l’entreprise IT Conseil va bientôt arriver. Cette ESN (entreprise de services numériques) y sera hébergée.
-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
 Mission - Détails
Une réunion d’équipe DSI a eu lieu hier pour lancer le projet de mise en réseau du nouveau bâtiment. Vous étiez en congé mais, heureusement, un replay de la réunion est disponible et vous permet donc de savoir ce qui s’y est dit :

 



 

 

Vous pouvez consulter le script du replay de cette réunion.

 

Ce même jour, vous recevez un e-mail de votre directrice Sarah Watson qui vous résume votre mission sur ce projet de mise en réseau.

 

De : Sarah Watson

À : Moi

Objet : Détails projet mise en place du réseau du nouveau bâtiment Hill Start

Bonjour, 

 

J’espère que tu as bien eu accès au replay de la réunion sur la mise en place du réseau de notre nouveau bâtiment. 

 

Je t’envoie en pièce jointe le document d’architecture technique (DAT) simplifié qu’il faudra compléter avec l’ensemble des informations demandées ci-dessous. C’est un DAT dédié aux techniciens en charge du déploiement donc pas aussi complet que le véritable DAT du projet.

 

Ta mission pour l’instant consiste à faire la conception du réseau que tu comptes mettre en place :

le schéma physique du matériel du SI, avec l‘emplacement de chaque équipement dans les locaux et en précisant la capacité de chaque switch — tu pourras t’appuyer sur les plans du bâtiment et les capacités des salles indiquées dans le cahier des charges ;
le schéma logique du réseau, avec les VLAN que tu as créés, leurs adresses réseaux avec leurs masques, le nom des VLAN et les règles de connexion entre les différents VLAN ;
le plan d’adressage réseau que tu prévois pour les équipements, avec les adresses qui seront en DHCP, celles qui seront en statique, les adresses de broadcast et surtout les masques les plus adaptés aux tailles des réseaux.

 

Tu peux faire les schémas physique et logique sur draw.io et le plan d’adressage sur une feuille de calcul type Excel.

 

Je te conseille également de t’appuyer du guide de l’ANSSI sur les cartographies d’un système d’information. Tu as d’ailleurs un modèle de cartographie physique, en annexe 3 (page 51), qui pourra t’inspirer. 

 

Je te fournis également en pièce jointe le cahier des charges contenant toutes les informations te permettant de mener à bien ce projet.

 

La première entreprise, l’ESN IT Conseil, va intégrer l’incubateur Hill Start dans 3 semaines. Il faut donc que le réseau soit opérationnel avant leur arrivée. Tu trouveras également en pièce jointe le descriptif de leurs besoins SI, comme mentionné dans ma présentation. C’est à toi de voir quelles salles ils occuperont, tu as la liste des salles disponibles dans le cahier des charges.

 

Merci beaucoup, bon courage pour cette mission et bonne journée !

 

Sarah Watson

 Pièces jointes :

Cahier des charges de l’incubateur
Besoins SI IT Conseil
DAT
 

 Ça y est, vous êtes prêt à mener à bien votre mission. À vous de jouer !
 -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Livrables et soutenance

 
Le Document d’Architecture Technique simplifié au format PDF contenant : 
Le schéma physique du SI, complété avec les équipements présents dans les différentes salles.
Le schéma logique du SI, avec les différentes informations réseaux représentées.
Le plan d'adressage, avec toutes les plages d’adresses et les informations réseaux nécessaires.
 

Pour faciliter votre passage devant le jury, déposez sur la plateforme, dans un dossier zip nommé “Titre_du_projet_nom_prénom”, tous les livrables du projet comme suit : Nom_Prenom_n° du livrable_nom du livrable_date de démarrage du projet.

Cela donnera : 

Nom_Prenom_DAT_mmaaaa
Par exemple, le premier livrable peut être nommé comme suit : Dupont_Jean_DAT_012022.

 


 

Durant la présentation orale, l’évaluateur interprétera le rôle de Sarah Watson, la DSI de l’incubateur. La soutenance est structurée de la manière suivante :

Présentation du livrable (15 minutes) 
Vous pouvez utiliser un support de présentation, mais ce n’est pas obligatoire.
Vous prendrez environ 15 min pour présenter votre travail : les schémas, le plan d’adressage, les composants de votre architecture, comment vous avez choisi de répartir les éléments, combien de VLAN vous avez choisi et pourquoi, comment se définit votre plan d’adressage, ainsi que vos choix en termes de masques de sous-réseaux. 
Discussion (10 minutes) 
L’évaluateur jouera le rôle de la DSI. Il vous challengera sur les points suivants :
Adressage IPv4
Passerelle par défaut
Route par défaut
Capacité des matériels réseau
Débriefing (5 minutes)
À la fin de la soutenance, l'évaluateur arrêtera de jouer le rôle de la DSI pour vous permettre de débriefer ensemble.
Votre présentation devrait durer 15 minutes (+/- 5 minutes). Puisque le respect des durées des présentations est important en milieu professionnel, les présentations en dessous de 10 minutes ou au-dessus de 20 minutes peuvent être refusées. 
 

