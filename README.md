
# Challenges capture de flag 

## FTP Authentification
Pour résoudre ce challenge,il a fallut :

- Démarrer le challenge
- Télécharger le fichier ch1.pcap
- L'ouvrir dans l'analyseur de paquet: Wireshark
- Cliquer sur le protocole FTB 
- Suivre en flux TCP

## TELNET Authentification
Pour ce problème,il a fallut:

-Démarrer le challenge
-Télécharger le fichier ch2.pcap
-L'ouvrir dans Wireshark
-Cliquer sur le protocole TELNET
-Suivre en flux TCP 


## Ethernet Trame
Pour celui-ci,

-Démarrer le challenge
-Affichage d'une série de codes hexadécimal
-Utilisation d'un décodeur (hpd.gasmi.net dans mon cas) pour déchiffrer les codes hexadécimal en code à base 64
-Une fois trouvé, convertir ce code à base 64 en string à l'aide de "www.string-functions.com"


## Twitter Authentification

- Démarrer le challenge
- Télécharger le fichier ch3.pcap
- L'ouvrir dans Wireshark
- Suivre l'unique paquet présent dans le fichier
- On retrouve sur la ligne "Authorization" un code à base 64
-Convertir ce code en string 


## BLUETOOTH - Fichier inconnu 

- Démarrer le challenge
- Télécharger le fichier char18.bin
- L'ouvrir dans Wireshark
- Séléctionner un protocole HCI EVT
- Cliquer sur l'option "Wireless" et choisir "équipements Bluetooth"
- S'affiche un adresse MAC et le nom d'un téléphone
- Concatener ces deux résultats (on mettra l'adresse Mac en majuscule)
- Le décrypter sur www.sha1.fr



