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

Vous avez le choix maintenant entre la version Classique ou Standard de BombaDB suivante :

![alt text](https://github.com/AnetoEnterprise/BombaDB/blob/main/images/Classique200.png)
# BOMBADB EDITION CLASSIQUE (1.0.0)
Utiliser BombaDB la version classique (traditionnelle) offerte pour les données des petits volumes et de disposer d’un volume important de données afin d’accéder rapidement et fréquemment à vos données.

![alt text](https://github.com/AnetoEnterprise/BombaDB/blob/main/images/standard200.png)
# BOMBADB EDITION STANDARD (1.0.0)
Combiner les deux versions traditionnelle et version de traitement ou sauvegarde en mémoire pour un traitement des données accéléré, une nouvelle orientation pour vos systèmes grâce à des applications novatrices et d'une plus grande adaptabilité.

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

# 4. MISE À JOUR DES INFORMATIONS UTILISATEUR DANS LA BASE DES DONNÉES :
Ajoutons la ligne suivante dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
mise à jour du mot de passe=`?`

dans la base des données=`?`

mot de passe existant=`?`

(bomba_modify_userdb);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante :
```shell
:s:mes_syntaxes.ure;

mise à jour du mot de passe=`1234`

dans la base des données=`testdb`

mot de passe existant=`12345`;
```

# 5. SUPPRESSION DE LA BASE DES DONNÉES :
Ajoutons la ligne suivante dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
supprimer la base de données=`?`

utiliser le mot de passe=`?`

(bomba_deletedb);
```
Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante :
```shell
:s:mes_syntaxes.ure;

supprimer la base de données=`testdb`

utiliser le mot de passe=`1234`;
```
# 6. LISTAGE DES BASES DES DONNÉES :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
lister les bases des données

(bomba_listdb);



lister les bases des données et connecter depuis l'utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_listdb);
```

Pourquoi dans la première ligne de syntaxe insérée n’a pas surement les accès pour se connecter à la base des données ?

Notre première ligne de syntaxe définie le type de procédure qui sera exécuté directement depuis le SHELL BombaDB utilisant la technologie client-serveur parce que depuis son interface, les accès sont définis qu’une seule fois. Tandis que la seconde ligne de syntaxe définie comme toujours le type de procédure qui s’exécute uniquement en utilisant l’environnement d’exécution universelle. A noter que pour la sécurité des informations relatives aux données, BombaDB privilégie certaines procédures afin qu’elles s’exécutent uniquement depuis l’interface SHELL URE pour l’assurance des données et non en utilisant le SHELL BombaDB d’un poste client. Vous pouvez avoir plus d’informations concernant BombaDB SHELL dans la rubrique Guide des connecteurs.

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

lister les bases des données

et connecter depuis l'utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```

Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante :
```shell
lister les bases des données;
```

Toutes les deux procédures testées depuis le SHEL URE ou BombaDB ont les mêmes resultat que de lister les bases des données crées dans votre disque dur.

# 7. CRÉATION DE LA TABLE :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt afin d'ajouter ou créer la nouvelle table test_table :
```shell
créer la table=`?` colones=`?` (bomba_createtb);



créer la table=`?`

colones=`?`

utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_createtb);
```

Avant de convertir et d’exécuter nos deux procédures ajoutées dans le fichier des syntaxes, nous devons premièrement comprendre chaque paramètre défini dans chaque colonne de la nouvelle table test_table. Voici une liste exhaustive des paramètres à adapter aux attributions de vos nouvelles tables :

 A() : Ce paramètre est utilisé afin d’incrémenter automatiquement les identifiants de chaque information insérée dans la table. Par défaut, utilise le nombre illimité de génération des identifiants automatiques. Et vous pouvez limiter le nombre d’identifiant en utilisant par exemple : ID:A(20) Ce qui veut dire, nous avons adapté à l’attribut ID (Identifiant) de limité la génération d’identifiant une fois que le nombre des chiffres générés sont strictement arrivés à 20 caractères (53647283645372837263).

 C() : Celui-ci est quasiment utiliser pour l’insertion de courte information. Comme le premier paramètre, vous avez le choix de spécifier le nombre limite des caractères à insérer.

 N() : Comme sa lettre l’indique, le N signifie le nombre. Il est souvent utilisé pour les attributs basés sur l’insertion de caractères numériques. Et par défaut, utilise comme nombre illimité des valeurs à insérer. Vous pouvez définir le nombre limite des caractères à insérer comme bon vous semble.

 L () : Signifie long en français, permet l’insertion des plusieurs caractères simultanément. Utiliser pour l’insertion de message ou commentaire d’une information. Ce paramètre n’as pas d’option supplémentaire comme d’autres.

 D() : Définie la date en cours. Elle peut être modifiée selon le format de votre choix. Par défaut utilise le format (dd/mm/yyyy) ou (jj/mm/yyyy), vous pouvez définir d’autres format tels que : (yyyy/mm/dd) ou (dd/mm).

 T() : Le paramètre T() définie le TEMPS, souvent utilisé pour l’affichage ou l’insertion de l’heure dans la base des données. Utilise comme options supplémentaires H : Pour l’heure en cours, M : Pour la minute et S : ou I : Pour la seconde. On aura comme paramètre (h:m:s) ou (h:m:i). Ou encore (h:m).

 P() : Utiliser uniquement pour l’insertion des informations chiffrées (cryptées). Souvent utiliser pour le chiffrement de mot de passe.

 F() : Pour finaliser, le paramètre du fichier permet à la base des données d’être compatible à intégrer d’autres fichiers binaires dans la base des données qu’ils soient portable avec d’autres informations insérées dans la base des données.

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

créer la table=`test_table` colones=`ID:a(),NOM:c(10),POSTNOM:c(10),PRENOM:c(10),TEL:n(12),DETAILS:l(),DATE:d(dd/mm/yyyy),HEURE:t(h:m:i),MOTDEPASSE:p(),FICHIER:f()`

utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```

Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante :
```shell
créer la table=`test_table` colones=`ID:a(),NOM:c(10),POSTNOM:c(10),PRENOM:c(10),TEL:n(12),DETAILS:l(),DATE:d(),HEURE:t(),MOTDEPASSE:p(),FICHIER:f()`;
```

Comme toujours, toutes les deux procédures qu'elles soient testées depuis le SHEL URE ou BombaDB ont les mêmes resultat.

# 8. MODIFICATION DE LA TABLE :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt qui nous permettront de modifier les colonnes de la table elle-même :
```shell
mise à jour de la table=`?`

colones=`?`

(bomba_modifytb);



mise à jour de la table=`?`

colones=`?` utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_modifytb);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

mise à jour de la table=`test_table`

colones=`ID:A(20)`

utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```
Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante afin de mettre à jour la colonne ID :
```shell
mise à jour de la table=`test_table`

colones=`ID:A(20)`;
```

On voie belle et bien que la colonne ID qu’utilisée comme paramètre A(), mise à jour par A(20). Vous avez le choix de mettre à jour une ou plusieurs colonnes en meme temps, en utilisant un séparateur virgule(s). Comme par exemple ID:A(20),NOM:C(4)

# 9. SUPPRESSION DE LA TABLE EXISTANTE DANS LA BASE DES DONNÉES :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
supprimer la table=`?`

(bomba_deletetb);



supprimer la table=`?`

utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_deletetb);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

supprimer la table=`test_table`

utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```

Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante afin de mettre à jour la colonne ID :
```shell
supprimer la table=`test_table`;
```

# 10. INSERTION DANS LA TABLE :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
inserer dans la table=`?`

colonnes=`?`

(bomba_insert);



inserer dans la table=`?`

colonnes=`?`

utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_insert);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

