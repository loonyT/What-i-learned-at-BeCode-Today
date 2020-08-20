# What-i-learned-at-BeCode-Today
short word document recapitulating whats been worked and learned on a typical 9 to 5 be code day. 


## BeCode présentiel du 19 aout 2020

1)Premièrement, nous avons abordé l’élément Canvas qui permet d’introduire du dessin 2D et 3D en HTML/CSS/JS/mysql. Ensuite, on a vu un peu de WEB GL qui est surtout utilisé pour la 3D. 

2)Function draw img. 

3)Seneca-CDOT/ Cd3L sur github c’est un repo pour les fonctions 3D en JS. 

4)TileSet ( small drawing to represent a map in JS videogames ) 

5)What are the formats and languages to store datas ? : XML, JSON, Txt, BIN, CSV. 

6)En principe la map sera stocké dans un array. 

7)Methode Json.parse pour récupérer des datas en JSON 

8) Pour charger des datas et interprêter le JSON fraichement extrait : Ajax et la fonction de Thunder Seb

9) pour charger du JSON : XHR + GET

10) Sprites concept

11) Pour la classe “personnage” : il faudra créer des instances pour la taille de l’img, l’img sprite, la position du perso en X et Y ainsi que l’orientation du personnage.

12) Comment faire pour détecter et enregistrer les frappes au clavier ? : onkeydown / keycode and e which et combiner tout ça dans un switch

13)  Concept de la boucle principal en programmation : en fait il s’agit d’une tâche de fond pour redessiner la map en permanence pendant que le code s’exécute.

14) à priori, en JS, on utilisera pas la boucle principal mais une fonction “set interval” qui aura deux paramètres : call back et number. Le call back appelera la fonction toutes les “x” secondes indiqués dans le number paramètre.

15) CTRL + shift + I sur VS code = auto identation of the code.

16) Dans un object,  il ne faut pas mettre du code car c’est considéré comme bad practice. Il faut plutôt placer ce code dans une instanciation de l’objet. A priori, dans un array et dans un objet, on stock plutôt des données.

17)  Il faut utiliser un FLOW CHART avant tout GROS projet sinon on risque d’oublier à quoi servent certaine portions du codes qu’on a rédigé.

18)  SQL is NOT case sensitive

19) WHERE keyword act as a filter in MY SQL.

20) UPDATE keyword is to change specific datas

21) CONSTRAINTS is a keyword to create conditions to apply in SQL.

22) YOU MUST create SQL PARAMETERS to protect against SQL INJECTIONS


23)  what are the options to host SQL ? : Mysql, Oracle, MS , …. Beware because MS is not free.

24 ) in MySQL , there are lots of pre defined functions such as those ones : string functions, numeric, date, advanced. 

25)  Théorie intéressante dans l’onglet w3school : SQL servers string function and data types.

26)  Whats is “extreme programing ?” it is a concept where two people are coding on the same machine there is a driver and a navigator, it is called “pair programming” If you code that way, youll have an easier to maintain code and also a faster one.

27) Restrospect often and ask for feed back of your code.

28) Kanban exploration

29) participate to as much dev community meeting as you can

30) learn lean start up concepts

31) learn what a minimum viable product is

32) talk to as much people as you can, you can ALWAYS learn something from someone.


## BeCode distanciel du 20 aout 2020

1) l'ordre pour effectuer des opérations de calcul en javascript est PEMDAS : parenthèse, exposant, multiplication addition et puis soustraction. 

2) les boucles conditionelles : il y a différent chemionement en fonction de certaines valeures. Si la valeure est inférieur ou supérieur à un certain seuil , le traitement sera différent, il est possible d'y rajouter un bouléen comme troisième paramètres. 

3) qu'est ce qu'un label D'instruction ? il s'agit de break and continue 

4) Les opérateurs ternaires : c'est plus compliqué à déboguer mais ça permet de racourcir la syntaxe du code. In a nutshell : "?" instead of plenty of else if 

5) Les boucles for/in traite toutes les propriétés d'un objet

