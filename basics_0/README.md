# Basics 0 - Fondamentaux du réseau

Ce projet introduit les concepts et protocoles fondamentaux du réseau.

## Objectifs d’apprentissage

- **Modèle OSI**  
  Un modèle conceptuel en 7 couches : Physique, Liaison de données, Réseau, Transport, Session, Présentation, Application.

- **Différents types de réseau**  
  - **LAN** (Local Area Network) : réseau local, par exemple dans une maison ou un bureau.  
  - **WAN** (Wide Area Network) : réseau étendu qui relie plusieurs LAN, par exemple Internet.  

- **Internet**  
  Le système mondial de réseaux interconnectés utilisant la suite de protocoles TCP/IP.

- **Adresse MAC**  
  Identifiant matériel unique attribué à chaque carte réseau.

- **Qu’est-ce qu’une adresse IP**  
  Une étiquette numérique assignée à un appareil connecté à un réseau.  
  - **Privée vs Publique** : privée pour l’usage interne (ex. 192.168.x.x), publique pour être joignable depuis Internet.  
  - **IPv4 vs IPv6** : IPv4 utilise 32 bits, IPv6 utilise 128 bits.

- **Localhost**  
  Désigne la machine locale, généralement `127.0.0.1`.

- **TCP et UDP**  
  - **TCP** : protocole fiable, orienté connexion.  
  - **UDP** : protocole rapide, sans connexion, sans garantie de livraison.  

- **Liste de ports TCP/UDP**  
  - Port 22 : SSH  
  - Port 80 : HTTP  
  - Port 443 : HTTPS  

- **Qu’est-ce que ping / ICMP**  
  `ping` utilise le protocole ICMP pour tester la connectivité entre deux machines.

- **Paramètres positionnels en Bash**  
  Variables `$0`, `$1`, `$2`, … qui représentent respectivement le nom du script et ses arguments.