inserer dans la table=`test_table`

colonnes=`ID:1,NOM:Aneto,POSTNOM:Minanga,PRENOM:Guyllit,TEL:0842666616,DETAILS:Test d'insertion.,DATE:19/09/2022,HEURE:10:41,MOTDEPASSE:monApplication.exe>0000,FICHIER:monfichier.txt`

utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```

Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante :
```shell
inserer dans la table=`test_table`

colonnes=`ID:a(),NOM:Aneto,POSTNOM:Minanga,PRENOM:Guyllit,TEL:0842666616,DETAILS:Test d'insertion des informations.,DATE:d(),HEURE:t(),MOTDEPASSE:monApplication.exe>0000,FICHIER:monfichier.txt`;
```

# 11. SELECTION DES DONNÉES DANS LA TABLE :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
selectionner dans la table=`?`

colonnes=`?`

d'ou=`?`

(bomba_select);



selectionner dans la table=`?`

colonnes=`?`

d'ou=`?`

utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_select);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

selectionner dans la table=`test_table`

colonnes=`ID,NOM,POSTNOM,PRENOM,HEURE` d'ou=`NOM:Aneto`

utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```

Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante :
```shell
selectionner dans la table=`test_table`

colonnes=`*.*`

d'ou=`NOM:Aneto`;
```

