# Projet WORDPRESS : Création d'une ***Web Agency***


## Thèmes
- Gestion de projet
- Conception graphique
- Animation 2D
- Développement *front-end*
- Intégration Web
- Système de Gestion de Contenu (CMS) WordPress


## Objectifs pédagogiques
- Gérer un projet numérique collaboratif avec une méthodologie de gestion de projet :
  - Utiliser un *Kanban* pour organiser les tâches ;
  - Utiliser la méthodologie Gitflow pour la gestion du *repository* (*a minima* les branches *main*, *develop* et  *features*)
- Concevoir et réaliser une identité graphique ;
- Réalisez des animations 2D ;
- Produire des maquettes et des prototypes d'interfaces Web ;
- Utiliser un Système de Gestion de Contenu pour créer un site Web basé sur des prototypes ;
- Développer un **thème** pour un Système de Gestion de Contenu ;
- Développer une **extension** pour un Système de Gestion de Contenu ;
- Intégrer des pages Web en utilisation les technologies *front-end*  :
  - Utiliser les langages HTML, CSS & JS ;
  - Utiliser la méthdologie BEM pour nommer les classes en HTML / CSS ;
  - Utiliser un préprocesseur CSS (Sass) ;
- Utiliser le langage de programmation *back-end* PHP pour générer dynamiquement l'affichage de pages Web ;
- Publier du contenu en utilisant un Système de Gestion de Contenu ;
- Publier un site Web en ligne ;
- Communiquer sur un réseau social professionnel ;

> **Contraintes :** 
> L'***orthographe*** de toute information textuelle publiée doit être irréprochable !


## Contexte 


### Cadre du projet

