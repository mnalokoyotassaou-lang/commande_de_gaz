# commande_de_gaz
GazExpress Connect : Solution omnicanale de commande de gaz via WhatsApp, mobile et web. Elle permet aux clients de commander avec géolocalisation et suivi en temps réel. Côté administration, le système centralise les flux, gère les stocks de bouteilles, les livreurs et les paiements pour optimiser la distribution et la logistique.
1. Vision du Projet

L'objectif est de digitaliser le processus de recharge de gaz en offrant aux clients une flexibilité totale de commande. Que ce soit via un smartphone, un ordinateur ou une simple discussion WhatsApp, le système centralise les flux pour garantir une livraison rapide et un suivi rigoureux des stocks.
2. Écosystème de la Plateforme
A. Le Canal WhatsApp (Interface Conversationnelle)

    Chatbot Intelligent : Intégration de l'API WhatsApp Business pour permettre la commande via un menu interactif.

    Simplicité : Idéal pour les clients n'ayant pas d'espace de stockage pour une application mobile ou préférant la rapidité d'un message.

    Géolocalisation : Partage de la position en temps réel pour faciliter la livraison.

B. L'Application Mobile (Client)

    Profil Utilisateur : Historique des commandes et gestion des types de bouteilles (6kg, 12kg, etc.).

    Tracking en Temps Réel : Suivi du livreur sur une carte (type Uber/Glovo).

    Notifications Push : Alertes sur l'état de la commande (en préparation, en livraison, livrée).

    Paiement Mobile : Intégration des solutions de paiement local (Mobile Money).

C. Le Portail Web (Client & Administrateur)

    Interface Client : Alternative pour les commandes depuis un ordinateur avec gestion de compte entreprise ou familiale.

    Tableau de Bord Administrateur (Back-office) :

        Gestion des Commandes : Réception et assignation des commandes aux livreurs disponibles.

        Gestion de la Flotte : Suivi des livreurs et de leurs zones de couverture.

        Inventaire : État des stocks de bouteilles pleines/vides par dépôt.

        Statistiques : Analyse des ventes, des zones de forte demande et des temps de livraison moyens.

3. Points Forts & Innovation

    Accessibilité Maximale : En combinant Web, Mobile et WhatsApp, vous couvrez 100% des profils d'utilisateurs.
# pour lancez le projet
1) placez vous à la racine du provjet à l'aide de votre terminale
2) tapez : python manage.py runserver 0.0.0.0:8000
3) Ouvrir toujour dans la racine de projet un autre terminale
4) tapez dans cet nouveau terminal ngrok http 8000
5) dans votre navigateur tappez https:127.0.0.1:8000
6) placez à la racine du projet flutter pour le mobile
7) à l'aide de votre terminal  tapez flutter run si vous avez flutter configurer sinon il faut faire l'installation
8) 

    Optimisation Logistique : L'administrateur peut optimiser les tournées de livraison grâce aux données de localisation.

    Fidélisation : Système de rappels automatiques basés sur la fréquence de consommation estimée du client.