# 12. MISE À JOUR DES INFORMATIONS EXISTANTES :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
modifier dans la table=`?`

mettre à jour=`?`

d'ou=`?`

(bomba_update_data);



modifier dans la table=`?`

mettre à jour=`?`

d'ou=`?`

utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_update_data);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

modifier dans la table=`test_table`

mettre à jour=`POSTNOM:Toto`

d'ou=`ID:3`

utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```

Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante :
```shell
modifier dans la table=`test_table`

mettre à jour=`POSTNOM:Toto,PRENOM:Jeremie`

d'ou=`NOM:Aneto`;
```

Dans cet exemple, mettons à jour 2 ou 3 informations portant le meme POSTNOM toto et exécuter cette procédure afin de mettre à jour toutes les informations dans la colonne POSTNOM qui débutent par To comme suivante :
```shell
modifier dans la table=`test_table`

mettre à jour=`POSTNOM:Mimi`

d'ou=`POSTNOM:To%`;
```

Vous verrez que tous les attributs POSTNOM portants comme valeur qui se débute par To, ses changeront à Mimi.

13. SUPPRESSION DES INFORMATIONS INSERÉES :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
supprimer dans la table=`?`

d'ou=`?`

(bomba_delete_users);



supprimer dans la table=`?`

d'ou=`?`

utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_delete_users);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

supprimer dans la table=`test_table`

d'ou=`ID:1`

utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```

Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante :
```shell
supprimer dans la table=`test_table`

d'ou=`ID:1`;
```

Passons à la suppression des informations qui débutent par Mi :
```shell
supprimer dans la table=`test_table`

d'ou=`POSTNOM:Mi%`;
```
Une fois l’action effectuée, toutes les informations portants les valeurs qui ses débutent par Mi seront disparues.

# 14. AFFICHAGE DE L'HEURE ACTUELLE :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
afficher heure actuelle()

(bomba_time);



afficher heure actuelle()

utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_time);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

afficher heure actuelle(`h:m:s`)

utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```

Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante :
```shell
afficher heure actuelle();
```

Vous pouvez aussi définir le format h:m:s comme suite :
```shell
afficher heure actuelle(`h:m:s`);
```

# 15. AFFICHAGE DE LA DATE ACTUELLE :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
afficher la date actuelle()

(bomba_date);



afficher la date actuelle()

utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_date);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

afficher la date actuelle(`jj/mm/yyyy`)

utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```

Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante :
```shell
afficher la date actuelle();
```

Vous pouvez aussi définir le format h:m:s comme suite :
```shell
afficher la date actuelle(`jj/mm/yyyy`);
```

# 16. AFFICHAGE DE L'HEURE ET LA DATE ACTUELLE :
Ajoutons les lignes suivantes dans notre fichier des syntaxes mes_syntaxes.txt :
```shell
maintenant()

(bomba_now);



maintenant()

utilisateur=`?`

utiliser le mot de passe=`?`

dans la base des données=`?`

(bomba_now);
```

Enregistrez, Convertissez et copiez-le dans le répertoire /usr/share/ure/int/ par la suite exécuter la procédure suivante depuis le SHELL URE :
```shell
:s:mes_syntaxes.ure;

maintenant(`h:m:s-jj/mm/yyyy`)

utilisateur=`root`

utiliser le mot de passe=`12345`

dans la base des données=`testdb`;
```

Pour les administrateurs qu'utilisent le SHELL BombaDB, exécuter la procédure suivante :
```shell
maintenant();
```

Vous pouvez aussi définir le format h:m:s comme suite :
```shell
maintenant(`h:m:s-jj/mm/yyyy`);
```

Nous sommes arrivés à la fin des syntaxes (procédures) pour l’Edition classique. Pour ceux qui veulent approfondir les procédures avancées de BombaDB, prière d’utiliser la version de l’édition Standard ou Entreprise. Passons maintenant à la rubrique GUIDE DES CONNECTEURS afin de voir comment intégrer ou utiliser BombaDB avec d’autres langages des programmations existants.

Vous pouvez télécharger les syntaxes complètes BombaDB édition classique sur le fichier mes_syntaxes et déjà prêtes à l’emploi.