6) une boucle s'exécute en fonction du nombre d'éléments dans le tableau 

7) " /n" means retour à la ligne 

8) Exemple d'un array a plusieurs dimensions : Un petit jeu de Sudoku. Enormément de moyens de manipuler les datas d'un array avec push, pop, shift, split, join , ... 

9) En javascript, les objets ne SONT PAS des instances de classe. 

10) Pour ne pas faire de DRY ( do not repeat yourself)  , il est recommendé de rédiger des fonctions spécifiques. 

11) ParseInt renvoit un entier. 

12) Pour sortir plusieurs résultats d'une fonction, il faut un objet. 

13) Une variable LOCALE s'utilise avec une fonction SPECIFIQUE sinon le code devient lourd. 

14) Bibliothèque d'évents listener :www.tinyurl/kob8ugz et n5zjs4u

15) What is glitch ? 

16) Ajax interroge un script PHP pour chercher la validité d'un input html par rapport à la base de donnée. On peut aussi utiliser du REgex pour ça. 

17) Bibliothèque pour fonction de formulaire : tinyurl/maese4s or parsleys.org 

18) fonction "blurr" pour quiter un champs de formulaire spécifique. 

19) Regex sert a définir un motif et à le chercher dans une chaine de caractère : ex : tinyurl/zrsdr4q

20) Pour uniformiser les réponses à un formulaire, utilisez le snippet suivant : alerte (chaine.CharAtco).toUpperCase() + chaine.slice(1).toLowerCase() ); 
checker aussi : bibliothèque VOCA pour les chaines de caracètres et stringjs.com

21) Comment récupérer un paramètre et le renvoyer mis en forme dans une chaine de charactères ? utilisez le snippet suivant : <? php if ( isset ($_Post['id] && ( $_Post['id]!=" )))
{echo "bonjour".$_POST["id"];
else{echo "nom"] ? >

22) watch about DEVOPS : 

concept du "mur de l'incompréhension", il y a un manque de deploiement car peur de release du code non parfait. De plus, il y a un gros manque de communication entres les équipes opérationelles et les équipes de développement. La méthodo DEVOPS est la pour pallier à ce problème, tout en augmentant la productivité de l'entreprise. 

PAr exemple, sur la plateforme ETSI, il y a dix déploiements par jours, ce qui est plutôt une bonne moyenne ( après, les monstres comme Google déploit 100 fois par jours  .... ) 

Après, le personnel devops c'est un peu comme du personnel de consultance en sécurité, qui est quelque chose de nécessaire mais non obligatoire. En général, la plupart des sociétés engage des "formateurs DEVOPS". 


23) Déployer un système de recherche en AJAX : dynamiser un site en actualisant des blocs précis de contenu et non la page entière, c'est le principe de l'asyncronous javascript and XML. Cela peut se démontrer au travers du déploiement d'un champ "auto complèté" par exemple au fur et à mesure de la saisie de l'utilisateur, des suggestions piochées dans une base de donnée SQL lui sont proposée. 

code snippet du système de suggestion avec CDN jquery : 

<script src = "htttps//code.jquery.com/jquery_3.2.1min.js> </script> <style> .recherche_pays {border : ..... bg colour, margin, padding, border radius, #list pays float left, list style none, margin top, padding, width, position absolute #listePays li padding, background, li hover </style> 
               <div class = "recherche_pays"> <input type ="text" id = "recherche" placeholder ="Nom Pays" /> <div id="suggestions"> </Div> 

site très complet à propos de Ajax : http://tinyurl.com/y8pu2dhg 

Widget jquery ui pour templates de système d'auto completion. 


24) En fait Jquerry permet d'assigner dynamiquement des règles CSS 

