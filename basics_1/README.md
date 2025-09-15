# Basics 1 - Réseau

Ce projet couvre des notions fondamentales de réseau et comment interagir avec elles via des scripts Bash sous Ubuntu 22.04.

## Objectifs d’apprentissage

- **Qu’est-ce que localhost / 127.0.0.1**  
  Localhost est le nom d’hôte qui désigne l’ordinateur local. L’adresse IP `127.0.0.1` est l’adresse de bouclage IPv4 utilisée pour tester la connexion réseau sur la machine elle-même.

- **Qu’est-ce que 0.0.0.0**  
  C’est une adresse spéciale qui signifie « toutes les adresses IPv4 de la machine locale ». Elle est souvent utilisée lorsqu’un programme doit écouter sur toutes les interfaces réseau.

- **Qu’est-ce que /etc/hosts**  
  C’est un fichier système qui associe des noms d’hôtes à des adresses IP. Il permet de résoudre localement des noms de domaine sans passer par un serveur DNS.

- **Comment afficher les interfaces réseau actives de la machine**  
  La commande `ip a` (ou `ifconfig` si installé) permet d’afficher toutes les interfaces réseau et leur configuration.
