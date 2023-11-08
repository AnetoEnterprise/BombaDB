# INSTALLATION ET CONFIGURATION
# INTRODUCTION
Ce tutoriel porte sur BombaDB, un Système de Gestion de Bases de Données Relationnelles et Relationnelles-objets (abrégé SGBDR-O). C'est-à-dire un logiciel qui permet de gérer les bases des données, ah oui, des myriades des données confidentielles. Il utilise pour cela le langage procédural PL/URE.

Le langage procédural URE (abrégé PL/URE) souvent appelé langage fréquentiel parce qu’il laisse l’opportunité à n’importe qui de traduire ses propres syntaxes (procédures) afin de protéger ses informations confidentielles dans ledit système de gestion de base des données relationnels-objets (SGBDR-O). Selon son concepteur Guyllit Aneto Minanga de la nationalité congolaise, la meilleure façon de protéger ses données est la définition de ses propres syntaxes (procédures) afin que d’autres personnes n’arrivent pas à comprendre ou manipuler la structure des données protégées.

Vous pouvez avoir l’accès dans une ou plusieurs bases de données dans un serveur quelconque, sans connaitre les procédures à manipuler ou à exécuter, votre accès serait inutilement apprécié. Nous allons voir plus tard comment opérer les fréquences de ce langage procédural exécutable depuis l’URE afin de protéger ses informations grâce à la sécurité assurer qu’offerte l’environnement d’exécution universelle.

Pourquoi URE ?
L'environnement d'exécution universelle (abrégé par EEU ou URE en Anglais) permet à n'importe quel programmeur informatique d'adapter son système ou son langage de programmation afin qu'il soit programmable et exécutable à n'importe quelle syntaxe employée et à n'importe quelle langue existante ou nouvelle dans le monde au lieu d'utiliser les syntaxes obligatoire anglaises.

Alors grâce à cette nouvelle innovation des langues indéterminées pour la programmation informatique, BombaDB s’adapte quasiment à l'environnement d'exécution universelle (EEU) afin que ces requêtes soient universelles et exécutables en utilisant n'importe quelle langue dans le monde ou rien que des symboles informatiques.

En parlant de URE, BombaDB peut donc être utilisé depuis la console par défaut de URE ou en utilisant son propre interface SHELL. Mais, est la plupart du temps combiné à un autre langage de programmation comme : PHP par exemple pour des nombreux sites web, mais aussi Java, JavaScript, Python, et C++.

Avant de procéder à l'installation et configuration de BombaDB, vous devez tout d'abord installer l'environnement d'exécution universel (EEU ou URE) en utilisant la commande :
Sous LINUX, tapez la commande :

```shell
sudo wget https://sourceforge.net/projects/ure/files/1.2/ConsoleLinux/ure-1.2.tar.xz

tar -xvf ure-1.2.tar.xz

cd ./SETUP/

./install.sh

rm -r ../SETUP



sudo wget https://sourceforge.net/projects/ure/files/1.2/AllModulesLangs/LINUX/URE-Libs-Langs-1.0-0.x86_64.tar.xz

tar -xvf URE-Libs-Langs-1.0-0.x86_64.tar.xz

cd SETUP/

./install.sh

```

Sous WINDOWS, en utilisant CYGWIN tapez la commande :
```shell
wget https://sourceforge.net/projects/ure/files/1.2/CYGWIN/ure-1.2.tar.xz

tar -xvf ure-1.2.tar.xz

cd ./SETUP/

./install.sh

rm -r ../SETUP



wget https://sourceforge.net/projects/ure/files/1.2/AllModulesLangs/CYGWIN/URE-Libs-Langs-1.0-0.x86_64.tar.xz

tar -xvf URE-Libs-Langs-1.0-0.x86_64.tar.xz

cd SETUP/

./install.sh

```

Pour NodeJS, tapez la commande  :
```shell
npm i ure_mod_linux all_langs_linux all_test_syntaxes
```
Sous MACOS, tapez la commande :
```shell
wget https://sourceforge.net/projects/ure/files/1.2/MACOS/ure-1.2.tar.xz

tar -xvf ure-1.2.tar.xz

cd ./SETUP/

./install.sh

rm -r ../SETUP



wget https://sourceforge.net/projects/ure/files/1.2/AllModulesLangs/MACOS/URE-Libs-Langs-1.0-0.x86_64.tar.xz

tar -xvf URE-Libs-Langs-1.0-0.x86_64.tar.xz

cd SETUP/

./install.sh

```

