---
layout: default
title: Bienvenue sur mon portfolio
---

<style>
  html {
    scroll-behavior: smooth;
  }

  .iframe-wrapper {
    display: flex;
    justify-content: center;
    margin-top: 2rem;
  }

  .iframe-wrapper iframe {
    width: 90%;
    max-width: 800px;
    border: none;
  }

  .iframe-wrapper + * {
    margin-top: 0;
  }
</style>



<a id="cybersecurite"></a>

## Cybersécurité (auto‐formation)

**Certifications et formations**

- Analyste Junior en Cybersécurité – Cisco Networking Academy (en cours)  
- MOOC SecNumacadémie – ANSSI  
- Practical Ethical Hacking – Udemy  
- Phishing : A Technical Course – JustHacking  
- Pratique régulière sur TryHackMe
<div class="iframe-wrapper">
  <iframe
    src="https://tryhackme.com/api/v2/badges/public-profile?userPublicId=2709730">
  </iframe>
</div>

**Environnements** 

- Virtualisation : QEMU/KVM, VirtualBox, Docker  
- Systèmes d’exploitation : Kali Linux, Parrot OS, Arch Linux  

**Pentest & outils**

- Reconnaissance et énumération : Nmap, Masscan, Gobuster, dirb  
- Exploitation : Metasploit  
- Analyse d’applications web : Burp Suite, OWASP ZAP  
- Outils complémentaires : Hydra, John the Ripper, sqlmap  

**Techniques de hacking**

- Élévation de privilèges sous Linux  
- Injections SQL  
- Upload de web-shells  
- Reverse shells  
- Cracking de hachages  
- Phishing avancé : déploiement d’infrastructures email et GoPhish, capture de credentials, suivi et reporting de campagne  

**Défense & surveillance (Blue Team)**

- Analyse de trafic réseau : Wireshark  
- Compréhension des rôles globaux des équipes Blue Team  
- Bonne compréhension des protocoles réseau et configuration Linux  

**Gouvernance, normes et conformité**

- Compréhension des rôles et responsabilités en gouvernance, gestion des risques et conformité (GRC)  
- Bases des cadres légaux et politiques internationaux  
- Notions clés des standards ISO 27001 et NIST 800-53  

Je compte renforcer encore davantage mes entraînements à l’avenir pour ancrer solidement mes bases et continuer à progresser.




<h1 style="border-bottom: none; display: inline-flex; align-items: center;">
  Projets académiques
  <img
    src="Logo_Sorbonne_Universite.png"
    alt="Logo Sorbonne Université"
    style="height:2em; vertical-align:middle; margin-left:0.5em;"
  />
</h1>




<a id="L3"></a>
## L3

* * *

### Cryptographie *(Python)*
- **Projets :** Implémentation et analyse de techniques de cryptanalyse.
- **Description :**  
  Ces projets visaient à étudier et comparer différentes méthodes de chiffrement.
- **Contenu :**  
  - Mise en œuvre du chiffrement et du déchiffrement avec des systèmes mono-alphabétiques.  
  - Exploitation du chiffre de Vigenère.  
  - Application des mécanismes de cryptographie RSA, illustrant le concept de chiffrement asymétrique.  
  - Utilisation de la cryptographie basée sur les courbes elliptiques.



### Réseaux

- **Travaux Pratiques :** analyse du trafic réseau et compréhension des protocoles de communication, à l’aide de Wireshark et de machines virtuelles.
- **Domaines étudiés :**  
  - Architecture LAN et VLAN  
  - Adressage IP et exploitation du protocole ARP  
  - Utilisation des protocoles IP et ICMP pour le diagnostic des réseaux  
  - Gestion des adresses via DHCP et traduction d’adresses (NAT)  
  - Configuration et optimisation du routage  
  - Communication via les protocoles UDP et TCP  
  - Mise en œuvre des technologies Web et compréhension du rôle du système DNS



### Développement Web

- **Projet :** Conception et développement d’un forum.
- **Langages et bibliothèques utilisés :**  
  - **Front-end :** HTML, CSS, React  
  - **Back-end :** JavaScript et MongoDB pour la gestion de la base de données  
 - Ce projet consiste à créer un forum web doté de fonctionnalités telles que : 
	  - Création de comptes et gestion de la connexion/déconnexion avec authentification par session.  
	  - Mise à disposition d’API REST.  
	  - Gestion des messages : envoi, suppression, filtrage.  
	  - Gestion des utilisateurs, avec différents statuts et informations personnelles.



### Intelligence artificielle et Jeux *(Python, Pygame, Gurobi, GLPK)*

- **Projet 1 : Étudier un problème d’affectation**  
  - **Objectif :** Évaluer différentes méthodes d’affectation.  
  - **Méthodologies :**  
    - Résolution du problème en utilisant l’algorithme de Gale-Shapley.  
    - Modélisation du problème comme un programme linéaire afin d’explorer des approches d’optimisation alternatives.