25) Comment fonctionne un code jquery initiant un appel AJAX ?  : $document.ready function $#recherche.keyup fn $ ajax type post url recherche pays.php data : nomPays + $this. ( attention, ce snippet est remplis de fautes de syntaxes ). En français, ça donne : A chaques fois que l'user saisit un caractère dans le champs "recherche" ( évènement keyUp) on lance un appel ajax vers un script externe recherchePays.php  avec le contenu actuel du champ. Celui ci va interroer la base de données MySQL et créer une liste  à puces en conséquence avec tous les résultats suscpetibles de correspondre, c'est la quinterviennent les styles CSS pour mettre en forme les résultats§. On leur associe une fonction choixPays qui se déclenche lorsqu'uon clique sur l'une de ces suggestions : masquer les résultats et afficher le nom complet du pays dans le champ prévu à cet effet. 

Ensuite, quand un caractère dans le champs "recherch" est saisis, on déclenche l'évènement keyup et puis on appel la méthode ajax en conséquences, ceci en initiant une requète de type POST vers le script PHP. On affiche les résultats délivés dans la div suggestion et on modifie l'arrière plan du champs de recherche. 

Après, on initialise la connexion à la base de données à l'aide de la fonction mysqli_connect,pour interroger la base de donnée, c'est plutpt mysqli_query(). Ensuite, il faut utiliser select avec le keyword like qui va chercher tous les termes approchant la recherche. Ensuite on fait une liste à puce avec les résultats trouvés et on leur met la fonction choixPays lorsqu'on clique dessus. /Le système est donc très simple et souple ainsi que facilement adaptable à tout type de projet. 
=> page 63 du magazine hors série numéro 20 "web design".

26) manipuler des images en javascript : on click et hover seront souvent utilisés pour associer des comportements dynamiques aux images. Cependant, les images en JS correspondent également à un type d'objet spécifique s'accompagnant de propriétés et d'évènements spécifiques :  new Image(largeur,hauteur).
exemple : effet "lightbox", pour manipuler une image en js.  

27) En fait, de nombreuses propriétés sont associées à l'objet image, celles ci vont ensuite participer à composer l'élément HTML correspondant avec tous les attributs classiques. 

28) Erreurs récurrentes quand chargement dynamique d'une iamge : tinyurl/q94b5af

29) Cela étant dit, le CSS 3 a apporté pas mal de propriétés modernes qui ont fait que le JS s'est plutot spécialisé dans la gestion d'évènements. 

30) ajouter à une zone une balise construire à partir d'un objet : c'est ce que fait : appendChild() . 

31) Les REGEX : il s'agit d'un aspect fondamentale du javascript : puisqu'elles permettent de définir des motifs à chercher dans des chars afin de procéder à des : VALIDATION DE FORMULAIRE, des CONVERSION de syntaxe, ou des EXCTRACTIONS de contenu par exemple. C'est en quelque sorte, presqu'un language à part, qu'il est cependant presque obligatoire de bien maitriser si on veut pouvoir soutenir les usages les plus ambitieux. 

32) Les regex sont utilisés pour valider les champs  de formulaire par exemple. 

33) mémo regex : tinyurl/y8cbrvu8.

34) consolider l'apprentissage regex : tinyurl/zrsdr4q

35) exemple de Regex : tinyurl/y79lx5z3

36) Gagner du temps en testant ses regex face à des templates regex : RegExr.com, Regex101.com , RegexTester.com ce dernier site est rempli de REGEX préfabriquées :D 

37) pour vérifier une REGEX : la définir à la manière d'une chaine de caractère puis appliquer la méthode test() sur l'élément à chercher. 

38) ZOUGLOUGLOUGLOUG 

39) méthodes liées à l'objet  String et utilisés pour les regex : match, search, split, replacE. 

40) Gérer les dates et le temps en JS : Il faut savoir que la notion de temps intervient de deux manière en javascript : on utilise d'abord l'objet Date pour afficher, calculer ou manipuler tout type de dates, que ça soit des années, des jours, des mois ou même des millisecondes. Il y a même des fonction visant à décaler ou au contraire à répéter à intervalles réguliers vos traitements. 

41) méthodes et propriétés de l'objet DATE : MDN at this adress : tinyurl/yaj4lxsd. 

42) pour localiser les dates : méthode toLocaleDateString() et ses divers propriétés. 