![alt text](https://github.com/AnetoEnterprise/BombaDB/blob/main/images/Connecteur.png)
# CONNECTEUR
Maintenant que vous savez comment installer, configurer et gérer vos données grâce au langage de programmation universel PL/URE, en même temps fréquentiel. BombaDB vous propose les différents connecteurs sur lequel vous allez l'adapter à vos système informatique.

Avant de lister ou procéder aux différents langages des programmations qui permettent l’intégration de BombaDB à vos systèmes qu’utilisent les langages des programmations existants, BombaDB propose deux bibliothèques dynamiques, l’une pour le serveur et l’autre pour le client (Shell BDB) afin de bien gérer vos informations correctement sans pour au tant passer à l’interface console de l’environnement d’exécution universelle (EEU ou URE), mais d’utiliser effectivement le shell BombaDB pour l’affichage des informations sous forme d’un tableau au lieu de les afficher au format JSON comme depuis la console URE.

![alt text](https://github.com/AnetoEnterprise/BombaDB/blob/main/images/ListageDB.png)

Pour procéder à l'installation de la version archive (XZ) :
Sous LINUX, tapez la commande :
```shell
sudo wget https://download.bombadb.tech/LINUX/BombaDB-server-1.0-0.x86_64.tar.xz
tar -xvf BombaDB-server-1.0-0.x86_64.tar.xz
cd SERVER-CLIENT/
./install.sh
rm -r ../SETUP
```

Pour ceux qui veulent adapter BombaDB aux langages de programmation existants, peuvent interagir complètement grâce aux APIs proposés aux différents langages de programmations ci-après utilisants les bibliothèques dynamiques BombaDB :

Avant de procéder, vous devez d’abord télécharger et installer les bibliothèques partagées BombaDB comme suite :
Sous LINUX, tapez la commande :
```shell
sudo wget https://download.bombadb.tech/LIBS/LINUX/BombaDB-libs-1.0-0.x86_64.tar.xz
tar -xvf BombaDB-libs-1.0-0.x86_64.tar.xz
cd LIBS/
./install.sh
rm -r ../SETUP
```

Sous CYGWIN (WINDOWS), tapez la commande :
```shell
wget https://download.bombadb.tech/LIBS/CYGWIN/BombaDB-libs-1.0-0.x86_64.tar.xz
tar -xvf BombaDB-libs-1.0-0.x86_64.tar.xz
cd LIBS/
./install.sh
rm -r ../SETUP
```

Sous MAC OS, tapez la commande :
```shell
wget https://download.bombadb.tech/LIBS/MACOS/BombaDB-libs-1.0-0.x86_64.tar.xz
tar -xvf BombaDB-libs-1.0-0.x86_64.tar.xz
cd LIBS/
./install.sh
rm -r ../SETUP
```

Une fois nos bibliothèques installées, vous pouvez aisément les intégrer à vos systèmes ou même vos serveurs TCP/IP existants si vous ne voulez pas utiliser celui proposé par BombaDB.

Intégrer BombaDB en utilisant C++ :
```c++
#include "bombadb.h"
#include <stdio.h>
#include <stdlib.h>
#include <stdbool.h>
#include <iostream>
#include <string>

using namespace std;


int main(int argc, char** argv)	{
string resultat="";
resultat=bombaDBModule_Exec("calculer 2+2;", "*.*");
cout << resultat << "\n";

return EXIT_SUCCESS;
}
```

Intégrer BombaDB en utilisant JAVA :
```java
import java.text.DateFormat;
import java.text.SimpleDateFormat;
import java.util.List;
import java.util.ArrayList;
import java.util.Date;
import java.io.*;
import java.util.*;

public class javabdblocal {

public static void main(String[] args) {
try{
System.loadLibrary("java-bdb-local"); // loads java-bdb-local.so
} catch (UnsatisfiedLinkError e) {
System.out.println("Impossible de lire la bibliothèque.\n" + e);
System.exit(1);
}


javabdblocal bombaDBModule=new javabdblocal();
String resultat=bombaDBModule.Exec("calculer 2+2;", "*.*");
System.out.println("" + resultat);
}


public native String Exec(String commande, String syntaxes);
}
```

Intégrer BombaDB en utilisant NodeJS :
```js
const bombaDBModule = require('nodejs-bdb-local');
console.log('', bombaDBModule.Exec("calculer 2+2;", "*.*"));
console.log();
```
Intégrer BombaDB en utilisant PHP :
Premièrement vous devez l'activer depuis votre fichier php.ini comme suite :
```php
nano /etc/php/7.2/cli/php.ini
extension=php_bdblocal.so
```
