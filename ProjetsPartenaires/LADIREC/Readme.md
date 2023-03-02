# Laboratoire d’analyse des discours et des récits collectifs
###### Membres : Pascal Brissette (PI), Julien Vallières-Gingras, Lisa Teichmann, Yu Chen Shi, Elisabeth Doyon, Amélie Ducharme

Le Laboratoire d’analyse des discours et des récits collectifs (LADIREC) vise à offrir à ses partenaires un appui dans la structuration, l’exploration et l’analyse des données textuelles dont ils disposent ainsi que des outils pour leur interprétation. Tirant profit de méthodologies et de processus de traitements informatiques développés par les chercheur·se·s en analyse des langues naturelles, il se greffe à l’Observatoire des enjeux sociaux de Montréal pour mieux comprendre les aspirations et les défis des citoyen·ne·s de la métropole, par quartiers et communautés.

Outre ce volet d’appui à l’analyse de données textuelles déjà partagées par les partenaires, le LADIREC espère procéder à la récolte, au traitement et à l’analyse de nouveaux ensembles de données textuelles sur des enjeux d’intérêt. Par exemple, nous analysons les discours médiatiques montréalais afin de comprendre l’évolution des récits, valeurs et « sentiments » attachés à certaines thématiques dans la sphère publique à l’aide de processus d’extraction automatisée d’informations et de séquences narratives.

## Contexte
L’appréhension et la compréhension des enjeux sociaux reposent sur différents types de discours dont certains sont difficiles à analyser et à objectiver. Par exemple, les citoyen·ne·s s’expriment sur les médias sociaux, dans des lettres ouvertes ou lors de forums publics; il·elle·s produisent des affiches, des placards, des slogans. Le défi réside dans l’ampleur de l’échantillon, que l’on souhaite aussi exhaustif que possible afin qu’il soit représentatif du discours global.

Ces productions discursives éphémères ne se laissent pas aisément intégrer à des colonnes de chiffres et de données. Au mieux, certains partenaires auront mené des enquêtes structurées permettant de recueillir des témoignages et avis qui seront compilés et, parfois, enregistrés sous forme de tableur. Dans tous les cas, l’analyse de ces discours produits par les citoyen·ne·s exige de grandes ressources, la mise en place de méthodologies d’analyses, la convocation d’expertises et de grandes précautions pour éviter les biais dans l’interprétation des avis compilés.

## Fonctionnement
Le LADIREC travaille à établir des liens avec d’autres laboratoires qui conduisent des recherches similaires dans diverses disciplines (notamment dans le domaine des sciences politiques, de la philosophie et des sciences cognitives), en plus de mener des recherches et un enseignement aux trois cycles universitaires en lien avec les travaux effectués. Il tâche également de planifier les processus d’analyse et de traiter les demandes des partenaires.

Dans une visée pédagogique, des étudiant·e·s sont formé·e·s pour occuper des postes d’auxiliaires de recherche au sein du laboratoire. Il·elle·s exécutent l’ensemble des tâches liées à l’extraction et à la récolte de données textuelles (moissonnage du Web; web scraping), à leur prétraitement (nettoyage et structuration), à leur analyse et à la production de graphiques permettant la compréhension des résultats obtenus.

## Liens utiles
#### https://medium.com/pds-dsh 
#### https://github.com/LADIREC 
#### https://www.mcgill.ca/centre-montreal/fr 
#### https://www.mcgill.ca/pds-dsh/fr 
#### https://www.mcgill.ca/pds-dsh/fr/modules-du-projet/ladirec 
#### https://www.mcgill.ca/centre-montreal/fr/ressources/infolettre

## Modèle de travail général – grand angle

<img alt="image" src="https://user-images.githubusercontent.com/85407589/222464460-348ff93b-5e40-4caa-a2d2-a42db523afd7.png">

