Reponse exercice 3
Question 1
La commande awk -F, '{print $1}' utilise awk pour traiter chaque ligne d'un fichier ou d'un flux de données, en séparant les champs par des virgules. 
Voici une explication détaillée de chaque partie de cette commande : awk : C'est un outil puissant de traitement de texte utilisé pour analyser et manipuler des fichiers 
ou des flux de données en ligne.

Qestion 2
chmod 744 myfile
Cela donne au propriétaire tous les droits (lecture, écriture, exécution), au groupe uniquement le droit de lecture, et aux autres également uniquement.

Question 3
En termes généraux, la différence entre une variable d'environnement et une variable locale réside dans leur portée et leur visibilité. - 
Variable locale : Elle est limitée au script ou à la fonction dans laquelle elle est définie. Elle n'est pas visible pour les autres processus ou scripts exécutés 
à partir du script actuel.La variable d'environnement son fonctionnement repose sur le concept de héritage des processus. Lorsqu'une variable est déclarée comme variable d'environnement, 
elle est enregistrée dans l'environnement du processus actuel (par exemple, le shell). Cela permet aux processus enfants ou sous-processus de l'accéder, 
facilitant ainsi le partage d'informations entre différents scripts, applications et commandes.

Question 4
IF quand on l'utilise elle appele une condition [ ] ou IF
Test quand la condition est remplie ou pas alors nous avons une autre commande ELSE qui nous donne alors la consequance soit pour activer une autre commande 
soit pour un affichage , et le IF ce termine toujours par un FI

Question 5 
echo 'Malgré le prix élevé de 100$, il a dit "Bonjour !" au vendeur :'
echo '- "Bonjour est-ce que ce clavier fonctionne bien ?"'
echo '- "Evidemment ! On peut tout écrire avec, que ce soit des pipe | ou bien des backslash \\ !"'
echo '- "Même des tildes ~ ?"'
echo '- "Evidemment !"'

Question 6
La commande jobs -l est utilisée dans le shell pour afficher la liste des tâches en arrière-plan ou suspendues dans la session actuelle, avec des informations détaillées. 
### Explication de jobs -l - jobs : Cette commande affiche les tâches (ou "jobs") en cours dans le shell actuel. Un "job" est un processus que vous avez lancé depuis le shell, 
comme un script ou une commande, qui peut être suspendu, exécuté en arrière-plan, ou en avant-plan.

Question 7
La couche 2 et 3 du model OSI c'est liaison de données pour 2 et reseau pour 3

Question 8 Les équivalence PowerShell des commandes bash 
cd = changer de repertoire = **Set-Location**
cp = copier = **Copy-Item**
mkdir = creer un repertoire = **New-Item -ItemType Directory**
ls = lit l interieur dun repertoire = **ls** comme un alias pour **Get Children**, on peut donc utiliser ls directement.

Question 9
Dans la trame ethernet, le payload est le paquet de donnée transportées

Question 10 Les classes IP étaient rigides, avec des plages (A, B, C) souvent trop grandes ou trop petites pour les réseaux réels. 
Cette gestion entraînait un gaspillage d'adresses IP, car de nombreux réseaux n'utilisaient qu'une fraction des adresses
CIDR permet de mieux utiliser l'espace d'adressage en allouant des blocs de taille adaptée aux besoins.
En offrant une meilleure gestion des adresses, le CIDR aide à préserver l'espace IPv4, qui est limité.
Le CIDR simplifie aussi le routage. La réduction de la taille des tables de routage rend Internet plus performant et les routeurs plus efficasse.
Enfin, CIDR permet de créer des sous-réseaux de tailles variées, donnant plus de liberté aux administrateurs réseau pour s'adapter aux besoins, sans les limitations rigides des classes IP fixes.
