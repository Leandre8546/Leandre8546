Étape 1:

Pour reproduire mon installation, il faut tout d'abord se rendre sur le site VirtualBox, plus sépcifiquement dans la partie "Downloads" (Installations) sur le lien ci-après : https://www.virtualbox.org/.
Il faut cliquer sur le boutton permettant de télécharger la dernière version de la machine virtuelle, puis cliquer sur le lien permettant d'installer le fichier exécutable.

Étape 2:

Une fois le fichier installé, il faut le déplacer dans le répertoire voulu puis faire un double-clique dessus. Cela va installer "Oracle VM VirtualBox".
Il y aura des questions à répondre, cela dépend entièrement de votre ordinateur et de votre configuration.
Sur l'interface, en haut au milieu, il y a un symbole bleu avec écrit "Nouvelle". Cliquez dessus et vous vous apprêtez à créer votre machine virtuelle. Saisissez "Ubuntu" dans la première barre de recherche.
Ensuite, encore une fois, une suite de question pour vous qui ne dépendra uniquement de votre PC et de ce que vous voulez faire de cette mchine virtuelle.
Maintenant, il faut télécharger un fichier ISO Ubuntu. Sinon, vous ne parviendrez pas à lancer votre VM (Virtual Machine). Pour cela, rien de plus simple, une recherche internet et le tour est joué.
Une fois cela fait, il suffit de se diriger (sur VirtualBox) sur la roue crantée à droite de "Nouvelle". Une fois dans "Configuration", cliquez sur "Stockage", dans "Contrôleur : IDE" il y a un disque vide avec un "+" vert. Cliquez dessus et retrouvez votre fichier ISO.
Maintenant, vous êtes prêt à lancer votre machine virtuelle.

Étape 3:

Maintenant, il s'agit de patienter lors de l'installation d'Ubuntu. Moment assez long à passer.

Étape 4:

Vous êtes enfin arrivé sur UBUNTU.
Commencez par ouvrir le terminal. Le moyen le plus simple est d'appuyer simultanément sur les touches 'Ctrl', 'Alt', 'T' de votre clavier.
Le plus simple est d'exécuter un script python. Pour cela, tappez : "python3". Une nouvelle interface s'offre à vous. Écrivez simplement : "print('Hello World !')" puis tapez Entrée.
Le message "Hello World !" s'affiche. Vous avez réussi !

Étape 5:

Vous allez installer Visual Studio Code.
Il faut tout d'abord aller sur internet et installer la version ".deb". Ensuite, il faut ouvrir l'emplacement du fichier et le replacer si besoin (il se trouve automatiquement dans "Téléchargements"). 
Ensuite, déplacez-vous dans le bon répertoire. Tapez la commande "sudo apt install ./nom_fichier.deb" (tapez votre mot de passe) puis inscrivez la commande "sudo dpkg -i nom_fichier.deb". 
Enfin, écrivez "code", Visual Studio Code se lancera

Étape 5:

Passons à l'installation de Docker.
Pour ce faire; il faut installer _curl_. Faites "sudo apt install curl". Il s'installera; maintenant, allez sur le site https://get.docker.com/. Les premières lignes où il y a des commandes sont pour installer Docker (elles se situent entre les deux premières lignes de "="). Saisissez-les, vous réussirez. Une fois cela fait, tapez dans le terminal "sudo docker run hello-world". S'il n'y a pas d'erreurs, vous avez réussi à exécuter Docker. BRAVO !

Étape 6:

Pour finir, nous allons installer java et compiler un fichier.
Commencez par écrire "sudo apt update".
Il faudra regarder les différentes versions de java. Pour cela: tapez "java -version" (rien de plus simple). Nous allons prendre la version basique c'est à dire : default-jre.
Inscrivez la commande "sudo apt install default-jre".
Ensuite la commande "sudo apt install default-jdk".
Tapez "nano" pour créer un script en java. Écrivez quelque chose de très simple.
Nommez votre fichier avec l'extension ".java".

Vous pouvez inscrire votre dernière commande : "java nom_fichier".
Tapez "Entrée".
Vous avez terminé !!