## Flux de traitement de la donnée – en bref
Le flux de traitement du LADIREC présente des méthodes d’analyse de texte assistées par l’ordinateur (ATO) qui nécessite l’apport d’un analyste et un ensemble d’outil du traitement des langues naturelles pour arriver à explorer et analyser des grands corpus de texte en fonction de question de recherche. 
Le projet pilote qui sert au développement se construit autour d’un corpus sur l’alimentation à Montréal. Voici une représentation de haut niveau de ce processus : 

<img alt="image" src="https://user-images.githubusercontent.com/85407589/222462877-0a46cb11-47e6-4fc4-b791-371111cc8dbe.png">

## Flux de traitement de la donnée – détaillé
Voici de manière plus détaillée comment se s’articulent les ressources en données, en logiciel et les ressources humaines qui exploitent les outils d’analyse au sein du laboratoire :

<img alt="image" src="https://user-images.githubusercontent.com/85407589/222463218-1eeaceaa-2f99-454b-886c-0c7f648615a5.png">

## Les projets réalisés et en cours
De manière générale, les projets en cours exploitent en totalité ou en partie la chaine de traitement du laboratoire en fonction de la pertinence des analyses et l’état des données d’origine.

### Banque alimentaire
###### Responsable : Lisa Teichmann
Nous avons mené une étude de cas sur la représentation des banques alimentaires dans notre corpus. Nous avons constaté que les banques alimentaires sont principalement mentionnées dans les médias locaux qui couvrent certains quartiers que nous avons pu visualiser sur une carte. Ce projet a souligné l'importance des petites sources de nouvelles dans la diffusion de l'information sur l'accès aux banques alimentaires. Nous avons utilisé nos outils de regroupement d'articles par sujet (dans ce cas les banques alimentaires) et de géomapping des articles mentionnant des arrondissements et des quartiers en utilisant les données disponibles par Données Québec. 
 
Sur demande, les outils utilisés pour les banques alimentaires peuvent également être appliqués à d'autres sujets tels que les organisations alimentaires, les marchés alimentaires, les événements, etc.  
 
### La traduction automatique en chaine
###### Responsable : Elisabeth Doyon
Le projet de traduction en chaine a plus d’un objectif. Tout d’abord, il nous est utile de traduire automatiquement le contenu du corpus médiatique sur l’alimentation pour certaines analyses puisqu’il contient deux langues, en anglais et en français. Aussi, la mise en série de traduction d’une langue à une autre, puis d’un retour à la langue originale transforme la traduction automatique en une fonction de reformulation de phrase ; la production de paraphrase. Cette fonction peut servir à augmenter le nombre d’exemple pour l’entrainement d’un classificateur automatique qui utilise de l’apprentissage-machine supervisée. Il s’agit d’une manière de multiplier la valeur d’un ensemble de données qui aurait été manuellement catégorisé selon n’importe quelle grille d’analyse. 
 
### Désambiguïsation
###### Responsable : Amélie Ducharme
#### https://github.com/LADIREC/ladirec_projetcafecafe_desambiguisation
Le projet « café-café » avait pour but de désambiguïser deux termes, « café » le lieu et « café » la chose (breuvage, grain, industrie…), afin d’aider à repérer automatiquement les mentions d’emplacements géographiques dans les textes analysés par le LADIREC. En utilisant un corpus médiatique sur l’alimentation composé de 46 513 articles récoltés par le LADIREC, nous avons d’abord réduit le nombre de textes en conservant seulement ceux dans lesquels nous avons trouvé, grâce à une expression régulière, certaines variations du mot « café » (avec ou sans accent/majuscule/marque du pluriel). Ensuite, nous n’avons retenu que les articles de langue française, puisque l’ambiguïté du mot « café » est inexistante en anglais (où « coffee house » et « cafe » se distinguent plus clairement du simple « coffee »). Ensuite, grâce à des procédés de vectorisation (word-to-vec), nous avons pu déterminer quels termes du sous-corpus étaient les plus similaires à chaque variation de « café » et, donc, quelles tendances se dégagent de l’emploi de chaque variation (catégorie grammaticale, accord, champ lexical, etc.). Nous avons également usé de fenêtres contextuelles (keyword-in-context) pour analyser les segments qui précèdent et suivent chaque occurrence de « café », encore dans le but de dégager les tendances quant à l’emploi de chaque variation et, ultimement, de formuler des hypothèses de stratégies qui rendraient l’ordinateur capable de distinguer les deux sens du mot « café » lors d’une analyse automatisée.
 
