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

21) Comment récupérer un paramètre et le renvoyer mis en forme dans une chaine de charactères ? utilisez le snippet suivant : 

<? php if ( isset ($_Post['id] && ( $_Post['id]!=" )))
{echo "bonjour".$_POST["id"];
else{echo "nom"] ? >

22) watch about DEVOPS : 

concept du "mur de l'incompréhension", il y a un manque de deploiement car peur de release du code non parfait. De plus, il y a un gros manque de communication entres les équipes opérationelles et les équipes de développement. La méthodo DEVOPS est la pour pallier à ce problème, tout en augmentant la productivité de l'entreprise. 

PAr exemple, sur la plateforme ETSI, il y a dix déploiements par jours, ce qui est plutôt une bonne moyenne ( après, les monstres comme Google déploit 100 fois par jours  .... ) 

Après, le personnel devops c'est un peu comme du personnel de consultance en sécurité, qui est quelque chose de nécessaire mais non obligatoire. En général, la plupart des sociétés engage des "formateurs DEVOPS". 





