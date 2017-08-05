# LifePanel
Développement du projet de panel web pour la gestion des joueurs pour les serveurs ArmA 3 Life.

# Introduction
Ce projet aura pour but de développer un outil d'administration web pour la gestion des serveurs Arma 3 Life. L'outil aura un système de droits d'accès permettant de donner certains droits d'accès aux utilisateurs du site.

# Utilisateurs cible
Les utilisateurs ciblés pour l'utilisation de l'outil sont les membres du staff du serveur Arma 3.

# Grades de gestion
Pour l'administration du serveur les groupes suivants seront créés de base.

- Helpeur (niveau 1) : lecture
- Modérateur (niveau 2) : écriture remboursement (jusqu'à 500k)
- Administrateur (niveau 3)
- Fondateur (niveau 4)

# Gestion de utilisateurs
Pour la gestion des utilisateurs les fondateurs auront la possibilité de créer et modifier les comptes utilisateurs.

# Développement
Le panel utilisera le framework bootstrap 4.0.0 pour assurer une développement responsive et propre au niveau de l'affichage.
Pour le remplissage du site, une connexion à deux bases de données (web et serveur arma) sera faite sur chaque page et ainsi récupérer les informations nécessaire via des requêts SQL.

Toutes la partie fonctionnel de l'outi sera codé en PHP.