### Indice de centralité sur l’insécurité alimentaire
###### Responsable : Elisabeth Doyon
Le projet de création de l’indice de centralité sur l’insécurité alimentaire a pour objectif de réduire les dimensions inhérentes au texte et aux discours médiatiques (complexe et dont la lecture prend du temps) à un indice qui pourrait servir d’alerte ou d’indicateur. Lorsque les médias parlent d’alimentation, ils parlent de sujets en fait différents, parfois de restaurant, de sorties et de gastronomie, parfois aussi de banque alimentaire, de trucs pour faire des économies ou éviter le gaspillage. Ces différents discours – et surtout les termes utilisés pour parler de l’alimentation – peuvent être associés à des scores qui placent sur l’axe singulier de la sécurité alimentaire chaque article de presse. À partir de cette réduction, il est alors possible de naviguer, comparer et cibler le matériel médiatique selon une autre dimension, celle du territoire ou des périodes temporelles. La création de l’indice de centralité inclut le développement d’outils de traitement de texte, mais aussi des étapes de consultation pour établir les scores associés aux différents enjeux de la sécurité alimentaire. 

### Géolocalisation
###### Responsable : Lisa Teichmann
Les outils et stratégies de géocartographie ont été développés pour répondre à des questions telles que : quels sont les quartiers de Montréal qui sont sous-représentés lorsque l'on parle d'insécurité alimentaire dans les médias d'information? Quels sont ceux qui sont mis en évidence ? Quelle est le rôle des médias d'information pour fournir aux résidents des informations sur comment et où accéder aux services alimentaires ? Nous avons conçu un modèle de géodonnées qui nous a permis de collecter et d'utiliser les différents jeux de données mis à notre disposition par diverses sources telles que Données Québec, les paroisses et les partenaires. Nous avons développé plusieurs stratégies pour extraire des textes du corpus les mentions de lieux, telles que les adresses, les arrondissements et les quartiers. Notre modèle nous permet de situer les adresses apparaissant dans les articles dans les limites des arrondissements ou des quartiers, ce qui nous donne la flexibilité de visualiser les dimensions géographiques dans le corpus. Nous élargissons continuellement notre ensemble de données en collectant des données auprès de sources supplémentaires. Nous aussi sommes en contact avec le GIC (Geographic Information Centre) de McGill pour une collaboration potentielle. 

### Traduction automatique/sommaire 
###### Responsable : Elisabeth Doyon
Le script de synthèse prend un corpus de texte structuré en entrée et résume la ou les colonnes choisis en début du script et dépose les synthèses dans une table en sortie. Le script de traduction prend un corpus de texte structuré en entrée, établit une chaine de traduction d'une langue à une autre pour produire des variations syntaxiques des textes envoyés tout en conservant la sémantique puis dépose les paraphrases dans une table en sortie. Il utilise le cadre de travail de Hugging face ou sont déposés des modèles de langues tiré de différentes stratégies. Ce script utilise les modèles de type BERT et applique les contraintes de ce type de modèle (longueur maximale, type de lemmatisation etc.). Il est possible de modifier le modèle utilisé à même le code. 
 
