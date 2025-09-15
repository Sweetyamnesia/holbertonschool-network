# 🌐 Modèle OSI et notions de base en réseaux

Ce document explique les principaux concepts liés aux réseaux informatiques : le modèle OSI, les types de réseaux (LAN, WAN, Internet), les adresses IP, ainsi que quelques notions essentielles comme TCP/UDP, les ports et les protocoles les plus utilisés.

---

## 📖 Le modèle OSI

### Qu'est-ce que c'est ?
Le modèle **OSI (Open Systems Interconnection)** est une norme de référence qui décrit comment les données circulent dans un réseau.  
Il divise la communication en plusieurs couches distinctes, chacune ayant un rôle précis.

### Combien de couches ?
Le modèle OSI possède **7 couches**.

### Organisation des couches
De haut en bas :
1. **Application** (interfaces utilisateurs et logiciels, ex. : HTTP, SMTP)
2. **Présentation** (traduction, chiffrement, compression)
3. **Session** (gestion des sessions entre applications)
4. **Transport** (segmentation, contrôle des flux – ex. : TCP, UDP)
5. **Réseau** (acheminement – ex. : IP)
6. **Liaison de données** (communication entre machines voisines – ex. : Ethernet, Wi-Fi)
7. **Physique** (câbles, ondes, matériel réseau)

---

## 🖧 Les types de réseaux

### LAN (Local Area Network)
- **Définition** : Réseau local, limité à une petite zone géographique.  
- **Utilisation typique** : Réseau domestique, réseau d’entreprise, salle de classe.  
- **Taille** : Généralement quelques mètres à quelques kilomètres.

### WAN (Wide Area Network)
- **Définition** : Réseau étendu reliant plusieurs LAN entre eux.  
- **Utilisation typique** : Connexion entre plusieurs agences d’une entreprise, interconnexion de campus universitaires.  
- **Taille** : Peut couvrir des villes, des pays ou des continents.

### Internet
- **Définition** : Réseau mondial interconnectant des millions de réseaux publics et privés.  
- **Utilisation typique** : Communication mondiale, navigation web, e-mails, services en ligne.  
- **Taille** : Planétaire.

---

## 📍 Adresses IP et concepts associés

### Qu'est-ce qu'une adresse IP ?
Une **adresse IP (Internet Protocol)** identifie une machine dans un réseau.

### Les 2 types d’adresses IP
- **IPv4** : format 32 bits (ex. : `192.168.1.1`)  
- **IPv6** : format 128 bits (ex. : `2001:0db8::1`)

### Localhost
- Adresse spéciale (`127.0.0.1` en IPv4, `::1` en IPv6) représentant l’ordinateur local.  
- Utilisée pour tester des services réseau en interne.

### Sous-réseau (Subnet)
- Division d’un réseau en segments plus petits.  
- Permet de mieux gérer les adresses IP et de limiter le trafic.

### Pourquoi IPv6 a été créé ?
- Pour pallier l’épuisement des adresses IPv4.  
- Pour offrir plus d’adresses disponibles, de meilleures performances et une sécurité renforcée.

---

## 🔄 Protocoles de transport : TCP et UDP

### Les 2 protocoles principaux
- **TCP (Transmission Control Protocol)**  
- **UDP (User Datagram Protocol)**  

### Différence principale
- **TCP** : fiable, avec contrôle d’erreurs, accusés de réception, retransmission des paquets.  
- **UDP** : plus rapide mais sans garantie (pas de vérification de réception).  

---

## 🎯 Ports et services

### Qu’est-ce qu’un port ?
Un **port** est un point de communication logique permettant de distinguer les différents services réseau sur une même machine.

### Ports à mémoriser
- **SSH** : 22  
- **HTTP** : 80  
- **HTTPS** : 443  

---

## 🛠️ Vérifier la connectivité d’un appareil

L’outil/protocole le plus couramment utilisé est **ping** (basé sur **ICMP**), qui permet de tester si une machine est joignable sur un réseau.

---

✍️ **Auteur** : Documentation simplifiée sur le modèle OSI et les concepts de base des réseaux.
