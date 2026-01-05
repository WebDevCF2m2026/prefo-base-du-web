# Préfo-base-du-web

## Internet et le web - Introduction.


### Historique de l'internet

Vous l'aviez compris, le web n'a pas émergé instantanément. Voici pour mémoire les principales étapes de son histoire :

**1969** : création de l’ancêtre d’Internet, appelé alors **ARPAnet**. C’est un réseau **militaire** qui se veut décentralisé (autrement dit, il n’a pas de lieu de commande central). Le réseau a ensuite évolué pour devenir un lieu d’**échange universitaire** avant de devenir progressivement grand public sous le nom d’Internet.

#### Arpanet en 1974
![Arpanet 1974](datas/Arpanet_1974.svg.png)

**1972** : apparition des e-mails pour échanger des messages.

**1983** : ARPANET adopte le TCP/IP qui sera la base d'Internet

**1990** : Arpanet ferme officiellement, et se transforme en internet civile.

**1991** : lancement du Web public, pour afficher des pages d’information, créé par **Tim Berners-Lee**. C’est à ce moment que la notion de « pages web » et de « liens hypertextes » (permettant de naviguer entre chaque page) apparaît. C’est la naissance de la toile !

**1994** : création du **W3C (World Wide Web Consortium)**, organisme qui a pris le relais de **Tim Berners-Lee** pour faire évoluer les technologies du web (HTML, CSS, PNG, XML et autres noms barbares).



### La définition technique : Le "Réseau des Réseaux"

Fondamentalement, Internet n'est pas un réseau unique, mais **une fédération de milliers de réseaux indépendants (appelés AS ou Autonomous Systems) qui acceptent de s'interconnecter**.

Le terme vient de Inter-connected Networks. Pour que ces réseaux hétérogènes (fibres transatlantiques, Wi-Fi domestique, 4G, réseaux d'entreprise) puissent communiquer, ils reposent sur deux piliers inventés dans les années 1970 (DARPA) :

La **commutation de paquets (Packet Switching)** : Contrairement au téléphone analogique (circuit dédié), les données sont découpées en petits morceaux (**paquets**). Chaque paquet peut emprunter une route différente pour arriver à destination où ils sont réassemblés. C'est ce qui rend le réseau résilient.

La suite de protocoles **TCP/IP** : Ce sont les langages de communication (protocoles) qui permettent de transmettre les données.

**IP (Internet Protocol)** : Gère l'adressage (Où aller ?). Chaque machine a une adresse unique (IPv4 ou IPv6).

**TCP (Transmission Control Protocol)** : Gère la fiabilité (Est-ce que tout est arrivé ?). Il établit la connexion et vérifie l'intégrité des données.

### Les protocoles principaux pour utiliser Internet

    HTTP (Hypertext Transfer Protocol) : Protocole de communication entre un navigateur et un serveur web.
    
    HTTPS (Hypertext Transfer Protocol Secure) : Version sécurisée de HTTP.
    
    FTP (File Transfer Protocol) : Protocole de transfert de fichiers.
    
    SMTP (Simple Mail Transfer Protocol) : Protocole de transfert de courriel (envoi).
    
    POP3 (Post Office Protocol version 3) : Protocole de transfert de courriel (réception).
    
    IMAP (Internet Message Access Protocol) : Protocole d'accès aux courriels.

    SSH (Secure Shell) : Protocole de connexion sécurisée.

    DNS (Domain Name System) : Protocole de résolution de nom de domaine.

    etc ...