### La synthèse automatique
###### Responsable : Elisabeth Doyon
La synthèse automatique nous sert pour reformuler les articles d'un corpus de textes. Elle est en soi une forme de paraphrase qui raccourcit le texte en utilisant un modèle de langue de type BERT. Selon le type d'entente et de licence obtenu avec les propriétaires, des textes permettent ou non la diffusion des textes originaux ayant servi aux analyses. La production de synthèse automatique permet de partager des résumés des articles analysés afin de rendre plus transparentes nos analyses et donner accès au contexte des résultats. Cette méthode de transformation du texte est imparfaite et est particulièrement déficiente pour certains types d'articles (les petites annonces par exemple). Elle rend tout de même possible le retour au corpus tout en respectant les ententes légales du partage des documents. 
 
### Subdivision automatique du jeu de donnée
###### Responsable : Elisabeth Doyon
Ce projet vise à produire un outil pour gérer la segmentation des grands corpus de texte pour les lourdes computations. Dans le traitement de nos données textuelles, il arrive que le temps de computation soit énorme. On parle ici d'une semaine ou plus de traitement pour une seule fonction. C'est le cas notamment lorsqu'un modèle de langue est utilisé, surchargeant la mémoire et les capacités de traitement. Il est alors préférable de perdre un peu en termes d'optimisation pour récupérer au fur et à mesure les résultats d'un traitement pour réduire le risque d'avoir à reprendre le travail depuis le début. Ce 'batching' segmentera le corpus de texte selon un ensemble de paramètres choisis par l'utilisateur qui décidera la fréquence pour les rejoindre pour l’export. 

### Projets à venir 
Nous travaillons sur l’addition d’un jeu de données sur les paroisses de Montréal à nos géodonnées, ce qui nous permettra de cartographier non seulement les quartiers, mais aussi les limites des paroisses. Ceci est particulièrement important pour des services alimentaires tels que les banques alimentaires, qui opèrent dans les communautés de façon très régionalisée. 
 
De plus, à la demande de nos partenaires, nous prévoyons explorer l’analyse de sentiments pour des arrondissements et des quartiers spécifiques, ainsi que des outils pour décrire le paysage médiatique du discours sur la sécurité alimentaire. 

## Les ateliers de formation ouverts à tous
En plus des projets, des ateliers d’nitiation à l’analyse de textes assistée par ordinateur sont donnés via les infrastructures pédagogiques à l’Université McGill afin de communiquer nos apprentissages à une plus grande communauté d’acteurs civiques et de membres de la communauté universitaire.
###### Programme 2023
Du 12 janvier au 23 mars 2023, dans le cadre du Pôle d’analyse de données sociales, le LADIREC offrira six ateliers en ligne d’initiation aux méthodes et outils d’analyse de textes assistée par ordinateur. Donnés en français, ils sont spécifiquement orientés vers l’acquisition, la structuration, la manipulation, l’analyse et la visualisation des données textuelles.

### Les essentiels de la programmation : logique et raisonnement formel 
###### Date : 12 janvier 2023 
###### Responsable :  Elisabeth Doyon
Cet atelier d’introduction vise à fournir aux étudiant·e·s et aux chercheur·euse·s qui ne sont pas familiers avec la programmation quelques notions de base qui les prépareront à plonger dans l’analyse de textes assistée par ordinateur. Qu’est-ce que la formalisation des données? Qu’est-ce qu’une chaîne de traitement et une structure de contrôle? Quels sont les opérateurs logiques utilisés en programmation?  Les participant·e·s apprendront à modéliser leurs données, à formaliser un raisonnement et à penser l’analyse d’un corpus textuel comme une série d’opérations. 
 