43) le calcul du temps et des dates s'effectue par rapport à "lunix epoch"

44) grâce aux méthodes setInterval() et setTimeout(), vous retardez ou vous répétez vos traitements afgin d'aboutir aux effets les plus divers. 

45) setTimeout() permet par exemple d'automatiser le chargement d'une succession d'images pour réaliser des diaporamas. 

46) on peut chronométrer la vitesse d'exécution d'une fonction JS grâce à la méthode getTime() de l'objet Date. 

47) : Déboguage de code JS : l'inspecteur web, les devs tools des naviguateurs, console.log, créer une maquette, 

48) visite guidé de l'inspecteur ( pour firefox : tinyurl/y8gozw7m ) ( pour chrome : tinyurl/y7gmun3q). 

49) point d'arrêt sert à passer en revue l'état de nos variables et les différentes opérations sy appliquant. 

50) JS class et object : Face à un projet ambitieux, le code JS a plutot bien intérêt à être STRUCTURE. On peut reproduire le principe des classes en leur associuants des propriétés et des méthodes pour avoir un code réutilisable et moins répétitif. 

51) JS est un language de progrmation orienté PROTOTYPE, cela veut dire qu'on instancie pas des classes mais directement des objets définis sous forme de prototypes => WTF ?!

52) service de Sand boxing comme JsFiddle pour tester la création de classes. 

53) mieux comprendre la POO : tinyurl/y7vm3r23

54) création de fonctions personalisés : tinyurl/mfe8tpl

55) un constructeur sert a définir les différentes propriétés d'un objet. 

56) article pour créer des méthodes VRAIMENT original : tinyurl/y73mxwdz

57) un méthode statique sert à associer à uune classe' une méthode générale ne dépendant pas de ses différentes instances, la statique a généralement un role utilitaire au seins de la classE. Cette méthode servira par exemple a formater une valeur ou procédera à un calcul régulièrement effectué. 

58) Jquerry : apparu en 2006 c'est une bibliothèque javascript. Cette bibli est remplie de méthodes éléments et proproétés. Cette bib modernise le traitement du language JS. On gagne un temps précieux grâce à l'emploi de méthodes simples.  

59) Les sélecteur Jquerry permettent de pointer en une ligne vers tous les éléments d'un choix déterminé, c'est ce qui fait la puissance de la bibliothéque en quelques sortes. 

60) Jquerry permet de dynamiser en qq lignes de code un site web grâce aux effets d'apparition. 

61) Méthodes et propriétés de Jquery listés à l'onglet API documentation de jquery.com 

62) Jquerry UI est une bibliothéque JS spécialisée dans les éléments d'interface. 

63) En combinant Jquerry et le CSS on peut faire des "choses spectaculaires" comme par exemple capturer les sections d'une greande image afin de les isoler. 

64) prepend ajoute un élément AVANT le sélecteur concerné. 

65) pour gérer l'ensemble des animations de Jquerry, il faut appeler la méthode animate ( propriété, durée, transition, fonction ). 

66) on peut créer son propre thème JqueryUI avec Theme Roller. 

67) la méthode tab (à créer rapidement un système de navigation par ongletS. C'est utilisé notamment dans Joomla et Wordpress. 

68) il existe full méthodes prêtes à l'emploi pour réaliser de superbes effet en quelques lignes de code, il suffit de visiter l'adresse suivante : http://api.jquery.com.category/effects 

69) Méthodes et objets NOUVEAU dans HTML 5 et dans "manipulating the DOM" : HISTORY est une API permettant de stocker temporairement des données pour autoriser les retours en arrière. SELECTEURS queryselector et queryselectorAll. TIMERS pour la gestion du temps et des délais avec setInterval et clearInterval. CONTENT EDITABLE : Tiny MCE. WEBSTORAGE : solution de stockage dans la mémoire du naviguateur pour conserver jusqu'à 10 mo de données. 

70) pour dessiner en JS, on utilise l'API "canvas". 