Par groupe de 3, vous fondez une agence Web. Pour ce faire, définissez l'identité de votre agence : son nom, son logotype. Sur cette base, créez l'identité visuelle de votre agence, sa charte graphique (couleurs, typographies, éléments d'interface). Ce travail vous permettra d'élaborer la maquette et le prototype d'un site Web *mobile* puis sa version *desktop*. Cette maquette vous servira pour déployer un site Web basé sur le Système de Gestion de Contenu WordPress. 

L'interface visiteur de ce site web sera **un thème WordPress original, créé sur mesure pour le site de votre agence Web** dont le contenu pourra être administré via le *back-office* de WordPress. 

De plus, vous devrez développer **un** ***plugin*** **WordPress de** ***Newsletters*** avec dans interface visiteur un champs de formulaire permettant de s'inscrire à la *newsletter*, et dans le *back-office* une interface pour rédiger la *newsletter* et l'envoyer à tous les inscrits. 


### Principe du projet

L'idée, c'est que tout au long de la suite de la session de formation, les agences créées se maintiendront, MAIS les équipes au sein de ces agences se reconfigureront à chaque projet ! C'est-à-dire que dès le projet suivant, un seul membre de chaque agence restera dans l'agence qu'il a fondé, ses collaborateurs se disperseront dans d'autres agences. Pour le troisième projet, le membre qui est resté changera d'agence, et l'un des autres membres fondateur reviendra dans son agence. À chaque nouveau projet, les équipes doivent entièrement se recomposer. Le membre-fondateur de l'agence se positionne comme « chef de projet » et pilote la nouvelle équipe qui se constitue à chaque projet.

## Livrables

- [ ] 12/07/2021, 13:30 : un dossier de conception d'un site de « *Web Agency* » ;
Le dossier de conception contient *a minima* : 
  - Cadre du projet
    - l'objectif
    - le contexte du projet
    - présentation de l'équipe de réalisation (compétences et tâches attribuées)
    - le public cible
    - le(s) support(s) cible(s) (par exemple smartphone, ordinateur)
    - la prise en compte des normes et la législation en vigueur (ex. : mentions légales, droits d'auteur, droit à l'image, données personnelles, licence pour la publication du *repository* GitHub)
  - Identité du site : nom & logo
  - Planche de tendances
  - Charte Graphique & UI KIT
  - Spécifications fonctionnelles
    - Arborescence
    - *Wireframes*
    - Maquettes *Desktop*
    - Maquettes *Mobile*
    - Maquette page « Mention légale »
    - *Screenshots* des prototypes *mobile* et *desktop* (avec relations entre les pages apparentes)
  - Spécifications techniques
    - Technologies utilisées pour l'intégration (HTML / CSS / JavaScript / PHP / MySQL)
    - Extensions WordPress identifiées pour le fonctionnement du site, par exemple pour : 
        - le référencement naturel, 
        - le passage en production d'un site développé en local, 
        - des statistiques,
        - la sécurisation,
        - etc.

- [ ] 19/07/2021, 13:30 : un thème WordPress original et fonctionnel, permettant d'afficher du contenu publié via le *back-office* de WordPress - code source publié sur Github contenant :
  - les fichiers du thème WordPress, à la racine du thème, *a minima* : 
    - index.php, 
    - home.php, 
    - front-page.php, 
    - page.php, 
    - single.php, 
    - 404.php, 
    - header.php, 
    - footer.php, 
    - functions.php, 
    - style.css,
    - screenshot.png ;
    - assets/
        - images/
        - styles/
            - main.css (le style commun à toutes les pages du site)
            - [nom-du-template].css (du style spécifique à une page en particulier)
            - [nom-du-composant].css (du style spécifique à un composant particulier)
        - scripts/
            - main.js (scripts utiles au fonctionnement général)
            - [nom-de-la-fonctionnalité].js (script dédié à une seule fonctionnalité du site)
    - .gitignore
    - README.md
    - robot.txt
    - LICENCE
  - Un système de branches, inspiré de la méthodologie GitFlow : 
    - une branche *main* pour la version validée pour le passage en production ;
    - une branche *develop* permettant de fusionner le travail réalisé sur chaque branche au fur-et-à-mesure du développement ;
    - des branches *feature* (autant que nécessaire) ;
  - une *board* de gestion et de suivi de projet de type *kanban*, contenant des *cards* spécifiant :
    - la tâche à réaliser, 
    - la date de démarrage de la réalisation de cette tâche, 
    - les ressources humaines allouées,
    - la date de fin de réalisation ;

- [ ] 23/07/2021, 13:30 : revue de projet - un site web en ligne présentant une agence web, avec un système de *newsletters* fonctionnel.


## Phases de réalisation du projet 


### Phase d’initialisation : constitution des groupes et définition de l'identité du projet

- Constituez des groupes de 3 personnes ;
  - Procédez à l'élection d'un « Chef de projet » qui sera en charge de la coordination des différents acteurs sur le projet ; 

- Commencez la rédaction du dossier de conception du projet :
  - Identifiez l'objectif :
    - rappelez le contexte du projet ;
    - identifiez le public cible (les différents types de clients d'une *web agency* - vous pouvez décider de spécialiser votre *web agency* sur un certain type de clientèles) ;
    - identifiez le(s) support(s) cible(s) ;
  - Réalisez un *benchmark* de sites d'agences Web (analysez des interfaces existantes et des tendances du Web) ;
    - Procédez à une analyse de type SWOT (*Strengths* (Forces), *Weaknesses* (Faiblesses), *Opportunities* (Opportunités), *Threats* (Menaces)) sur un échantillon de sites d'agences web ;
  - Anticipez la prise en compte des normes et la législation en vigueur (ex. : mentions légales, droits d'auteur, droit à l'image, données personnelles)
  - Jusitifiez la solution technique répondant au besoin : un site basé sur le CMS WordPress, et la création d'un thème sur mesure ;

- Définissez l'identité de votre agence : 
  - nom de l'agence ;
  - logotype ;
  - Créez une charte graphique ;
   - Définissez votre palette chromatique ;
   - Choisissez vos typographies (gérez le texte pour optimiser la lecture sur écran) ;
   - Recherchez des visuels complémentaires (ex. : photos, dessins, icônes) que vous pourriez incorporer au moment de la conception ;
    - Rassemblez des visuels significatifs, que vous comptez utiliser ou simplement qui vous inspirent - pour créez l'atmosphère graphique de votre site dans une une **planche de tendances** ;
- Définissez l'arborescence de votre site web ;
  - Structurez et hiérarchisez l'information dans vos pages Web ;


### Phase de lancement : Gestion de projet

- Créez une page *Organization* sur GitHub au nom de votre *Web Agency* et personnalisez-là avec le logo ;
  - Invitez tous les collaborateurs de votre *Web Agency* à devenir administrateur de cette page ;
- Créez un « *Project* »  de type *kanban* classique (*to do*, *in progress*, *done*) sur la page *Organization* et listez, organisez et répartissez toutes les tâches ;
  - Utilisez cet outil de gestion de projet tout au long de votre travail collaboratif ;
- Créez sur Github un *repository* du nom de votre projet sur la page organisation de votre agence pour héberger les versions de vos travaux ;
- Créez une *team* sur GitHub et invitez les collaborateurs à en faire partie, puis dans les *settings* du *repository*, ajoutez la *team* comme *collaborators* ;
- [OPTIONNEL] Créez une *mindmap* sur draw.io et sauvegardez-la non pas en local mais dans le *repository* Github que vous avez créé ;
> Une *[mindmap](https://fr.wikipedia.org/wiki/Carte_heuristique)* est un outil qui peut s'avérer utilise dans un contexte de gestion de projet !

- Créez un nouveau site basé sur WordPress en local, nommez le répertoire « site_[nom-de-votre-agence] » ;
  - Dans *wp-content > theme*, créez un nouveau dossier nommé « theme_[nom-de-votre-agence] », dans ce répertoire, créez les fichiers « index.php », « style.css » et « functions.php » ainsi qu'un fichier « README.md » ;
    - Dans style.css, déclarez le thème ;
    - Vous pouvez également dès maintenant placer un fichier nommé « screenshot.png » à la racine, de dimensions 880×660 pixels ;
  - Initialisez le *repository* dans le répertoire nommé « theme_[nom-de-votre-agence] », et liez-le au *repository* en ligne sur votre page *organization* GitHub ;
  - Dans phpMyAdmin, créez une nouvelle base de données intitulée « db_[nom-de-votre-agence] » ;
  - Depuis un navigateur, rendez-vous sur l'url correspondant à votre répertoire nommé « site_[nom-de-votre-agence] », et lancez la procédure d'installation de WordPress : remplacez le préfixe « wp_ » par les deux ou trois premières lettres du nom de votre agence, ou les premières consones, ou les initiales si c'est un nom composé de plusieurs mots (la seule contrainte c'est qu'il faut que ça fasse sens !), et faites suivre ce préfixe d'un *underscore* : par exemple, pour un site nomé Access Code School, on préfixera « acs_ » ;
  - Depuis le *back-office* de WordPress, activez le thème ;
  - Configurez l'espace d'administration (droits des utilisateurs, paramétrage des URL, gestion des médias) ;


### Phase de Conception : Graphisme et ergonomie

- Utilisez Adobe Illustrator pour réaliser des schémas (ex. : *zoning*, *wireframe*) de l'interface illustrant la position et le contenu des différents éléments (navigation, entête, contenu, pied de page) ;
  - Concevez votre thème WordPress dans une logique *mobile first* ;
  - Déclinez vos schémas pour différents types de périphériques ;
  - Anticipez l'interactivité de vos pages Web (tracez des liens entre les éléments de vos schémas : tel bouton conduit à tel page, etc.) ;

> Attention ! Il faut que les choses soient bien claires dans votre esprit : si le sujet dont traitera le site Web que vous allez développer est votre *Web Agency*, l'objectif de ce projet est de créer un thème WordPress. Cela implique que vous allez devoir créer des *templates* pour vos pages web, il serait donc judicieux d'étudier le « Template Hierarchy » de WordPress pour bien distinguer ce qui sera de l'ordre de la structure de vos pages (donc conçu dès l'étape de *wireframing*) de ce qui relèvera du contenu publié en utilisant le *back-office* de WordPress.

- Réalisez des illustrations, des graphismes et des visuels ;
  - En utilisant le logiciel professionnel de traitement d'images Adobe Photoshop, effectuez des retouches, des recadrages, des sélections, des corrections colorimétriques, des photomontages, appliquez des effets spéciaux ;
  - En utilisant le logiciel professionnel de traitement d'images Adobe Illustrator, réalisez des illustrations vectorielles (logotype, éléments d'interface, pictogrammes) ;

> * Utilisez les différents éléments en respectant la législation des droits d'auteurs
> * Optimisez le poids et la qualité, sélectionnez le format d’enregistrement et définissez la taille des réalisations
> * Adaptez les réalisations aux différents supports de diffusion

- Utilisez [Adobe Spark](https://www.adobe.com/fr/express/) ou un service équivalent ([WeVideo ](https://www.wevideo.com/), [Vimeo Create](https://vimeo.com/create), [Canva](https://www.canva.com/fr_fr/) ou [Crello](https://crello.com/fr/) par exemple) pour produire une animation ;
> ***Extrait du REAC :*** « Le Designer Web élabore une animation destinée à différents supports de diffusion : site Web, site Web mobile, affichage dynamique. En fonction de la durée et de la complexité de l'animation, il conçoit un scénarimage (*story-board*) en tenant compte des règles de cadrage, de rythme, d’échelle des plans et de mouvement. Il définit l'univers graphique, crée ou adapte les différents médias (ex. : illustrations, typographies, images, photos) et les intègre dans l'animation. Il associe des effets visuels et sonores au scénario. Il optimise le poids et la fluidité de l’animation, et choisit le format de publication adapté au support de diffusion. »
  
- Concevez les éléments d'interface (*UI KIT*), par exemple :
  - des éléments de navigation ;
  - des boutons ou des *Call To Action* ;
  - des champs textuels ;
  - des icônes au format vectoriel ;
  - l'encadrement des illustrations et photos (par exemple circulaire, carré arrondi) ;
  - des exemples de *card* ;
  - un exemple de *slideshow* ;

- Réalisez des maquettes hautes fidélité de votre site web :
  - Utilisez Adobe Photoshop pour créer les versions des maquettes pour l'affichage *mobile* et *desktop*, sur la base de vos *wireframes* :
    - N'oubliez pas d'intégrer un champs de formulaire pour que vos visiteurs puissent s'inscrire à la *newsletter* ; 
    - Concevez donc aussi le *template* de vos *Newsletter* ;
    - N'oubliez pas de faire le *design* de la page de Mentions Légales ;
> Gardez à l'esprit en concevant vos maquettes que le contenu des pages pourra être intégré avec l'éditeur de blog Gutemberg, qui sera de toutes façons utilisé par les administrateurs du site WordPress qui utiliseront votre thème ;
> Par contre le travail de développement consistera à créer la structure des différents types de page : un *template* de page d'accueil, un *template* pour toutes autres les pages crées par l'utilisateur, un *template* de page qui affiche la liste des articles et un *template* de page d'un article.
> Prenez en compte les problématiques d'accessibilité et d'ergonomie ;

- Utiliser un logiciel type Figma ou Adobe XD pour transformer vos maquettes en prototype ;

- Finalisez le dossier de conception :
  - Intégrez les éléments précédemment conçus à votre dossier de conception ;

> LIVRABLES : Les maquettes au format PSD, le prototype au format XD et le dossier de conception + une page *organization* au nom de votre agence et un *repository* du nom de votre thème.


### Phase de Développement : thème, extension et passage en production

> ***PLOT TWIST :*** les groupes s'échangent leurs prototypes pour la phase de développement ! Chaque agence développe le site d'une autre agence web, qui devient par là son premier « client ».

- Développez votre thème WordPress :
  - Créez les pages *front-page.php*, *page.php*, *home.php* et *single.php* puis *archive.php* , *404.php* et *search.php* ;
  - Avec PHP et les fonctions de WordPress, placez les requêtes à la base de données pour afficher le contenu et utiliser les fonctionnalités de WordPress dont votre thème a besoin pour fonctionner ;
  - Dans *functions.php*, déclarez les fonctionnalités de WordPress dont votre thème a besoin pour fonctionner ;
  - En HTML / CSS / JS, développez la structure de ces pages ;
    - [OPTIONNEL] Utilisez un framework *front-end* type Bootstrap ou Foundation pour structurer votre développement de pages Web ;
    - Développez votre thème WordPress dans une logique *mobile first* ;
    - Utilisez des balises HTML sémantiques ;
    - Utilisez la technologie Sass pour introduire de la logique de programmation dans votre CSS ;
  - Prenez en compte les problématiques de référencement naturel dans votre développement ;

- Développez une extension de *Newsletter* ;

- Effectuez le passage en production du site réalisé avec le CMS WordPress :
  - Identifiez une extension WordPress pour migrer en ligne un site développé en local (par exemple Duplicator) ;
  - Utilisez Adminer, l'application Web de gestion de base de données MySQL sur un serveur PHP installé sur le serveur ACS, pour créer la base de données ;
  - Utilisez le protocole SSH ou l'outil de transfert de fichiers Filezilla pour héberger les fichiers sur le serveur ;
  - Gérez les droits des fichiers et des dossiers :
    - Créez un fichier [robot.txt](http://robots-txt.com/) et placez-le à la racine du site ;
    - Testez les pages en ligne dans différents navigateurs et sur différents périphériques ;
  - Sélectionnez et installez une (ou des) extensions pour optimiser le référencement naturel (SEO) ;
  - Soumettez le site aux différents moteurs de recherche (a minima Google & Bing) ;
  - Apportez les améliorations pour optimiser les performances (ex. : temps de chargement, rapidité d'affichage) ;
  - Livrez le site réalisé à l'agence qui avait travaillé sur la phase de conception :
    - Prenez acte des retours ;
    - Apportez d'éventuelles modifications ;

> LIVRABLE : Un site web fonctionnel, hébergé sur le serveur de promo.


### Phase d'Exploitation

> ***PLOT TWIST :*** les membres-fondateurs de chaque agence reprennent les rennes du projet et utilisent le thème qui a été développé pour eux afin de communiquer sur leur agence.

- Intégrez le contenu de vos prototypes dans des pages Web :
  - Créez vos pages dans le back-office de WordPress ;
  - Utilisez l'éditeur de blog Gutemberg pour organiser vos contenus ;

- Vie du site et maintenance :
  - Communiquez sur l'existence de votre agence :
    - Créez une page Entreprise sur LinkedIn reprenant l'identité visuelle de votre agence ;
    - Tous les membres-fondateurs de l'agence sont administrateur de la page Entreprise ;
    - Créez des posts en tant qu'entreprise pour communiquer sur les différentes étapes de votre travail ;
  - Optimisez en continu le site Web de votre agence :
    - Mettez à jour et améliorez le contenu ;
    - Optimisez le référencement naturel ;
    - Utilisez la page Entreprise de l'agence sur LinkedIn pour communiquer sur chaque nouveau projet réalisé par l'agence (c'est le membre-fondateur de l'agence qui communique sur la page Entreprise de LinkedIn au sujet du projet réalisé par son agence (en ayant soin d'identifier ses collaborateurs évidemment)) ;
    - Élaborez des newsletters à chaque nouveau projet réalisé par l'agence pour fidéliser les utilisateurs du site ;

> LIVRABLES : (dernier jour de la session de formation) Un site qui a été maintenu tout au long de la session, chaque projet ayant été documenté, et une communication systématique sur la page Entreprise de LinkedIn au sujet de chaque projet réalisé par l'agence.

## Ressources 

- L'excellent site [CAPITAINE WP](https://capitainewp.io/formations/developper-theme-wordpress/introduction-anatomie-dun-theme/)
