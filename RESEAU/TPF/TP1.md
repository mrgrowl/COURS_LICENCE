# TPF 1 RESEAU

### Exercice 1 


1.1) Les liens clignotes car des paquets sont échangés entre les deux machines 

1.2) On observe les adresses mac du PC 192.168.0.10 et 192.168.0.133 ainsi que leurs ports utilisés
sur le switch. Le switch les a gardé en "mémoire"

1.3) Les paquets échangés sont des paquets ARP dans un premier temps (afin de connaitre l'adresse MAC destination associé à l'IP destination)
et des paquet ICMP par la suite pour le ping 

### Exercice 2

2.1) La machine envoi plusieurs paquets ARP en broadcast afin de trouver l'adresse mac de l'ip 192.168.0.14 . Or, cette ip n'existe pas, donc la machine n'obtient aucune réponse et renvoi donc une requête arp en boucle.

2.2) Pour chaque tentative de ping , Il y a une seule trame émise par le PC qui envoi la requête.

2.3) Il y a en tout 8 trames reçues par les machines (Nombre de machine - celle qui qui envoi le paquet).

### Exercice 3

3.1) On ne peux pas faire de ping. La console indique "Destination inacessible". Cela est normal car les 2 machines ne font pas partie du même sous réseau et les 2 sous réseaux ne sont pas liés par un routeur