Nous venons d'installé l'environnement d'exécution universelle (URE) y compris ces composants. Maintenant passons à l'installation de notre système de gestion de base des données BombaDB.

![alt text](https://github.com/AnetoEnterprise/BombaDB/blob/main/images/Installation.png)
# INSTALLATION
Ce guide d'installation du dit système de gestion de base des données requiert un environnement LINUX, MAC OS ou WINDOWS depuis l’interface SHELL. Alors vous avez le choix d’installation parmi les différentes plateformes proposées et d’en choisir celle qui vous convienne la plus facile. Assurez-vous que votre connexion internet marche successivement afin de procéder à l’installation. Et dans cet exemple nous allons procéder à l’installation de la version classique. Vous pouvez changer la version d’édition selon vos besoins.

Sous LINUX, placez-vous sur le SHELL et tapez les commandes :

```shell
sudo wget https://download.bombadb.tech/LINUX/BombaDB-classic-1.0-0.x86_64.tar.xz

tar -xvf BombaDB-classic-1.0-0.x86_64.tar.xz

cd BOMBADB/

./install.sh

```

Sous WINDOWS depuis la console CYGWIN, tapez les commandes :
```shell
wget https://download.bombadb.tech/CYGWIN/BombaDB-classic-1.0-0.x86_64.tar.xz

tar -xvf BombaDB-classic-1.0-0.x86_64.tar.xz

cd BOMBADB/

./install.sh

```
Et sur MACOS, tapez les commandes :
```shell
wget https://download.bombadb.tech/MACOS/BombaDB-classic-1.0-0.x86_64.tar.xz

tar -xvf BombaDB-classic-1.0-0.x86_64.tar.xz

cd BOMBADB/

./install.sh

```
Comme vous pouvez le voir, l’installation du système de gestion de base des données (BombaDB) est si simple que ça en a l’air. Passons maintenant à la configuration de notre système téléchargé et installé afin de structurer et faire en sorte qu’il reconnaisse nos nouvelles langues pour l’exécution des taches avenir sécurisées

![alt text](https://github.com/AnetoEnterprise/BombaDB/blob/main/images/Configuration.png)
# CONFIGURATION
Par défaut BombaDB utilise la configuration structurée francophone. Telle est la langue officielle de la République Démocratique du Congo. Tous les messages en cas du succès ou d'échec sont quasiment édités en français. Pour les configurer comme bon vous semble afin de traduire la langue par défaut et d’utiliser celle qui vous convienne, vous devez trouver un fichier lang.conf dans le répertoire précis depuis :
/usr/share/bombadb/ sous LINUX;
/usr/share/bombadb/ sous CYGWIN (WINDOWS);
C:/bombadb/ sous WINDOWS;
/usr/share/bombadb/ sous MAC OS.

Pour se faire, sous LINUX, tapez la commande :
```shell
sudo nano /usr/share/bombadb/lang.conf
```
En utilisant CYGWIN ou MSYS, la commande belle et bien :
```shell
nano /usr/share/bombadb/lang.conf
```
Sous WINDOWS depuis l'invite de commandes (CMD), tapez la commande :
```shell
notepad "C:/bombadb/lang.conf"
```
Sous MACOS, tapez la commande :
```shell
nano /usr/share/bombadb/lang.conf
```
Une fois la commande est correcte, vous allez voir les informations ci-après apparaitront afin de bien configurer et traduire les messages concernant le succès ou l’échec de vos procédures avenir :
```shell
:-1:/usr/db/bombadb/
:0:    ->:B1:Désolé, erreur fatale de la résolution.:A2::EE:
:1:    ->Désolé, syntaxes ::EE::B1::E1::A2::EE:Non valide depuis ::A1::E2::A2::EE:
:2:    ->:B1:Désolé, syntaxes non valide depuis ::EE::E1::A2::EE:
:3:    ->:B1:Désolé, certains champs ne sont pas définis.:A2::EE:
:4:    ->:B1:Désolé, impossible d'ajouter l'utilisateur (:E1:).:A2::EE:
:5:    ->:B1:Désolé, utilisateur :E1: existe déjà.:A2::EE:
:6:    ->:B1:Désolé, impossible de vérifier (:E1:).:A2::EE:
:7:    ->:A1:Utilisateur :E1: ajouté correctement !:A2::EE:
:8:quitter
:9:ERREUR
:10:    ->Désolé, la requete ::EE::B1:    ->:E1::A2::EE:    ->N'est pas valide.:EE:
:11:    ->:B1:Echec de Socket !:A2::EE:
:12:    ->Désolé, le répertoire ::EE::B1:    ->:E1::A2::EE:    ->Est introuvable.:EE:
:13:    ->:B1:Désolé, échec de connexion.:A2::EE:
:14:    ->:B1:Désolé, aucune information définie pour lancer le serveur BombaDB.:A2::EE:
:15:    ->En écoute depuis le port : :E1::EE:
:16:    ->:B1:Un utilisateur déconnecté:A2::EE:
:17:    ->Nouvelle connexion, le socket est : :E1:, IP : :E2:, le port est : :E3::EE:
:18::A1:Au revoir !:A2::EE:
:19:Client ajouté à la liste via le socket : :E1::EE:
:20:    ->:B1:Erreur d'obtention de la valeur :E1:.:A2::EE:
:21:    ->:B1:Client déconnecté, IP : :E1:, PORT : :E1::A2::EE:
:22:PORT:8899
:23::A1:Mot de passe ::A2:
:24:Bienvenu(e) sur BombaDB moniteur. Toutes les commandes requises un ; à la fin.:EE:Copyright (c) :A1:2021-:E1::A2:, par AnetoEnterprise Inc. Tout droit réservée.:EE:BombaDB est la marque déponsée de
:25::B1:Le nom d'utilisateur ou le mot de passe n'est pas valide.:A2::EE:
:26::B1:Erreur de la création d'un socket.:A2::EE:
:27::B1:Adresse invalide. Non supportée.:A2::EE:
:28::B1:Désolé, la base des données :A1::E1::A2: est introuvable.:A2::EE::A1:Vous devez d'abord créer une vers le répertoire (:E2:).:A2::EE:
:29::B1:Désolé, érreur fatale des informations définies.:A2::EE:
:30::B1:Désolé, érreur de la création de la base des données :E1:.:A2::EE:
:31::A1:La base des données :E1: crée correctement !:A2::EE:
:32::B1:Désolé, l'utilisateur défini n'existe pas.:A2::EE:
:33::B1:Désolé, le mot de passe n'est pas correcte.:A2::EE:
:34::A1:Modifié correctement !:A2::EE:
:35::A1:Supprimé correctement !:A2::EE:
:36::B1:Désolé, érreur fatale de la mise à jour.:A2::EE:
:37::B1:Désolé, cette action ne peut etre éffectuer sur le poste client.:EE:Pour la sécurité, vous devez etre un administrateur afin d'exécuter cette action depuis le serveur spécifique en utilisant URE.:A2::EE:
:38:    ->:B1:Désolé, aucune base des données existante trouvée.:A2:
:39:BASE DES DONEES
:40:TYPE
:41::A1:Appuyez sur la touche entrée pour valider ::A2:
:42:    ->:B1:Désolé, la base des données:A2: :A1::E1::A2: :B1:existe déjà.:A2:
:43:    ->:B1:Désolé, la table:A2: :A1::E1::A2: :B1:existe déjà.:A2:
:44:    ->:B1:Désolé, la création de la table:A2: :A1::E1::A2: :B1:impossible.:A2:
:45:    ->La table :A1::E1::A2: ajoutée correctement via :A1::E2::A2: !
:46:    ->:B1:Désolé, colonne(s):A2: :A1::E1::A2: :B1:non valide.:A2::EE:
:47:    ->:B1:Désolé, aucune information trouvée.:A2::EE:
:48::E1: :A1:Table et:A2: :E2: :A1:Utilisateur(s) supprimé(s) correctement.:A2::EE:
:49:DONNEES
:50:Supprimé(s) correctement.
:51:    ->:B1:Désolé, colonne(s):A2: :A1::E1::A2: :B1:mal définie.:A2::EE:
:52:    ->:B1:Désolé, la taille limite de la colonne :A2: :A1::E1::A2: :B1: est :A2: :A1::E2::A2::B1:. Elle à était remplacé par la valeur vide.:A2::EE:
:53:    ->:B1:Désolé, erreur dans la table au format de l'attribut :A2: :A1::E1::A2: :B1: mal définie et remplacé par la valeur vide.:A2::EE:
:54:    ->:B1:Désolé, la colonne :A2: :A1::E1::A2: :B1: devrait comporter uniquement les chiffres. Elle à était remplacé par la valeur vide.:A2::EE:
:55:    ->:B1:Désolé, la colonne :A2: :A1::E1::A2: :B1: est mal définie et remplacé par la valeur automatique.:A2::EE:
:56:    ->:B1:Désolé, la valeur:A2: :A1::E1::A2: :B1: de l'attribut :A2: :A1::E2::A2: :B1:ne corresponde pas.:A2::EE:
:57::A1:Les informations ont étaient inserées correctement dans la table:A2: :E1::EE:
:58:    ->:B1:Désolé, les colonnes définies ne sont pas au complet comme définie sur la table :A2: :A1::E1::A2::EE:
:59:    ->:B1:Désolé, la table :A2: :A1::E1::A2: :B1:inexistante.:A2::EE:
:60:    ->:B1:Désolé, erreur d'insertion des données dans la table :A2: :A1::E1::A2::EE:
:61::B1:L'application:A2: :A1::E1::A2: :B1:non trouvée.:A2:
:62::B1:Le fichier:A2: :A1::E1::A2: :B1:non trouvé et remplacé par la valeur vide.:A2:
:63::B1:Désolé, le nombre limite dans l'attribut:A2: :A1::E1::A2: :B1:est:A2: :A1::E2::A2: :B1:Vous avez spécifié:A2: :A1::E3::A2: :B1:charactères.:A2:
:64:    ->:B1:Désolé, aucune information trouvée au terme de la récherche spécifiée :A2: :A1::E1::A2::EE:
:65:    ->:B1:Désolé, le nombre limite des colonnes est de 5. Veuillez reduire les attributs définis dans :A2: :A1::E1::A2::EE:
:66:    ->:B1:Lecture impossible de la donne ::A2::EE::A1::E1::A2::EE:
:67:HEURE
:68:DATE
:69:HEURE et DATE
:70::A1:Mise à jour effectuée !:A2::EE:
```
Comme vous pouvez le voir, depuis la ligne :-1, BombaDB utilise le répertoire /usr/db/bombadb/ afin de detecter le chemin par défaut d'ou toutes les données vont etre enregistrer. Vous êtes libre de changer le répertoire des données, de modifier la langue par défaut et d'utiliser celle qui est compréhensive pour votre administration, à condition de ne pas modifier le numéro des lignes et des lettres qui sont entre les deux points. Cet exemple de fichier de configuration est strictement basé à la configuration du système de gestion BombaDB et non pour la traduction de vos syntaxes procédurales et sécuritaires.

Pour la meilleure compréhension de ces caractères (balises) entre les deux points :

 Les caractères numériques qui sont entre les deux points comme par exemple :0: définis le numéro de ligne sur lequel BombaDB détectera la ligne du message à retourner par l’action effectuée, en cas d’échec ou du succès ;

 Les textes qui sont entre :B1: et se termine par :A2: sont définis pour le renvoi des messages d’erreurs utilisant la couleur rouge depuis l’environnement console (SHELL) ;

 Et les textes qui débutent avec la balise :A1: et se termine par :A2: affiche effectivement le message du succès en vert ;

 La balise :E1:, :E2: ou :E3: définis l’emplacement sur lequel le nom ou syntaxes d’échec ou du succès serait placer pour la meilleure compréhension de la réponse de retour après l’action ;

 Et pour clôturer, la balise :EE: définie le saut de ligne à chaque fin du message renvoyer au SHELL ou via le poste client.

Par exemple, modifions la ligne :69: en français pour l’anglais :
     Français	             Anglais
:69:HEURE et DATE	    :69:TIME and DATE

On voie clairement que le numéro de la ligne reste le 69 entre les deux points, contrairement nous avons pu traduire l’HEURE et la DATE. Passons maintenant à la configuration et définition de nos propres syntaxes (procédures) à exécuter depuis l’environnement d’exécution universelle (URE) pour mieux gérer les données en toute sécurité.

Comme nous l’avions précisé, BombaDB utilise le langage procédural universel (PL/URE) et c’est-ce qui fait qu’il soit un langage de programmation fréquentiel. C’est-à-dire, dans chaque syntaxe (procédure) vous devez respecter l’ordre de fréquence des attributs définies après le signe égal (=) ou entre parenthèse (). Avant de comprendre comment les procédures qu’utilise BombaDB pour la traduction des syntaxes universelles fonctionnent, passons premièrement à la création de notre fichier des syntaxes qui sera utilisé pour les requêtes et la sécurité des informations relative aux données protégées.

Vous devez savoir qu’après l’installation de l’environnement d’exécution universelle (EEU ou URE en anglais), un répertoire /usr/share/ure/int/ était créé automatiquement. C’est par ce répertoire que nous allons placer notre fichier des syntaxes pour qu’il comprenne la langue sur laquelle nous allons procéder pour la gestion de nos informations personnelles. Dans ce cas, vous avez le choix d’utiliser une langue existante pour vos requêtes ou d’en créer votre propre langue pour la meilleure sécurité de vos informations.

Créons maintenant notre fichier des syntaxes à utiliser avec BombaDB et qui sera compréhensif au langage PL/URE :
Sous LINUX, placez-vous dans n'importe quel répertoire dans votre disque dur et tapez la commande :
```shell
sudo nano mes_syntaxes.txt
```
En utilisant CYGWIN ou MSYS sous (WINDOWS), tapez la commande :
```shell
nano mes_syntaxes.txt
```
Sous MACOS, tapez la commande :
```shell
nano mes_syntaxes.txt
```
Comme exemple, nous allons inserer deux lignes des syntaxes dans le fichier mes_syntaxes.txt afin de vous clarifier un peu les fonctionnements du langage procédural PL/URE :
Syntaxes francophones :
```shell
quitter (bomba_exit);

calculer ?+? (bomba_math);
```
Syntaxes anglophones :
```shell
exit (bomba_exit);

sum ?+? (bomba_math);
```
Syntaxes lingalaphones :
```shell
bima (bomba_exit);

pesa réponse ya ?+? (bomba_math);
```
Pourquoi nous n’avons pas pu modifier ou traduire les syntaxes qui sont entre parenthèse dans notre fichier de syntaxes ?
Parce que c’est sont des bibliothèques BombaDB que nous avons utilisée ou appelée afin d’exécuter nos syntaxes facilement dans n’importe quelle langue.

NB : Nous avons le choix de définir une ou plusieurs langues dans le même fichier des syntaxes à utiliser. Ça dépend des administrateurs sur lesquels vont gérer vos données. Si vous êtes le seul administrateur qu’utilisera l’unique accès, par exemple l’utilisateur : root et le mot de passe : 12345, il est conseillé de définir qu’une seule langue pour vous-même. Au cas contraire, si le même accès serait utilisable à plusieurs personnes (administrateurs), dans ce cas vous avez le choix de définir plusieurs langues pour chaque administrateur. Cette méthode est déconseillée si chaque administrateur utilise son propre accès pour la gestion des informations.

Maintenant il est temps de copier et coller notre fichier des syntaxes dans le répertoire /usr/share/ure/int/ pour que l’environnement d’exécution universelle les comprennent facilement et d’exécuter les taches voulues :

```shell
cp -r ./mes_syntaxes.txt /usr/share/ure/int/
```
Attention, si vous voulez que personne d'autre ne comprenne vos syntaxes des gestions, vous devez premièrement sécuriser votre fichier avant qu'il soit copier dans le répertoire /usr/share/ure/int/ comme suite :
Depuis la console, lancer l'environnement d'exécution universelle (EEU) comme suite :
```shell
ure
```
Exécuter la commande suivante :
```shell
ure -e "mes_syntaxes.txt" ".ure"
```

Par la suite, copier le fichier des syntaxes au répertoire /usr/share/ure/int/ :
```shell
cp -r ./mes_syntaxes.txt /usr/share/ure/int/
```
On voie clairement que nous avons pu définir l’extension .ure pour notre fichier de syntaxes sécurisé et accessible qu’a nous seul. Essayons maintenant nos syntaxes afin de savoir qu’elles fonctionnent correctement :
```shell
:s:mes_syntaxes.ure;
calculer 2+3;
quitter;
```
A la première ligne de commande depuis le SHELL URE, nous avons pu préciser à l’environnement d’exécution universelle de lire rien que notre fichier des syntaxes et par la suite on exécute nos commandes de teste aisément qui nous renvoi les résultats 

![alt text](https://github.com/AnetoEnterprise/BombaDB/blob/main/images/Calcul_Classique.png)

Le resultat de la commande (calculer 2+3) affirme que BombaDB renvoi ces resultat au format JSON afin qu’ils soient manipulables dans n’importe quel système informatique. Nous venons de voir comment installer et configurer l’environnement d’exécution universelle y compris BombaDB. Maintenant il est temps de savoir le reste des syntaxes avancer dans la rubrique MANUEL DE REFERENCE ci-après :

![alt text](https://github.com/AnetoEnterprise/BombaDB/blob/main/images/Manuel.png)
# MANUEL DE RÉFERENCE
Maintenant que tous fonctionnent correctement, nous allons passer à la compréhension et traduction de langage procédural PL/URE afin de bien gérer les informations. Comme nous l’avions précisé depuis la page d’installation, le langage URE ou environnement d’exécution universelle est fréquentiel. Il suffit de tous traduire comme bon vous semble à condition de respecter la position active de chaque attribut définie.

# IMPORTANT :
Vous n’êtes pas obliger de définir toutes les syntaxes que nous allons expliquer sur cette page dans votre fichier des syntaxes. Vous êtes libre de choisir quelques syntaxes utiles de votre base des données afin que toute autre action inutile ne s’exécute pas. Parce que si la syntaxe définie ou l’action effectuée ne se retrouve pas dans le fichier des syntaxes (votre fichier des syntaxes), même si un hackeur ou qui que ce soit l’exécute, l’environnement d’exécution universelle (EEU ou URE) n’exécutera aucune action. C’est-ce qui fait que BombaDB soit le système de gestion de base des données le plus sécurisé tant qu’il exécute uniquement les syntaxes qu’on lui ordonne par le propriétaire de la base des données lui-même.


En parlant de la sécurité, BombaDB occupe 3 facteurs des sécurités :

 Le facteur premier : Est celui de l’accès à la base des données ;

 Le facteur secondaire : Planché par la vérification correcte des syntaxes ;

 Le troisième ou dernier facteur : Vérifie si l’utilisateur connecté à l’autorisation d’exécuter ou pas la procédure en cours et en attente de ses résultats.

Passons maintenant aux choses sérieuses :
Premièrement nous allons définir dans notre fichier des syntaxes la procédure sur laquelle nous permettra de créer une ou plusieurs bases des données en cas utile. Comme nous avons déjà notre fichier mes_syntaxes.txt, ajoutons-le la ligne des syntaxes suivante :

# 1. CRÉATION DE LA BASE DES DONNÉES :
Syntaxes francophones :
```shell
créer base des données=`?`

utilisateur=`?`

mot de passe=`?`

type des données=`?`

(bomba_createdb);
```
Syntaxes angloophones :
```shell
create database=`?`

user=`?`

password=`?`

data type=`?`

(bomba_createdb);
```
Syntaxes lingalaphones :
```shell
sala ébombelo=`?`

mosaleli=`?`

liloba yako kota=`?`

modelo ya makambo=`?`

(bomba_createdb);
```
Un peu d’explication pour notre langage procédural fréquentiel (PL/URE) :
L’environnement d’exécution universelle détecte automatiquement les valeurs qui sont après les attributs égal =, l’entre parenthèse () ou entre les accolades {}. Comme vous venez de le voir, nous avons uniquement traduit nos syntaxes françaises aux syntaxes anglaises et sans oublié en lingala (La langue la plus répandue et utilisée en République Démocratique du Congo). Mais nos symboles égaux (=) restent dans leurs positions exactes afin de définir leurs fréquences par l’environnement d’exécution universelle.

Pour les points d’interrogations (`?`) qui sont entre des petits guillemets, ceux-là définissent que les valeurs sur lesquelles les administrateurs vont saisir dans les attributs de leurs langues traduites tout en respectant leurs fréquences, doivent être utilisées en tant que valeurs valides. Meme si vous avez bouleversé vos syntaxes, l’environnement d’exécution universelle détectera les attributs par l’ordre automatique fréquentiel que le nom de la base des données soit sur le premier attribut, son utilisateur sur la seconde position fréquentielle et ainsi de suite.

A noter que BombaDB utilise deux types des données pour l’édition classique :

 Le 0 : Définit le type de base des données qu’utilise qu’un seul fichier pour stocker toutes les informations personnelles dans ledit fichier (Portable) ;
NB : Ce type de base des données est limité à un faible volume des données.

 Le 1 : Celui-ci définit le type des données indépendantes qui peuvent être stockées dans plusieurs fichiers indépendamment (Non portable).
NB : Il est capable de gérer des myriades des données en meme temps.

Enregistrer les modifications apportées à notre fichier mes_syntaxes.txt, sécurisez-le en utilisant la méthode de conversion URE que nous avons pu procéder à la page de configuration BombaDB et par la suite copiez-le dans le répertoire /usr/share/ure/int/. Alors, vous êtes libre de tester votre nouvelle ligne des syntaxes afin de créer votre nouvelle base des données en exécutant la commande suivante depuis le SHEL URE :
```shell
:s:mes_syntaxes.ure;

créer base des données=`testdb`

utilisateur=`root`

mot de passe=`12345`

type des données=`0`;
```

Vous savez maintenant comment traduire les syntaxes de notre langage procédural (PL/URE). Avançons maintenant pour l’ajout d’un ou plusieurs utilisateur(s) dans notre nouvelle base des données crée.

# 2. AJOUT D’UTILISATEUR DANS LA BASE DES DONNÉES :
Ajoutons la ligne suivante dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
ajout utilisateur=`?`

mot de passe=`?`

comme syntaxes=`?`

utilisateur existant=`?`

mot de passe existant=`?`

dans la base des données=`?`

(bomba_add_userdb);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante :
```shell
:s:mes_syntaxes.ure;

ajout utilisateur=`user2`

mot de passe=`1234`

comme syntaxes=`quitter (bomba_exit)#afficher '?' (bomba_print)#calculer ?+? (bomba_math)#`

utilisateur existant=`root`

mot de passe existant=`12345`

dans la base des données=`testdb`;
```

Examinons un peu la ligne 4 en ciblant l’attribut syntaxes. On voie clairement que nous avons pu définir quelques syntaxes sur lesquelles notre nouveau invité utilisateur, dénommé user2, utilisera comme procédures correctes afin de sécurisé les informations structurées dans la base des données. Qui veut dire qu’il n’est pas autorisé à exécuter d’autres procédures que celles spécifiées dans son compte automatiquement. Autrement nous pouvons dire que c’est la seule manière que BombaDB gère les droits d’accès aux sous utilisateurs de la base des données tant qu’à la création de la base des données, un administrateur primordial à était déjà ajouté utilisant le nom : root et comme mot de passe : 12345.
Pour clarifier, notre sous utilisateur exécutera que les procédures :
```shell
quitter (bomba_exit);

afficher '?' (bomba_print);

calculer ?+? (bomba_math);
```

Vous vous poser des questions concernant les symboles # ?
Tant que dans nos syntaxes principales nous utilisons déjà les points virgules, alors pour le sous utilisateur, ses syntaxes dans la base des données devraient être structurées et finir par #. A son exécution avenir, l’environnement d’exécution universelle remplacera le Diez (#) contenu dans la base des données par le point-virgule (;) saisi par le sous utilisateur automatiquement afin que les procédures exécutées fonctionnent correctement.

# 3. LISTAGE DES UTILISATEURS DANS LA BASE DES DONNÉES :
Ajoutons la ligne suivante dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
lister les utilisateurs=`?`

utilisateur existant=`?`

mot de passe existant=`?`

dans la base des données=`?`

(bomba_list_userdb);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante :
```shell
:s:mes_syntaxes.ure;

lister les utilisateurs=`*.*`

utilisateur existant=`root`

mot de passe existant=`12345`

dans la base des données=`testdb`;
```

![alt text](https://github.com/AnetoEnterprise/BombaDB/blob/main/images/Connecteur.png)
# CONNECTEUR
Guide rélatif aux connecteurs pour l'utilisation de BombaDB à d'autres langage de programmation.
