WASALI Mobile

Application mobile de livraison collaborative

WASALI Mobile est l'application React Native de la plateforme WASALI permettant de connecter les expéditeurs et les voyageurs pour la livraison nationale et internationale de colis.

Fonctionnalités

Authentification

Inscription et connexion

Authentification JWT

Gestion du profil utilisateur

Gestion des colis

Création d'un colis

Consultation des colis publiés

Suivi du statut des livraisons

Gestion des trajets

Publication d'un trajet

Consultation des trajets disponibles

Acceptation des demandes de livraison

Suivi en temps réel

Partage de position GPS

Suivi du voyageur

Notifications

Confirmation de livraison

Vérification OTP

Historique des livraisons

Technologies utilisées

React Native

TypeScript

React Navigation

Axios

Context API

JWT Authentication

GPS Tracking

REST API

Installation

Prérequis

Node.js

npm

Android Studio

React Native CLI

Installation

npm install 

Lancement Android

npx react-native run-android 

Démarrage du serveur Metro

npx react-native start 

Structure du projet

mobile/ ├── src/ │ ├── screens/ │ ├── components/ │ ├── services/ │ ├── navigation/ │ ├── context/ │ ├── hooks/ │ └── utils/ ├── android/ ├── ios/ └── App.tsx 

API Backend

Le backend Spring Boot fournit :

Authentification JWT

Gestion des colis

Gestion des trajets

Notifications

Confirmation OTP

Suivi GPS

Auteur

Moulaye Elhacen Selam
Licence Professionnelle MIAGE
Faculté des Sciences et Techniques
Université de Nouakchott

Projet PFE

Conception et développement d'un système de livraison nationale et internationale de colis par les voyageurs (WASALI)
Année universitaire : 2025 – 2026