- **Projet 2 : Stratégies de Décision dans une Simulation de Choix de Restaurant**  
  - **Objectif :** Comparer et évaluer différentes stratégies, afin de mesurer leur efficacité et de comprendre les marges d’amélioration.  
  - **Méthodologies :**  
    - Utilisation de l’algorithme A* pour explorer des solutions optimisées dans des environnements de jeu.  
    - Comparaison entre trois types de stratégies :  
      1. **Stratégie non informée :** Basée sur des choix aléatoires, elle repose sur l'absence totale d’information préalable.  
      2. **Stratégie basée sur l’observation :** S’appuie sur les informations visuelles visibles dans le jeu pour adapter les décisions en temps réel.  
      3. **Stratégie basée sur l’historique :** Utilise l’analyse des parties précédentes pour identifier des patterns et affiner la prise de décision.

  
- **Projet 3 : Bataille des robots**  
  - **Objectif :** Simuler des affrontements entre robots en intégrant plusieurs stratégies de comportement.  
  - **Méthodologies :**  
    - Implémentation de comportements inspirés des modèles Braitenberg et de l’architecture subsomption.  
    - Optimisation des comportements via des algorithmes génétiques.



### Statistique et informatique *(Python, Matplotlib, NumPy, Pandas, Scikit-Learn)*

- **Projet 1 : Bataille Navale**  
  - **Objectif :** Modéliser le jeu de la bataille navale de manière probabiliste.  
  - **Méthodologies :**  
    - Implémentation d’une version aléatoire et d’une version heuristique.  
    - Utilisation de la méthode Monte Carlo pour simuler des scénarios multiples.  
    - Mise en place d’une approche bayésienne afin d’estimer les probabilités d’apparition d’événements stratégiques.
  
- **Projet 2 : Analyse de Données en Agriculture**  
  - Développer et appliquer des modèles statistiques pour analyser et modéliser des données agricoles.
  
- **Projet 3 : Classification Probabiliste**  
    - Mise en place de classifieurs pour des données représentées dans un espace en deux dimensions, en s’appuyant sur la règle du maximum a posteriori (MAP) via le modèle naïve Bayes.  
    - Implémentation du TAN (Tree-Augmented Naïve Bayes) pour modéliser les dépendances entre variables et améliorer la précision de la classification.



### Science des Données *(Python, Matplotlib, NumPy, Pandas, Scikit-Learn)*

- **Projet :** Conception et mise en œuvre de traitements et d'analyses de données.
  - **Prétraitement :** Application de techniques de vectorisation et de normalisation pour structurer des données brutes.  
  - **Apprentissage supervisé :** Implémentation d’algorithmes de classification (SVM linéaire, Perceptron, K-NN) pour modéliser des problèmes avec des données étiquetées.  
  - **Apprentissage non supervisé :** Utilisation de méthodes telles que TF-IDF pour l’analyse textuelle et réalisation de clustering via des approches hiérarchiques et l’algorithme K-means afin de segmenter des ensembles de données sans étiquettes.



### Algorithmiques *(Python, Matplotlib)*

- **Projet :** Modélisation d’un problème pratique illustré par la répartition de confiture dans des bocaux vides.
  - Évaluation systématique de la complexité en temps et en espace des solutions, permettant de quantifier l’efficacité de chacune.  
  - Comparaison approfondie entre une approche gloutonne (greedy) et la programmation dynamique pour déterminer la méthode la mieux adaptée aux contraintes du problème.



<a id="L2"></a>
## L2

* * *



### Structures de données : Reconfiguration d’un réseau fibre optique *(C)*

- Conception et comparaison de plusieurs structures de données  pour stocker la topologie.  



### Projet de développement : Simulation de systèmes électoraux *(Théorie du choix social, Python, Pygame)*

- Conception d’un moteur de simulation permettant de comparer plusieurs modes de scrutin (pluralité, Borda, Condorcet, vote alternatif…).  
- Implémentation de scénarios de vote stratégique pour analyser la robustesse des systèmes étudiés.  



### Programmation orientée objet : Jeu de stratégie multi-agents 2D *(Java)*
- Développement d'un programme qui réalise une simulation se déroulant sur une grille. La simulation a pour cadre la collecte de joyaux dans une grille où se trouvent des gardiens. 



### C avancé : Bibliothèque virtuelle & écosystème simulé *(C, Gnuplot)*

- Développement d’une bibliothèque virtuelle (catalogue, emprunts, réservations).  
- Projet parallèle : simulateur d’écosystème (prédateurs/proies) avec grille et règles de reproduction aléatoires.  
- Intégration continue avec un Makefile complet et tests automatisés.



<a id="L1"></a>
## L1

* * *



### Atelier de recherche encadrée dynamique : Modélisation des marées *(Python, Matplotlib, Pygame)*

- Élaboration de modèles de prévision de la hauteur des marées, calibrés et validés par confrontation à des données réelles.



### Informatique (NSI) : Console de mini-jeux embarqués *(Python, Pygame, Arduino, Raspberry Pi)*

- Conception d’une station de jeux rétro mêlant Flappy Bird, jeu de réflexe et Pierre-Feuille-Ciseaux.  
- Gestion des entrées physiques : boutons, microphone.  
- Communication série Arduino ↔ Raspberry Pi pour la partie scoring et affichage.  

