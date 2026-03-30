# Projet-Wakdo-Samia-CHERKIWakdo – Borne de commande & Back-office
Présentation du projet
Le projet est à réaliser dans le cadre de la certification RNCP 37805 – Développeur Web.
C'est la  conception d'une solution complète de digitalisation d'un restaurant fast-food (Wakdo), idée du fonctionnement des bornes de commande modernes.
L’application permettra aux clients de passer commandes de manière autonome à l'aide d'une borne tactile, ensuite de récupérer les commandes au comptoir avec un numéro unique.
Le projet comprend également un back-office permettant à l'équipe interne d'organiser les produits, le menu et les commandes.
Squelette du projet
Le projet est structuré en 3 parties principales :
Front borne en Bloc 1 : interface client avec HTML, CSS, JavaScript
Back-office & API en Bloc 2 : gestion des données avec Node.js, Express, MySQL
Application React en Bloc 3 : recherche de restaurants sur carte avec React + Vite
Fonctionnalités principales
Borne de commande
Parcours utilisateur simple et intuitif
Navigation par catégories (menus, burgers, boissons, desserts…)
Composition de menus (burger + accompagnement + boisson + sauce)
Personnalisation des produits
Gestion du panier en temps réel
Validation commande à l'aide d'un numéro unique
Back-office
Authentification des utilisateurs
Gestion des rôles (administration, préparation, accueil)
Gestion des produits et menus
Suivi des commandes
Mise à jour des statuts (en préparation, prêt, livré)
 API
Récupération des produits et menus
Envoi des commandes (POST /api/orders)
Communication entre le front et le back
Application React
Recherche de ville
Affichage sur carte (react-leaflet)
Sélection d’un restaurant
Interaction utilisateur dynamique
Base de données
Une base de données MySQL a été mise en place pour gérer :
les utilisateurs
les produits
les menus
les commandes
Initialisation via :
schema.sql
seed.sql
Sécurité
Le projet inclut :
authentification des utilisateurs
gestion des rôles et permissions
validation des données côté serveur
protection des routes API
