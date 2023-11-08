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
