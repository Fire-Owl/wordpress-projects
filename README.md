# Projet WORDPRESS : Création d'un thème pour une agence Web

## Thèmes : 
- Gestion de projet
- Conception graphique
- CMS WordPress

## Objectifs pédagogiques
- Gérer un projet digital en équipe avec une méthodologie de gestion de projet ;
- Concevoir et réaliser une identité graphique ;
- Réalisez des animations 2D avec Adobe Spark ;
- Produire des maquettes et des prototypes d'interfaces Web ;
- Utiliser un CMS pour créer un site Web basé sur des prototypes ;
- Intégrer des pages Web en utilisation les technologies front-end  :
  - Utiliser les langages HTML, CSS & JS ;
  - Utiliser un préprocesseur CSS (Sass) ;
- Utiliser le langage de programmation *back-end* PHP pour générer dynamiquement l'affichage de pages Web ;
- Publier du contenu en utilisant un CMS ; 
- Publier un site en ligne ;
- Communiquer sur un produit sur un réseau social professionnel.

## Contexte 

### Cadre du projet
Par groupe de 3, vous allez fonder une agence Web. Pour ce faire, vous allez définir l'identité de votre agence : son nom, son logotype. Sur cette base, vous créerez l'identité visuelle de votre agence, sa charte graphique (couleurs, typographies, éléments d'interface). Ce travail vous permettra d'élaborer la maquette et le prototype d'un site Web *mobile* puis sa version *desktop*. Cette maquette vous servira pour déployer un site Web basé sur le CMS WordPress.

## Description des phases de réalisation du projet 

### Phases d’initialisation : constitution des groupes et définition de l'identité du projet

- Constituez des groupes de 3 personnes
  - Procédez à l'élection d'un « Chef de projet » qui sera en charge de la coordination des différents acteurs sur le projet ; 
- Commencez la rédaction du dossier de conception du projet :
  - Identifiez l'objectif :
    - rappelez le contexte du projet
    - identifiez le public cible
    - identifiez le(s) support(s) cible(s)
  - Réalisez un benchmark de sites d'agences Web (analyser des interfaces existantes et des tendances du Web) 
  - Anticipez la prise en compte des normes et la législation en vigueur (ex. : mentions légales, droits d'auteur, droit à l'image, données personnelles)
- Jusitifiez la solution technique répondant au besoin : un site basé sur le CMS WordPress, et la création d'un thème sur mesure
- Définissez l'identité de votre agence : son nom, son logotype
  - Créez une charte graphique
   - Définissez votre palette chromatique
   - Choisissez vos typographies (gérez le texte pour optimiser la lecture sur écran)
- Définissez l'arborescence de votre site web
  - Structurez et hiérarchisez l'information dans vos pages Web

### Phase de lancement : préparation de l'environnement de travail

- Créez une page Organizations au nom de votre Web Agency sur Github et personnalisée là avec le logo
  - Invitez tous les collaborateurs de votre web agency à devenir administrateur de cette page
- Créez un « Project »  de type *kanban* classique (*to do*, *in progress*, *done*) sur la page Organization et listez, organisez et répartissez toutes les tâches ;
  - Utilisez cet outil de gestion de projet tout au long de votre travail collaboratif.  ;
- Créez sur Github un *repository* du nom de votre projet sur la page organisation de votre agence pour héberger les versions de vos travaux ;
- Créez une *team* sur GitHub et invitez les collaborateurs à en faire partie, puis dans les *settings* du *repository*, ajoutez la *team* comme *collaborators* ;
- Créer un nouveau site basé sur WordPress en local, nomé le répertoire « site_[nom-de-votre-agence] » ;
  - Dans wp-content > theme, créez un nouveau dossier nommé « theme_[nom-de-votre-agence] », dans ce répertoire, créez les fichiers « index.php », « style.css » et « functions.php » ainsi qu'un fichier « README.md »;
  - Initialisez le *repository* dans le répertoire nommé « theme_[nom-de-votre-agence] », et liez-le au *repository* en ligne sur votre page *organization* GitHub ;
  - Dans phpMyAdmin, créez une nouvelle base de données intitulée db_[nom-de-votre-agence] » ;
  - Rendez-vous sur l'url correspondant à votre répertoire nommé « site_[nom-de-votre-agence] », et lancez la procédure d'installation de WordPress : remplacez le préfixe « wp_ » par les deux ou trois premières lettres du nom de votre agence, ou les premières consones, ou les initiales si c'est un nom composé de plusieurs mots (la seule contrainte c'est qu'il faut que ça fasse sens !), et faites suivre ce préfixe d'un *underscore* : par exemple, pour un site nomé Access Code School, on préfixera « acs_ » ;

### Phase de Conception

- Réalisez des illustrations, des graphismes et des visuels
  - Utilisez Adobe Illustrator pour réaliser des schémas (ex. : zoning, wireframe) de l'interface illustrant la position et le contenu des différents éléments (navigation, entête, contenu, pied de page) ;
  - Déclinez vos schémas pour différents types de périphériques ;
  - Anticipez l'interactivité de vos pages Web (tracez des liens entre les éléments de vos schémas : tel bouton conduit à tel page, etc.) ;
  - Recherchez des visuels complémentaires (ex. : photos, dessins, icônes)
  - Réalisez des illustrations, des graphismes et des visuels
    - En utilisant le logiciel professionnel de traitement d'images Adobe Illustrator, réalisez des illustrations vectorielles (logotype, éléments d'interface, pictogrammes) ;
  - Utilisez [Adobe Spark](https://www.adobe.com/fr/express/) ou un service équivalent ([WeVideo ](https://www.wevideo.com/), [Vimeo Create](https://vimeo.com/create) ou [Canva](https://www.canva.com/fr_fr/) par exemple, pour produire une animation ;
> Le Designer Web élabore une animation destinée à différents supports de diffusion : site Web, site Web mobile, affichage dynamique. En fonction de la durée et de la complexité de l'animation, il conçoit un scénarimage (story-board) en tenant compte des règles de cadrage, de rythme, d’échelle des plans et de mouvement. Il définit l'univers graphique, crée ou adapte les différents médias (ex. : illustrations, typographies, images, photos) et les intègre dans l'animation. Il associe des effets visuels et sonores au scénario. Il optimise le poids et la fluidité de l’animation, et choisit le format de publication adapté au support de diffusion.
  - En utilisant le logiciel professionnel de traitement d'images Adobe Photoshop, effectuez des retouches, des recadrages, des sélections, des corrections colorimétriques, des photomontages, appliquez des effets spéciaux
  - Utilisez les différents éléments en respectant la législation des droits d'auteurs
  - Optimisez le poids et la qualité, sélectionnez le format d’enregistrement et définissez la taille des réalisations
  - Adaptez les réalisations aux différents supports de diffusion
- Concevez les éléments d'interface (UI KIT), par exemple :
  - des éléments de navigation ;
  - des boutons ou des Call To Action ;
  - des champs textuels ;
  - des icônes au format vectoriel ;
  - l'encadrement des illustrations et photos (par exemple circulaire, carré arrondi) ;
  - des exemples de card ;
  - un exemple de slideshow ;
- Réalisez des maquettes et des prototypes
  - Utilisez Adobe Photoshop pour créer vos maquettes sur la base de vos wireframes
    - N'oubliez pas de prendre en compte les problématiques d'accessibilité et d'ergonomie
    - Concevez le template d'une Newsletter
    - N'oubliez pas non plus de faire le design de la page de Mentions Légales
  - Utiliser Adobe XD pour transformer vos maquettes en prototype
- Finalisez le dossier de conception
  - Intégrez les éléments précédents à votre dossier de conception 

> LIVRABLES : Les maquettes au format PSD, le prototype au format XD et le dossier de conception.

### Phase de Développement
