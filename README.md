# SAE 2.04 Scapy

## Introduction

Le but de ce projet est d'apprendre à utiliser la bibliothèque **Scapy** en Python pour analyser des trames réseau. 

Pour cela, il est demandé d'utiliser **Jupyter Notebook** afin d'exécuter et d'apprendre les concepts progressivement. 

Ce projet se déroule en plusieurs étapes, chaque étape proposant des exercices ou des challenges spécifiques qui vous aideront à développer vos compétences en cybersécurité et en analyse de protocoles réseau.



## Étape 1: Débuter avec Scapy

Dans cette première étape, vous allez découvrir les bases de l'utilisation de **Scapy**.

Le notebook suivant vous guidera à travers les premières commandes et notions essentielles.

- **[debuter_scapy.ipynb](debuter_scapy.ipynb)** : Introduction aux bases de Scapy.



## Étape 2: Ping avec Scapy

Cette étape vous introduit aux notions de **ping** en utilisant **Scapy**, afin de comprendre comment manipuler et analyser ce protocole.

- **[ping_6.ipynb](ping_6.ipynb)** : Apprendre à réaliser et analyser un ping avec Scapy.



## Étape 3: Bases des chaînes et des fichiers en Python

Avant d'aller plus loin avec **Scapy**, il est important de maîtriser certaines bases de **Python**, notamment la manipulation des chaînes de caractères et des fichiers. 

Les notebooks suivants vous expliquent ces concepts :

- **[Debuter_chaines_python.ipynb](Debuter_chaines_python.ipynb)** : Introduction à la manipulation des chaînes de caractères en Python.
- **[les_fichier_avec_python.ipynb](les_fichier_avec_python.ipynb)** : Introduction à la manipulation des fichiers en Python.




## Étape 4: Challenge FTP

Nous allons maintenant travailler sur des protocoles tels que **FTP**, **TELNET**, **HTTP**, etc., qui ne sont pas chiffrés, contrairement à leurs homologues sécurisés (**SFTP**, **FTPS**, **HTTPS**, **SSH**, etc.). Cela nous permettra de mieux comprendre les risques d'utiliser des protocoles non sécurisés.

Ce premier challenge consiste à analyser une capture Wireshark d'un transfert de fichier via le protocole FTP. Vous devrez écrire des scripts Python permettant d'automatiser cette analyse.

- **[FTP_challenge.ipynb](FTP_challenge.ipynb)** : Challenge sur le protocole FTP, où vous devez récupérer des informations sur une connexion non sécurisée.



## Étape 5: Challenge TELNET

Dans cette étape, nous allons adapter le code FTP pour un nouveau protocole : **TELNET**. 

Ce challenge nous demande de retrouver les identifiants de connexion d'une capture TELNET et de créer un script Python capable de les extraire automatiquement.

- **[TELNET_challenge.ipynb](TELNET_challenge.ipynb)** : Challenge TELNET où vous devez retrouver et analyser les identifiants d'une connexion non chiffrée.



## Étape 6: Challenge HTTP

Dans ce challenge, nous allons travailler avec le protocole **HTTP**. 

Un utilisateur interroge un serveur web nécessitant une authentification, mais l'échange de login/mot de passe n'est pas chiffré. Notre objectif est de retrouver ces identifiants dans la capture réseau.

- **[HTTP_challenge.ipynb](HTTP_challenge.ipynb)** : Challenge HTTP nous devons intercepter et extraire des identifiants non sécurisés dans une communication HTTP.

## Conclusion

Ce projet nous permet d'explorer des protocoles non sécurisés à travers des challenges pratiques. Les compétences acquises ici vous prépareront à mieux comprendre les risques liés à ces protocoles et à développer des outils d'analyse réseau en **Python** avec **Scapy**.

**Bon courage pour la SAE !**