71) on peut apprendre a gérer les transferts de fichier et déployer des systèmes ergonomiques en checkant les propriétés des méthodes de l'API FILE. 

72) API media element pour lire directement du contenu audio et vidéo dans le naviguateur. 

73) Autres méthodes et nouveaux objets en HTML 5 : GEOLOCALISATION, WEK WORKERS: puisque js ne peut pas exécuter des opérations en paralèle ( language mono tâche), lAPI WEB WORKER est la pour palier à ce problème. OFFLINE WEB APPLICATION : API pour garder en mémoire des données pour exécuter une app web même SANS CONNEXION internet. DRAGNDROP. Par exemple en combinant API FILE et DRAGNDROP, on peut créer des interfaces plus riches et plus intuitives. 

74) Canvas peut permettre d'afficher du texte et alors ltuilisateur pourra par exemple librement déplacer son text sur une image

75) GEOLOCALISATION : grâce à getCurrentPosition() on récupérer ponctuellement la position de l'utilisateur et avec watchPosition() permet le suivi du déplacement de l'utilisateur. 

76) L'API FILE READER propose plusieurs méthodes pour lire des fichiers de manières asynchrone. Grâce à cette API, on peut aussi afficher une barre de progression au cours de l'envoi, c'est à dire montrer à l'utilisateur où en est un téléchargement par exemple. 

77) Manipuler le CSS en javascript : puisque JS a full évènements et sélecteur, il joue un role de "chef d'orchestre" et associe, active et remplace tous les styles CSS lorsqu'une intéraction précise se déclenche. 

78) Il est possible de prédéfinir des classes spécifiques dans une feuille de style avec de nombreuses régler CSS, pour les appliquer d'un seul coup avec la propriété className. Exemple concrets de className : tinyurl/ya4ryqbg. 

79) Avec jQuery, il suffit d'appeler la méthode css() sur le sélecteur de son choix pour modifier ou relever la valeure des styles CSS de votre choi, tutoriel complet à l'adresse suivante : tinyurl/yaoh23k 

80) Jquery dispose d'une méthode entièrement dédiée à la définition ou à la récupération de styles : il suffit d'appliquer css ( régles, valeur) au sélecteur de son choix. 

81) Comment faire pour obtenir la valeur considéré pour réaliser des traitements et calculs spécifiques ? il faut utiliser la méthode getComputedStyle(), qui permet de récupérer des valeurs mais pas de les assigner. 

82) combiner la méthode css() avec getComputedStyle, addClass() removeClass() et switchClass() pour échanger deux classes entre elles. Par exemple, le snippet suivant va échanger les deux classes lorsqu'on survolera l'élément '#blok' dans un effet de transition non linéaire qui s'étend sur 1000ms: $("#bloc").hover(function)() { $(this).switchClass("inactive", "active", 1000, "easeInOutQuad")}; function () {$(this).switchClass("active", "inactive", 1000, "easeInOutQuad"); }); 

83) putain jcommence a en avoir plein lcul la 

84) allez courage, bientôt terminé fou. 

85) Formation complète sur l'usage de l'API FILE : tinyurl/y7el5pwn

86) trois types d'objets doivent être maitrisé pour gérer efficacement les transferts de fichiers à travers le naviguateur : FILE (pour un fichier unique) FileList ( multiples instances d'objets Files séparée dans un tableau et enfin FileReader ( pour la lecture de fichier). Très pertinent pour la gestion des CMS (content management system) bibliothéques media. 

87) API DRAGNDROP : l'objet DataTransfer va soutenir les données à transférer entre la zone de départ la zone d'arrivée, on retrouvera l'ensemble des propriétés comme la posibilité de transférer des fichiers ou de préparer divers effet de dépots. Adresse : tinyurl/nv6949z. Très intéressant comme API quand il s'agit de concevoir un panier d'achat par exemple. 

88) méthode canvas présentées de manière intéractive : www.html5canvastutorials.com 

89) série d'exemple de gestion d'animation, avec des effets avancés comme par exemple la gestion de la physique : http://tinyurl.com/y823etsb








