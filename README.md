# Gestion de l'Emploi du Temps avec MongoDB et Laravel

## Description
Ce projet est une application web de gestion de l'emploi du temps, développée avec le framework Laravel et utilisant MongoDB comme base de données NoSQL. L'application permet aux utilisateurs de créer, modifier et supprimer des emplois du temps, d'ajouter des événements, et de visualiser les emplois du temps de manière conviviale.

## Fonctionnalités
- Création, modification et suppression d'emplois du temps
- Ajout et gestion d'événements dans les emplois du temps
- Visualisation intuitive des emplois du temps avec des vues par jour, semaine et mois
- Authentification des utilisateurs pour sécuriser l'accès aux fonctionnalités

## Installation
### Prérequis
- PHP >= 7.3
- Composer
- MongoDB
- Serveur web (Apache, Nginx, etc.)

### Étapes d'installation
1. Clonez ce dépôt : `git clone [lien du dépôt]`
2. Installez les dépendances PHP via Composer : `composer install`
3. Copiez le fichier `.env.example` et renommez-le en `.env`
4. Configurez votre base de données MongoDB dans le fichier `.env`
5. Générez une clé d'application Laravel : `php artisan key:generate`
6. Lancez les migrations pour créer les collections MongoDB : `php artisan migrate`
7. Démarrez le serveur de développement Laravel : `php artisan serve`

## Configuration
- Assurez-vous d'avoir MongoDB installé et configuré sur votre système
- Vérifiez les paramètres de connexion à MongoDB dans le fichier `.env` 

## Utilisation
- Accédez à l'application via votre navigateur web à l'adresse fournie par `php artisan serve`
- Connectez-vous avec les identifiants par défaut ou créez un nouveau compte utilisateur
- Explorez les fonctionnalités de gestion d'emploi du temps disponibles dans l'application

## Contributions
Les contributions sont les bienvenues ! Si vous souhaitez contribuer à ce projet, veuillez soumettre une demande de pull avec vos modifications.

## Auteurs
- [Imadnajam ]([lien vers votre profil GitHub](https://github.com/Imadnajam)) - Développeur principal

## Licence
Ce projet est sous licence [MIT License](lien vers le fichier LICENSE).
