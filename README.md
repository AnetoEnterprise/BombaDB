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
