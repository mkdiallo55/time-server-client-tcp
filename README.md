Time Server-Client TCP
Description
Ce projet est une application client-serveur développée en Java, utilisant des sockets TCP pour la communication entre le client et le serveur. Le client envoie des commandes telles que heure, date, année, mois, jour au serveur, et ce dernier répond avec les informations temporelles appropriées.

Fonctionnalités
Client :

Envoi de commandes pour obtenir l'heure actuelle, la date, l'année, le mois, ou le jour.
Réception et affichage des réponses du serveur.
Interface graphique pour une interaction facile :
Zone de saisie pour entrer les commandes.
Bouton "Envoyer" pour soumettre les commandes.
Zone d'affichage pour montrer les réponses du serveur.
Bouton "Quitter" pour fermer la connexion avec le serveur.
Serveur :

Réception des commandes du client via TCP.
Calcul et envoi des réponses appropriées (heure, date, année, mois, jour).
Technologies Utilisées
Java SE : Pour le développement de l'application client et serveur.
Sockets TCP : Pour la communication réseau entre le client et le serveur.
Swing : Pour la création de l'interface graphique du client.
Instructions d'installation et d'utilisation
1 Cloner le dépôt :
  git clone https://github.com/votre_nom_d_utilisateur/time-server-client-tcp.git
2 Naviguer dans le répertoire du projet :
  cd time-server-client-tcp
3 Compiler le code : Utilisez la commande suivante pour compiler les fichiers Java :
  javac -d bin src/**/*.java
4 Exécuter le serveur : Lancez le serveur avec la commande suivante :
  java -cp bin Server
5 Exécuter le client : Lancez le client avec la commande suivante dans une autre fenêtre de terminal :
  java -cp bin Client
6 Utilisation :

Dans la fenêtre du client, entrez une commande (comme heure, date, année, mois, jour) et cliquez sur "Envoyer".
Le client affichera la réponse du serveur dans la zone de texte dédiée.
Cliquez sur "Quitter" pour fermer l'application.