### La constitution de corpus pour l’analyse textuelle 
###### Date : 26 janvier 2023 
###### Responsables : Yu Chen Shi et Julien Vallières-Gingras 
Préalable à toute analyse, la constitution de corpus recouvre un ensemble de tâches parmi lesquelles il s’agit ici de proposer un parcours accessible à toutes et à tous. Quels sont les problèmes les plus fréquents que présente l’extraction de textes et quels sont les moyens de les résoudre? Cet atelier offrira une introduction pratique à l’utilisation des expressions régulières (regex) dans Microsoft Word, ainsi qu’à OpenRefine, un logiciel libre spécialisé dans la manipulation de données tabulaires. On y apprendra à extraire d’un lot de fichiers au format PDF les textes qu’il contient, à les nettoyer et à les structurer dans Microsoft Word, à les verser et réunir dans OpenRefine au sein d’une table unique à deux dimensions, et à structurer la table ainsi obtenue. 
 
### Explorer les données textuelles avec Voyant Tools 
###### Date : 9 février 2023 
###### Responsables : Lisa Teichmann et Julien Vallières-Gingras  
Voyant Tools est un progiciel d’analyse de texte gratuit disponible en ligne. Il s’agit d’un projet universitaire conçu pour faciliter les pratiques de lecture distante pour les étudiant·e·s et les chercheur·euse·s en humanités numériques. Dans cet atelier, les participant·e·s apprendront quelles sont les applications de base offertes par le progiciel; ils·elles apprendront également à créer des visualisations interactives de données textuelles à l’aide de celui-ci. Une brève introduction aux carnets Spyral, une interface développée dans le prolongement de Voyant Tools permettant d’intégrer texte, code et données dans une même pratique rédactionnelle, terminera la séance. 
 
### Explorer les données textuelles avec R 
###### Date : 23 février 2023 
###### Responsable : Pascal Brissette  
R est un langage de programmation largement utilisé par les chercheur·euse·s et les étudiant·e·s universitaires pour analyser des données, y compris les données textuelles. Il est gratuit et ouvert, tout comme son puissant et convivial environnement de programmation, RStudio, et des milliers d’extensions sont offertes par la communauté pour faciliter l’exécution de tâches comme celles liées au traitement du langage naturel (Natural language processing). Dans cet atelier, les participant·e·s auront l’occasion d’installer R et de se familiariser avec son environnement de programmation, d’importer et de manipuler un corpus textuel dans cet environnement et de produire des statistiques sur les textes du corpus et les métadonnées. 
 
### Visualiser les résultats d’analyses avec ggplot2 (R) 
###### Date : 9 mars 2023 
###### Responsables : Lisa Teichmann et Pascal Brissette
Prérequis : avoir suivi l’atelier « Explorer les données textuelles avec R », ou l’équivalent 
Les graphiques constituent un outil du plus grand intérêt pour « faire parler » les données. Qui n’a pas suivi avec plaisir ou anxiété, selon les moments, les effets de vague de la COVID à travers les courbes présentées par la Santé publique du Québec? Les courbes, les colonnes et les points permettent de dévoiler toutes sortes de dimensions des jeux de données et peuvent utilement accompagner la présentation d’analyses. Dans cet atelier, les participant·e·s apprendront diverses méthodes de visualisation de jeux de données et se familiariseront avec l’extension ggplot2 (Hadley Wickham et al.) et la grammaire des graphiques sur laquelle repose cette extension de R. 
#### https://github.com/LADIREC/202303_PB_LT_atelier_ggplot2
 
### Géolocaliser des données avec tydigeocoder et leaflet (R)
###### Date : 23 mars 2023 
###### Responsables : Lisa Teichmann  et  Pascal Brissette
La géolocalisation est un utile moyen de présenter des données et de les explorer en faisant apparaître une dimension qui échappe souvent à leur examen sous la forme de tables ou de graphiques à barres, soit leur distribution dans l’espace géographique. Cependant, ce passage de la table simple à la carte n’est pas toujours facile. Cet atelier partira d’un cas particulier, la représentation spatiale de crimes sur le territoire montréalais. On verra comment importer un jeu de données depuis le site de Données Québec, puis on utilisera les extensions tidygeocoder et leaflet for R pour projeter ces données sur une carte de la Ville de Montréal. 
