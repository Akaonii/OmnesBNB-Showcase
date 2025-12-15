# OmnesBNB-Showcase
# 🛡️ OmnesBNB - Secure Full Stack Platform
> **Note:** Ce dépôt est une vitrine technologique. Le code source est privé pour des raisons de confidentialité académique (ECE Paris).

![PHP](https://img.shields.io/badge/Backend-PHP%208-777BB4?style=for-the-badge&logo=php&logoColor=white)
![MySQL](https://img.shields.io/badge/Database-MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Security](https://img.shields.io/badge/Security-OWASP%20Top%2010-green?style=for-the-badge)

## 🎯 Aperçu
Développement complet d'une plateforme de réservation immobilière (type AirBnB) permettant la publication d'annonces, la réservation et le paiement en ligne.
L'objectif était de maîtriser le cycle de vie complet d'une application Web, du design de la base de données au déploiement en production.

## 🛠️ Stack Technique
* **Backend:** PHP 8 Natif (Architecture MVC personnalisée)
* **Frontend:** HTML5, CSS3, JavaScript Vanilla
* **Database:** MySQL (Modélisation relationnelle complexe)
* **Déploiement:** Hébergement Web réel (Mise en production)

## 🔒 Focus Cybersécurité (Blue Team Approach)
En tant que responsable Back-End, j'ai implémenté une approche "Secure by Design" :
1.  **Prévention SQL Injection (SQLi) :** Utilisation systématique de `PDO Prepared Statements` pour toutes les requêtes.
2.  **Protection XSS :** Sanitization stricte des entrées/sorties via `htmlspecialchars` et filtrage des données postées.
3.  **Authentification Forte :** Hashage des mots de passe avec sel (Hashing algorithms) directement en base SQL.
4.  **Contrôle d'accès (RBAC) :** Système de rôles strict (Utilisateur vs Admin) avec panneau d'administration sécurisé pour la modération (CRUD).

## 🚀 Fonctionnalités Clés
* Système de réservation avec gestion des conflits de dates.
* Upload et gestion sécurisée des images des biens.
* Interface d'administration pour bannir des utilisateurs ou supprimer des annonces frauduleuses.
